---
layout: default
title: Diode Network
nav_order: 4
---

# Diode Network

The Diode Network provides end-to-end encrypted communication, and related capabilities, to endpoints.  It is an open protocol DePIN network that is comprised of a diverse set of contributors who run a [Diode Network Node](https://github.com/diodechain/diode_server).  These contributors operate their node in keeping with the [Diode Network Node License](https://github.com/diodechain/diode_server/blob/master/LICENSE) and are not obligated to provide services to anyone.

Relay Node operators the bandwidth they host for [DIODE tokens](/docs/token.html).

## How to use the Network

You need to use an application that uses the network.  For example, see [Diode's website](https://diode.io) for more information on the Diode App and the Diode CLI.

If you want to build your own application that uses the network, checkout the [Diode CLI's open source client software](https://github.com/diodechain/diode_client).

## Relay Nodes

The Diode Network is made up of many decentralized physical infrastructure (DePIN) nodes we call Relay Nodes.  These nodes run the [Diode Network Node](https://github.com/diodechain/diode_server) software.

The requirements to host a Relay Nodes are:

- Linux system (VM or box) - something as light as a Raspberry Pi or a $4 Digital Ocean VM will work to start out
- A static IP address - if you don't have a static IP address, the network will not be able to find your node reliably and you will be deprioritized for traffic routing

## Relay Node security

The Diode Network uses 256 bit end-to-end encrypted communications that are "relayed" by Diode Network Relay Nodes to the desired destination.

The reasons why anyone can host a Relay Node without detracting from network security are two:

- Both the network and the endpoints validate participants via access control lists stored in smart contracts.  If any one of the participants or the node is dishonest, the blockchain-anchored data will expose it.
- All communications are end to end encrypted using industry battle tested negotiation algorithms and encryption encapsulation.  The network nodes have zero visibility into the communications.

Many organizations also opt to host their own Relay Node.  In this way, they can take advantage of the global network addressing and routing, while directing their traffic to ultimately use their own Relay Node.

## Relay Node Incentives

Most people will host a Relay Node to trade the bandwidth they supply for [DIODE bandwidth tokens](/docs/token.html).

However, some people will host a node to provide themselves, and their users, with their own Diode Network bandwidth - this can have the advantages of greater privacy and potentially lower cost.


## Relay Node Legal Considerations

Because all data touching a Relay Node is fully encrypted, a Relay Node will usually be considered an "Intermediary Internet Service" (AKA "Common Carrier") and can be operated with the same legal standing as other similar infrastructure (for example, like infrastructure another Internet Service Provider operates).

Relay Nodes must abide by the [Diode Network Node License](https://github.com/diodechain/diode_server/blob/master/LICENSE).

Otherwise, the are no other contractual liabilities or warranties required from Relay Node operators.

## Application Sponsors

Application Sponsors (AKA Fleet Contract Owners) stake DIODE tokens into a Fleet Contract that sponsors bandwidth for any endpoint listed in the Fleet Contract.  When endpoint traffic is routed to a Relay Node, the Relay Node checks the sponsoring Fleet Contract to see how many DIODE tokens it will trade for bandwidth - if the Relay Node determines the trade is good enough, it will accept the traffic.

At the end of the month, the DIODE tokens are deducted from the Fleet Contracts by the Diode Network, and distributed to the Relay Nodes algorithmically.  The [Fleet Contract LICENSE](https://github.com/diodechain/diode_contract/blob/master/LICENSE) governs the Application Sponsor's use of the Fleet Contract to trade DIODE tokens for bandwidth.
