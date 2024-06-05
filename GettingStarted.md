# 🚀 Getting Started with Solana Bootcamp

Before you begin, make sure you have both Rust and Solana CLI installed. If you're running on MacOS M1 and encounter issues, we recommend not using brew to install Rust. Instead, use curl or install from source.

### Install and Build

1. Install dependencies and build: This will create binary files for each of the examples in `examples_baremetal/` inside `target/`.

   ```bash
   npm install
   npm run build
2. Set your config to localhost:
   
   ```bash
   solana config set --url localhost
3. Run in a separate terminal window: This will spin up a local Solana cluster for you with the RPC endpoint defaulted to localhost:8899, equivalent to running solana-test-validator --reset.

   ```bash
   npm run start-local-cluster
4. Monitor the logs in a separate window by running:

   ```bash
   solana logs
   
Now you're all set to dive into the Solana Bootcamp examples! Happy coding! 🌟
