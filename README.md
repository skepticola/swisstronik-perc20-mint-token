# Swisstronik Testnet 2.0 - Mint PERC-20 Token.

Link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Swisstronik Testnet Address

```
0xE9b0493B3A058E467FFAA1c57b7b5DFD80d40C0d
```

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/skepticola/swisstronik-perc20-mint-token.git
```

```
cd swisstronik-perc20-mint-token
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file
```bash
PRIVATE_KEY="your private key"
```

### 4. Update Smart Contract

- Open contracts folder
- Open PERC20Sample.sol file
- Feel free to modify token name and token symbol

### 5. Compile Smart Contract

```bash
npm run compile
```

### 6. Deploy Smart Contract

```bash
npm run deploy
```

### 7. Mint Token

```bash
npm run mint
```

### 8. Transfer Token

```bash
npm run transfer
```

### Finished.
