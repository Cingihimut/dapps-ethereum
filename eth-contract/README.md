<h1 align="center" id="title">Smart Contract Development</h1>
<p id="description">Welcome to this smart contract development repository!🖐 This repository is designed to facilitate the development and implementation of smart contracts using Hardhat, a powerful Ethereum development tool. This project is optimized for deployment on the Sepolia Testnet, with support from Infura API endpoint for reliable connections.</p>

✌ Try running some of the following tasks:

```shell
git clone https://github.com/your-username/smart-contract-repo.git
```
Install project dependencies by running the command:
```shell
npm install
```
🔌Configure Infura API Endpoint
- Obtain an API key from Infura
- Replace the value of INFURA_API_KEY in the .env file with the obtained API key.
 
🖥Compilation and Deployment to Sepolia Testnet:
- Adjust the configuration in `hardhat.config.js` if needed.
- Run the command for compilation and deployment to Sepolia Testnet:
  ```shell
  npx hardhat run scripts/deploy.js --network sepolia
  ```
