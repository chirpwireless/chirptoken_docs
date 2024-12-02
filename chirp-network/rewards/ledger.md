---
sidebar_position: 5
---

# Ledger Wallet and Rewards Claim

## Using Ledger Wallet to Withdraw Chirp Tokens to Your Wallet

Before You Begin: If you haven't set up a wallet on your Ledger device, follow instructions:

* [Using hardware wallets with Suiet](https://docs.suiet.app/wallet/guides/using-hardware-wallet)
* [Connect your Ledger to SUI via SUI Wallet](https://support.ledger.com/article/10779621201949-zd)

**⚠️ Currently, the** [**Sui Wallet**](https://suiwallet.com/) **Chrome extension may cause errors during transaction signing. If you encounter such issues, we recommend setting up your Ledger wallet using the** [**Suiet wallet**](https://suiet.app/) **extension instead**

### Working with Ledger Wallet

1. Blind Sign Transaction Process:
   * When withdrawing funds to a wallet via Ledger, the "Blind Sign Transaction" process will be utilized.
   * Blind signing allows you to sign transactions without revealing their details, significantly enhancing the security of your operations. Before confirming, ensure you understand the transaction you are about to sign.
2. Transaction Confirmation:
   * A confirmation request will appear on your Ledger device screen.
   * Carefully review the transaction details displayed on the Ledger device, including the amount, recipient address, and other parameters.
   * If all the details are correct and the transaction appears valid, press "Confirm" on the Ledger to complete the withdrawal process.

### Completing and Verifying the Transaction

* After confirming the transaction, it will be sent to the blockchain for processing. Ensure that the transaction is successfully completed and the funds have been credited to your wallet.
* For additional security and to verify the success of the operation, use the transaction hash to track its status on the blockchain.

### Video instructions

Open Sui app on Ledger

[ledger\_open\_sui](../../docs/Chirp%20Network/Rewards/Ledger%20Wallet%20and%20Rewards%20Claim/media/ledger_open_sui.webm)

Claim tokens with Suiet Wallet

[claim\_rewards\_suiet](../../docs/Chirp%20Network/Rewards/Ledger%20Wallet%20and%20Rewards%20Claim/media/claim_rewards_suiet.webm)

Claim tokens with Sui Wallet

[ledger\_claim\_chirp\_token](../../docs/Chirp%20Network/Rewards/Ledger%20Wallet%20and%20Rewards%20Claim/media/ledger_claim_chirp_token.webm)

Sign the transaction with Ledger

[ledger\_confirm\_transaction](../../docs/Chirp%20Network/Rewards/Ledger%20Wallet%20and%20Rewards%20Claim/media/ledger_confirm_transaction.mp4)

## How to Export a Seed Phrase from Ledger

1.  **What is a Seed Phrase?**

    A seed phrase (or recovery phrase) is a set of 24 words generated when setting up your Ledger device. It is used to recover access to your wallet in case the device is lost or reset.
2.  **Accessing the Seed Phrase**

    Ledger does not allow you to view the seed phrase after the initial setup. If you haven’t saved it, you won’t be able to recover your wallet later.

    * If you lose the seed phrase, you won’t be able to access the funds in your wallet. In this case, you will need to reset the device and create a new wallet.
3.  **How to Export a Seed Phrase**

    While the seed phrase cannot be exported directly, you can reset the device and create a new wallet:

    1. **Reset the Device**:
       * Open the Ledger Live app and go to device settings.
       * Choose the reset option to erase all data.
    2. **Create a New Wallet**:
       * Follow the on-screen instructions to set up a new wallet with a new seed phrase. Write it down and store it securely.
4. **Seed Phrase Security**

* Never share your seed phrase with anyone.
* Store the seed phrase securely to avoid losing access to your funds.

**Additional Reference Links**:

* [How to Manage Your Seed Phrase in Ledger](https://support.ledger.com/article/4404382560913-zd)
* [Seed Phrase Backup Recommendations](https://support.ledger.com/article/8154109204509-zd)
