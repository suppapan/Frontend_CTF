Quick start
The first things you need to do are cloning this repository and installing its dependencies:

git clone https://github.com/nomiclabs/hardhat-hackathon-boilerplate.git
cd hardhat-hackathon-boilerplate
npm install
Once installed, let's run Hardhat's testing network:

npx hardhat node
Then, on a new terminal, go to the repository's root folder and run this to deploy your contract:

npx hardhat run scripts/deploy.js --network localhost
Finally, we can run the frontend with:

cd frontend
npm install
npm start
Note: There's an issue in ganache-core that can make the npm install step fail.

If you see npm ERR! code ENOLOCAL, try running npm ci instead of npm install.

Open http://localhost:3000/ to see your Dapp. You will need to have Metamask installed and listening to localhost 8545.
