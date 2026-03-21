# RoadCoin Token — TODO

## [RC] Token Foundation
- [ ] ERC-20 smart contract (Solidity, audited)
- [ ] Token economics document (supply, distribution, vesting)
- [ ] Multi-sig treasury wallet setup
- [ ] Testnet deployment (Sepolia)
- [ ] Mainnet deployment with time-locked admin functions
- [ ] Contract verification on Etherscan

## [RC] Utility — Agent Micropayments
- [ ] Agent-to-agent payment protocol specification
- [ ] Payment channel for high-frequency micro-transactions
- [ ] Gas-abstracted meta-transactions (agents don't need ETH)
- [ ] Usage metering: compute, storage, bandwidth per agent
- [ ] Settlement batching (aggregate micro-payments, settle hourly)
- [ ] Rate oracle for ROAD/USD pricing

## [RC] Utility — Creator Payouts
- [ ] Creator registration and KYC/KYB flow
- [ ] Revenue share smart contract (configurable splits)
- [ ] Payout scheduling (daily, weekly, monthly)
- [ ] Minimum payout threshold logic
- [ ] Creator dashboard with earnings history
- [ ] Tax document generation (1099 for US creators)

## [RC] Stripe Bridge (Fiat On/Off Ramp)
- [ ] Buy ROAD with credit card via Stripe
- [ ] Sell ROAD to bank account via Stripe Connect
- [ ] Real-time ROAD/USD rate display
- [ ] Transaction limits and velocity checks
- [ ] KYC integration for fiat conversion
- [ ] Compliance reporting for fiat transactions

## [RC] Wallet Infrastructure
- [ ] Web wallet (non-custodial, browser-based)
- [ ] Mobile wallet (React Native)
- [ ] Hardware wallet support (Ledger, Trezor)
- [ ] Multi-sig wallet for team treasuries
- [ ] Wallet connect integration
- [ ] QR code payment flows

## [RC] Governance
- [ ] Governance smart contract (proposal + voting)
- [ ] Snapshot-style off-chain voting for gas-free governance
- [ ] Proposal threshold and quorum parameters
- [ ] Delegation mechanism
- [ ] Governance dashboard UI
- [ ] Treasury spending proposals

## [RC] Security & Compliance
- [ ] Smart contract audit (2 independent firms)
- [ ] SEC compliance review (utility token classification)
- [ ] FinCEN MSB registration assessment
- [ ] AML/KYC provider integration
- [ ] Rate limiting and abuse prevention
- [ ] Incident response plan for smart contract issues

## [RC] SDK & Integration
- [ ] @roadcoin/sdk npm package
- [ ] Python SDK for agent integration
- [ ] RoadPay integration (accept ROAD in checkout)
- [ ] REST API for balance, transfer, history
- [ ] Webhook notifications for transfers
- [ ] Explorer integration (block, tx, address lookup)

## [RC] Documentation
- [ ] Whitepaper (token economics, utility, governance)
- [ ] Technical architecture document
- [ ] API reference with examples
- [ ] Integration guide for RoadPay merchants
- [ ] Agent developer guide (micropayment setup)
- [ ] Creator onboarding guide

## [RC] Infrastructure
- [ ] Block explorer (self-hosted, Blockscout fork)
- [ ] Token indexer for fast balance/history queries
- [ ] Price feed oracle (Chainlink + custom)
- [ ] Monitoring and alerting for contract events
- [ ] Automated liquidity management
- [ ] Disaster recovery for treasury operations
