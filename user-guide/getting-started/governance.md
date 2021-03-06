# Governance

The **Governance** page displays operations related to MIR staking and creating / voting on polls. For more details regarding the Mirror Governance process, [click here](../../protocol/governance/).

## Stake / Unstake MIR Tokens

MIR tokens are distributed as reward for staked LP tokens, which are generated when user provides liquidity. [Click here](stake.md) to learn more about staking LP tokens.

In order to vote on governance polls, MIR must be staked to be used as voting power.

1. Navigate to the [**Governance**](https://terra.mirror.finance/gov) page. The Governance page displays the following data:

* **Market information about MIR Staking**: Information about current staked MIR in the market, and staking ratio are displayed
* **MIR Staking Position:** MIR staking pool box displays expected APR \(annual percentage rate\) from staking MIR tokens, user's staked and unstaked MIR balances.
* **Poll History**: Each poll has a unique poll ID, poll type \(whitelist or parameter change\), poll result, voting ratio and end time.

2. Click **`STAKE`**

![](../../.gitbook/assets/image%20%2840%29.png)

3. Select either **Stake** / **Unstake**

![](../../.gitbook/assets/image%20%2838%29.png)

4. Enter amount to Stake or Unstake

![](../../.gitbook/assets/image%20%2830%29.png)

5. Click **`STAKE`** / **`UNSTAKE`**. Station Extension should prompt you to sign the transaction. Confirm the details presented and input your password to sign.

![](../../.gitbook/assets/image%20%2867%29.png)

## Create Poll

1. Navigate to the [**Governance**](https://terra.mirror.finance/gov) page

![](../../.gitbook/assets/image%20%2851%29.png)

2. Click **`CREATE POLL`**

![](../../.gitbook/assets/image%20%2843%29.png)

3. Select one of the below:

* **Whitelist:** Poll to list new mAsset on Mirror Protocol
* **Parameter Change:** Poll to change parameter of a listed mAsset
* **Community Pool:** Poll to request MIR funds from Community Pool

![](../../.gitbook/assets/image%20%2820%29.png)

4. After entering desired inputs, click activated button to confirm. 

![](../../.gitbook/assets/image%20%2839%29.png)

5. Station Extension should prompt you to sign the transaction. Confirm the details presented and input your password to sign.

![](../../.gitbook/assets/image%20%2861%29.png)

## Vote on Poll

1. Navigate to the [**Governance**](https://terra.mirror.finance/gov) page

![](../../.gitbook/assets/image%20%2854%29.png)

2. Select poll that is `IN PROGRESS`

![](../../.gitbook/assets/image%20%2845%29.png)

3. Click **`Vote`**

![](../../.gitbook/assets/image%20%2826%29.png)

4. Select **YES** or **NO**. 

![](../../.gitbook/assets/image%20%2831%29.png)

5. Click **`Submit`** to confirm. Station Extension should prompt you to sign the transaction. Confirm the details presented and input your password to sign.

![](../../.gitbook/assets/image%20%2844%29.png)

For every poll to be passed, they must meet the conditions below:

* Voting quorum must be greater than or equal to 10% of the total staked MIR. Without meeting this condition, no matter how much portion of the voting power has been voted Yes, the poll is ineffective.
* Over 50% of voting power which is dedicated to the poll must be **Yes**
* Voting period \(number of blocks corresponding to 2 weeks\) has ended
* After the voting period is over and the poll passes, it takes 7 days \(number of blocks corresponding to a week\) for the poll to become effective in the protocol.

