# rksol-cli

`rksol-cli` is a command-line interface (CLI) tool for interacting with the Solana blockchain. With this tool, you can generate a new keypair, request an airdrop, and send SOL to another public key.

## Features

- Generate a new Solana keypair
- Request an airdrop on the Solana Devnet
- Send SOL to another public key

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (v6 or later)

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/rksol-cli.git
    cd rksol-cli
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Compile the TypeScript code:

    ```bash
    npm run build
    ```

4. Link the CLI tool globally:

    ```bash
    npm link
    ```

## Usage

### Generate a New Keypair

To generate a new Solana keypair:

```bash
rksol generate
```

This will generate a new keypair and save it to keypair.json in the current directory. The public key will be displayed in the console.

### Request an Airdrop
To request an airdrop of 1 SOL on the Solana Devnet:

```bash
rksol airdrop <publicKey>
```

Replace <publicKey> with the public key for which you want to request an airdrop.

### Send SOL
To send SOL to another public key:

```bash
rksol send <recipientPublicKey> <amount>
```
Replace <recipientPublicKey> with the recipient's public key and <amount> with the amount of SOL to send.

## Development
Compiling TypeScript
To compile the TypeScript code:

```
npm run build
```

## Running the CLI Tool
To run the CLI tool in development:

```
chmod +x dist/index.js

npm link

```
<img width="1136" alt="Screenshot 2024-07-29 at 11 54 09 AM" src="https://github.com/user-attachments/assets/8bbf9b04-e429-4b05-a0ab-7466e0d1c404">


### License
This project is licensed under the MIT License - see the LICENSE file for details.

