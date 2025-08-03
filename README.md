# Only Tokens

A comprehensive cross-chain token transaction platform with smart contracts, frontend dashboard, and swap functionality.

## Project Structure

This repository contains three main components organized as git submodules:

### 🎨 [only-tokens-dashboard](https://github.com/patiee/only-tokens-dashboard)
**Frontend Application**
- Modern web interface for interacting with deployed smart contracts
- Enables cross-chain transactions through a user-friendly dashboard
- Provides seamless user experience for token operations across multiple blockchains

### 🔧 [only-tokens-smart-contracts](https://github.com/patiee/only-tokens-smart-contracts)
**Smart Contract Suite**
- Complete collection of deployed smart contracts for cross-chain functionality
- Supports multiple blockchain networks
- Handles token operations, transfers, and cross-chain bridges
- Includes comprehensive testing and deployment scripts

### 🔄 [only-tokens-swap](https://github.com/patiee/only-tokens-swap)
**Swap Integration Module**
- 1inch API integration for token swapping functionality
- Designed to be merged into the dashboard for enhanced trading capabilities
- Provides best-price routing and liquidity aggregation
- Enables users to swap tokens efficiently across multiple DEXs

### 💼 [only-tokens-wallet](https://github.com/patiee/only-tokens-wallet)
**Browser Wallet Extension**
- Multi-chain browser extension supporting EVM, Cosmos, and Dogecoin networks
- Seamless integration with only-tokens-dashboard and only-tokens-swap
- Provides secure wallet interface for cross-chain transactions
- Enables users to manage multiple blockchain accounts from a single extension

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- Git
- Access to the required blockchain networks

### Installation

1. **Clone the main repository:**
   ```bash
   git clone <repository-url>
   cd only-tokens
   ```

2. **Initialize and update submodules:**
   ```bash
   git submodule init
   git submodule update
   ```

3. **Install dependencies for each component:**
   ```bash
   # Dashboard
   cd only-tokens-dashboard
   npm install
   
   # Smart Contracts
   cd ../only-tokens-smart-contracts
   npm install
   
   # Swap Module
   cd ../only-tokens-swap
   npm install
   
   # Wallet Extension
   cd ../only-tokens-wallet
   npm install
   ```

## Development

### Dashboard Development
```bash
cd only-tokens-dashboard
npm run dev
```

### Smart Contract Development
```bash
cd only-tokens-smart-contracts
npm run test
npm run deploy
```

### Swap Integration
The swap module is designed to be integrated into the dashboard, providing 1inch API functionality for enhanced trading capabilities.

### Wallet Extension Development
```bash
cd only-tokens-wallet
npm run build
npm run dev
```

## Architecture

```
only-tokens/
├── only-tokens-dashboard/     # Frontend application
├── only-tokens-smart-contracts/ # Smart contract suite
├── only-tokens-swap/         # 1inch integration module
└── only-tokens-wallet/       # Browser wallet extension
```

## Features

- **Cross-Chain Transactions**: Seamless token transfers across multiple blockchains
- **Smart Contract Integration**: Direct interaction with deployed contracts
- **1inch Swap Integration**: Best-price routing for token swaps
- **Multi-Chain Wallet**: Browser extension supporting EVM, Cosmos, and Dogecoin
- **Modern UI/UX**: User-friendly dashboard interface
- **Multi-Chain Support**: Compatible with multiple blockchain networks

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

[Add your license information here]

## Support

For questions and support, please open an issue in the respective submodule repository or contact the development team.
