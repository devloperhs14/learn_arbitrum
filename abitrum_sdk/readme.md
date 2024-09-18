# Arbitrum SDK Bridge
A simple script to use Arbitrum Bridge to transfer tokens between L1 and arbitrum


# USAGE
Clone the repo
```
git clone https://github.com/devloperhs14/learn_arbitrum-.git
```

Navigate to the script
```
cd abitrum_sdk
```

Create a .env file and fill the credentials
```
PRIVATE_KEY="REPLACE WITH PRIVATE KEY"
L1RPC="REPLACE WITH SEPOLIA ENDPOINT"
L2RPC="REPLACE WITH ARBITRUM SEPOLIA ENDPOINT"
```

* Replace your PRIVATE_KEY with private key from METAMASK / ANY WALLET
* Replace your L1RPC from any RPC provider like Infura (TRANSFER FUNDS FROM)
* Replace your L2RPC from any RPC provider like Infura (ARBITRUM SEPOLIA)
* You can get the RPC URL from ACTIVE END POINTS Tab / similar

Install the node modules
```
npm install --save
```

Run the transaction script
```
node bridge.js
```

After sucessfull transaction you can see a image similar to below

![image](https://github.com/user-attachments/assets/4dfaa034-8ae8-4014-a6d2-9ac5096033c6)

Thanks!
