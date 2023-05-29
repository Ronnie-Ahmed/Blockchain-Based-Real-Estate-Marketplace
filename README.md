
# Blockchain Based Real Estate Marketplace(BlockEstate)
BlockEstate is a blockchain-based real estate marketplace that allows users to list and buy properties using the Ethereum blockchain. It is developed using various technologies and tools, including the ERC721 library, Hardhat, IPFS, Ethers.js, React.js, Tailwind CSS, and HTML5.

The frontend of BlockEstate is built using React.js, Tailwind CSS, and HTML5. It provides a user-friendly interface for users to interact with the marketplace. Users can connect their MetaMask wallet to the platform to access their Ethereum accounts and perform transactions.

To list a property, users can provide property information such as address, description, price, and any additional details required. This information is stored securely on the Ethereum blockchain using the ERC721 standard. Each property is represented as a unique non-fungible token (NFT), allowing for easy ownership tracking and transfer.

The buy page of BlockEstate displays all the listed properties available for purchase. Users can browse through the listings and click on "Learn More" to view detailed information about a specific property. This information may include images, property features, seller information, and any other relevant details.

Additionally, BlockEstate provides a feature that allows users to view their own listed properties. This gives sellers the ability to manage and monitor their listings easily.

The backend of BlockEstate is implemented using Solidity, the programming language for writing smart contracts on the Ethereum blockchain. Ethers.js is used as a JavaScript library to interact with the Ethereum network and perform transactions. IPFS (InterPlanetary File System) is used for storing and retrieving property images and other large data files.

NPM (Node Package Manager) is utilized as the package manager for managing dependencies and ensuring the smooth functioning of the application.

Overall, BlockEstate aims to create a decentralized and transparent marketplace for buying and selling real estate properties using the power of blockchain technology.





## Authors

- [@Raisul Islam](https://www.github.com/Ronnie-Ahmed)




## Tech Stack

**Frontend:** React, TailwindCSS , HTML

**Backend:** Solidity, Ethers.js




## Installation

Install my-project with npm

```bash
  npm install my-project
  git clone git@github.com:Ronnie-Ahmed/Blockchain-Based-Real-Estate-Marketplace.git
  cd Blockchain-Based-Real-Estate-Marketplace
  npm install
  npx hardhat node
  npx hardhat run .\scripts\deploy.js --network   localhost
  cd frontend
  npm install
  npm run start
```
    
```![home](https://github.com/Ronnie-Ahmed/Blockchain-Based-Real-Estate-Marketplace/assets/68500792/5ebf6666-0ccb-4a2c-b514-6619d6fa2b85)



