## Decentralized, Open-Source Social Networking and Collaboration Applications and Platforms

### Contents
* [Purpose](#purpose)
* [Roadmap](#roadmap)
* [Applications and Platforms](#applications-and-platforms)
    * [Social Networking](#social-networking)
    * [Collaboration](#collaboration)
    * [Identity](#identity)
    * [Decentralized Protocols](#decentralized-protocols)
* [Concepts](#concepts)    
* [Contributions](#contributions)
* [License](#license)

### Purpose
The purpose of this document is to provide an overview and guide to existing open-source decentralized applications (dapps) and platforms for social interaction, social networking, social media, social engagement and creative or project-based collaboration (e.g. Decentralized Autonomous Organizations).

For our purposes, **decentralized** means that these apps are peer-to-peer (P2P) and/or rely on decentralized infrastructure like public, open-source blockchains (e.g. Ethereum or Bitcoin) or protocols (e.g. IPFS, Secure Scuttlebut, Dat, Gun, WebTorrent, ActivityPub). If they rely on blockchains or protocols like these, it must be practically possible for users to run their own nodes without having to pay fees to any centralized entity.

_Decentralized_ apps and platforms are distinguished from _centralized_ ones (e.g. Facebook) that rely on centrally managed servers/databases and _federated_ ones that rely on a network of locally centralized servers (e.g. Mastodon).

Only _open-source_ apps and platforms will be listed here.

This is a curated list. More developed apps and platforms with more features and/or a wider user base may be highlighted, but all apps/platforms that meet the overall purpose will be listed here if submitted.

A question for all decentralized social networking and collaboration tools is how to pay for the underlying storage and computing cycles needed to support it. Some of the solutions below require you to pay (in one form or another) to "post" content or initiate an action. Others make no guarantees that your content will be available to others unless you host it yourself and keep your computer constantly on, and then people across the world may be only able to access it very slowly.


### Roadmap

This is a work in progress! Please help extend it and keep it up to date.

It is hoped that in the future a comparison of the various apps and platforms will be provided. Some of the criteria that will be worth highlighting are:
* Availability / use of encryption
* Privacy and management of personal data
* Underlying technologies used
* Adoption and use
* Level of maintenance and ongoing development
* License type
* Features provided
* Ability to do financial transactions
* Sponsors / contributors
* Degree of _lock in_ that prevents leaving or migrating from the app / platform
* Degree of integration available with other networks and tools
* Performance / speed


### Applications and Platforms

#### Social Networking

* [Briar](https://briarproject.org/) - WhatsApp clone with security focus. GPL licensed
* [DTube](https://d.tube/) - Youtube clone using Steemit blockchain and IPFS. GPL licensed
* [Iris](https://irislib.github.io/) - Social sharing using Gun and IPFS
* [Jami](https://jami.net/) - WhatsApp clone
* [Junto](https://junto.foundation/) - Social network on Holochain
* [Peerpeth](https://peepeth.com/welcome) - Twitter clone on the Ethereum blockchain
* [PeerTube](https://joinpeertube.org/en/) - Youtube clone using ActivityPub
* [Patchwork](https://github.com/ssbc/patchwork) - Social network on Secure Scuttlebut. AGPL licensed


##### Platforms

* [3box](https://3box.io/) Nascent social networking platform using Ethereum and OrbitDB (IPFS-based)
* [Mix platform](https://www.mix-blockchain.org/) - Using Ethereum and IPFS
* [Textile platform](https://textile.io/) - Using IPFS



##### Meta

* [app.co](https://app.co/) - Decentralized app store (not all are open source!)
* An overview of existing social networking options including decentralized ones (6/26/19): [So You Want to Leave Facebook](https://hackernoon.com/so-you-want-to-leave-facebook-1ab3603f164a)

#### Collaboration


##### Ethereum blockchain based

###### DAO platforms
* [Aragon platform](https://aragon.one/)
* [DAOStack platform](https://daostack.io/)
* [Colony platform](https://colony.io/)
* [Moloch platform](https://github.com/MolochVentures/moloch)

###### Ethereum, other

* [Gitcoin](https://gitcoin.co/) - Bounties for software projects
* [BroncoVotes](https://github.com/pmarella2/BroncoVotes) - Ethereum based secure voting platform
* [PeepsDemocracy](https://www.peepsdemocracy.com/) - ActBlue alternative. Nothing there yet? Open source?


##### Bitcoin blockchain based

* [Blockstack platform](https://blockstack.org/) - [Various dapps](https://blockstack.org/try-blockstack) are available, including [Graphite](https://www.graphitedocs.com/), a Google Docs/Sheets clone. Some but not all are open source

##### Github/Gitlab alternatives

* [git-remote-ipfs](https://github.com/cryptix/git-remote-ipfs/) - Git push/pull to IPFS
* [git-ssb](https://github.com/noffle/git-ssb-intro) - Git over Secure Scuttlebut
* [Mango](https://github.com/axic/mango) - Git using Ethereum, IPFS
* [Radicle](http://www.radicle.xyz/) - using IPFS

##### Other

* [Secret voting (Enigma)](https://blog.enigma.co/secret-voting-smart-contracts-with-enigma-a-walkthrough-5bb976164753) using Enigma (see below)
* [Secret voting (Oasis)](https://docs.oasiscloud.io/en/latest/secret-ballot/) - using Oasis (see below)
* [Trellis](https://github.com/automerge/trellis) - Trello clone based on MPL (Automerge & WebRTC)


##### Meta
* An overview of existing Ethereum-based DAO (decentralized autonomous organization) platforms (6/16/19): [Aragon, DAOStack, Colony, Moloch](https://kronosapiens.github.io/blog/2019/06/16/aragon-daostack-colony-moloch.html)

#### Identity

Identity services are a key requirement of most social/collaborative apps. Decentralized and self-sovereign identity platforms and "wallets" are listed here.

* [IDM](https://github.com/ipfs-shipyard/pm-idm) General purpose identity manager for DIDs
* [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy)
* [MetaMask](https://metamask.io/) Ethereum wallet/identity manager
* [uPort](https://www.uport.me/) Ethereum wallet/identity manager

##### Meta

* [Decentralized Identity Foundation](https://identity.foundation/)

#### Decentralized protocols
These are the underlying decentralized protocols underlying the dapps and platforms above

* [ActivityPub](https://activitypub.rocks/)
* [Automerge](https://github.com/automerge/automerge) - CRDT implementation
* [Bitcoin blockchain](https://bitcoin.org/en/)
* [BitTorrent](https://en.wikipedia.org/wiki/BitTorrent)
* [Dat](https://www.datprotocol.com/)
* [Enigma](https://enigma.co/) - Secure protocol extended from Ethereum
* [Ethereum blockchain](https://www.ethereum.org/)
* [Gun](https://github.com/amark/gun) - CRDT implementation
* [Holochain](https://holochain.org/)
* [LibP2P](https://libp2p.io/)
* [IPFS](https://ipfs.io/) - libp2p based
* [MPL](https://github.com/automerge/mpl) - Using automerge and WebRTC
* [Oasis](https://www.oasislabs.com/) - Secure protocol on extended from Ethereum
* [OrbitDB](https://github.com/orbitdb/orbit-db) - Distributed DB implementing CRDTs on IPFS
* [Secure Scuttlebut](https://www.scuttlebutt.nz/)
* [Steem blockchain](https://steem.com/)
* [WebRTC](https://webrtc.org/)


### Concepts 

Some relevant concepts

* [Blockchain](https://en.wikipedia.org/wiki/Blockchain)
* [Byzantine Faults](https://en.wikipedia.org/wiki/Byzantine_fault) A type of challenge facing decentralized systems
* [CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type) Conflict free replicated data types
* [DAG](https://en.wikipedia.org/wiki/Directed_acyclic_graph) - Directed acyclic graph
* [DIDs](https://medium.com/moxystudio/the-need-for-decentralized-identity-4d369408e10e) Decentralized Identifiers
* [P2P](https://en.wikipedia.org/wiki/Peer-to-peer) Peer to peer
* [Self-sovereign identity](https://en.wikipedia.org/wiki/Digital_identity#Self-sovereign_identity)
* [Smart contracts](https://en.wikipedia.org/wiki/Smart_contract)
* [SMC](https://en.wikipedia.org/wiki/Secure_multi-party_computation) - Secure multi-party computation
* [Sybil attacks](https://en.wikipedia.org/wiki/Sybil_attack) - A type of attack on a decentralized system
* [TEEs](https://en.wikipedia.org/wiki/Trusted_execution_environment) Trusted execution environments, used in current versions of secure/private smart contracts

### Contributions
Contributions aligned with the stated purpose and consistent with our [code of conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct) are welcome! Make a pull request to suggest additional resources or enhance this document. Edits to pull requests may be requested for placement, accuracy. Contributions that highlight the criteria mentioned in the roadmap above are especially appreciated.


### License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.