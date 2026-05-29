# MO-IT148 Smart Tracking System Blockchain Ledger

**Section:** H3101  
**Team:** CTRL+ALT+ELITE ADET EDITION

This project stores simulated smart logistics IoT records on a local Ethereum blockchain using Ganache, Remix IDE, Solidity, Python, and Web3.py.

## Files

- `IoTDataStorage.sol` - Solidity smart contract deployed through Remix IDE.
- `week5_milestone1_submission.py` - Python script that reads the CSV and submits each row to the blockchain.


## Setup

1. Open Ganache and confirm the RPC server is `http://127.0.0.1:7545`.
2. Deploy `IoTDataStorage.sol` in Remix using Solidity `0.8.18` and the External HTTP Provider.
3. Install dependencies:

```bash
pip install pandas web3
```

4. Update `CONTRACT_ADDRESS` in the Python script if a new contract is deployed.
5. Run:

```bash
python week5_milestone1_submission.py
```

## Recorded Submission Output

- Contract address: `0xAF5D8457982f15462235ADa59BF7a5d97a7D022C`
- CSV records uploaded: `80`
- Records already present before CSV upload: `2`
- Total records after upload: `82`
