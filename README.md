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
5. Open to the Consul web dashboard to monitor your services health:
```bash
http://localhost:9501/
```

**For installation with local-persist, install the plugin instead if step 2:**
```bash
curl -fsSL https://raw.githubusercontent.com/CWSpear/local-persist/master/scripts/install.sh | sudo bash
```

### Supported Cryptocurrencies:
* Bitcoin (bitcoind)
* Litecoin (ltcd)
* Ethereum (geth)
* Ripple (rippled)
