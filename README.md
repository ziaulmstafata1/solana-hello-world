# Solana Wallet Balance Checker and Airdrop Script
This Node.js script utilizes Solana's web3 functionalities to check the balance of a wallet and perform an airdrop of SOL tokens to it. Follow the steps below to run the script:

# Prerequisites
. Node.js installed on your system.
. Basic understanding of JavaScript and Node.js.
# Instructions
. Clone this repository to your local machine.
. Navigate to the directory containing the README.md file.
. Install dependencies by running npm install in your terminal.
. Run the script by executing node <filename>.js in your terminal, replacing <filename> with the name of the file containing the script.

# Notes
. The script generates a new keypair for the wallet if not provided.
. It connects to the Solana devnet cluster by default. Modify clusterApiUrl("devnet") to connect to other clusters.
. The script prompts the user to input their public address.
. It performs an airdrop of 2 SOL tokens to the specified wallet.
. The wallet balance is displayed before and after the airdrop.
