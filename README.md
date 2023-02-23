mkdir NFT-Collection
cd NFT-Collection
mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat

npm install --save-dev @nomicfoundation/hardhat-toolbox

npx hardhat   选择Create a Javascript Project
npm install @openzeppelin/contracts

创建 IWhitelist.sol
创建 CryptoDevs.sol
npm install dotenv

创建 .env 
包含内容
QUICKNODE_HTTP_URL="add-quicknode-http-provider-url-here"

PRIVATE_KEY="add-the-private-key-here"

创建 scripts/deploy.js
创建 目录constants  里面创建文件 index.js
修改 hardhat.config.js 进行配置

npx hardhat compile
npx hardhat run scripts/deploy.js --network goerli
链端完毕

----------------------------

前端
在目录 NFT-Collection 下面
npx create-next-app@latest    全部回车
cd my-app
npm run dev

搭好框架后进行开发

npm install web3modal
npm install ethers@5
修改 Home.modules.css
修改 pages/index.js 

在目录my-app 下面创建目录constants 在下面创建文件index.js
配置两个参数
export const abi =---your abi---
export const NFT_CONTRACT_ADDRESS = "address of your NFT contract"

运行 npm run dev
