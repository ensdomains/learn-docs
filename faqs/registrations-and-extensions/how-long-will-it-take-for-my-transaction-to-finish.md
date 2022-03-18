# How long will it take for my transaction to finish?

### Ethereum Gas (Gwei) and Transactions

The time for Ethereum transactions to finish adding data to a block is dependent upon network usage. There's a fee charged for using the blockchain, which is the gas fee in gwei. One gwei is 0.000000001 ETH. When there are a lot of transactions happening on the blockchain, gas fees can increase due to competition for the validators to mine a transaction. In most cases, the transaction will eventually finish. However, the time frame would be dependent on when the miners add the data to the block. Setting too low of a maximum for a gas fee can cause a transaction to sit for too long; hours or days, or even not get mined at all.

### Looking for Stuck Transactions

When looking for the reason why a transaction might not have finished, the first place to look is on a blockchain explorer such as [Etherscan.io](https://etherscani.io). After searching for your wallet, you can see any pending transactions listed there. If you don't see any pending transactions, but you see them in your wallet software such as MetaMask, those transactions pending there have not been sent to the blockchain. They are stuck locally in the wallet software.&#x20;

On the other hand, if you do have pending transactions seen on the block explorer, you can clear them out by sending a 0 ETH transaction with the same nonce value to your own wallet. In this new transaction, you must set the gas price higher so that it will be picked up and the old transaction with the same nonce canceled. There's more reading from the [Etherscan documentation on how to replace a transaction. ](https://info.etherscan.com/how-to-replace-a-transaction/)
