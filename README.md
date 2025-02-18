![image](https://github.com/sarcophagus-org/base-token-incentives/blob/main/resurrection.png)


# Sarcophagus Resurrection - $SARCO Token Incentives For BASE 

Things have been a little too quiet in the Sarcophagus ecosystem for a little too long. It’s time to shake things up and do whatever we can to share the novelty and utility of an on-chain dead man’s switch. Given that over 53% of the total token supply is owned by the DAO, it is time to use these latent tokens to incentivize positive actions on-chain. Below are several token incentives that current $SARCO holders can benefit from, as well as benefits for new users looking to use the application. 


# BASE Transition Bridge Incentive

There is a need to cover the costs of moving **$SARCO** from **ETH** to **BASE**. To do this, we have allocated **7,499,493 $SARCO** (27% of remaining DAO tokens) as a budget to cover these costs **+ additional time-based incentive**.

### Method
- The holders of **$SARCO on ETH** will be snapshotted prior to the announcement.
- Each wallet that bridges their **$SARCO from ETH to BASE** using [SuperBridge](https://superbridge.app/base) will be reimbursed with **12,776.77385159 $SARCO** to cover the gas costs of bridging.
- Snapshots of **$SARCO holders on ETH and BASE** will be taken on the **14th of each month for 3 months**.
- Reimbursement for these bridges will be distributed on the **15th of each month for 3 months**.
- **Reimbursements will be sent on BASE**.

### Rationale
Sarcophagus is too expensive to use on ETH, and having token liquidity around a bunch of different chains does not help drive forward the mission of building a **decentralized dead man’s switch**.

BASE is most likely going to be the most **stable L2 in the future**, so the Sarcophagus team has decided to **move all efforts to BASE**. The app can still work on existing deployments, but core team efforts will **no longer focus on other chains**. Legacy chain implementations can be accessed at [legacy.sarcophagus.io](https://legacy.sarcophagus.io).

### Notes / Rules
- **Only one bridge transaction per wallet** will be reimbursed.
- Only **$SARCO bridged through** [SuperBridge](https://superbridge.app/base) will be eligible for reimbursement.
- **Reimbursements will run for 3 months**.
- **Only $SARCO bridged from ETH to BASE** will be eligible for reimbursement.
- Any attempt to **game, loop, sybil, or otherwise manipulate the system** will result in **blacklisting from future rewards**.
- **Token contract addresses:**  
  - ETH: [0x7697b462a7c4ff5f8b55bdbc2f4076c2af9cf51a](https://etherscan.io/token/0x7697b462a7c4ff5f8b55bdbc2f4076c2af9cf51a)  
  - BASE: [0xf3907bc0fff5ff5acf1e3dd7987005779c7bf57d](https://basescan.org/token/0xf3907bc0fff5ff5acf1e3dd7987005779c7bf57d)

---


# Sarcophagus dApp Usage Incentive

To make it as easy as possible for new users to try **Sarcophagus** and create their own **dead man’s switches**, we will **reimburse any user** that **creates or re-wraps a Sarcophagus on BASE**.

- **Reimbursements will cover the $SARCO costs** associated with using Sarcophagus.
- **Gas expenses will not be covered**.

**Allocation:** **5,356,781 $SARCO** (10% of remaining DAO tokens) has been budgeted for **testing and using Sarcophagus**.

### Method
- On the **14th of each month**, a **snapshot will be taken** of the Curse contract on BASE:  
  [Curse Contract](https://basescan.org/address/0xc1984df3e3ddc1dc24d54179ccd5537e290c7e9c#tokentxns)
- On the **15th of each month**, **$SARCO tokens will be distributed** in an amount **equal to the $SARCO spent using the dApp** since the 14th of the previous month.
- The **program will run until the budget is exhausted**.

### Notes
Any attempt to **game, loop, sybil, or otherwise manipulate the system** will result in **blacklisting from future rewards**.

---


# DAO Lockup + Vesting


To communicate our **long-term goals and values**, **30% of the remaining DAO tokens** will be **locked into a vesting schedule for 24 months** using [DecentDAO](https://decentdao.org/) via SAFE on BASE.

- **Total Locked Tokens:** **16,070,342 $SARCO**
- **DAO control removed for 24 months**

### Method
- The **Sarcophagus DAO** will use **Sabiler finance dApp** via SAFE on BASE to **lock 16,070,342 $SARCO** into a **linear + cliff vesting contract** with a **24-month duration**.
- **Cliff period:** **12 months from creation date** (0 tokens claimable until then).
- **After the cliff period, tokens will vest linearly** over the remaining **12 months**.
- **Vesting is non-cancelable**, meaning **this action cannot be undone**.

---

# DEX Liquidity Provision + Incentives


To facilitate a **smooth market for $SARCO token holders**, **17,677,376 $SARCO** (33% of remaining DAO tokens) will be allocated for **liquidity incentive and market-making programs**.

### Method
- Given that there is **no proper incentivization dApp** for user-owned liquidity on **Uniswap V3 on BASE**, the DAO will **partner with** [H20 Finance](https://h20.finance/) to **achieve liquidity goals**.
- The plan includes **DAO-owned liquidity** and **incentives for external liquidity providers** via **$SARCO token rewards**.

---

# Public Disclosure Built-In


The team is working on a feature for **public disclosure of Sarcophagus contents via an X/Twitter bot**.

- The account [@Thoth_Discloser](https://x.com/Thoth_Discloser) will be connected to a **bot/agent** that posts a **permanent link to Sarcophagus contents** when set to **"disclose publicly"**.

### Feature Details
- This feature allows **important information to be publicly accessible**.
- The disclosure will be a **link to the payload**, including credentials for public access.
- In the future, the bot will analyze the contents of the Sarcophagus and post a description as well. 

**Link Format:**
`https://app.sarcophagus.io/dashboard/<sarco_id>?action=claim&pk=0xffcdfe055623e2d931910984c8fdb713ecbc065b49c620daf52f3239f7f74ea2`

When a **Sarcophagus set for public disclosure is resurrected**, the bot will post:
1. The **link to the payload**.
2. The **BASE address that created the Sarcophagus** originally.


