# CryptoDaemon

Collection of all official cryptocurrencies daemons on docker.

All files are based on Alpine.

### Instruction
0. Install Docker and Docker-Compose
1. Clone the repository
2. Set data directory
```bash
export BLOCKCHAIN_DATA_DIR=./data
```
3. Build
```bash
docker-compose build
```
4. Run
```bash
docker-compose up -d
```
5. Check status
```bash
docker-compose ps
```
6. Follow logs
```bash
docker-compose logs -f
```

### Supported Cryptocurrencies:
* Bitcoin (bitcoind)
* Litecoin (ltcd)
* Ethereum (geth)
* Ripple (rippled)
