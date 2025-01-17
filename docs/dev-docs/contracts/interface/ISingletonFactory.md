Exposes CREATE2 (EIP-1014) to deploy bytecode on deterministic addresses based on initialization code and salt.



## Functions
### deploy
```solidity
  function deploy(
    bytes initCode,
    bytes32 salt
  ) external returns (address payable createdContract)
```
Deploys `initCode` using `salt` for defining the deterministic address.


#### Parameters:
| Name | Type | Description                                                          |
| :--- | :--- | :------------------------------------------------------------------- |
|`initCode` | bytes | Initialization code.
|`salt` | bytes32 | Arbitrary value to modify resulting address.

#### Return Values:
| Name                           | Type          | Description                                                                  |
| :----------------------------- | :------------ | :--------------------------------------------------------------------------- |
|`createdContract`| bytes | Created contract address.
