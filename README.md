# Age of Strategy
Age of Strategy: A Never-Before NFT+Blind Box Strategic SLG GameFi

GameFi, a fusion of Game and DeFi, its core value lies in integrating the financial element into the game, which enhances the game economy through financial attributes while promoting them through the game, forming a dynamic balance and internal circulation. Moreover, GameFi operates on a Play to Earn (P2E) model which attracts and incentivizes players.

DeFi is an inseparable component of GameFi and it enriches the gameplay and playability in the form of NFT game assets, liquidity mining and so on. Besides Play to Earn, GameFi opens a window to the world of Metaverse for the realistic world. This is highly favored by the capitals. They swarm into this market and make GameFi the next outlet of blockchain technology with innumerous economic and investment values.
Such attention from the capitals comes with the goods and bads. Some GameFi projects were launched for the sake of launching. The essence of “game” was overlooked. However on a global scale, many projects with great potential are coming into the light.

# Battle Mode
Age of Strategy is a classic yet unique turn-based SLG based on blockchain technology with 4 battle modes including PVE, PVP, GVG, and AVA. The game is designed with the application of P2E and token economy, aiming to build a "GameFi + DeFi + NFT + DAO + Blind Box" ecosystem in the grand Metaverse.

Players of Age of Strategy will be incentivized and rewarded by the blind boxes game mechanism. They can collect different NFT Heroes by opening blind boxes, and these NFT Heroes all come in with unique skills. By forming a team of 3 heroes, players can enter the PVE, PVP, GVG or AVA battle, and play strategically to earn. In Age of Strategy players are challenged to think and plan strategically in order to win a battle. This largely increases the playability of the game and grants different levels of satisfaction to the players.

# NFT
The NFT Heroes in Age of Strategy come in different rarity scales: Normal, Rare, Super Rare, Superior Super Rare and Ultra Rare. Players will initially obtain the heroes by opening blind boxes and from special events. Later the Heroes can be bought and sold at the NFT trade market. The rarer the Heroes, the smaller the amount and the higher the damage points.

By design, the NFT Heroes in Age of Strategy can not only wear a variety of skills and weapons, but also upgrade to higher levels as the game proceeds. Players are granted the ownership of their game assets. They can earn ASR from the game or sell their NFTs for ASR to join Farms and to buy NFT game props. While driven by the token and NFT rewards, players will also gain the sense of conquering and accomplishment. 

# Token Economy
Age of Strategy runs on a bi-token economic model. AS, the core token, can be used for staking with calculated APY. Players can also use AS to get blind boxes with NFT Heroes, Skills and Weapons, and Level Up Potion and Food. When players build the NFT, half of all AS spent will be directly destroyed, and the other half will enter the reward pool that will later be given back to the players.

On the other hand, ASR, the game token, is 100% produced and mainly used in the game. Players can use ASR for staking to collect game props such as the Level Up Potion and Food. Given the consumptive nature of the NFT game props, it attracts players to use ASR for staking and as a result, reduces its amount on the market. Players can use ASR to not only purchase NFT Heroes, Skills, Weapons, and Farms on the NFT trade market, but also exchange for rare blind boxes in the game.
In comparison with AS, half of all ASR spent will be directly destroyed, and the other half will enter the reward pool which will later be given back to the players, creating deflation and internal recycle of ASR.

# Technical Framework

![1648463284(1)](https://user-images.githubusercontent.com/102289203/160379386-3658cd68-c9c0-4f64-8a37-b9c6e514836b.jpg)

***\*Technical Security\****

Age of Strategy uses Sign Typed Data v4, which is the latest version of the EIP-712 governance, sign typed data parameters. The advantages are:

- Applies only to certain contracts

- The only contract that allows to own verification address

- Anti-phishing Dapp

- Ensures that a signature is only valid when it is expected to be valid and does not conflict with other signatures

- Ownership of the game assets belongs to only the owner of the private key

ETH wallets like MetaMask will soon introduce the EIP712 standard for sigops. EIP712 standard allows wallets to display data in signature prompts in a structured and readable format. EIP712 is a huge step forward in terms of security and usability, as users will no longer need to sign on hex strings, a potentially confusing and insecure practice.

Smart contract and dApp developers should adopt the EIP712 standard as it has been in the Ethereum Improvement Proposal and major ETH wallet providers will soon all support it.

EIP712 offers powerful improvements in usability and security. When an EIP712-enabled dApp requests a signature, the user's wallet presents them with the pre-hashed raw data, which they can then choose to sign. This makes it easier for users to verify it.

 

**OnChain**

AS, the token of ERC-20, can be swapped by players on DEX. AS can be used for governance in the ecology, mining in the Farm to obtain income, and purchasing Hero and Skill blind boxes to participate in the game to obtain ASR income. 50% of the consumed AS is destroyed, and 50% goes into staking.

The AS governance protocol, governed and upgraded by AS token holders, has 3 components: AS token, governance module (Governor Bravo), and Timelock. Together, these contracts allow the community to propose, vote, and implement changes to protocol.

Proposals can modify system parameters, or add new features to the protocol.

AS token holders can delegate their voting power to themselves, or to an address of their choice. Governance proposals can be created by an address that delegates at least 100000AS. Any address can lock 1000AS to create an autonomous proposal, which becomes a governance proposal after being delegated 100000AS.

After a governance proposal is filed, it enters a 1-day review period, after which vote weights are recorded and voting begins, and voting lasts 2 days. If the proposal receives a majority and at least 2,000,000 votes, the proposal will be queued in Timelock, and will be implemented after 1 day.

AS allows the owner to delegate voting rights to any address, including their own addresses. Changes in the owner's token balance automatically adjust the delegate's voting rights. Proposals will be voted on by delegated voters. If obtained before the end of the voting period with enough votes, the proposal will automatically pass. The filed proposal will be queued and executed in the Timelock contract.

The proposer must hold more AS than the current proposal threshold of the previous block, and a proposal can have up to 5 actions. If the proposer currently has a pending or active proposal, then they cannot create another proposal. Due to Timelock limitations, it is not possible to queue two identical actions in the same block. Therefore actions within a single proposal must be unique, and unique proposal that share the same actions must be queued in different blocks.

Proposals are eligible to be cancelled at any time before execution, including using this function when queued in Timelock.

Any address can call the execution function of the queued and passed governance proposal in Timelock, so as to implement the changes to the target contract as described in the proposal.

NFT Market allows players to trade ASR LP Farm and stake obtained game props such as Level Up Potion and Food. There is a 10% tax on each transaction. 50% of the taxation will be destroyed and the other 50% goes to LP Farm and staking. Players can exchange rare NFT with ASR. After the exchange is done, ASR is destroyed. 

 
**PVE Games**

After a battle is won, players can get token and experience point rewards. When the energy points are full, launch a battle to wake up wallet plug-ins such as MetaMask, and through structured data hashing and signature and verification of on-chain contracts, players can save gas costs and reduce transactions on the blockchain.

Signed message ensures that only the owner of the private key can access the player's game assets, so as to prevent situations such as the loss of the private key and the theft of game assets.
