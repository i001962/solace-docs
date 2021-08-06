---
title: ClaimModal
---

## Props

### `ClaimModalProps`
- **closeModal (function)**: Function to call when closing modal
- **isOpen (boolean)**: Boolean to open modal
- **latestBlock (number)**: The latest block number
- **selectedPolicy (Policy | undefined)**: The currently selected policy

## Components

### `ClaimModal` (exported)

Props Dependencies:

- `ClaimModalProps`

Manager Dependencies:

- **Wallet**: `account` , `chainId` , `errors` , `library`
- **Contracts**: `selectedProtocol` , `getProtocolByName`
- **CachedData**: `tokenPositionDataInitialized` , `gasPrices` , `reload` , `addLocalTransactions`

Hook Dependencies:

- `useGetCooldownPeriod()`
- `useTokenAllowance(contractForAllowance, spenderAddress)`
- `useToasts()`

Contract Functions:

- `approve` : Approve amount to be transferred.

- `submitClaim` : Calls function from product contract to submit claim.

Local Functions:

- `getUserBalances()` : Get balances for user's positions

- `handleClose()` : Handle closing modal

Data Refresh:

- [ `isOpen` , `selectedPolicy` , `account` , `library` , `tokenPositionDataInitialized` ]: get user balances, get contract for allowance, get spender address, get claim assessment

- [ `latestBlock` ]: get user balances

Info: Returns modal to submit claim for a user's policy.