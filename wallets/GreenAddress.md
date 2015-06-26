GreenAddress is a multisignature Bitcoin wallet available on the web, desktop, Android, and iOS.

By default GA is a 2 of 2 wallet, which means you control one private key, and GA the other. GreenAddress must sign every transaction. This forces you to rely on GA, but offers true 2-factor authentication.

GA claims it will never sign a double-spend transaction. You can send & receive to other GA users and receive instant confirmations, but this only works if both parties trust GreenAddress.

You can log into your GA account in watch-only mode. The account balance can be viewed and payments requested, but funds cannot be spent.

Users may add spending limits to their accounts. Because GreenAdress controls one key, it can prevent all transactions which request more than the set limit.

GreenAddress's servers provide transaction data, but also use Electrum servers for extra verification.

## Security

GreenAddress offers a unique setup with its options of 2-2 wallets and 2-3 wallets.

In a 2 of 2 wallet, you control one key and GreenAddress the other. If GreenAddress's servers go down, you cannot immediately spend funds because it would be impossible to access GA's signature. GreenAddress solves this by providing nLocktime transactions, which release funds after a chosen period of time.

GreenAddress has a PIN feature that is required to access funds. After three incorrect guesses, the wallet is erased from GA servers and recovery must be done with the seed.

## Privacy

Users in need of privacy should avoid linking their social networks to their account. GreenAddress plans to add CoinJoin in a future update. GA knows your IP address and balance.

As an HD wallet, GreenAddress generates a new address for every transaction and does not re-use addresses. Using a new address for each transaction helps prevent spying on your payments and funds.
