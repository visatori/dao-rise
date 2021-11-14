# Dreamers Rise and Dreamers DAO

This describes the idea of setting up the instance that will give rise to the Dreamers DAO.

The "Dreamers Rise" is a short-lived smart contract that will be used only to get an initial set of members who will be able to vote on the Dreamers DAO. The details of the Dreamers DAO are to be discussed; the purpose of this proposal is to get the Dreamers Rise up and running.

## Purpose of Dreamers DAO

The purpose of the Dreamers DAO is to provide a governance mechanism for the Dreamers community. The Dreamers DAO will be a voting platform for the Dreamers community to vote on proposals.

Once the Dreamers DAO is spawned into existence, the mechanics of the DAO are subject to change and voted on by the people who are part of the Dreamers community. The weight (amount) of their tokens will determine their voting power.

Access to the community is also gatekept by a certain number of tokens in one's wallet.

Some of you may know that a group of people (some of them are here) initially invested in the Decentraland project. At the moment, there is only one wallet that controls the funds of the project. This wallet is owned by one person. Since the group is not cohesive anymore, decisions regarding those funds are difficult to make. A platform does not exist that can help those members do actions regarding their common funds. At the moment, it's challenging to make any decisions that affect the invested funds. Effectively the funds are locked until a better way of organizing is put in place.

The Dreamers DAO could be a solution for a similar initiative; it could hold the invested funds, generate shares to represent each person's involvement, and serve as a platform for buying, selling, or other specific project actions. 

Other ideas for the Dreamers DAO could be:

- mutual investment fund (an administrator could be set to receive a certain percentage of the profits)
- ape-ing into stupid coins like [gm](https://coinmarketcap.com/currencies/gm/)
- buying/selling NFTs
- voting members in/out
- creating a "free invite" ticket which bypasses the need for tokens for a new member (each member could have such a ticket generated once per year)
- paying for Discord features; we could get nice things for the community because we could set a budget. I believe we should be able to afford niceties.
- killing the DAO itself; I believe a DAO has to have the power to kill itself. One should have the possibility to end the existence of the DAO.

Its purposes vary from simple things like admitting a new member into the community (or voting one out) to more complex things like changing the rules of the DAO or creating a mutual fund that can be used by the community in the DeFi ecosystem. Its profits can be split or consumed by the community after a vote is made.

## Joining Dreamers Rise

One can join Dreamers Rise by sending between 0.1 and 0.5 ETH to the Dreamers Rise contract. In exchange, the Dreamers Rise will mint between 100 and 500 tokens to the user. These funds can be used in the future to do different actions on the Ethereum network. It is important to lock some funds in the system to ensure that the users are invested in the Dreamers Rise.

Any usage of the funds will be voted by the members of Dreamers DAO once it is spawned.

## Timeline

The following is an open-for-discussion timeline of the Dreamers DAO from the moment of the inception, to the moment of its spawn.

### 2021-11-14: Dreamers proposal

Today is the first day the proposal sees the dawn of day. People will be able to discuss ideas on how the Dreamers DAO should spawn. 

Discussion is open, things can change, nothing is set in stone.

### 2021-11-21: Dreamers Rise

We have a better overview of the Dreamers DAO's future based on the initial proposal and ideas around it.

Ideally, we have set a minimum and maximum fee for joining the Dreamers DAO. At the moment, the minimum is set to 0.1 ETH, and the maximum is 0.5 ETH.

We can start working on the Dreamers Rise contracts, accepting funds and spawning the Dreamers DAO. At the same time, the $DREAMER token will be created. This token will represent one's share of the DAO.

A DAO implementation can be created from scratch. However, it is recommended to use one of the existing DAO implementations. More research needs to be put into this, but there are some notable examples:

- ⛓ [Governor Alpha](https://github.com/compound-finance/compound-protocol/blob/master/contracts/Governance/GovernorAlpha.sol)
- ⛓ [Governor Bravo](https://github.com/compound-finance/compound-protocol/blob/master/contracts/Governance/GovernorBravoDelegate.sol)
- ⛓ [Aragon Govern](https://govern.aragon.org/#/)
- ⛓ [Aragon Client](https://client.aragon.org/#/)
- ⛓ [Gnosis Safe multisig](https://gnosis-safe.io/)
- [Snapshot](https://snapshot.org/#/)
- [EIP-like proposals](https://eips.ethereum.org/EIPS/eip-1)

#### Legend

⛓ on-chain, usually directly enforced (passing the vote executes a set of actions)

### 2021-11-28: Dreamers Rise and shine 

Dreamers Rise contract is deployed. People can start joining in by depositing their entry fee.

### 2021-12-06: Dreamers DAO spawn

Dreamers DAO is deployed. Future actions can be proposed and voted on.

## Notes and mentions

### Gas costs

At the moment, the gas costs on Ethereum are high, not higher than ever, but high nonetheless. Because we might want to trigger immediate actions once a vote is passed, we must adequately consider some steps to be voted directly on the Ethereum blockchain. This means that the costs will be considerable. Such actions have to have an economic incentive to make sense. To allow users to send transactions with the lowest gas cost possible, we'd need to have the shortest timeline of 1 week. Historically, Sundays have the lowest gas cost.

[![Gas prices](https://i.imgur.com/5JEZMME.png)](https://dune.xyz/embeds/243271/455018/c2f4b5d1-ebf6-4e89-9dba-1957719c1f85)

A different way of reducing costs is to have a few trusted parties access a shared multisig with a particular purpose. These parties will receive a portion of the funds in the Dreamers DAO, and they are free to use the received funds to apply the investment strategy directly. This indeed reduces costs because there's no need to run code that validates the actions in question. Instead of having a multisig, one can also use a wallet. However, this increases the trust needed in the system.

### Effective work

To make this happen, some people will need to put in a significant amount of effort. We should consider rewarding these people for their effort. We all have limited time; any amount of monetary compensation will be in direct competition with other sources of income. It is unlikely that we want and will compensate people enough to make them prioritize Dreamers DAO over other things.

It is imperative to note that the best way to help is to actively participate in the development of the community. 

### Compatible platforms to fork

We may decide that we can use some already existing platforms that serve most of our purposes. For example, we can use the Aragon DAO to create a DAO that can be used by the community. Another option *could be* to fork [yearn.finance](https://yearn.finance/) and extend and customize the strategies they use. However, this is not the initial idea I started with, forking code that we don't completely understand. Considering it was created with a different purpose in mind (catering to a trustless community) might make us decide it could be just an inspiration, but forking is not desired.

### Speed of execution

Community projects depend a lot on just a very few number of members who use their own time and energy to push things forward. Using the initial momentum is critical to the success of the project. If the initial members lose their momentum, there is a very high chance that the project will be unsuccessful. Moving fast, having a good roadmap, showing interest and helping out severely increases the likelihood of success.

### Developer oriented tools

Most of the communication and collaboration will happen on platforms that are created for developers (like GitHub). This might be a difficulty for people who are not familiar with these tools. Fortunately, these platforms have shown to be very successful in helping different actors collaborate and share their ideas.

Some people who want to participate might feel like the tools used, create problems in participating in the project and the DAO. I am sure that the people familiar with them will provide enough help to get you started. Also, most of them improved their UX significantly over the years, and they show no sign of stopping. i.e., [GitHub has an edit button](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files), pages can be edited directly in the browser, preview is provided.
