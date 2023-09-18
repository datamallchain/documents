DMC Ambassador Training

# Module 7—DMC Smart Contract

<img alt="DMC Ambassador Training" style="height: 300px" src="./Main.png">

## Overview

The Global Ambassador Program (GAP) is open to individuals who have a desire to learn DMC and its app Foggie, regardless of prior knowledge. A can-do attitude is preferred.

The program includes nine modules, its projects, and corresponding DMC awards associated with projects. The length of the GAP can range from 4 to 24 weeks. You are welcome to expedite your learning path and finish all the projects earlier. Upon project completion, participants are eligible for DMC or Foggie badges. Currently, these awards range from 5 DMC to 720,000 DMC. And the awards are subject to change without advanced notice.

This program is ongoing, allowing participants to join at their convenience. Once enrolled, you will become part of the Global Ambassador Group, which includes numerous experts who are ready to support you in your project endeavors. We encourage you to make the most of this valuable resource, learn from them, and most importantly establish your own DMC community.

We recognize and appreciate the efforts of those who work hard to complete their projects by awarding them badges. The highest level of achievement in the project is marked by a blue ribbon.The GAP program has two levels: GAP class & its project, and Foggie Badge Level as below:

![Project levels](./Projects.jpg)

## 7.1 Lecture

**Lectured by:** Nam team, the creator of DMC Smart Contract

Hello everyone, it is a great pleasure and honor to be here. Today, I will share with you an introduction to the technical aspects of the DMC blockchain.

First of all, as everyone knows, DMC is a public chain platform that supports the creation and development of blockchain application ecosystems, allowing you to easily create your own value network and help developers and entrepreneurs step into the world of blockchain. In addition, Datamall Chain is an open-source public blockchain that provides stable, reliable, and decentralized storage services by building a decentralized storage network based on Nash-Consensus.For those who are interested in smart contracts, you can also visit GitHub to learn more: https://github.com/datamallchain. You can also check on: https://github.com/datamallchain/dmchain_contract.

The most important part of the DMC blockchain is the smart contracts, and today I will be sharing with you about smart contracts.Currently, the ecosystem consists of two main types of contracts: system contracts and token contracts. This includes contracts for minting, trading, delivery, storage challenges, and more. For detailed information about each contract, you can click on our developer platform to learn more:

- System Contracts: https://developer.dmctech.io/zh-cn/api/system/index.html

- Token Contracts: https://developer.dmctech.io/zh-cn/api/token/index.html

You can find information on how to deploy nodes on the blockchain and participate in ecosystem development, among other things, on the developer website.

In previous discussions, we have briefly introduced concepts such as minting, trading, and storage challenges. Today, I will provide a more detailed explanation to help you better understand these concepts.

First, let's discuss the minting contract, which can be found at: https://developer.dmctech.io/zh-cn/api/token/index.html#mint.

When you review the relevant methods, you will come across the "mint" method. This part mainly focuses on the minting contract, MP (Miner the Provider) can obtain the right to mint PST (Proof of service token) by staking DMC tokens. It's important to note that MP can choose to stake their own DMC tokens or accept LP (Limited Partner) amounts. Larger mining pools can choose to make their computing power public to attract more LP. When MP meets the minimum share requirement (20%), they can accept up to 80% of the amount put in. When an order is executed, the profits and dividends will be settled according to the corresponding proportions. However, LPs should also assess the MP before putting in because this comes with risks. If a miner defaults, LPs may suffer losses.The most crucial part is the liquidation, which must satisfy the condition that `r` (current stake rate) is less than `n'` (`n'` = `0.6m'`, where `m'` is the custom stake rate). Since the market is volatile, MP needs to constantly monitor whether they meet the stake requirements to avoid triggering liquidation.If MPs want to exit, they must meet two conditions. First, all LPs must have exited the system. Second, all PSTs must be completely burned.

Next is the trading and delivery contract, which can be found at: https://developer.dmctech.io/en-us/api/token/index.html.

Currently, the platform adopts a matching trading mechanism. MC can search and select the desired orders based on their actual needs and execute the transactions. It's important to note that the minimum service period on the chain is currently 24 weeks. This means that when MCs make a payment, they need to pay for at least 24 periods.When they want to renew the contract, they can directly recharge the order with the required fees. The fees will be locked in the delivery contract, and the contract will deduct the fees every 7 days based on the order period.MP can choose to claim the fees every 7 days or accumulate them and claim them all at once. When claiming, MP needs to be aware that the system uses an internal Uniswap algorithm. When they click on the claim button, the system will perform a unified exchange and distribute the incentives according to the rules. Therefore, miners can choose the appropriate timing to claim their rewards.

The last part is the Storage Challenge Contract, which can be found at: https://developer.dmctech.io/en-us/api/token/index.html#addmerkle. Currently, there are three types of storage challenges on the chain. The first type is the storage challenge initiated by MC. There are also random challenges initiated by the system and directed challenges that can be initiated by the DMC Foundation. These challenges are designed to prevent malicious behavior on the chain.

