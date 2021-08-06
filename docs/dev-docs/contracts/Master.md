## `Master`

This contract is the SOLACE token distributor.




### `constructor(contract SOLACE _solace, uint256 _solacePerBlock)` (public)

Constructs the master contract.




### `setGovernance(address _governance)` (external)

Transfers the governance role to a new governor.
Can only be called by the current governor.




### `registerFarm(address _farmAddress, uint256 _allocPoints) → uint256 farmId` (external)

Registers a farm.
Can only be called by the current governor.
Cannot register a farm more than once.




### `setAllocPoints(uint256 _farmId, uint256 _allocPoints)` (external)

Sets a farm's allocation points.
Can only be called by the current governor.




### `setSolacePerBlock(uint256 _solacePerBlock)` (external)

Sets the Solace reward distribution across all farms.
Optionally updates all farms.




### `massUpdateFarms()` (public)

Updates all farms to be up to date to the current block.



### `_setAllocPoints(uint256 _farmId, uint256 _allocPoints)` (internal)

Sets a farm's allocation points.




### `_updateRewards()` (internal)

Updates each farm's block rewards.



