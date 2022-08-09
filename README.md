Whitelist Dapp to give your early supporters access to a whitelist for your collection!
![image](https://user-images.githubusercontent.com/102557215/183715708-1b036132-a178-4799-b5d0-2da65c11bf04.png)
Deployed on vercel : https://whitelist-dapp-nine-lemon.vercel.app/

Contract Dependencies:
npm init --yes
npm install --save-dev hardhat
npx hardhat // in same folder
Select Create a basic sample project
Press enter for the already specified Hardhat Project root
Press enter for the question on if you want to add a .gitignore
Press enter for Do you want to install this sample project's dependencies with npm (@nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers)?
Additional for windows users
npm install --save-dev @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers
npm install dotenv //for env file package
npx hardhat compile // compile
npx hardhat run scripts/deploy.js --network rinkeby


my-app terminal dependencies
For Front end:
Create my-app folder
npx create-next-app@latest //packages for nextjs
cd my-app
npm run dev // local host will be working with nextjs 
npm install web3modal
npm install ethers
