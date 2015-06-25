Electrum is a light weight Bitcoin wallet for Mac, Linux, and Windows. It was created in November 2011. 

The main features of Electrum are support for hardware wallets TREZOR and HW1, secure cold storage using an offline computer, and decentralized verification using SPV.

## Security

Electrum functions as a hot wallet or cold storage. For both wallet types, a 12 word seed is generated which allows you to backup and restore the entire wallet and its keys.

For cold storage, a seed is generated on a secure offline computer and written to a piece of paper. A master public key is created from the seed and imported into a separate Electrum install on your everyday computer. You can now view the wallet balance, accept payments, and create new addresses on a hot computer without the risk of funds being stolen. All transactions must be signed by the offline computer.

All Electrum private keys are encrypted and never leave your computer. Electrum wallets not using an offline computer should be treated as a hot wallet, as it's still possible to have malware steal funds.

Although Electrum relies on third-party servers, the worst attack possible is the faking of transaction data. The servers have no way of accessing funds.

## Privacy

Electrum is a lightweight Bitcoin client, and uses servers created by users to get transaction and balance information. A server has no way of knowing your actual identity, but does know your IP address, wallet addresses, and balance.

Tor can be used to prevent the server from knowing your IP address, but cannot prevent the server from knowing that a list of addresses belong to one entity.

Some servers claim to not log or store information, but it is impossible to know for sure without setting up your own Electrum server.

As an HD wallet, Electrum generates a new address for every transaction and does not re-use addresses. Using a new address for each transaction helps prevent spying on your payments and funds.
