### Install dependencies

- [NodeJS](https://nodejs.org/en/)

- NPM

- GIT

```
curl http://deb.nodesource.com/setup_lts.x | sudo bash -
sudo apt install git nodejs -y
```

### Clone
```
git clone https://github.com/UndefinedHash/inery-testnet-faucet-tasks -b task4
```
###
### Configuring env vars in
- `NODE_URL="NODE_URL"`
- `ACCOUNT="YOUR_INERY_ACCOUNT_NAME"`
- `PRIV_KEY="PRIVATE_KEY_OF_INERY_ACCOUNT_NAME"`
- `DATA_ID="DATA_ID"` Number only

```
cd inery-testnet-faucet-tasks/ollo.inery
```
```
nano .env
```

### Install module dependencies

```
npm install -g npm
npm install
```

## Run the script
```
npm run push-tx
```
