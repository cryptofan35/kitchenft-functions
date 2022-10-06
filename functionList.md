_KitcheNFT Functions_

1. **Create Collection**

- Create collection with collection name, banner, logo image etc.
- Set royalty fee on this page.
- You also set blockchain(Velas or Binance smart chain) to deploy it.
- It doesn't call any contract.

2. **Create NFT**

- Create NFT with nft image or video, name, properties etc.
- It isn't minted on this step because we are using lazy minting.
- If you are create a new NFT, any users can make offer about the nft with wrapped token. And you can accept or cancel it. If you are accept it, the owner will be changed and it will be minted on chain.

3. **List NFT**

- List your NFT on marketplace to trade it.
- You can list your nft with fixed or timed method. Once you list your nft, users can buy it directly or make an offer about it.
- You can also cancel list it on the NFT detail page or decrease value on it.

4. **Mint NFT**

- When your NFT is traded firstly on our platform, it will be minted on chain. At this point the collection is deployed on chain and added on the marketplace.

5. **Transfer NFT**

- You can transfer your NFT to the other address without payment(It doesn't mean txn gas fee.). Of course, at this point if you NFT isn't minted yet, it will be minted on chain before it is transferred.

6. **Buy or Sell NFT**

- Once you listed your NFT on the kitchenft, users can buy the NFT directly.
- But if the user make an offer, you should accept it to sell NFT. When you click the accept button, the sell txn will be occured.

7. **Filtering NFTs**

- You can filter or search nfts with several conditions on all nfts page or collection detail pages.

8. **Search NFTs**

- You can search NFTs using the search box on the heard.
- It returns collections and NFTs are matched with your search index.

9. **Rankings**

- You can check collection ranking with serveral sort indexes(ex: volume, 24h% etc)

10. **Activities**

- You can find all activies are performed on the kitchenft.
- You can filter on this page, too.

11. **Apply Launchpad**

- Apply with launchpad detail info.
- If admin accept the launchpad, you will see `Add to launchpad` option on lauchpad submenu.

12. **Add to Launchpad**

- You should insert launchpad info to create launchpad collection.
- Insert collection hash(IPFS hash value)
- Here is metadata standard.

```
{
    name: "Velaspunk #1",
    description: "Velas punk collection",
    attributes: [
      { type: "Background", value: "red" },
      { type: "Color", value: "black" },
    ],
    image:"https://kitchenft.mypinata.cloud/ipfs/QmbqAH7RQfkWX9sGotuW8mMD1sXCbjBAdxxxXZLFY6BnDE/1.png",
}
```

13. **Add step on launchpad collection**

- You can add steps on your launchpad colleciton(ex: Private Sale, Public Sale, etc)
- You can set whitelist so that users can mint.
- If users mint NFT, you can find NFTs on kitchenft.

14. **Import Collection**

- Import collection deployed on the other platform with contract address.
- It will take some time. So you can't find your collection soon.

15. **Add Profile**

- You can set profile setting with banner, logo, email address, social links etc.
- Once you set them, users will find you on your account page.

16. **Add to Watchlist**

- You can make watchlist with collections.
- Only traded collections will be displayed on it.

17. **Add to favorite**

- You can get favorite nfts on NFT detail page.
- They will be displayed on favorite page.
