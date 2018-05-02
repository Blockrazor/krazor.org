Krazor is the underlying cryptocurrency used on [Blockrazor](https://github.com/Blockrazor/blockrazor).

### How do I get some Krazor?
You can mine it, or earn some by completing [Blockrazor bounties](https://blockrazor.org/bounties). You can also sometimes buy some on Blockrazor if anyone is selling. 

If you add Krazor to your exchange, you should send a pull request to update this page.

### Technical details
Krazor is a modified version of the Monero V7 codebase and uses a (currently) ASIC-proof variant of Cryptonight as the Proof of Work algorithm. 

Some of the reasons we used the Monero codebase as a starting point:
- Monero's privacy means coins are fungible, the only other currencies with similar levels of privacy are those using zk-SNARKS however they have problems that might hurt Krazor in the long term,
- Monero has the least centralized and most inviting development environment of all cryptocurrency projects, the codebase reflects this. An important consideration when attempting to build a cryptocurrency that takes advantage of Conway's law instead of being hindered by it is the history of the codebase,
- The Cryptonight (Monero variant) is, to the best of our knowledge, the most egalitarian PoW algorithm - there are even CPUs that have higher hashrates than the latest NVIDIA graphics cards when using this algorithm. Cuckoo cycles could improve on this and might be adopted later.

#### What's different to Monero?
A cardinal sin that many open source developers make is to place themselves above others. "I founded or am a regular contributor to this project thus my intellect is superior to that of others". It's immodest and rude, and usually inaccurate, but it's the norm for cryptocurrencies and Monero is no different in this regard. 

The contribution policy used by Krazor is called the Collective Code Construction Contract (C4) using the *Serbian method* for problem solving. It is the result of 20 years of research by by Pieter Hintjens as he worked on the ZeroMQ project, and the proof that it works is in the results it delivers. 

The C4 is essentially a hill-climbing algorithm, it has a life and direction of its own. It's akin to Evolution *vs.* Intelligent design or central planning *vs.* the free market. Open source projects in general (and every single one of the top 100 cryptocurrencies) use some form of central planning or intelligent design, and are unable to entertain the idea of using an evolutionary approach because it means no one can be in control. This means they are constantly working against the forces behind Conway's law.

Monero has ostensibly adopted the C4, but they don't actually follow it and a keen observer will note that they have removed the parts that actually make it decentralized. This is perfectly understandable however, anyone who's used the C4 properly will understand that it's practically **impossible** to convert an existing project over to using it.

The power of the C4 *cannot be overstated*. Human decisions about direction, vision, and planning are completely incompatible with the C4. All control is relinquished to a decentralized *protocol*. As far as we know, this is the first time that any cryptocurrency project has attempted such a decentralized approach to development. It could be a raving success or it could be a complete disaster, but whatever the outcome it will push the envelope in social architecture research to the absolute limits. Buckle up.

#### Coin distribution
Approximately 50% of Krazor's supply will be distributed through Blockrazor, with the remaining coins to be distributed to miners (in coinbase transactions).

The coins to be distributed through Blockrazor are time-locked at the protocol level and a new batch will be made available annually for the first 10 years. This can be verified by examining the blockchain at blocks 0 through 11.

The distribution of coins through Blockrazor is publicly auditable. The [code running the site](https://github.com/Blockrazor/blockrazor) is open completely open source and publicly auditable. Blockrazor's treasury wallet is publicly auditable with the public view key and publicly available key images that are updated with every transfer and cryptographically provable to be complete.

#### Launch
The launch of Krazor is different to most cryptocurrency launches. Instead of setting an estimated time to mine the genesis block, the chain is launched early but the block reward is 0 until the Kickoff block height is reached. This is much more predictable and also gives a chance for everyone to get up and running *before* launch without giving an advantage to people (or pools) who happen to be awake and in front of their equipment during the 1 minute window when mainnet is launched.

The Blockrazor website itself will also transition from *development mode* to *live* automatically once the Kickoff block is mined. All wallets on Blockrazor will be reset at that time, and any coins earned past that point will be real Krazor.
