Krazor is the underlying cryptocurrency used on [Blockrazor](https://github.com/Blockrazor/blockrazor).

#### Launch
The launch of Krazor is different to most cryptocurrency launches. Instead of setting an estimated time to mine the genesis block, the chain is launched early but the block reward is 0 until the Kickoff block height is reached. 

This is much more predictable and also gives a chance for everyone to get up and running *before* launch without giving an advantage to people (or pools) who happen to be awake and in front of their equipment during the 1 minute window when mainnet is launched.

The Blockrazor website itself will also transition from *development mode* to *live* automatically once the Kickoff block is mined. All wallets on Blockrazor will be reset at that time, and any coins earned after that point will be real Krazor.

#### Coin distribution
Half the supply will be distributed through Blockrazor, and the other half to miners (in coinbase transactions).

The coins to be distributed through Blockrazor are time-locked at the protocol level and a new batch will be made available annually for the first 10 years. This can be verified by examining the blockchain.

The distribution of coins through Blockrazor is transparent and publicly auditable. The [code running the site](https://github.com/Blockrazor/blockrazor) is open source and publicly auditable. Blockrazor's treasury wallet is publicly auditable by using the [public view key](#) to see incoming transactions, and examining the [key images](#) that are updated with every transfer (and are cryptographically provable to be complete).

### How do I get some Krazor?
You can [mine it](MINING.md), or earn some by completing [Blockrazor bounties](https://blockrazor.org/bounties).

If you run a cryptocurrency exchange and you add Krazor support, you should send a pull request to update this page and provide a link.

### Technical details
Krazor is a modified version of the Monero V7 codebase and uses a (currently) ASIC-proof variant of Cryptonight as the Proof of Work algorithm. 

Some of the reasons we used the Monero codebase as a starting point:
- Monero's privacy means coins are fungible,
- Monero has the least centralized and most inviting development environment of all cryptocurrency projects, the codebase reflects this. An important consideration when attempting to build a cryptocurrency that takes advantage of Conway's law instead of fighting it is the history of the codebase,
- The Monero variant of the 2MB Cryptonight algorithm is (to the best of our knowledge) the most egalitarian PoW algorithm in existence - there are even CPUs that have higher hashrates than the latest NVIDIA graphics cards when using this algorithm.

#### Differences between Krazor and Monero
There are numerous differences and the two projects will continue to diverge, please examine the [git commit history](#) for a comprehensive and up to date view. There's also a summary [here](#). The most important difference however is not technical, there's a much deeper and fundamental difference.

A cardinal sin that many open source developers make is to place themselves above others. "I founded or am a regular contributor to this project thus my intellect is superior to that of others". It's immodest and rude, and usually inaccurate, but it's the norm for cryptocurrencies. Monero is better than most, but it's definitely no exception to the rule. The *vision* is decided upon by an established group of developers and all proposed changes to the codebase are judged against this vision. 

The contribution policy used by Krazor is called the Collective Code Construction Contract (C4) with the *Serbian method* for problem solving. It's the result of 20 years of research by by Pieter Hintjens as he worked on the ZeroMQ project, and the proof that it works is in the results it delivers. Krazor and Blockrazor exist in part to continue this research.

Monero has ostensibly adopted the C4, but they don't actually use it. A keen observer will also note that they have even modified the C4 document in their repository to reinstate central planning. 

This is perfectly understandable however, anyone who's used the C4 properly will understand that it's practically **impossible** to convert an existing project over to using it, and in Monero's case it would introduce uncertainty at a time when their existing processes seem to be doing a better job than any other cryptocurrency.

#### Evolution vs Intelligent Design
The C4 is essentially a hill-climbing algorithm, it has a life and direction of its own and doesn't require leadership - just enforcement of the protocol itself. 

It's akin to Evolution *vs.* Intelligent design; central planning *vs.* the free market. It may sound strange, but open source projects almost universally adopt some form of central command and control structure. The project founders or key developers decide what can and can't go into the project, and what the long term vision is. 

This is even more pronounced when it comes to cryptocurrencies, the idea seems to be that because they have value they're too important to trust anything but a centrally controlled development protocol - everything must be approved by the project leaders. It's impossible to entertain the idea of using an evolutionary approach because upfront consensus is incompatible with evolution. 

This unfortunately means that cryptocurrencies are *constantly fighting a battle against the forces behind Conway's law*.

#### Direction, vision, and planning
The power of the C4 *cannot be overstated*. Human decisions about direction, vision, and planning are completely incompatible with the C4. All control is relinquished to a decentralized *protocol*. 

As far as we know, this is the first time that any cryptocurrency project has attempted such a decentralized approach to development. 

It's an experiment. It could be a raving success or it could be a complete disaster, but whatever the outcome it will push the envelope in social architecture research to the absolute limits. 

Krazor is entering the unknown; raw chaos itself. Buckle up.
