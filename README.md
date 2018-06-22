# thor-sync

[![GitHub (pre-)release](https://img.shields.io/github/release/vechain/thor-sync/all.svg)](https://github.com/vechain/thor-sync/releases)

## Installation 
You can download preview version on [Release page](https://github.com/vechain/thor-sync/releases), you can easily explore the VeChainThor after download. 

## OS requirements 
|  Operation system  | Version |
| --- | --- |
| Mac OS  | 10.9 and later version |
| Windows | Windows 7 and later version |

## Built-in Apps
### Account

| Sub-modules| network | Description |
| --- | --- | --- |
| Create  | MainNet / TestNet | Allow user to create an account or more, the address will be unique ID on blockChain |
| export key store| MainNet / TestNet  | export the key store and save to custom path. its for recovery use  |
| export private key| MainNet / TestNet  | export the private key and save to custom path. its for recovery use  |
| import Key Store | MainNet / TestNet | import key store to recover account. |
| Mnemonic recovery | MainNet / TestNet | During account creation, it ask user to write down and keep it safe. write the mnemonic words to recover account.|
| import private key | MainNet / TestNet | input the private key to recover account. |

### Txbuilder

| Sub-modules| network | Description |
| --- | --- | --- |
| Single transaction |MainNet / TestNet | sending an transaction(transfer) to a recipient  |
| Multi- transaction | MainNet / TestNet | sending an transaction include multiple recipient(clauses) |
| contract deployment|MainNet / TestNet  | deploy a a smart contract on VeChainThor network  |

### Insights

| Sub-modules| network | Description |
| --- | --- | --- |
| best block query | MainNet / TestNet | once open the Insight，as default it shows the best block , there's also a button it can query the best block   |
| block Number query | MainNet / TestNet | query specific block number using search function,it will return block details and transactions|
| block ID query | MainNet / TestNet | query specific block ID using search function,it will return block details and transactions  |
| transaction query | MainNet / TestNet  | query specific txID using search function, it will return details and receipt of the transaction.  |
| address query | MainNet / TestNet | query specific address using search function, it will return latest account balance and transfer logs  |

### Faucet

| Sub-modules| network | Description |
| --- | --- | --- |
| Claim token | TestNet | Type in / select the account or input the address which is willing to receive the amount of  dual-token .  |
