# Swisstronik Sample using Hardhat

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.


```
npm install
```

## Variable Configuration
```
npx hardhat vars set PRIVATE_KEY
```

input your test private key

- get list variable
```
npx hardhat vars list
```

## compile 
```
npx hardhat compile
```

## Deploy

- deploy Sample Contract
```
npx hardhat run scripts/simplecontract/deploy.js --network swisstronik
```

- Deploy Token
```
npx hardhat run scripts/erc20/deploy.js --network swisstronik
```

- Deploy Private Token
```
npx hardhat run scripts/perc20/deploy.js --network swisstronik
```

- Deploy NFT
```
npx hardhat run scripts/erc721/deploy.js --network swisstronik
```

- Deploy Private NFT
```
npx hardhat run scripts/perc721/deploy.js --network swisstronik
```

- Deploy Proxy
```
npx hardhat run scripts/proxy/deploy.js --network swisstronik
```

### Sample Contract

- Sample Contract

sample : `0x.......`


- Set Value
```
npx hardhat run scripts/erc20/setMessage.js --network swisstronik
```

- Get Value
```
npx hardhat run scripts/erc20/setMessage.js --network swisstronik
```


### Token

Muuu
`0x.......`


- transfer token
```
npx hardhat run scripts/erc20/transfer.js --network swisstronik
```

- Mint token
```
npx hardhat run scripts/erc20/mint.js --network swisstronik
```

- transfer private token
```
npx hardhat run scripts/perc20/transfer.js --network swisstronik
```

- Mint private token
```
npx hardhat run scripts/perc20/mint.js --network swisstronik
```

## nft

MushNft
`0x.......`

- test
```
npx hardhat run scripts/nft/mint.js --network swisstronik
```