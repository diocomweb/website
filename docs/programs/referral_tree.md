---
layout: default
title: Referral Tree
parent: Programs
nav_order: 4
---

# Referral Tree

Active!  Monitor the [Discord](https://discord.gg/qdGCAKJdHs) for announcements.

[Terms and Conditions](/docs/programs/terms.html)

## Overview

Participants in the Diode Referral Program are eligible to receive Referral Tree Points - also known as "Indirect Points".

A Referral Tree is created when someone uses your Referral Code to register for the [Diode Referral Program](/docs/programs/ambassador_registration_program.html) - these are your "children".  When someone else uses your child's Referral Code to register, they are your "grandchild".  In this way, a Referral Tree is built - sometimes with many members under your code.  A given participant in your Referral Tree is called your "descendant".

## Goals

A healthy ecosystem requires active ecosystem leaders.  If you have referred others to the Diode Referral Program, you can be rewarded for your "descendant's" contributions as an incentive to keeping your Referral Tree working well for both the Diode Foundation and for yourself.

## Rewards

Participants are rewarded based on the activity of their descendants, up to a maximum of their own direct rewards.  See Reward Calculation below for details.

### Reward Qualifications

In order to be rewarded by your Referral Tree you must:

- be an [Active Affiliate](/docs/programs/diode_affiliate_program.html)
- have others who have registered with your Referral Code
- have descendants who have earned direct points
- have earned direct points yourself

### Reward Calculation

Your Referral Tree points can be a maximum of your Direct Points.  Direct Points are points earned from your contributions to various programs, like hosting active nodes for the [Bandwidth Growth Program](/docs/programs/bandwdith_growth_program.html)

Referral Tree points are earned when a descendant in your Referral Tree earns points.  Referral Tree points are calculated by awarding points to each antecedent of the participant who registered the active item (node, zone, referral), all the way up to the top Seed Referral Code.

The reward for each antecedent is based on the geometric progression r = b * 0.5^h,  where r is the relevant antecedent reward, b is the active participant's total Direct Points, and h is the height of the antecedent relative to the active participant (e.g. the parent of a node runner has a height of 1, their grandparent has a height of 2).  The Seed Referral Code’s reward is the same as its child (r = b * 0.5^(h-1) ). In this way, the total distribution is always the same and there is no incentive to create fake descendants.

An example distribution to the antecedents of an active participant who has earned 100 points from running nodes is shown below:

| Entity      | Referral Tree Award |
| ----------- | ----------- |
| Seed Code (h=5) | 12.5 Points |
| Child Code | 12.5 Points |
| Grandchild | 25 Points |
| Great Grandchild | 50 Points |
| Great-Great Grandchild (h=1) | 100 Points |
| **Participant Direct Award** | **200 Points** |

## Governance

**The following activities are bannable offenses:**

* Attempting to game the system in ways that are not aligned with the Diode Foundation's purpose or the program's goals

The Diode Community DAO is responsible for governance of this program.  


  


