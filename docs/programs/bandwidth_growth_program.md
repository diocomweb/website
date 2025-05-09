---
layout: default
title: Bandwidth Growth Program
parent: Programs
nav_order: 3
---

# Bandwidth Growth Program

Active!  Monitor the [Discord](https://discord.gg/qdGCAKJdHs) for announcements.

[Register](#registration)

[Terms and Conditions](/docs/programs/terms.html)

## Overview

The goal of the regional Bandwidth Growth Program is to grow the capacity of high-quality regional network bandwidth around the globe.  

In order to participate in this program, you must first register for a [Referral Code](/docs/programs/ambassador_registration_program.html).

## Goals

A key competitive differentiator for a communications network is the availability and quality of the network, which is in turn directly related to the regional distribution of “Points of Presence” (PoPs) in the network. For example, if two people want to chat securely with each other, their experience will be much better if a Relay Node is located near to them.  Their encrypted messages will never leave their immediate region, and the round-trip time for the messages will be very short.

In the Diode Network, the PoPs are the Relay Nodes. Therefore, the program is focused on the deployment of Relay Nodes.

A 12-month goal of the Diode Community DAO is to achieve 1,500 regional Relay Nodes. A secondary goal of the Diode Community DAO is to achieve greater bandwidth demand from ecosystem fleets than from Diode commercial Fleet Contracts within 36 months.

## Rewards

Participants are rewarded based on the activity of the Relay Nodes who have been registered by the Referral Code owner or by others they have referred (see "Reward Calculation" below). Although Relay Nodes get Bandwidth Rewards whether or not they participate in the program, they will also receive Bandwidth Boost Rewards as part of the program.

### Reward Mechanism

In order to be rewarded by this program, you must have registered for a [Referral Code](/docs/programs/ambassador_registration_program.html), you must have registered your Relay Node, and your Relay Node must have provided some bandwidth to the Diode Network (as proven through bandwidth proofs that the Relay Nodes automatically submit to the network at the end of each month), and must be online for the majority of the epoch - including within 24 hours of the close of the epoch.  If a registered Relay Node achieves these requirements, they will be eligible for rewards.

### Reward Calculation

When Bandwidth Rewards are deployed at the end of each month, the percentage of the total network rewards that each Relay Node receives is calculated as its “Relay Bandwidth Contribution”. Based on its Relay Bandwidth Contribution, if a Relay Node has registered for the program, a “Bandwidth Boost Award” will be allocated to the Relay Node from a monthly Bandwidth Growth Program pool amount. This allocation is then distributed to the Relay Node, and the antecedents of the Referral Code under which it was registered, all the way up to the top Seed Referral Code.

The reward for all antecedents under the Seed Referral Code is based on the geometric progression r = b * 0.5^h,  where r is the relevant antecedent reward, b is the relay’s total allocated Bandwidth Boost Award, and h is the height of the antecedent relative to the relay (e.g. the relay has a height of 1, it’s parent has a height of 2).

The Seed Referral Code’s reward is the same as its child (r = b * 0.5^(h-1) ). In this way, the total distribution is always the allocated Bandwidth Boost Award, there is no incentive to create fake descendants, and there is no incentive for creating fake traffic.

An example distribution to the antecedents of a Relay Node who has handled 2% of the network’s staked traffic when the monthly Bandwidth Growth Program pool has 10,000 DIODE is shown below:

| Entity      | Bandwidth Boost Award |
| ----------- | ----------- |
| Seed Code (h=5) | 12.5 DIODE |
| Child Code | 12.5 DIODE |
| Grandchild | 25 DIODE |
| Great Grandchild | 50 DIODE |
| Relay Node (Great-Great Grandchild) (h=1) | 100 DIODE |
| **Total Allocated Award** | **200 DIODE** |

## Registration

You must register your Relay Node in order to attributed rewardable traffic to your Referral Code, and any code in the hierarchy above you.

### How to Register a Relay Node

1. Join the [Diode Referral Program](https://diode.foundation/docs/programs/ambassador_registration_program.html) and get your own referral code
2. [Put a Relay Node online!](https://forum.diode.io/t/lite-node-installation/33)
3. Open the [Diode Referrals Zone](https://diode.io/joinzone/#p0xUHtufRS_tMNd9XRvnxbMmXPtOyRbPrQLnLN4j3VNsDhwSrpRYpwbnhMZ2) in your Diode App and click the "Registrar" DM
5. Use the command "register [node address]" where [node address] is the public key of your Relay Node (make sure you don't attempt to register a node / address that you do not own - this can result in your code being banned from the system)
6. You can type "nodes" to get a list of nodes that belong to you
7. Start relaying traffic!

## Governance

**The following activities are bannable offenses:**

* Registering a node or zone that does not belong to you
* Falsifying data from a node or zone
* Creation of multiple user identities by the same person in order to acquire referral points
* Otherwise attempting to game the system in ways that are not aligned with the Diode Foundation's purpose or the program's goals

The Diode Community DAO is responsible for governance of this program.  For example, the DAO will decide whether to continue the program after the first 36 months.

All Relay Node registrations are valid for 36 months only, after which the Relay Node rewards will no longer be allocated a Bandwidth Boost Award. Once a child Relay Node has been registered, registrations may not be changed.

Unallocated Bandwidth Boost Award, if any, will be added to the following month’s Bandwidth Growth Program Pool.

  


