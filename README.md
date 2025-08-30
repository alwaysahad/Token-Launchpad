# Token Launchpad

## Description

This project is a simple Solana Token Launchpad built with React and Vite. It provides a user interface to create SPL tokens on the Solana devnet. Users can input the token's name, symbol, image URL, and initial supply, and create the token mint account.

Note: The current implementation creates the mint account but does not yet handle minting the initial supply or uploading the image. These features are placeholders.

## Prerequisites

- Node.js (version 18 or higher) and npm
- A Solana-compatible wallet (e.g., Phantom) for connecting to the app

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/token-launchpad.git
   cd token-launchpad
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Running the App

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:5173` (or the port shown in the console).

3. Connect your wallet using the "Connect Wallet" button.

4. Fill in the token details:
   - Name: The name of your token
   - Symbol: The token symbol (e.g., TOK)
   - Image URL: URL to the token's image (not yet implemented)
   - Initial Supply: The initial amount of tokens (not yet implemented for minting)

5. Click "Create a token" to create the token mint on Solana devnet.

## Dependencies

- React
- @solana/web3.js
- @solana/spl-token
- @solana/wallet-adapter-react and related packages for wallet integration

## Development

- To lint the code: `npm run lint`
- To build for production: `npm run build`
- To preview the build: `npm run preview`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.