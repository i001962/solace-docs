---
title: MyInvestments
---

## Components

### `MyInvestments` (exported)

Manager Dependencies:
- **Wallet**: `account` , `chainId`
- **Contracts**: `cpFarm` , `lpFarm`

Hook Dependencies:
- `useUserPendingRewards()`
- `useUserRewardsPerDay()`
- `useUserStakedValue()`

Info: Returns a card container of the user's investments in cards.