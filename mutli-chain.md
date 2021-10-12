Multi-Chain Blockchain Game Development 

Hi friends, Kwame here with another article on the state of blockchain gaming. In this article, we are going to look at Multi-Chain development. Blockchain agnosticism is essential to the mission at ChainSafe as we work closely with many blockchains, Mina / Cosmos / Ethereum Classic and various flavours of the EVM Binance and Polygon, to name a few. For the ChainSafe gaming SDK, we currently support Ethereum / Avalanche / Binance / Moonbeam / Polygon and XDai, with many more currently in development and testing. Many of you now reading this article may have some knowledge and background on the Ethereum Virtual Machine and its flexibility to fork(create a copy) and make your version/s of Ethereum. Forking Ethereum may be a pain point in the industry, but this also has risen to the rise and adoption of Ethereum and DeFi on L2 solutions.


Gas Pains and Ethereum Scalability 

It is impossible not to bring up gas prices, i.e. transaction fees when talking about Ethereum. The one downside that we see with Ethereum's popularity is that the more we use the Ethereum blockchain, the more expensive it is to transact on that network. Adding a new consensus model to the Ethereum EVM aloud faster transaction times and reduced fees "Layer 2's". The elephant in the room for Ethereum is its scalability and high gas fees. However, many of these will be fixed hopefully with the release of Eth2.  Now, some of you are reading this that are familiar with the EIP-1559 standard, and it aims to make gas prices cheaper, and mining is an afterthought and is beyond the scope of this article, but here is a link for the curious https://consensys.net/blog/quorum/what-is-eip-1559-how-will-it-change-ethereum/  . It is still not determined if this will change the enormous gas fees we see on Ethereum. We are still waiting, and many of these layer2 solutions we discussed earlier are filling the gap for the time being. 

With so many EVM compatible chains, which one do I choose?

EVM compatible chain one or EVM compatible chain two is the question I get asked every day. I'm a multi-chain maximalist and want to support as many chains as possible. I think it is usually up to the developer and their users to decide but also consider these. 
What chain the developer initially wrote the contracts for the supported chain.
On what chain are the assets deployed too, which means if you have NFT's in your game where these contracts deployed to multiple chains of just a specific one.
The network effect is usually the most important. What chain are you going to see the most adoption?  If there is a majority of users on a specific chain. You will most likely choose the one with the most users or the most significant network effect.  
So, with the above stated, it will likely come down to you, the developer deciding the major chain you wish to support and the compiled contracts for the other chains.

Write Once Play Anywhere?

So, we have tried to explain in short form what the multi-chain paradigm is and the initial reason for creating a Gaming SDK that supports multiple blockchains but do we write our games once and play anywhere? No, not exactly. What happens is that our frontend dApp communicates with the various backends, i.e. "smart contracts", but our contracts need to be launched and deployed to the different chains we are supporting. The one that is great in this scenario is that the other chains are all EVM compatible. We are still writing our code in Solidity, the primary programming language of the Ethereum blockchain. Then, our users will play the game or dApp on the specified platform by selecting the appropriate wallet to pay funds and transact. Now, this is a highly contested and argued topic. Should our games be chain specific or chain agnostic at ChainSafe, we choose the latter and is how our gaming SDK works. So, you write one frontend, i.e. "Unity3D", regarding the gaming SDK, and have multiple backends, i.e. "Polygon/Binance/Moonbeam", etc. These are your deployed contracts and, lastly, the middleware that ties all these together, the ChainSafe gaming SDK.

In closing...

We tried to explain what multi-chain support is and how we can solve this problem with the ChainSafe Gaming SDK. The multi-chain paradigm is the most talked about topic in the blockchain space, all looking and working towards a world of co-chain consensus. We also looked at the underlying technology Ethereum. Finally, we mentioned how a "layer2" like Polygon and Binance live on top of the underlying protocol "Ethereum" and add the own consensus model can alleviate high gas prices and slow transaction fees.  Not to forget, we also mentioned ETH2, which will hopefully add everything we see in these layer2 solutions in Ethereum as a whole. I'm hoping that by reading this article, you will know the importance of this multi-chain paradigm, how it grows and makes the Ethereum and other supported chains stronger and a need for these blockchains to communicate in a concept called co-chain consensus.

Until next time
 
