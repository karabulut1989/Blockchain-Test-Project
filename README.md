# Blockchain-Test-Project
Test Project for Blockchain job

Test Project
Create and deploy an upgradeable ERC-721 NFT marketplace smart contract with auction functionalities.
This smart contract should be able to list an ERC-721 NFT with:
• Fixed price (eg., 0.0001 eth).
• An auction based listing for a specific time period, where the highest bid secures the NFT.
The smart contract should include the following functionalities:
1. List an NFT for fixed price (price should be provided by user).
2. List an NFT on auction basis for a specific time (highest bidder acquires the NFT).
3. Retrieve data of NFT(s) listed at a fixed price.
4. Retrieve data of NFT(s) listed on an auction basis.
5. Retrieve the auction end time for a specific NFT ID.
6. Retrieve wallets addresses of bidders for specific NFT ID.
7. Add a function to mint ERC-721 NFTs. (Note: Only wallet addresses with “MINTER_ROLE” can mint the
NFT, use the AccessControl smart contract).
Create a Node.js backend script with functions to call the above functionalities of the smart contract, and
use ethers.js library for smart contract calls.
Deploy the smart contracts on the Goerli Testnet.
Additionally, provide MINTER_ROLE to this wallet address as well:
0xFbB28e9380B6657b4134329B47D9588aCfb8E33B
Note:
• All deployed smart contracts should be upgradeable.
• Deploy smart contracts using hardhat. Including test cases for the smart contract would be an advantage.
• Using of OpenZeppelin 5.0 contracts would be an advantage.
• Maintain an organized and maintainable project structure.
You have 3 days to complete this test project. Please upload your project to GitHub and share your GitHub
repository link.
Feel free to reach out if you have any questions.
Good luck with your project!
