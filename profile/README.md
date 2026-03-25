# PuzzleX

[![GitHub Org](https://img.shields.io/badge/GitHub-PuzzleX--club-181717?logo=github&logoColor=white)](https://github.com/PuzzleX-club)
[![X](https://img.shields.io/badge/X-@PuzzleX__club-000000?logo=x&logoColor=white)](https://x.com/PuzzleX_club)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20PuzzleX-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/Q5Q61WM14D)
[![Donate with Crypto](https://img.shields.io/badge/Crypto-USDT%20on%20TRON-26A17B?logo=tether&logoColor=white)](https://nowpayments.io/donation?api_key=60e167ac-c9ce-49b4-9286-67008f10e58d)

PuzzleX is an open-source marketplace infrastructure effort focused on reusable trading primitives, execution helpers, reference services, and protocol-facing contracts.

We are opening the stack in stages. The shared core package, reference web application, reference API service, and public contract surface are available today.

## Connect & Support

- GitHub organization: [PuzzleX-club](https://github.com/PuzzleX-club)
- X: [@PuzzleX_club](https://x.com/PuzzleX_club)
- Donation options and network notes: [DONATE.md](https://github.com/PuzzleX-club/.github/blob/main/DONATE.md)
- Contribution guide: [CONTRIBUTING.md](https://github.com/PuzzleX-club/.github/blob/main/CONTRIBUTING.md)
- Contributor license terms: [CLA.md](https://github.com/PuzzleX-club/.github/blob/main/CLA.md)

## Public now

- [`puzzlex-core`](https://github.com/PuzzleX-club/puzzlex-core): Shared TypeScript core library for order management, match execution helpers, configuration validation, Merkle utilities, and WebSocket support
- [`@puzzlex/core`](https://www.npmjs.com/package/@puzzlex/core): Public npm package for integrating the shared core library
- [`puzzlex-web`](https://github.com/PuzzleX-club/puzzlex-web): Reference frontend implementation with explorer, analyzer, exchange-lite, and example-mode support
- [`puzzlex-api`](https://github.com/PuzzleX-club/puzzlex-api): Reference Rails API service with canonical baseline migration and OSS config surface
- [`puzzlex-contracts`](https://github.com/PuzzleX-club/puzzlex-contracts): Public Seaport-related contract surface, PuzzleXZone, and documented protocol patches

## Get started

```bash
npm install @puzzlex/core
```

Package repository:
- [PuzzleX-club/puzzlex-core](https://github.com/PuzzleX-club/puzzlex-core)

Latest public release:
- [v1.1.0](https://github.com/PuzzleX-club/puzzlex-core/releases/tag/v1.1.0)

## Repository roadmap

We are publishing PuzzleX in layers instead of opening every repository at once.

| Repository | Status | Purpose |
| --- | --- | --- |
| [`puzzlex-core`](https://github.com/PuzzleX-club/puzzlex-core) | Public | Shared library and npm package |
| [`puzzlex-web`](https://github.com/PuzzleX-club/puzzlex-web) | Public | Reference web application |
| [`puzzlex-contracts`](https://github.com/PuzzleX-club/puzzlex-contracts) | Public | Protocol-facing contracts and PuzzleXZone |
| [`puzzlex-api`](https://github.com/PuzzleX-club/puzzlex-api) | Public | Reference API service |

## Project focus

- Environment-agnostic trading logic
- Seaport-oriented execution and matching helpers
- Shared configuration and validation primitives
- Merkle tooling for criteria-based orders
- Reference implementations for broader PuzzleX components
- Public API and contract baselines for integrators

## Notes

- Public package releases are published from GitHub Actions with npm Trusted Publishing
- Each repository carries its own license and release boundary
- Additional repositories will continue to be published gradually as their public boundaries are finalized
