---
date: 2020-08-27T00:0:00+00:00
title: SOL Wallet
weight: 1
---

## Create your SOL wallet & Deposit Funds

Serum is built on the [Solana blockchain](https://solana.com), so the first step is to create a SOL wallet. For this we recommend using [Sollet.io](https://sollet.io).

Once you arrive on [Sollet.io](https://sollet.io) for the first time you have the possibility to create a new wallet. You will be given seed words, make sure to save them offline somewhere safe. This is the only way you can recover your wallet, don’t lose them!

![creat-wallet](/images/articles/serum-dex/sol-wallet/create-new-wallet.png?classes=shadow&width=25pc)

Once you have noted down your seeds, you will have the possibility to add a password to your [Sollet.io](https://sollet.io) wallet. Even though this is optional, it is highly recommended for your own security.

![password](/images/articles/serum-dex/sol-wallet/password.png?classes=shadow&width=25pc)

Once the password is set (or not) you have successfully created your SOL wallet. The next step will be to send SOL to your deposit address. SOL can be bought on several exchanges like [Binance](https://binance.com) or [FTX](https://ftx.com).

![balance](/images/articles/serum-dex/sol-wallet/balance.png?classes=shadow&width=50pc)

Now, let’s add some SOL to our wallet. For this you need to click on **Receive**. A pop up will appear with your SOL address. Use this address to send SOL from an exchange. (**Only send SOL to this address, do not send SPL tokens (e.g. SRM) to this address**)

![deposit-sol](/images/articles/serum-dex/sol-wallet/deposit-sol.png?classes=shadow&width=50pc)

Now that you have some SOL in your wallet you can create another SPL address in your wallet. For this click on the **+** icon in the top right corner. A pop up will appear, you will have the possibility to add a popular SPL token such as: **SRM**, **MSRM**, **FTT**, **BTC**, **ETH**, **LINK** **XRP**, **USDT**, **USDC**.
Then deposit your USDC, USDT, XRP, LINK, YFI, FTT, ETH, and/or BTC into your FTX account. Enter in your Sollet deposit address for the crypto you would like to withdraw and FTX will automatically wrap your crypto in an SPL token to be used with the Serum dex.
Please note that to convert wrapped SPL assets back into their native chain, you can deposit into FTX and withdraw the unwrapped assets.

![add-token-popular](/images/articles/serum-dex/sol-wallet/add-token-popular.png?classes=shadow&width=25pc)

You can see that below your SOL address a SRM address appeared. You can use this address to send and receive funds to your [Sollet.io](https://sollet.io) wallet.

![srm-balance](/images/articles/serum-dex/sol-wallet/srm-balance.png?classes=shadow&width=50pc)

If you would like to add another token that's not on the Popular Token list, you can add it manually by entering the **Mint Address** of the token.

![add-token-manual](/images/articles/serum-dex/sol-wallet/add-token-manual.png?classes=shadow&width=25pc).

### Convert ERC20 to SPL tokens

Some tokens are both ERC20 and SPL, [Sollet.io](https://sollet.io) allows you to convert ERC20 to SPL using your **MetaMask Wallet**.

To do so, click on the token you would like to deposit, once deposit pop opened click on the **ERC20 Tab**

![erc20 tab](/images/articles/serum-dex/sol-wallet/deposit-erc20.png?classes=shadow&width=25pc).

Now, click on **CONNECT TO METAMASK**, a **MetaMask** pop up will open, click on **Confirm**.

Once your wallet is connected enter the amount of **ERC20** you would like to convert and click on **CONVERT**. A **MetaMask** pop up will open to confirm the transaction and set the gas fees:

![metamask popup](/images/articles/serum-dex/sol-wallet/metamask-popups.png?classes=shadow&width=25pc).

Then wait for the transaction to be confirmed on the blockchain

![confirmation](/images/articles/serum-dex/sol-wallet/erc20-confirm.png?classes=shadow&width=25pc).

Once the transaction is confirm the funds will be available in your wallet.

Now we have deposited some tokens in our [Sollet.io](https://sollet.io) wallet. Time to do a trade on Serum!

{{% notice warning %}}
The Token Address or **Mint Address** is the **contract address** of a token i.e the **token identifier, do not send tokens to this address**.
{{% /notice %}}

{{% notice warning %}}
The **Deposit Address** is the address where you deposit a token to.
{{% /notice %}}
