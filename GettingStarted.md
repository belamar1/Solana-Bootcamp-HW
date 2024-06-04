# 🚀 Getting Started with Solana Bootcamp

Before you begin, make sure you have both Rust and Solana CLI installed. If you're running on MacOS M1 and encounter issues, we recommend not using brew to install Rust. Instead, use curl or install from source.

### Install and Build

1. Install dependencies and build: This will create binary files for each of the examples in `examples_baremetal/` inside `target/`.

   ```bash
   npm install
   npm run build
Set your config to localhost:

   ```bash
Copy code
solana config set --url localhost
Run in a separate terminal window: This will spin up a local Solana cluster for you with the RPC endpoint defaulted to localhost:8899, equivalent to running solana-test-validator --reset.

   ```bash
Copy code
npm run start-local-cluster
Monitor the logs in a separate window by running:

   ```bash
Copy code
solana logs
Commands for Each Example
For each example, follow these commands:

Deploy the program:

   ```bash
Copy code
npm run deploy:n
Replace n with the example number from 1 to 7. This script deploys the program to the network specified in the Solana config.

Interact with the contract:

   ```bash
Copy code
npm run call:n
Replace n with the example number from 1 to 7.

Devnet
If you want to use Devnet, run:

   ```bash
Copy code
solana config set --url https://api.devnet.solana.com
or

   ```bash
Copy code
solana config set --url devnet
Now you're all set to dive into the Solana Bootcamp examples! Happy coding! 🌟
