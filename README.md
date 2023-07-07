# NFT-Collection

Enables whitelisted users to mint a collection of NFTs named `Brahmaputra NFTs` on the Sepolia testnet. The <br />

The project can be viewed [here](https://nft-collection-five-mu.vercel.app/). <br />

The contract can be accessed [here](https://sepolia.etherscan.io/address/0xE68EFffB7caD10C0AdD9522055c4c9F2ee0e2393). <br />

The collection can be viewed [here](https://sepolia.etherscan.io/token/0xe68efffb7cad10c0add9522055c4c9f2ee0e2393).

## More Details

The dApp has been deployed on Sepolia Testnet of Ethereum. The backend of the dApp has been created using [Hardhat](https://hardhat.org/) and is available in the [hardhat-tutorial](https://github.com/Tanmay-Bhatnagar-03/NFT-Collection/tree/main/hardhat-tutorial) directory. Whitelist smart contract script is available in [hardhat-tutorial/contracts](https://github.com/Tanmay-Bhatnagar-03/NFT-Collection/tree/main/hardhat-tutorial/contracts) directory and it is written in [Solidity](https://soliditylang.org/). The deployment script for the smart contract is written in [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript). <br />
The frontend of the website has been created by [Next.js](https://nextjs.org/) and deployed on [Vercel](https://vercel.com/). The website automatically sends a prompt to connect your wallet ([MetaMask](https://metamask.io/)) and you are then required to approve the request in the wallet, click the `Join the Whitelist` button and your wallet address is stored in the contract itself (on-chain). Be sure to change your network to [Sepolia](https://sepolia.dev/) in the wallet.  

## Upcoming

- [x] The dApp connects to the wallet automatically.
- [x] Project has been deployed on Sepolia and hence, users have to change their network to Sepolia before complete functionality is unlocked.
- [x] The upper limit on whitelisted users has been set to 10.
- [x] On clicking one button, the wallet address (public key) gets stored in the contract and can be accessed by the contract owner at any time.
- [x] The whitelisted users have to be given special privileges in the upcoming projects, such as NFT minting, token minting, etc.

## Contribution

Feel free to contribute to this project to make it better!

## License

This project has an MIT License.

## Made by love

- [StarterTemplates](https://twitter.com/startertemp)
- [LearnWeb3DAO](https://learnweb3.io)
