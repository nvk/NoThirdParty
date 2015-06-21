GreenBits is the native Android version of GreenAddress. It's a multi-signature wallet that supports hardware wallets like TREZOR and Ledger. A seed created with GreenAddress can be imported into GreenBits, or a new seed can be created.

By default, GreenBits is a 2 of 2 wallet, which means that you control one private key, and GreenAddress the other. GreenAddress must sign every transaction. This forces you to rely on GA, but offers true 2-factor authentication.

GreenBits has a unique instant-confirmation feature. GreenAddress claims that it will never sign a double-spend transaction. Users can send & receive to other GreenAddress and GreenBits users and receive instant confirmations, but this only works if the other party trusts GreenAddress.

Users may add spending limits to their accounts. This works because GreenAdress controls one key, it can prevent all transactions which request more than the set limit. Some features, like disabling 2FA and spending limits, must be set using GreenAddress.

## Security 

A mobile wallet is only as secure as the device it’s running on. GreenAddress encrypts all your data and keys. An unrooted device should be used.

Users backup their wallets by writing down the 24 word seed provided in the app. If the phone is reset or lost, all funds can be recovered by re-entering the seed.

GreenBits offers a unique setup with its options of 2-2 wallets and 2-3 wallets.

In a 2 of 2 wallet, you control one key and GreenBits controls the other. If GreenBit’s servers go down, you cannot immediately spend funds because it would be impossible to access GB’s signature. GreenBits solves this by providing nLocktime transactions, which release the your funds after a chosen period of time. You must set this up using GreenAddress.

GreenBits relies on GreenAddress’s servers for transaction data, but uses Electrum servers for extra verification.

A user-set PIN is required to open your wallet each time.

## Privacy 

GreenAddress plans to add CoinJoin to GreenBits in a future update. GreenBits knows your IP address and balance.

As an HD wallet, GreenBits generates a new address for every transaction and does not re-use addresses. Using a new address for each transaction helps prevent spying on your payments and funds.
