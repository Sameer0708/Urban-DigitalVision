# 🌐 Urban DigitalVision: Empowering Cities with Blockchain

Welcome to Urban DigitalVision – a dual-module platform that integrates blockchain technology for secure and decentralized governance. This project includes:

- ✅ Decentralized File Storage (DFS) – Ensures tamper-proof file uploads using IPFS and smart contracts.
- ✅ Land Registration System (LRS) – Offers a transparent and immutable land record management system.

For DFS to Run we have to run commands below:
we have to make(split) 3 different terminal
1st terminal: npm start
2nd terminal: npx hardhat node
3rd terminal: npx hardhat run --network localhost scripts/deploy.js

For LRS to Run we have to run commands below:
npm install(in root directory)
truffle compile
truffle migrate --network development(for this ganache should be running in BG)
change to front-end(cd front-end)
npm install --legacy-peer-deps
npm start
