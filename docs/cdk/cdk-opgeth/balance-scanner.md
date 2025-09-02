## Balance Scanner

Original contract code from: [https://github.com/MyCryptoHQ/eth-scan](https://github.com/MyCryptoHQ/eth-scan)

With slight modifications, such as:
- newer compiler
- ported tests to foundry
- create2 deploy to achieve same address across networks


### Deployment

Set .env with PRIVATE_KEY and RPC_URL  
`forge install`  
`forge test`  
`forge script script/Deploy.s.sol --rpc-url $RPC_URL --broadcast`  
  
Ideally verify on the main block explorer of the chain.

### Existing deployments:

All deployments are on the same address: 0xba1a5ca51097c890d0e595c9c5c290985034ddcb  
If something just says "deployed," it exists, but simply couldn't be verified for some reason. (e.g. no blockexplorer)

| Network   | Blockexplorer                                                                                     |
| --------  | --------                                                                                          |  
|ethereum   | https://etherscan.io/address/0xba1a5ca51097c890d0e595c9c5c290985034ddcb                           |
|sepolia    | https://sepolia.etherscan.io/address/0xba1a5ca51097c890d0e595c9c5c290985034ddcb                   |
|polygon    | https://polygonscan.com/address/0xba1a5ca51097c890d0e595c9c5c290985034ddcb                        |
|amoy       | https://amoy.polygonscan.com/address/0xba1a5ca51097c890d0e595c9c5c290985034ddcb                   |
|katana     | https://katanascan.com/address/0xba1a5ca51097c890d0e595c9c5c290985034ddcb                         |
|bokuto     | https://explorer-bokuto.katanarpc.com/address/0xBA1a5cA51097C890d0E595C9c5C290985034ddCB          |
|tatara     | https://explorer.tatara.katana.network/address/0xBA1a5cA51097C890d0E595C9c5C290985034ddCB         |
|zkevm      | https://zkevm.polygonscan.com/address/0xba1a5ca51097c890d0e595c9c5c290985034ddcb                  |
|cardona    | https://cardona-zkevm.polygonscan.com/address/0xBA1a5cA51097C890d0E595C9c5C290985034ddCB          |
|silicon    | deployed                                                                                          |
|xlayer     | https://www.oklink.com/x-layer/address/0xba1a5ca51097c890d0e595c9c5c290985034ddcb                 |
|lumia      | https://explorer.lumia.org/address/0xBA1a5cA51097C890d0E595C9c5C290985034ddCB                     |
|ternoa     | https://explorer-mainnet.zkevm.ternoa.network/address/0xBA1a5cA51097C890d0E595C9c5C290985034ddCB  |
