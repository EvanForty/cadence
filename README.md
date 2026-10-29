# Cadence

The credit layer for autonomous agents on Solana. Credit moves at the speed of agents.

A static site: no build step, no dependencies to install.

## Files

- `index.html` - the whole site (styles and scripts inline)
- `favicon.svg` - the Cadence pixel logo
- `vercel.json` - Vercel settings

Libraries load from CDNs at runtime: three.js (3D colonnade) and @solana/web3.js (wallet connect).

## Deploy to Vercel

1. Push these files to the root of a GitHub repo.
2. In Vercel, choose Add New > Project and import the repo.
3. Framework preset: Other. Leave the build command and output directory empty.
4. Deploy.

## Before going live

- Figures, agents and ledger entries on the page are a devnet simulation and are labelled as such.
- The wallet uses `CLUSTER = 'devnet'`. Switch to `'mainnet-beta'` and a dedicated RPC endpoint for production.
- The skill line points to `https://cadence.so/skill.md`. Replace it with your real domain.

X: https://x.com/CadenceCredits