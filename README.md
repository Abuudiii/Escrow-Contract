# Escrow-Contract

<h2>A demo of an escrow smart contract with a web UI<h2>

<h3>Follow the steps to setup the contract and launch it on the web interface:</h3>

1. Set up Ganache or ganache-cli -d, and change "/express/index.js:3" from 8545 to 7545 if needed
2. Compile Escrow.sol and deploy
3. cd into "/express" and "npm i", then perform "node index"
4. cd into "/react" and "npm i", then perform "npm start"
5. If not auto-launched, navigate to http://localhost:3000
6. Deposit from '0xFFcf8FDEE72ac11b5c542428B35EEF5769C409f0' to the Escrow
7. Make a payment from '0xFFcf8FDEE72ac11b5c542428B35EEF5769C409f0' to '0x22d491Bde2303f2f43325b2108D26f1eAbA1e32b' within the Escrow's safe
8. Withdraw from the Escrow to '0x22d491Bde2303f2f43325b2108D26f1eAbA1e32b'
9. ETH was moved from 0xFFc...0f0 to 0x22d...32b within the safe and can now be withdrawn by 0x22d...32b

