# Decentralized AI Training Network

A decentralized system for distributed AI model training using WebRTC and blockchain technology.

## Features

- Secure, privacy-preserving AI model training
- Decentralized task distribution using WebRTC
- Blockchain-based task management and payments
- Homomorphic encryption for data privacy
- GPU-powered distributed computing
- Automated payment system for workers

## Project Structure

```
├── client/                 # Client-side code
│   ├── encryption/        # Homomorphic encryption utilities
│   ├── model/            # AI model definitions
│   └── network/          # WebRTC networking
├── worker/                # Worker node implementation
│   ├── compute/          # GPU computation code
│   └── verification/     # Result verification
├── blockchain/           # Smart contracts
│   ├── contracts/        # Solidity contracts
│   └── scripts/         # Deployment scripts
└── common/               # Shared utilities
```

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

3. Start a worker node:
```bash
python worker/main.py
```

4. Start the client:
```bash
python client/main.py
```

## Security Features

- Homomorphic Encryption (FHE) for data privacy
- Trusted Execution Environments (TEE) support
- Zero-Knowledge Proofs for computation verification
- Blockchain-based task verification
- Decentralized payment system

