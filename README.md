# MADNFTs Subgraph for indexing NFTs on Rinkeby Testnet

This project uses the
[ERC721MadNfts contract](https://rinkeby.etherscan.io/address/0x53358dB1825EFEed349915e31298aB464637b0E4),

See playground:
https://thegraph.com/hosted-service/subgraph/sunny0714/madnfts-rinkeby-subgraph

Feel free to extend the [`schema.graphql`](./schema.graphql) and the
[`mapping.ts`](./src/mapping.ts)

```
yarn install
yarn codegen
yarn build
yarn deploy
```

This will be extended to ERC1155 and Exchange smart contract