The storage challenge consists of four stages: storage preparation, storage proof, challenge notarization, and arbitration. There has been a detailed explanation of this part before, so I won't go into too much detail here. I'll mainly explain random challenges and foundation-directed challenges.

We have two main types of challenges. The first type is a data challenge where MC can store a portion of the data locally and select a portion of the data to initiate a storage challenge to MP. Upon receiving the request, MP needs to respond within 24 hours to prove that they have indeed stored MC's data.

Another scenario where local data is not available is when a challenge is initiated based on the Block ID. This is known as a random challenge, and the Foundation also uses this approach to initiate challenges. Random challenges involve the system randomly challenging orders on the chain at regular intervals. The challenged orders must respond within a specified time frame, or they will be treated as defaults. Similarly, in the case of targeted challenges by the Foundation, when abnormal transactions occur on the chain, the Foundation can initiate storage challenges for the relevant orders.

That’s all for today’s lecture, I hope you have learned something and know DMC better. Thank you for your participation and engagement!

## 7.2 Quiz

1. What are the roles in the DMC ecosystem?

   1. MC, MP, LP
   2. Developers and programmers
   3. Token holders and participants putting in tokens
   4. Community members and ambassadors

   > Answer: MC, MP, LP

2. What does PST stand for?

   1. Public Security Token
   2. Private Sales Token
   3. Proof of Service Token
   4. Payment Settlement Token

   > Answer: Proof of Service Token

3. When will MC be liquidated?

   1. When `m'` is less than or equal to `n'`
   2. When `m'` is greater than or equal to `n'`
   3. When `r` is less than `n'`
   4. When `r` is less than `m'`

   > Answer: When `r` is less than `n'`

4. How many stages are there in the storage challenge?

   1. Storage Preparation, Storage Proof, Challenge Notarization, Arbitration
   2. Storage Preparation, Storage Challenge, Random Challenge, Arbitration
   3. Notarization of Storage, Hash Comparison, Storage Challenge, Challenge Notarization
   4. Hash Upload, Block ID Challenge, Challenge Notarization, Arbitration

   > Answer: Storage Preparation, Storage Proof, Challenge Notarization, Arbitration

5. What does `m'` represent?

   1. Minimum stake rate
   2. Custom stake rate
   3. Compensation rate
   4. Liquidation rate

   > Answer: Custom stake rate

## 7.3 Live Q&A

1. What happens if an MP failed the challenge but MP thinks it is not his fault?

   > Answer: You can Increase the DMC staking amount or choose to destroy the minted but unexecuted portion of PST. MP can initiate arbitration within a specified time frame. For specific details, please refer to the arbitration section in the technical yellow paper. [*https://www.dmctech.io/down/DMC%20Technical%20Yellowpaper-v2.0.pdf*](https://www.dmctech.io/down/DMC%20Technical%20Yellowpaper-v2.0.pdf)

2. If a miner defaults, and I am an LP, can I redeem the DMC I put in?

   > Answer: No, LP cannot claim the DMC under this situation.

3. What should i do if I trigger the liquidation?

   > Answer: MC can only choose the longest service period, you can choose to buy 36 weeks instead

4. Can I cancel the order midway? What will happen?

   > Answer: MC or MP can cancel orders, but they will face severe penalties.

# :medal_sports: Project 7: 1,000 Foggie Users

Please recruit your community to become Foggie “Storage” users of 100G for 24 weeks. Your Foggie users need to purchase storage space of 72 DMC under the required IDs. Please check with the DMC team on IDs. The target for project 7 is 1000 Foggie Users. Please use your referral code for the recruitment.

The award for 1,000 users is 14,400 DMC. You can either claim it or save more in the future claim for a bigger award.

![](Module 3 media/Buy storage.jpg)

DMC Initiative of 100,000 Foggie users for 100G/24 weeks within 24 weeks is as followed:

| **Storage Pool** | **Sales# in 24 weeks**                                                                 | **DMC Staking** | **Commission Rate** | **DMC Commission** | **Foggie Badge**       |
|------------------|----------------------------------------------------------------------------------------|-----------------|---------------------|--------------------|------------------------|
| Level 5          | 10,000                                                                                  | 720,000         | 100%                | 720,000             | ![](Module 6 media/Level 5.png) |
| Level 4          | 5000                                                                                   | 360,000          | 40%                 | 144,000            | ![](Module 6 media/Level 4.png) |
| Level 3          | 1000                                                                                   | 72,000          | 20%                 | 14,400             | ![](Module 6 media/Level 3.png) |
| Level 2          | 100                                                                                    | 7,200           | 10%                 | 720                | ![](Module 6 media/Level 2.png) |
| Level 1          | 10                                                                                     | 720             | 0                   | 0                  |                        |

Notes:

1. You need to claim the number of Foggie Sales with one referral account within 24 weeks.
2. The timeframe for one referral code last for 24 weeks
3. After 24 weeks, the recalculation of sale# will be in place	

The award is subject to change without any advanced notice.
