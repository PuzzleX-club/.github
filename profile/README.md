# PuzzleX

PuzzleX is an open-source marketplace infrastructure effort focused on reusable trading primitives, execution helpers, and reference application layers.

We are opening the stack in stages. The core package is public today, while additional repositories will be released after their public boundaries are finalized.

## Public now

- [`puzzlex-core`](https://github.com/PuzzleX-club/puzzlex-core): Shared TypeScript core library for order management, match execution helpers, configuration validation, Merkle utilities, and WebSocket support
- [`@puzzlex/core`](https://www.npmjs.com/package/@puzzlex/core): Public npm package for integrating the shared core library

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
| `puzzlex-contracts` | Preparing | Smart contracts and protocol-facing components |
| `puzzlex-api` | Preparing | Reference API service |
| `puzzlex-web` | Preparing | Reference web application |

## Project focus

- Environment-agnostic trading logic
- Seaport-oriented execution and matching helpers
- Shared configuration and validation primitives
- Merkle tooling for criteria-based orders
- Reference implementations for broader PuzzleX components

## Notes

- Public package releases are published from GitHub Actions with npm Trusted Publishing
- Each repository carries its own license and release boundary
- Additional repositories will be opened gradually as they are hardened for public use
