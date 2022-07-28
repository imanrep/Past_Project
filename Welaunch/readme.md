# Development website
We currently on development, make sure you using **BSC-tsnt** parameter
https://development-app.welaunch.app/?chain=BSC-tsnt

# Directory

## Frontend

### Next
This is frontend of client using NextJS for proccessing web3.js / web3Modal / WalletConnect.

## Backend

### Chat
Chat Directory is a Backend to chat for the launchpad, from user to user using NodeJS to check the web3 token, minimum holding etc.
If user according the condition, NodeJS will post to my Backend to save the data on MySQL.
There is no POST data in here!
User will send data using GET using custom header and encoded data

### PaidTrending
Project Owner must be holding or burn web3 Token to get Trending on home section. PaidTrending fetched every people hit the HomePage.
I'm using NodeJS btw.

### Solidity
Using Remix as EVM (Ethereum Virtual Machine) to deploy the Smart Contract to Testnet, and validation for web3 things.
Why im using testnet on Remix ? Why im not using framework like Ganache, Hardhat ?

- Remix on testnet is better to check the development, fast, and easy.
- I do use Ganache / Hardhat, but its better to development for your own chain or your own data.

### Trending
Trending section is the algorithm where people access the website, they will GET the trending, and my NodeJS program will be count it's self from all of Contract Address and return from the best of the best. 
