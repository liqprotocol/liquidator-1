# Port Finance Loan Liquidator

## Setup Liquidator
### Prerequisites
To run the liquidator you will need:
* A Solana account with some SOL deposited to cover transaction fees
* Token accounts for each token in the reserve
* Roughly equal deposits for each token.
### Setup
Make sure to edit the .env file to look something like this:
```
export CLUSTER="mainnet-beta"
export CLUSTER_URL="https://solana-api.projectserum.com"
export KEYPAIR=~/.config/solana/id.json
export NODE_ENV=production
export CHECK_INTERVAL="1000.0"
```

`CHECK_INTERVAL` is the amount of milliseconds to wait between querying user's loan

### Run
```
yarn install
source .env
yarn pyth
```

## Mainnet

Lending Market: `6T4XxKerq744sSuj3jaoV6QiZ8acirf4TrPwQzHAoSy5`

### Reserve Public Keys

| Asset Name      | Reserve Address                                     |
| :---            |    ----:                                            |
| SOL             | X9ByyhmtQH3Wjku9N5obPy54DbVjZV7Z99TPJZ2rwcs         |
| USDC            | DcENuKuYd6BWGhKfGr7eARxodqG12Bz1sN5WA8NwvLRx        |
| USDT            | 4tqY9Hv7e8YhNQXuH75WKrZ7tTckbv2GfFVxmVcScW5s        |
| PAI             | DSw99gXoGzvc4N7cNGU7TJ9bCWFq96NU2Cczi1TabDx2        |
| SRM             | ZgS3sv1tJAor2rbGMFLeJwxsEGDiHkcrR2ZaNHZUpyF         |
| BTC             | DSST29PMCVkxo8cf5ht9LxrPoMc8jAZt98t6nuJywz8p        |
| MER             | BnhsmYVvNjXK3TGDHLj1Yr1jBGCmD1gZMkAyCwoXsHwt        |

### pToken Mint

| Asset Name     | pToken Mint                                   |
| :---           |      ---:                                     |
| SOL            | 8ezDtNNhX91t1NbSLe8xV2PcCEfoQjEm2qDVGjt3rjhg  |
| USDC           | FgSsGV8GByPaMERxeQJPvZRZHf7zCBhrdYtztKorJS58  |
| USDT           | 3RudPTAkfcq9Q9Jk8SVeCoecCBmdKMj6q5smsWzxqtqZ  |
| PAI            | GaqxUwFGGrDouYLqghchmZU97Y1rNhyF7noMTJNvpQPa  |
| SRM            | 77TBgKmTNtMdGrt1ewNRb56F2Xw6fNLZZj33JZ3oGwXh  |
| BTC            | QN2HkkBaWHfYSU5bybyups9z1UHu8Eu7QeeyMbjD2JA   |
| MER            | 6UgGnLA3Lfe8NBLAESctsUXWdP3zjMFzSLEZxS3tiaKh  |

### Oracle Public Keys

| Asset Name      |  Oracle Pubkey                                |
| :---            |      ---:                                     |
| SOL             | H6ARHf6YXhGYeQfUzQNGk6rDNnLBQKrenN712K4AQJEG  |
| USDC            | N / A                                         |
| USDT            | 3vxLXJqLqF3JG5TCbYycbKWRBbCJQLxQmBGCkyqEEefL  |
| PAI             | N/A                                           |
| SRM             | 3NBReDRTLKMQEKiLD5tGcx4kXbTf88b7f2xLS9UuGjym  |
| BTC             | GVXRSBjFk6e6J3NbVPXohDJetcTjaeeuykUpbQF8UoMU  |
| MER             | G4AQpTYKH1Fmg38VpFQbv6uKYQMpRhJzNPALhp7hqdrs  |


### Supply Public Keys
| Asset Name     | Supply Public Keys                            |
| :---           |      ---:                                     |
| SOL            | BLAFX12cDmsumyB6k3L6whJZqNqySaWeCmS5rVuzy3SS  |
| USDC           | 2xPnqU4bWhUSjZ74CibY63NrtkHHw5eKntsxf8dzwiid  |
| USDT           | QyvfrbqH7Mo8W5tHN31nzbfNiwFwqPqahjm9fnzo5EJ   |
| PAI            | 42kNZrAuwZHLtuc7jvVX7zMfkfgwbPynqzFB3zdkAEGM  |
| SRM            | DjhMNdgdbxNud1gmc4DUwrQqJxNbjhxiwNnhc4usSXmQ  |
| BTC            | FZKP27Zxz9GbW86hhq3d1egzpBH5ZnYkyjQZVf86NQJ8  |
| MER            | 6UmrawFZgdPvMe6BLZdZCNRFz9u2TWsu5enFbTufA3a1  |


## Dev Net

Lending Market: H27Quk3DSbu55T4dCr1NddTTSAezXwHU67FPCZVKLhS

### Reserve Public Keys

| Asset Name      | Reserve Address                           |
| :---  |    ----:                                            |
| SOL   | 6FeVStQAGPWvfWijDHF7cTWRCi7He6vTT3ubfNhe9SPt        |
| USDC  | G1CcAWGhfxhHQaivC1Sh5CWVta6P4dc7a5BDSg9ERjV1        |

### pToken Mint

| Asset Name     | pToken Mint                          |
| :---  |      ---:                                     |
| SOL   | Hk4Rp3kaPssB6hnjah3Mrqpt5CAXWGoqFT5dVsWA3TaM  |
| USDC  | HyxraiKfdajDbYTC6MVRToEUBdevBN5M5gfyR4LC3WSF  |


### Oracle Public Keys

| Asset Name      |  Oracle Pubkey  |
| :---  |      ---:                                     |
| SOL   | J83w4HKfqxwcq3BEMMkPFSppX3gqekLyLJBexebFVkix  |
| USDC  | N/A                                           |

### Supply Public Keys
| Asset Name     | Supply Public Keys  |
| :---  |      ---:                                     |
| SOL   | AbKeR7nQdHPDddiDQ71YUsz1F138a7cJMfJVtpdYUSvE  |
| USDC  | GAPyFes3o7S7coY9nsuhaRZBEA7DdQPHBfVdY2DdgNua  |
