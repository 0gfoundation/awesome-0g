# 0G Tooling Hub

> Your one-stop resource for building on 0G — the first decentralized AI operating system

0G combines the fastest, infinitely scalable data availability layer, the most affordable decentralized storage system, and a flexible framework for inference and fine-tuning — enabling resource-intensive AI applications to run on-chain with unparalleled performance.

## Contents

- [Getting Started](#getting-started)
- [SDKs & Libraries](#sdks--libraries)
- [Starter Kits](#starter-kits)
- [Developer Tools](#developer-tools)
- [RPC & Infrastructure Providers](#rpc--infrastructure-providers)
- [Documentation Reference](#documentation-reference)
- [AI & Zero-Code Tools](#ai--zero-code-tools)
- [Technical Blogs](#technical-blogs)
- [Tutorials](#tutorials)
- [Community & Links](#community--links)
- [Contributing](#contributing)

---

## Getting Started

| Resource | Link |
|----------|------|
| Documentation | [docs.0g.ai](https://docs.0g.ai/) |
| Builder Hub | [build.0g.ai](https://build.0g.ai/) |
| Testnet Faucet | [faucet.0g.ai](https://faucet.0g.ai/) |
| Chain Scan (Testnet) | [chainscan-galileo.0g.ai](https://chainscan-galileo.0g.ai/) |
| Chain Scan (Mainnet) | [chainscan.0g.ai](https://chainscan.0g.ai/) |
| Storage Scan (Testnet) | [storagescan-galileo.0g.ai](https://storagescan-galileo.0g.ai/) |

### Testnet Configuration (Galileo)

| Parameter | Value |
|-----------|-------|
| Network Name | 0G-Galileo-Testnet |
| Chain ID | `16601` |
| RPC Endpoint | `http://evmrpc-testnet.0g.ai` |
| Token Symbol | OG |
| Explorer | [chainscan-galileo.0g.ai](https://chainscan-galileo.0g.ai/) |

### Mainnet Configuration (Aristotle)

| Parameter | Value |
|-----------|-------|
| Network Name | 0G-Aristotle |
| Chain ID | `16661` |
| RPC Endpoint | `https://evmrpc.0g.ai` |
| Token Symbol | OG |
| Explorer | [chainscan.0g.ai](https://chainscan.0g.ai/) |

## SDKs & Libraries

| SDK | Language | Install | Docs / Repo |
|-----|----------|---------|-------------|
| 0G TypeScript SDK | TypeScript | `npm install @0glabs/0g-ts-sdk` | [GitHub](https://github.com/0glabs/0g-ts-sdk) · [npm](https://www.npmjs.com/package/@0glabs/0g-ts-sdk) |
| 0G Foundation TS SDK | TypeScript | `npm install @0gfoundation/0g-ts-sdk` | [GitHub](https://github.com/0gfoundation/0g-ts-sdk) · [npm](https://www.npmjs.com/package/@0gfoundation/0g-ts-sdk) |
| 0G Storage Client | Go | `go get github.com/0glabs/0g-storage-client` | [GitHub](https://github.com/0glabs/0g-storage-client) · [pkg.go.dev](https://pkg.go.dev/github.com/0glabs/0g-storage-client) |
| python-0g | Python | `pip install python-0g` | [GitHub](https://github.com/DormintLab/python-0g) · [PyPI](https://pypi.org/project/python-0g/) |
| 0G Chain | Go (Cosmos + Ethermint) | — | [GitHub](https://github.com/0glabs/0g-chain) |

## Starter Kits

| Kit | Stack | Repo |
|-----|-------|------|
| Compute TypeScript Starter Kit | Express, ethers v6, Swagger | [0gfoundation/0g-compute-ts-starter-kit](https://github.com/0gfoundation/0g-compute-ts-starter-kit) |
| Storage Web Starter Kit | Next.js, React, drag-and-drop upload | [0glabs/0g-storage-web-starter-kit](https://github.com/0glabs/0g-storage-web-starter-kit) |
| Storage TypeScript Starter Kit | Express, Swagger, CLI tools | [0glabs/0g-storage-ts-starter-kit](https://github.com/0glabs/0g-storage-ts-starter-kit) |
| Storage Go Starter Kit | Gin, Swagger, CLI | [0glabs/0g-storage-go-starter-kit](https://github.com/0glabs/0g-storage-go-starter-kit) |

## Developer Tools

| Tool | Description | Link |
|------|-------------|------|
| Storage CLI | Upload, download, encrypt files (AES-256-CTR), key-value ops | [GitHub](https://github.com/0glabs/0g-storage-client) |
| Testnet Faucet | Get testnet OG tokens | [faucet.0g.ai](https://faucet.0g.ai/) |
| Storage Scan (Galileo) | File tracking, upload tools, miner info | [storagescan-galileo.0g.ai](https://storagescan-galileo.0g.ai/) |
| Chain Scan (Testnet) | Galileo testnet block explorer | [chainscan-galileo.0g.ai](https://chainscan-galileo.0g.ai/) |
| Chain Scan (Mainnet) | Aristotle mainnet block explorer | [chainscan.0g.ai](https://chainscan.0g.ai/) |
| Validator Dashboard | Validator tracking, delegation & uptime | [0g.exploreme.pro/validators](https://0g.exploreme.pro/validators) |

## RPC & Infrastructure Providers

| Provider | Links |
|----------|-------|
| QuickNode | [Docs](https://www.quicknode.com/docs/0g) · [Chain Page](https://www.quicknode.com/chains/0g) |
| ThirdWeb | [Mainnet](https://thirdweb.com/0g-aristotle) · [Galileo Testnet](https://thirdweb.com/0g-galileo-testnet-16601) |
| Ankr | [RPC Service](https://www.ankr.com/rpc/0g/) |
| dRPC | [Chain Page](https://drpc.org/chainlist/0g-mainnet-rpc) |

## Documentation Reference

Organized by product area — all hosted at [docs.0g.ai](https://docs.0g.ai/).

### 0G Chain
- [Deploy Contracts on 0G Chain](https://docs.0g.ai/developer-hub/building-on-0g/contracts-on-0g/deploy-contracts) (Solidity — use `evmVersion: "cancun"`)
- [Staking Interfaces](https://docs.0g.ai/developer-hub/building-on-0g/contracts-on-0g/staking-interfaces)
- [Validator Contract Functions](https://docs.0g.ai/developer-hub/building-on-0g/contracts-on-0g/validator-contract-functions)
- [Precompiles Overview](https://docs.0g.ai/developer-hub/building-on-0g/contracts-on-0g/precompiles/precompiles-overview)
- [Indexing with Goldsky](https://docs.0g.ai/developer-hub/building-on-0g/indexing/goldsky)

### 0G Storage
- [Storage SDK](https://docs.0g.ai/developer-hub/building-on-0g/storage/sdk)
- [Storage CLI](https://docs.0g.ai/developer-hub/building-on-0g/storage/storage-cli)
- [Storage Architecture](https://docs.0g.ai/concepts/storage)

### 0G Compute
- [Compute Network Overview](https://docs.0g.ai/developer-hub/building-on-0g/compute-network/overview)
- [On-chain Inference](https://docs.0g.ai/developer-hub/building-on-0g/compute-network/inference)
- [Fine-tuning](https://docs.0g.ai/developer-hub/building-on-0g/compute-network/fine-tuning)
- [Account Management](https://docs.0g.ai/developer-hub/building-on-0g/compute-network/account-management)
- [Provider Setup](https://docs.0g.ai/developer-hub/building-on-0g/compute-network/inference-provider)

### 0G DA (Data Availability)
- [DA Deep Dive](https://docs.0g.ai/developer-hub/building-on-0g/da-deep-dive)
- [DA Integration Guide](https://docs.0g.ai/developer-hub/building-on-0g/da-integration)

### INFT (ERC-7857)
- [INFT Overview](https://docs.0g.ai/developer-hub/building-on-0g/inft/inft-overview)
- [Integration Guide](https://docs.0g.ai/developer-hub/building-on-0g/inft/integration)
- [ERC-7857 Standard](https://docs.0g.ai/developer-hub/building-on-0g/inft/erc7857)

### Node Operations
- [Overview](https://docs.0g.ai/run-a-node/overview)
- [Validator Node](https://docs.0g.ai/run-a-node/validator-node)
- [Storage Node](https://docs.0g.ai/run-a-node/storage-node)
- [DA Node](https://docs.0g.ai/run-a-node/da-node)
- [Archival Node](https://docs.0g.ai/run-a-node/archival-node)
- [Community Docker Repo](https://docs.0g.ai/run-a-node/community-docker-repo)

### Rollups & Appchains
- [OP Stack on 0G DA](https://docs.0g.ai/developer-hub/building-on-0g/rollups-and-appchains/op-stack-on-0g-da)
- [Arbitrum Nitro on 0G DA](https://docs.0g.ai/developer-hub/building-on-0g/rollups-and-appchains/arbitrum-nitro-on-0g-da)

## AI & Zero-Code Tools

| Tool | Description | Link |
|------|-------------|------|
| 0G Agent Skills | AI-assisted 0G development for Cursor IDE (14 skills, multi-IDE) | [GitHub](https://github.com/0gfoundation/0g-agent-skills) |
| 0G Blockchain MCP Server | Model Context Protocol server for 0G chain operations | [GitHub](https://github.com/colygon/0g-mcp-server) |
| 0G Chain MCP | MCP server for blockchain interactions | [GitHub](https://github.com/Tairon-ai/0g-chain-mcp) |
| Prompt Templates | Storage patterns, Solidity contracts, inference, DA integration | Bundled in [0g-agent-skills](https://github.com/0gfoundation/0g-agent-skills) |

## Technical Blogs

All posts at [0g.ai/blog](https://0g.ai/blog).

### Architecture & Deep Dives
- [0G Deep Dive: Unpacking the World's First AI-Native L1](https://0g.ai/blog)
- [Navigating 0G's Tech: An Update On The Latest in 0G's Products](https://0g.ai/blog/navigating-0g-s-tech-an-update-on-the-latest-in-0g-s-products)
- [True AI Ownership vs API Access: Returning Power to the Builders](https://0g.ai/blog/ai-ownership-vs-api-access)

### Performance
- [Breaking Barriers: 0G Hits 11,000 TPS with Parallel Consensus per Shard](https://0g.ai/blog)

### Data Availability
- [How Does 0G DA Compare to Celestia and EigenLayer?](https://0g.ai/blog)
- [The Evolution of Data Availability in Blockchain](https://0g.ai/blog)

### Storage & Compute
- [0G Storage: Built for the AI Era](https://0g.ai/blog)
- [Revolutionizing AI Fine-Tuning with the 0G Compute Network](https://0g.ai/blog/ai-fine-tuning-with-0g-compute)
- [GLM-5 on 0G Compute: 744B Open-Source AI, Zero Data Logging](https://0g.ai/blog)
- [Beyond Centralized Limits: First Globally Distributed 100B+ Parameter AI Model](https://0g.ai/blog)

### Security
- [0G Tapp: Securing TEE Deployments Without SSH](https://0g.ai/blog)

### Developer Guides
- [Building Decentralized AI? Here's Why 0G Should Be Part of Your Stack](https://0g.ai/blog/partial-0g-deployment)
- [Introducing 0G's V3 Testnet: Galileo](https://0g.ai/blog/introducing-v3-testnet-galileo)
- [AI Evolution: How Intelligent Agents Will Learn, Adapt, and Compete in Web3](https://0g.ai/blog/how-ai-will-adapt-in-web3)
- [Guild on 0G: A New Frontier for Decentralized AI Builders](https://0g.ai/blog/guild-on-0g)
- [Forging the Future of Onchain AI: 0G's Latest Hackathon Highlights](https://0g.ai/blog/0g-latest-hackathon-highlights)

## Tutorials

Hosted at [build.0g.ai/tutorials](https://build.0g.ai/tutorials/).

### Getting Started
- [Intro to 0G Ecosystem](https://youtube.com/watch?v=gCgMSa3nzv0)
- [0G Storage 101](https://youtube.com/watch?v=G1ea42zaxnE)
- [0G Storage 101 - Quick Guide](https://youtube.com/watch?v=fF4G3BjU2dI)
- [0G Compute Network 101](https://youtube.com/watch?v=bSCLDm7EETg)
- [Hands-on Starter Kits 101](https://youtube.com/watch?v=2n2PG1lYDzE)

### Workshops
- [ETHGlobal Cannes Workshop: Building with 0G Storage and Compute](https://youtube.com/watch?v=LxcV-DGmNLs)
- [0G's WaveHack: $50K Grant Buildathon Kickoff & Workshop](https://youtube.com/watch?v=pTd0NuPGj7A)

### iNFT / ERC-7857
- [0G iNFT: Tokenizing AI Agents (ERC-7857)](https://youtube.com/watch?v=Vo_z6ruKmyo)

### Partner Sessions
- [0G & Goldsky: Indexing and Streaming 0G Data](https://youtube.com/watch?v=nCn3atlqkpk)
- [0G & Euclid: Cross-chain Liquidity Infrastructure](https://youtube.com/watch?v=BGgSgXaWRzI)
- [0G & BAD AI: Build AI Agents with BAD Chaingraph](https://youtube.com/watch?v=2aUYuOdlEnE)
- [0G & NODERS: Professional Validators & Web3 Developers](https://youtube.com/watch?v=GMcisvyoEm4)
- [0G & SocialScan: Community Owned AI](https://youtube.com/watch?v=b9NOpg-Wk9g)
- [0G & Gevulot: ZkCloud](https://youtube.com/watch?v=6Z4ENUBs4pE)
- [0G & PublicAI: AI Data Infrastructure](https://youtube.com/watch?v=J3bWRC7i214)
- [0G & Pond: Crypto's Foundation Model](https://youtube.com/watch?v=DefB06HS_SU)
- [0G & Assisterr: Network of SLM](https://youtube.com/watch?v=h25Ks3uCvpI)
- [0G & Talus Network: AI Agent Hub](https://youtube.com/watch?v=UGZ7I36SpLk)

### Developer Bootcamp (5-part series)
- [Office Hour 1](https://youtube.com/watch?v=0bxhGX3c_Fc)
- [Office Hour 2](https://youtube.com/watch?v=sWqdtn5pFoM)
- [Office Hour 3](https://youtube.com/watch?v=btUbgGjYGeU)
- [Office Hour 4](https://youtube.com/watch?v=nzsE1ekY44Y)
- [Office Hour 5](https://youtube.com/watch?v=EhEJcxqEKrA)

## Community & Links

| Channel | Link |
|---------|------|
| GitHub | [github.com/0glabs](https://github.com/0glabs) · [github.com/0gfoundation](https://github.com/0gfoundation) |
| Discord | [discord.gg/0glabs](https://discord.gg/0glabs) |
| Twitter / X | [@0aboretum](https://twitter.com/0G_labs) |
| Blog | [0g.ai/blog](https://0g.ai/blog) |
| Docs | [docs.0g.ai](https://docs.0g.ai/) |
| Build | [build.0g.ai](https://build.0g.ai/) |
| Website | [0g.ai](https://0g.ai) |

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute to this hub.

---

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
