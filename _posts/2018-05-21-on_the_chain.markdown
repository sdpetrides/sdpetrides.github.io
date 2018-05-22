---
layout: post
title:  "On the Chain"
date:   2018-05-21 13:20:00 -0400
categories: technology
---

# The problem with designing applications for the blockchain is not the platform itself, but managing the interaction between a messy reality and a sterile network.
A huge staple of blockchain technology (Bitcoin, Ethereum) is that there is no reliance on third-parties. Anyone can participate in the network and full-nodes get everything there is to know. This creates a sterile environment free of errors and mistakes.

As the blockchain experiment rolls on, it seems that this system is working. With many distributed nodes checking everyone’s work (transactions, smart contracts), there have been few issues with the technology itself. As long as everything stays “on the chain,” we observe the expected behavior.

However, there is an issue for real-world applications that use these platforms. How do we put things onto blockchains? How do we take them off?

Take, for example, making a transaction on the Bitcoin platform. One can simply create the transaction with the sending and receiving addresses, add the amount, sign with the private key, and propagate across the network. Soon, nodes will verify that the transaction is valid and add it to the next block. This process is happening constantly and without fail due to the design of the Bitcoin platform. The issue is, how does one go from zero to one? How does a new user get any Bitcoin to spend?

Currently, the only solution trusting a third-party to exchange some goods or value for Bitcoin. This critical first step could be as simple as asking a friend to send your new address some Bitcoin. More commonly, new users rely on large private exchanges. [Coinbase](https://www.coinbase.com/) is the largest and most common exchange in the US. The purpose of a private exchange is very the same as the example above. However, by introducing a large, centralized service that operates within a black box, Bitcoin is inviting some of the issues that it was trying to avoid in the first place.

This issue reflects a larger challenge within blockchain development: how does our messy reality interface with our pristine blockchains?

The Ethereum platform has trouble answering this question as well.

While Bitcoin is a distributed ledger, Ethereum is a distributed computer. It has smart contracts that are autonomously triggered in response to certain events. These smart contracts go on to change some state that is meaningful in some way. Many have theorized that this platform can potentially go on to host many (if not endless) applications. Examples include legal and medical documentation, social platforms, distributed media companies, etc. Ethereum is faced with many issues as a platform: scaling, power, etc. Still, it must also deal with the challenge of interacting with our messy reality.

Imagine there is a set of smart contracts that act as legal wills. In the case of death, the will document is revealed. This application benefits from the Ethereum platform since all participants will have a copy of the single, legally-binding will.

Assume that there is a way to hide the contents and existence of the will until the event of death (not a trivial task but assumed to be solved), there is still the issue of how to trigger the smart contract. Who decides that the person is dead? How does this proclamation make its way onto the platform? How can it programmatically trigger the smart contract? Currently, revealing a will occurs after an authority confirms the event of death. So how is the authority in this trustless blockchain network?

In a similar example, imagine implementing the company [Back Up Your Life](https://www.technologyreview.com/s/611162/job-of-the-future-embalming-your-online-persona/) that “focus[es] on preparing people, particularly in their digital lives, for the day they can no longer speak for themselves.” A common case is the release of passwords and transfer of digital accounts to a trusted family member or friend upon a person’s death. It is clear that the policies of password dissemination and account transfer should be broadcast to the Etheruem platform and revealed upon the person’s death. However, the same questions arise: who has the authority to add these policies to the network and who has the authority to trigger the smart contract?

While blockchain technology is fascinating, how can we possible sanitize our reality to fully mesh? Is it particularly necessary? Is the use of trusted third parties inevitable?

Personally, I believe that there will be ways for many applications to thrive on the blockchain. Still, there will be a period of critical thinking and experimentation that will give rise to these application-specific solutions.

---

* [Coinbase](https://www.coinbase.com/)
* [Back Up Your Life](https://www.technologyreview.com/s/611162/job-of-the-future-embalming-your-online-persona/)
