## `SOLACE`

Solace tokens can be earned by depositing Capital Provider or Liquidity Provider tokens to the Master contract.
        SOLACE can also be locked for a preset time in the Locker contract to recieve veSOLACE tokens.




### `constructor()` (public)

Constructs the Solace Token contract.



### `mint(address account, uint256 amount)` (public)

Creates `amount` new tokens for `to`.
The caller must be a minter.




### `setGovernance(address _governance)` (public)

Transfers the governance role to a new governor.
Can only be called by the current governor.




### `addMinter(address _minter)` (public)

Adds a new minter.
Can only be called by the current governor.




### `removeMinter(address _minter)` (public)

Removes a minter.
Can only be called by the current governor.




