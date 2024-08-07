# SWISSTRONIK Technical Task 4

Steps to mint PERC-20 Token

1. Clone repository
```shell
https://github.com/fung93/swisstronik-perc20-task-4.git
```
```shell
cd swisstronik-perc20-task-4
```
2. Install Dependency
```shell
npm install
```
3. Set .env File
```shell
PRIVATE_KEY="your private key"
```
4. Update Smart Contract (Skipp if you won't modify Token name)
- Open contracts folder
- Open PERC20Sample.sol file
- Feel free to modify token name and token symbol
5. Compile Smart Contract
```shell
npm run compile
```
6. Deploy Smart Contract
```shell
npm run deploy
```
7. Mint Token
```shell
npm run mint
```
8. Transfer Token
9. Final
   - Copy the address and paste the address to testnet dashboard
   - Copy the transaction link to testnet dashboard
   - Push this project to your github and paste the repository link to testnet dashboard
