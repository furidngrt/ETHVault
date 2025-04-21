# ETHVault - Ethereum Staking & Governance Platform

ETHVault is a decentralized platform for Ethereum staking, governance, and participation in the Ethereum ecosystem. It allows users to stake ETH, earn rewards, and vote on proposals that shape the future of the protocol.

## Features

- **ETH Staking**: Deposit ETH and receive dETH tokens at a 1:1 ratio
- **Stake dETH**: Stake your dETH tokens to receive sETH governance tokens
- **Governance**: Create and vote on proposals using sETH tokens
- **Leaderboard**: View top stakers and their contributions
- **Dashboard**: Monitor your balances and protocol statistics
- **Responsive Design**: Fully responsive UI that works on desktop and mobile devices

## Technology Stack

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **Blockchain Interaction**: ethers.js
- **Smart Contracts**: Solidity (ERC20-based tokens)
- **UI Components**: shadcn/ui
- **State Management**: React Hooks

## Smart Contracts

The platform is built on four main smart contracts:

1. **DepositETH (dETH)**: ERC20 token that users receive when depositing ETH
2. **StakedETH (sETH)**: ERC20 token that users receive when staking dETH
3. **Governance**: Handles proposal creation, voting, and execution
4. **StakingDashboard**: Provides statistics and leaderboard functionality

## Getting Started

### Prerequisites

- Node.js 16.x or higher
- Metamask or another Ethereum wallet
- Access to Ethereum Holesky testnet

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ethvault.git
   cd ethvault
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Connecting to the Platform

1. Make sure your wallet is connected to the Holesky testnet
2. Click "Connect Wallet" in the application
3. You can now interact with the platform

## Project Structure

```
ethvault/
├── app/                  # Next.js app router pages
├── components/           # React components
│   ├── layout/           # Layout components
│   └── ui/               # UI components
├── contracts/            # Smart contract source code
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions and ABIs
│   └── abis/             # Contract ABIs
├── public/               # Static assets
└── styles/               # Global styles
```

## Contract Address (Holesky Testnet)

- **dETH**: 0x520d7dAB4A5bCE6ceA323470dbffCea14b78253a
- **sETH**: 0x16b0cD88e546a90DbE380A63EbfcB487A9A05D8e
- **Governance**: 0xD396FE92075716598FAC875D12E708622339FA3e
- **StakingDashboard**: 0xd33e9676463597AfFF5bB829796836631F4e2f1f

## Workflow

1. **Deposit ETH**: Users deposit ETH and receive dETH tokens
2. **Stake dETH**: Users stake dETH tokens and receive sETH tokens
3. **Governance**: Users with sETH can create and vote on proposals
4. **Unstake**: Users can unstake their sETH to receive dETH back
5. **Withdraw**: Users can withdraw their dETH to receive ETH back

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

plaintext file="LICENSE"
MIT License

Copyright (c) 2023 ETHVault

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
