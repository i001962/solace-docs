Circle's USDC has the ability to blacklist accounts. We need to circumvent the blacklist to test our products, and IBlacklist helps us do that.


## Functions
### isBlacklisted
```solidity
  function isBlacklisted(
    address account
  ) external returns (bool status)
```
Checks if account is blacklisted.


#### Parameters:
| Name | Type | Description                                                          |
| :--- | :--- | :------------------------------------------------------------------- |
|`account` | address | The address to check.

#### Return Values:
| Name                           | Type          | Description                                                                  |
| :----------------------------- | :------------ | :--------------------------------------------------------------------------- |
|`status`| address | True if the account is blacklisted.
