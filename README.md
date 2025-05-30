# MetaMass Crypto Wallet Extension

Build a Blockchain Crypto Wallet Chrome Extension | Connect to Any Blockchain (Full Project Tutorial)

A secure, feature-rich cryptocurrency wallet extension for Chrome that supports Ethereum and Polygon networks with dApp connectivity.

## Project Overview

![alt text](https://www.daulathussain.com/wp-content/uploads/2025/05/Build-a-Blockchain-Crypto-Wallet-Chrome-Extension-Connect-to-Any-Blockchain-Full-Project-Tutorial.jpg)

## Instruction

Kindly follow the following Instructions to run the project in your system and install the necessary requirements

- [Final Source Code]()

#### Setup Video

- [Final Code Setup video]()

## Features

### 🔐 Wallet Management

- **Create Multiple Wallets**: Generate new wallets with secure private key encryption
- **Import Existing Wallets**: Import wallets using private keys
- **Password Protection**: All private keys are encrypted with user passwords
- **Multiple Wallet Support**: Switch between different wallets seamlessly

### 🌐 Network Support

- **Ethereum Mainnet**: Full support for ETH transactions and ERC-20 tokens
- **Polygon Network**: Native MATIC support and Polygon-based tokens
- **Testnet Support**: Goerli and Mumbai testnets for development
- **Custom Networks**: Add any EVM-compatible network manually

### 🪙 Token Management

- **Native Token Support**: ETH, MATIC, and other native currencies
- **ERC-20 Tokens**: Add any ERC-20 token by contract address
- **Token Balance Display**: Real-time balance updates
- **Token Transfer**: Send tokens to any address

### 🔗 dApp Integration

- **Web3 Provider**: Compatible with existing Ethereum dApps
- **Transaction Signing**: Secure transaction approval workflow
- **Message Signing**: Support for personal message signing
- **Connection Management**: Control which dApps can access your wallet

### 🎨 User Interface

- **Dark/Light Themes**: Modern, responsive design
- **Intuitive Navigation**: Easy-to-use interface for all skill levels
- **Real-time Updates**: Live balance and transaction status updates
- **Mobile-Friendly**: Responsive design works on all screen sizes

#### Deploying Dapp

```
  WATCH: Hostinger
  Get : Discount 75%
  URL: https://www.hostg.xyz/aff_c?offer_id=6&aff_id=139422
```

#### Install Vs Code Editor

```
  GET: VsCode Editor
  URL: https://code.visualstudio.com/download
```

#### NodeJs & NPM Version

```
  NodeJs: v18.17.1 / LATEST
  NPM: 8.19.2
  URL: https://nodejs.org/en/download
  Video: https://youtu.be/PIR0oBVowXU?si=9eNdR29u37F2ujJJ
```

All you need to follow the complete project and follow the instructions which are explained in the tutorial by Daulat

## Final Code Instruction

If you download the final source code then you can follow the following instructions to run the Dapp successfully

#### Setup Video

```
  WATCH: Setup & Demo Of Project
  CODE URL:
  VIDEO:
```

#### Install Vs Code Editor

```
  GET: VsCode Editor
  URL: https://code.visualstudio.com/download
```

#### ARNK

```
  OPEN: ARNK.COM
  URL:https://www.ankr.com/rpc/
```

#### ALCHEMY

```
  OPEN: ALCHEMY.COM
  URL: https://www.alchemy.com/
```

#### TATUM

```
  OPEN: TATUM.IO
  URL: https://tatum.io/
```

## Important Links

- [Get Pro Blockchain Developer Course](https://www.theblockchaincoders.com/pro-nft-marketplace)
- [Support Creator](https://bit.ly/Support-Creator)
- [All Projects Source Code](https://www.theblockchaincoders.com/SourceCode)

## Authors

- [@theblockchaincoders.com](https://www.theblockchaincoders.com/)
- [@consultancy](https://www.theblockchaincoders.com/consultancy)
- [@youtube](https://www.youtube.com/@daulathussain)

## Installation

### From Source

1. **Download the Extension Files**

   ```
   - manifest.json
   - popup.html
   - background.js
   - content.js
   - injected.js
   - styles/popup.css
   - styles/additional.css
   - js/popup.js
   - js/utils/walletManager.js
   - js/utils/networkManager.js
   - js/utils/tokenManager.js
   - js/utils/uiManager.js
   - js/utils/storageManager.js
   ```

2. **Create Icons Folder**
   Create an `icons` folder and add icon files:

   - `icon16.png` (16x16 pixels)
   - `icon48.png` (48x48 pixels)
   - `icon128.png` (128x128 pixels)

3. **Load in Chrome**
   - Open Chrome and go to `chrome://extensions/`
   - Enable "Developer mode" in the top right
   - Click "Load unpacked"
   - Select the folder containing the extension files
   - The MetaMass Wallet extension should now appear in your extensions

## File Structure

```
metamass-wallet/
├── manifest.json              # Extension manifest
├── popup.html                # Main popup interface
├── background.js             # Service worker background script
├── content.js                # Content script for dApp integration
├── injected.js               # Web3 provider injection script
├── icons/                    # Extension icons
│   ├── icon16.png
│   ├── icon48.png
│   └── icon128.png
├── styles/                   # CSS stylesheets
│   ├── popup.css
│   └── additional.css
└── js/                       # JavaScript modules
    ├── popup.js              # Main popup logic
    └── utils/                # Utility modules
        ├── walletManager.js  # Wallet creation/management
        ├── networkManager.js # Blockchain network handling
        ├── tokenManager.js   # ERC-20 token management
        ├── uiManager.js      # User interface utilities
        └── storageManager.js # Chrome storage management
```

## Usage

### First Time Setup

1. **Click the MetaMass extension icon** in your Chrome toolbar
2. **Choose to create a new wallet or import an existing one**
   - **Create New**: Enter a wallet name and secure password
   - **Import**: Enter wallet name, private key, and password
3. **Your wallet is now ready to use!**

### Basic Operations

#### Viewing Balance

- Your native currency balance (ETH/MATIC) is displayed prominently
- Switch networks using the dropdown in the header
- Token balances are shown in the tokens section

#### Sending Transactions

1. Click the "Send" button
2. Enter recipient address and amount
3. Select the token to send (native currency or ERC-20 token)
4. Confirm the transaction

#### Adding Tokens

1. Click the "+" button in the tokens section
2. Enter the token contract address
3. Token information will be automatically retrieved
4. Click "Add Token" to confirm

#### Managing Multiple Wallets

- Use the wallet dropdown to switch between wallets
- Click the "+" button next to the wallet selector to add more wallets

### dApp Integration

#### Connecting to dApps

1. Visit a Web3-enabled website
2. Look for "Connect Wallet" buttons
3. Select MetaMass when prompted
4. Approve the connection in the popup

#### Transaction Approval

- When a dApp requests a transaction, MetaMass will open an approval popup
- Review the transaction details carefully
- Click "Approve" to sign and send, or "Reject" to cancel

## Security Features

### Private Key Protection

- All private keys are encrypted using industry-standard AES-GCM encryption
- Keys are derived from user passwords using PBKDF2 with 100,000 iterations
- Private keys never leave your device

### Auto-Lock

- Wallet automatically locks after a period of inactivity
- Lock time can be configured in settings
- Locked wallet requires password to access

### dApp Permissions

- Each dApp connection requires explicit user approval
- Permissions can be revoked at any time
- Connection status is clearly displayed

## Development

### Prerequisites

- Chrome browser with Developer mode enabled
- Basic knowledge of Web3 and Ethereum

### Building from Source

1. Clone or download all the provided files
2. Maintain the exact file structure as specified
3. Add appropriate icon files to the `icons` folder
4. Load the extension in Chrome using Developer mode

### Customization

- Modify `styles/popup.css` for UI theming
- Update `js/utils/networkManager.js` to add new networks
- Extend `js/utils/tokenManager.js` for additional token features

## API Integration

### RPC Endpoints

The extension uses public RPC endpoints by default:

- **Ethereum**: Multiple providers including Infura, Alchemy, Cloudflare
- **Polygon**: Official Polygon RPC and backup providers
- **Testnets**: Goerli and Mumbai testnet endpoints

### Custom RPC

You can add custom RPC endpoints in the network settings for:

- Private networks
- Alternative providers
- Local development networks

## Troubleshooting

### Common Issues

#### Extension Not Loading

- Ensure all files are in the correct structure
- Check that manifest.json is valid
- Verify Developer mode is enabled in Chrome

#### Transaction Failures

- Check network connectivity
- Verify sufficient balance for gas fees
- Ensure the recipient address is valid

#### dApp Connection Issues

- Refresh the webpage
- Check if the dApp supports MetaMass
- Try disconnecting and reconnecting

#### Balance Not Updating

- Switch networks and switch back
- Refresh the extension popup
- Check if the RPC endpoint is responsive

### Support

For technical issues or questions:

1. Check the browser console for error messages
2. Verify all files are correctly placed
3. Ensure you're using a compatible Chrome version

## Security Warnings

⚠️ **Important Security Notes:**

- Never share your private keys with anyone
- Always verify transaction details before approving
- Only download the extension from trusted sources
- Use strong, unique passwords for wallet encryption
- Regularly backup your wallet information

## Contributing

This is an open-source project. Contributions are welcome for:

- Bug fixes and security improvements
- Additional network support
- UI/UX enhancements
- Documentation improvements

## Disclaimer

This wallet extension is provided as-is for educational and development purposes. Users are responsible for:

- Securing their private keys and passwords
- Verifying transaction details before approval
- Understanding the risks associated with cryptocurrency transactions
- Keeping the extension updated with security patches

## License

This project is released under the MIT License. See the license terms for full details.

---

**MetaMass Wallet** - Your gateway to the decentralized web! 🚀
