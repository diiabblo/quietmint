# StackMint - Decentralized NFT Marketplace on Stacks

StackMint is a premier NFT marketplace and auction platform built on the Stacks blockchain, leveraging Clarity smart contracts for secure, transparent, and efficient digital asset trading.

## Key Features

- **NFT Minting**: Create and deploy SIP-009 compliant NFTs with customizable metadata.
- **Marketplace**: List NFTs for sale with fixed prices or open offers.
- **Auctions**: Create time-bound auctions with reserve prices and extended bidding periods.
- **Bundles**: Sell multiple NFTs as a single package.
- **Escrow System**: Secure fund management ensuring safe transactions between buyers and sellers.
- **Royalty Support**: Built-in royalty enforcement for creators on secondary sales.

## Project Structure

- `contracts/`: Clarity smart contracts (SIP-009 NFT, Marketplace, Treasury).
- `frontend/`: Next.js 14 frontend application.
- `tests/`: Clarinet test suite (in progress).

## Getting Started

### Prerequisites

- [Clarinet](https://github.com/hirosystems/clarinet) (for contract development)
- Node.js v18+ & npm/yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/stacksmint/stacksmint.git
   cd stacksmint
   ```

2. Install dependencies:
   ```bash
   npm install
   cd frontend && npm install
   ```

### Development

To run the local Stacks devnet and test contracts:

```bash
clarinet integrate
```

To start the frontend:

```bash
cd frontend
npm run dev
```

## Contributing

Please check `CONTRIBUTING.md` for details on how to contribute to this project.

## License

MIT

---

## Project Status

🚀 **Active Development** - This project is under active development and welcomes contributions.

## Getting Involved

- Check out our [Contributing Guidelines](./CONTRIBUTING.md)
- Join the discussion in [GitHub Issues](../../issues)
- Follow development updates

---

## Artist & Creator Onboarding

### Getting Started as a Creator

#### Step 1: Wallet Setup
1. Install a Stacks-compatible wallet (Leather, Xverse, or Hiro)
2. Fund your wallet with STX for transaction fees
3. Verify your wallet address for NFT minting

#### Step 2: Create Your Collection
1. Design your NFT artwork (recommended: 1000x1000px, under 10MB)
2. Prepare metadata (name, description, attributes)
3. Mint your first NFT on QuietMint
4. Set up your creator profile

#### Step 3: List for Sale
1. Choose between fixed-price or auction listing
2. Set competitive pricing based on market rates
3. Add detailed descriptions and unlockable content
4. Promote your collection on social media

### Creator Benefits
- **Royalty Enforcement:** Automatic 5-10% royalties on secondary sales
- **Bundle Support:** Create themed collections and bulk listings
- **Auction Flexibility:** Time-bound auctions with reserve prices
- **Community Building:** Direct connection with collectors

### Supported File Types
- **Images:** PNG, JPG, GIF, SVG, WebP
- **Video:** MP4, MOV, AVI (max 100MB)
- **Audio:** MP3, WAV, FLAC
- **3D Models:** GLTF, GLB, OBJ

### Best Practices
- **Consistent Branding:** Maintain cohesive collection themes
- **Fair Pricing:** Research comparable collections
- **Community Engagement:** Respond to collectors and build relationships
- **Regular Drops:** Maintain momentum with scheduled releases

