# t3rn_node by ColonyAirdrops

- Hardware Requirements (16GB RAM, Multicore)
- Video: Youtube

## Prerequisite:
- Need testnet gas on (op_sepolia, arb_sepolia, base_sepolia, blast_sepolia): https://testnetbridge.com/sepolia
- Bridge: https://testnets.relay.link/
- Need testnet brn (atleast 10)

```bash
sudo apt update

sudo apt install build-essential

sudo apt install git -y

sudo apt install screen
```

## Download Binary
```bash
screen -S t3rn
```
```bash
wget https://github.com/t3rn/executor-release/releases/download/v0.32.0/executor-linux-v0.32.0.tar.gz
```
```bash
tar -xvzf executor-linux-v0.32.0.tar.gz
```

## Configure Settings and Environment
```bash
cd executor/executor/bin
```
```bash
export NODE_ENV=testnet
```
```bash
export LOG_LEVEL=debug
```
```bash
export LOG_PRETTY=false
```
```bash
export EXECUTOR_PROCESS_ORDERS=true
```
```bash
export EXECUTOR_PROCESS_CLAIMS=true
```
```bash
export RPC_ENDPOINTS_L1RN='https://brn.rpc.caldera.xyz'
```
```bash
export PRIVATE_KEY_LOCAL=ENTER YOUR_PRIVATKEY
```
```bash
export ENABLED_NETWORKS='base-sepolia,arbitrum-sepolia,optimism-sepolia,blast-sepolia,l1rn'
```
```bash
export EXECUTOR_MAX_L3_GAS_PRICE=200
```

## Run Executor
```bash
./executor
```

## Check Executor Status
Executor status: https://bridge.t1rn.io/explorer/executors

---
- Done !! Feel free to ask queries in telegram channel
- Telegram - https://t.me/colonyairdrops
- Youtube - https://www.youtube.com/@ColonyAirdrops




