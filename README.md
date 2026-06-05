# LiteWater Capital DAO LLC

This repository contains the public smart contract interface for the JAB01 treasury reserve token.

### Institutional Architecture
JAB01 operates as the core unit of account for the LiteWater Capital DAO LLC treasury. 

To ensure absolute privacy and institutional security, JAB01 is tokenized against legal treasury obligations (which are wrapped and entangled with base treasury Genesis 3 UTXOs). 

The solvency and validity of these legal obligations are mathematically verified on-chain via a Zero-Knowledge (ZK) attestation infrastructure provided by Westwyrd. This ZK architecture allows risk curators and institutional partners to cryptographically verify the backing of the JAB01 token without ever requiring the public disclosure of the DAO's proprietary internal treasury operations, obligations, or private key infrastructure.

### Development
To run this interface locally:
```bash
npm install
npm run dev
```
