# Rewards: dQueues

dQueues are designed to manage essential tasks required for the protocol's perpetual operation and regular maintenance. Much like traditional cron jobs, they allow anyone to execute scheduled or recurring tasks, but without the need for a centralized server and are therefore, totally decentralized. No centralized LTS dependency is required. Tasks such as recalling expired genus names or performing other protocol maintenance can be processed through the dQueue, ensuring the system remains operational. Those who execute dQueue tasks are rewarded with $RNS tokens, which cover transaction fees and incentivize participation.

---

## dQueue Functionality

The $RNS rewards for dQueue participants come from the DAO's maintenance pool, which is funded by 1% of the DAO's revenue. The reward distribution is demand-based, meaning that the rewards increase when there is a higher volume of tasks in the queue. This ensures that the protocol remains well-maintained, even during periods of heavy demand.

**1. Task Execution and Rewards:**<br />
- When a task is executed from the dQueue, the participant receives $RNS tokens. These tokens act both as an incentive and as a reimbursement for the transaction fees incurred when executing the task.
- Tasks are queued based on operational needs, and anyone can claim and execute them. Rewards vary based on demand, complexity, and task backlog.

**2. Variable Pool Size and Reward Regulation:**<br />
- The maintenance pool, which funds these rewards, can fluctuate based on DAO revenue. To prevent depletion of the pool, a dynamic reward cap system regulates the distribution of rewards.
- The reward cap is determined based on the size of the pool and the number of pending tasks in the dQueue. If there are many pending tasks, the reward cap increases proportionally to encourage users to help clear the backlog.


## Dynamic Reward Cap

The dQueue reward system uses a dynamic cap model to regulate how much $RNS can be distributed during each epoch (a fixed time period). The cap adjusts based on:

- **Maintenance Pool Size:** A percentage of the pool is allocated for rewards each epoch. For example, if the pool holds 10,000 $RNS, perhaps 10% (1,000 $RNS) can be distributed in that epoch.
- **Demand-Based Multiplier:** The reward cap can increase if the dQueue has a large backlog of tasks. For every predefined number of pending tasks (e.g., 50), the reward cap increases slightly to incentivize quicker execution.

<em>Cap for Epoch = Pool Size * (Base $RNS Cap + Task Threshold / Pending Tasks)</em>

This model ensures that:

- **Few Tasks:** The reward remains close to the base level if the dQueue is nearly empty.
- **High Backlog:** If there is a large backlog of tasks, rewards increase, motivating users to engage and clear the queue faster.

## Participation

**1. Monitor the dQueue:**<br />
Users can view the available tasks in the queue and select tasks they want to execute by calling the dQueue component.

**2. Execute Tasks:**<br />
By executing a task, users contribute to the protocol's maintenance and ensure smooth operation.

**3. Receive Rewards:**<br />
After completing a task, users automatically receive $RNS tokens. Rewards include both an incentive and reimbursement for transaction fees incurred during execution.

**4. Benefit from Dynamic Rewards:**<br />
The more tasks there are in the dQueue, the higher the potential reward, making it advantageous to engage when required provision is high.

## Key Advantages

**Decentralized and Reliable:** With no need for a centralized server, the protocol is more resilient to outages or failures, as any participant can maintain it by executing tasks.<br />
**Incentivized Participation:** The reward structure encourages active participation, with higher rewards during periods of high demand, ensuring critical tasks are completed promptly.<br />
**Cost Reimbursement:** Participants receive $RNS tokens not only as an incentive but also to cover transaction fees, making it economically viable to participate.<br />
**Sustainable Protocol Maintenance:** By distributing the responsibility of protocol maintenance across many participants, dQueues help ensure the long-term sustainability and smooth operation of the protocol.

<!-- changelog:start -->

This is the contribution that serves to keep track of ideation sources, authorship and documentation modifications within the DAO. If you have created or contributed to an idea, or optimized the content of this page, please fill out the form to allow others to see under which context the submission occurred.

| Name  | Date            | Notes |
| :-----: | :---------------: | :---------------------------: |
| James Wylie (Wylie.xrd) | 6th Oct 2024 | Concept Ideation / Authorship |

<!-- changelog:end -->