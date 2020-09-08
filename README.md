## Shasta testnet
already migrate on Shasta testnet
- YAM: TSYFdmRdnqwd3KpsTFjysLpZRjhpaSn61H

- wtron: TAc8NE2Hccy7CCxmwKHrSsgg6hRKaPQ43A
 
- POOL: TKvVYxUN3kVp8MzMuJ5RJSkFqnrwvDVrJR

⚠️ must uss toHex method to convert Tron contract address
```javascript
tronWeb.address.toHex() 
```
-------------------------------------

## mainnet 

usdt: TR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t
- 0xa614f803B6FD780986A42c78Ec9c7f77e6DeD13C

ivory: TMGrN8W9JCiWyXGQsiQs8Sf3r3aoAWp5tn
- 0x7BFFa4EF967C68D14c8AA8cB888854F771C6db6B

pool: TUr32hCzTdWCMjJXZvphLgafFEVfKagoAC

## usage
⚠️ start time: 09/07/2020 @ 9:30am (UTC +00:00)
⚠️ Distribution amount: 1000000 ivory
1. call pool setRewardDistribution method
2. ivory token transfer <X> amount to pool address
3. call pool notifyRewardAmount <X> 