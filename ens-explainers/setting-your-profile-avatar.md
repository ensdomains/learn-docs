# Setting your Profile Avatar

**WARNING**: Support in the ENS Manager right now is very manual! A redesign of the ENS manager will be released soon to make this much more manageable. For now, though, here is a guide.

### Do you have an ENS name?

If you don’t already have an ENS name, you can [register an ENS name ](registering-a-name.md)or [import a DNS domain name](../advanced-tutorials/import-a-dns-domain-into-ens.md) you already own at [app.ens.domains](https://app.ens.domains). You can set an NFT avatar for either kind of ENS name.

### Is your Primary ENS Name record set?

A primary name is a record of which ENS name you own that represents your wallet. You can find out more about it here: [primary-names.md](../reference/names/primary-names.md "mention"). If you don’t have a primary name set, you can follow [setting-your-primary-name.md](setting-your-primary-name.md "mention") as a guide.

### Are you willing to spend ETH on gas fees?

You're probably aware of what gas fees on the Ethereum network are by now (if not, you can [read here](../faqs/wallets/what-are-gas-fees.md)), and since this transaction will be **on-chain**, it means that you **will have to spend ETH**. If you're ok with that, perfect! You can continue following the steps

### Setting the Avatar record

Go to [app.ens.domains](https://app.ens.domains) and search for your ENS name to get to its records page. Make sure you Connect with the wallet that owns the ENS name. You should see an `ADD/EDIT RECORD` button. Click it, and you’ll be shown a highlighted dropdown box.

![](<../.gitbook/assets/Screenshot from 2022-01-06 13-31-51.png>)

In the first dropdown box select `text`, then once the second dropdown box appears, select `avatar`. You can put an HTTPS link or IPFS hash to a file in this field, but if you’d like to put an **NFT that you own**, then you can input it **with this format**:

```
eip155:1/[NFT standard]:[contract address for NFT collection]/[token ID or the number it is in the collection]
```

You can find all of this information in the `Details` section of your NFT on OpenSea.

![NFT details displayed on OpenSea.io](<../.gitbook/assets/Screenshot from 2022-01-06 13-33-56.png>)

Clicking the blue text across from `Contract Address` will take you to it's Etherscan page, where you can copy the full contract address.

![Etherscan details displaying the token contract.](<../.gitbook/assets/Screenshot from 2022-01-06 13-37-02.png>)

In this example, you would put all of this information like this:

```
eip155:1/erc721:0xb7F7F6C52F2e2fdb1963Eab30438024864c313F6/2430
```

**Warning: The token standard cannot contain a hyphen, and must be all lowercase. So even though OpenSea may show it as "ERC-721", enter it as "erc721".**

As mentioned at the start of the article, this will be much easier in the future. For now though, everything needs to be set and corrected manually, so be aware of the previous common mistakes, as well as others such as:

* Setting the token standard to "erc721", even though it is actually "erc1155"
* Using a cryptokitty as the NFT, which is **currently not supported**
* Using any other NFT that doesn't use either NFT standard entirely. If you're unsure about this, you can always [ask in the discord](https://chat.ens.domains)!

Click `Save` once your correctly formatted NFT has been entered into the text field. You will be prompted to approve a transaction in your wallet.. You will be prompted to approve a transaction in your wallet. Once that transaction shows that it is confirmed on Etherscan, your avatar is set!

### Try it out!

Refresh the page in the ENS Manager app, and you should see your ENS name and avatar on the left-hand side. It may take a few seconds for your NFT avatar to show up, but we're working on reducing this in the future.

![](../.gitbook/assets/1V2MZowhu-jLYBYzMeyTJUw.png)

Next, head over to OpenSea and search for your name. Refresh the metadata (click the circular arrow button on the top right), wait a few minutes, and then reload the page. Your avatar should now be the background image for the NFT image of your ENS name!

![](../.gitbook/assets/opensea.png)

Now go visit [app.uniswap.org](https://app.uniswap.org) and connect your wallet. Give it a few seconds, and your ENS name and avatar should show up!

![](../.gitbook/assets/uniswap.png)

Click on your name and you'll see it again.

![](../.gitbook/assets/uniswap\_accounts.png)

Lastly, go to [app.1inch.io](https://app.1inch.io) and connect your wallet. Similarly to Uniswap, you'll be able to first see it on the top right.

![](../.gitbook/assets/1inch.png)

Also, you'll be able to see it if you click your ENS name.

![](../.gitbook/assets/1inch\_accounts.png)

That's it! Have fun with your newly set NFT avatar!
