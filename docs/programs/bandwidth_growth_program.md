---
layout: default
title: Bandwidth Growth Program
parent: Programs
nav_order: 2
---

# Bandwidth Growth Program

**Launching in May, 2024** Monitor the [Diode Telegram channel](https://t.me/diode_chain) or [X](https://x.com/diode_chain) for details.

[Register](#registration)

[Terms and Conditions](/docs/programs/terms.html)

## Overview

The goal of the regional Bandwidth Growth Program is to grow the capacity of high-quality regional network bandwidth around the globe.  

In order to participate in this program, you must first register as an [Ambassador](/docs/programs/ambassador_registration_program.html).

## Goals

A key competitive differentiator for a communications network is the availability and quality of the network, which is in turn directly related to the regional distribution of “Points of Presence” (PoPs) in the network. For example, if two people want to chat securely with each other, their experience will be much better if a Relay Node is located near to them.  Their encrypted messages will never leave their immediate region, and the round-trip time for the messages will be very short.

In the Diode Network, the PoPs are the Relay Nodes. Therefore, the program is focused on the deployment of Relay Nodes.

A 12-month goal of the Diode Community DAO is to achieve 1,500 regional Relay Nodes. A secondary goal of the Diode Community DAO is to achieve greater bandwidth demand from ecosystem fleets than from Diode commercial Fleet Contracts within 36 months.

## Rewards

Ambassadors are rewarded based on the activity of the Relay Nodes who have been referred by the Ambassador directly or by other Ambassadors who the Ambassador has referred (see "Reward Calculation" below). Although Relay Nodes get Bandwidth Rewards whether or not they participate in the program, they will also receive Bandwidth Boost Rewards as part of the program.

### Reward Mechanism

In order to be rewarded by this program, each Ambassador or Relay Node must be part of the [Ambassador Program](/docs/programs/ambassador_registration_program.html) and must have provided some bandwidth to the Diode Network.  If a registered Ambassador provides bandwidth to the network, as proven through bandwidth proofs that the Relay Nodes automatically submit to the network at the end of each month, the network will calculate and distribute rewards.

### Reward Calculation

When Bandwidth Rewards are deployed at the end of each month, the percentage of the total network rewards that each Relay Node receives is calculated as its “Relay Bandwidth Contribution”. Based on its Relay Bandwidth Contribution, if a Relay Node has registered for the program, a “Bandwidth Boost Award” will be allocated to the Relay Node from a monthly Bandwidth Growth Program pool amount. This allocation is then distributed to the Relay Node, its associated parent Ambassador, and that Ambassador’s antecedents, all the way up to the top Seed Ambassador.

The reward for all antecedents under the Seed Ambassador is based on the geometric progression r = b * 0.5^h,  where r is the relevant antecedent reward, b is the relay’s total allocated Bandwidth Boost Award, and h is the height of the antecedent relative to the relay (e.g. the relay has a height of 1, it’s parent has a height of 2).

The Seed Ambassador’s reward is the same as its child (r = b * 0.5^(h-1) ). In this way, the total distribution is always the allocated Bandwidth Boost Award, there is no incentive to create fake descendants, and there is no incentive for creating fake traffic.

An example distribution to the antecedents of a Relay Node who has handled 2% of the network’s staked traffic when the monthly Bandwidth Growth Program pool has 10,000 DIODE is shown below:

| Entity      | Bandwidth Boost Award |
| ----------- | ----------- |
| Seed Ambassador (h=5) | 12.5 DIODE |
| Child Ambassador | 12.5 DIODE |
| Grandchild | 25 DIODE |
| Great Grandchild | 50 DIODE |
| Relay Node (Great-Great Grandchild) (h=1) | 100 DIODE |
| **Total Allocated Award** | **200 DIODE** |


### Reward Pool

The Diode Foundation has set-aside 1M DIODE for the Bandwidth Growth Program. The Bandwidth Growth Program Pool will be filled by the Diode Foundation at the beginning of every month for 36 months with a minimum of 10,000 DIODE. After 36 months, depending on the overall bandwidth supply in the network, the Diode Foundation will evaluate whether to extend the program for an additional 12 months at a time, or to distribute the remaining allocated tokens to program contributors.

## Registration

You must register your Relay Node in order to attributed rewardable traffic to yourself as an Ambassador, and anyone in the hierarchy above you.

### How to Register a Relay Node

**Details will be updated in April, 2024**

1. Join the [Ambassador Program](https://diode.foundation/docs/programs/ambassador_registration_program.html) and get your own referral code
2. In **Mide/Late April of 2024, monitor the Diode Community Telegram channel** for information about how to host a Relay Node
3. Put a Relay Node online!
4. Open the Ambassador Zone in your Diode App and click the "Registrar" DM
5. Use the command "register [node address]" where [node address] is the public key of your Relay Node (make sure you don't attempt to register a node / address that you do not own - this can result in your Ambassador profile being banned from the system)
6. You can type "nodes" to get a list of nodes that belong to you
7. Start relaying traffic!

## Governance

**Please do NOT register a node that does not belong to you - this may result in your being banned from the system**

The Diode Community DAO is responsible for governance of this program.  For example, the DAO will decide whether to continue the program after the first 36 months.

All Relay Node registrations are valid for 36 months only, after which the Relay Node rewards will no longer be allocated a Bandwidth Boost Award. Once a child Relay Node has been registered, registrations may not be changed.

Unallocated Bandwidth Boost Award, if any, will be added to the following month’s Bandwidth Growth Program Pool.

Please do NOT* Register a node that does not belong to you - this may result in your being banned from the system
  


