## 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](./contract_call.png)
## 2. The transaction hash from the console output (in text format).
0x99960577549e85901f907ba66daefb32c29f29b630acbdf2a0ee24b00bec4ee2
## 3. The contract address that you called (in text format).
0xDC018C0C56843ece5360d15Eb0B6D133f58215Dd
## 4. The ABI for contract you made a call on (in text format).
```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]
```