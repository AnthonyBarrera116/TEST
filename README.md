# CryptoCoin

# College-token
 * Make a .env file and paste in
   * PRIVATE_KEY = 
   * INFURA_RINKEBY_ENDPOINT=  https://sepolia.infura.io/v3/3a425a766a6a454abdfa2196ef9a62da
   
  * put your private key of the wallet
  * Deploy contract to TestNet
    * npx hardhat run --network Goreli scripts/deploy.js
    (NOTE IN CONSOLE: it will give you your blockchain address contract)
   
   * After this take the contract address made from the deploy and put the address of the contract in the deplyf.js
   * do npx hardhat run --network Goreli scripts/deplyf.js
   * in metamask import the coin to your wallet with the address made from deploy.js
   * Send coin to the deplyf.js address from the wallat that has all the coin

# SRC/App
  * change Faucet Address in line 33 and 56. new ethers.Contract(FAUCET ADDRESS,contractABI,provider)
  # click the Source control in vicual studio the branch on bvelow the magnifying glass click that and add a clone of repository
  * when done you must connect your github. 
    * git init
    * git remote add origin git@github.com:AnthonyBarrera116/"Name of Repository".git
  * In Package Json change "homepage": "http://"Username of giuthub".github.io/"Name of repository"
  * 
  

Sepolia faucet: https://sepoliafaucet.com/

TestNet contract look up: https://sepolia.etherscan.io/

https://sepolia.etherscan.io/token/0xfA96a0A682d26212D3911bFf13f001626679cD9D
0xfA96a0A682d26212D3911bFf13f001626679cD9D- Contract Deployed

https://sepolia.etherscan.io/token/0xfa96a0a682d26212d3911bff13f001626679cd9d?a=0xC2ffc2F6E316CE12eA7ED2A4ce666171A312895d
0xC2ffc2F6E316CE12eA7ED2A4ce666171A312895d - Faucet


API web: https://app.infura.io/

