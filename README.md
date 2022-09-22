## 🎇OmniBTC is an omnichain financial platform for web3.
  Including OmniSwap, OmniBridge and OmniLending.  
   
### OmniSwap.
  Based on LayerZero,an omnichain interoperability protocol,users can swap any token between any chain with one click. By unifying liquidity on each chain, OmniBTC enables users to swap with one-click and enjoy the best liquidity and the lowest slippage. 

### OmniBridge.
  Lock the deposited bitcoins into the Lightning Network contract, realize decentralized trusted custody, and make the mirror assets $XBTC flow to each chain.

### OmniLending.
  Enable users to deposit/borrow assets on chainA/B/C and withdraw/repay assets on chainB/C/D without bridge. 
  E.g. You can deposit $ETH on Ethereum, and borrow $USDC on #Aptos, but repay $USDC on #Sui, withdraw $ETH on Polygon.

## 💡What makes OmniBTC unique?
  The first platform, which successfully introduced fully decentralized trusted $BTC into Aptos/Sui.
  Just one click, without switch pages.
  Best liquidity and lowest slippage for swap users and lending users.
  Wholly decentralized trusted $BTC custodian mechanism, provided by Lightning Network.
  Unify the liquidity on every chain, instead of building up pools, and provide more profits for LPs.
  
  ### What makes OmniSwap unique?
  Compared with existing solutions. Most of the existing cross-chain swap schemes have a fractured state between bridging and swapping, which means that users have to make at least two transactions to complete the cross-chain swap. To make matters worse, the existing bridges only accept limited tokens and networks. For example as follows, users have to make at least three transactions(two thirds are manual) to swap LINK on Ethereum for Doge on BSC.
  For a few better schemes, users only need to make two transactions but still need an extra swap on destination chain manually.
  However, by using OmniBTC, users can swap any token between any chain with one click. Besides, we have a novel algorithm which can calculate the best price and the lowest slippage for users so that users can enjoy cross-chain swap with one click in a low-consumption environment.
  As you can see, OmniSwap unifies the liquidity on every chain, instead of building up pools, and provides more profits for LPs.
  
  ### What makes OmniBridge unique?
  Now OmniBridge fully serves Sui and Aptos.
  Solve the problem: Fully decentralized support for BTC Move contracts on the Sui & Aptos network.
  #### Reference project: ChainX and ICP​
  Their solution： BTC Light Node + Threshold Aggregate Signature + Smart Contract platform
  For the BTC aggregate address to host BTC, only the addresses and accounts hosting BTC are decentralized enough to make BTC look as decentralized as POS. 
  For example: Bind the aggregated custody account to the node account on the chain one by one, which is as decentralized as the POS chain.
  There is still a problem with this way of thinking. OmniBTC wants to combine the solution of ChainX and the Lightning Network to be deployed on Sui to provide Sui with a fully decentralized BTC. It also allows BTC to carry the Move contract.
  #### OmniBTC solution:
  BTC Light Node + Threshold Aggregate Signature + BTC Lightning Network + MoveVM
  Lightning Network solves the mutual trust problem between Alice and Bob.
  We just need to replace Alice with a BTC aggregate signature account (co-hosted by a sufficiently decentralized POS node on Aptos/Sui or a DAO administrator selected above).
  $BTC holders can fully trust the $BTC to the Lightning Network, and then come to Aptos/Sui to use any Defi and gamefi product.
  Transition plan:
  Using BTC's L2 network ChainX as the BTC relay network, combined with the LayerZero message transmission protocol, OmniBTC sends BTC to the MoveVM of the Aptos/Sui network, so that the mirror network asset XBTC can have the ability to program in the Move language.
  
  ### What makes OmniLending unique?
  Here is the technical yellow paper of OmniLending.
  https://github.com/OmniBTC/yellow-paper

## 🛠What problem will be solved?
### Swap Users. 
  For higher profitability, users have to click the bridge & swap buttons frequently, and have to bear higher slippage.
  
### Lending Users. 
  For higher capital utilization, users have to frequently bridge/deposit/withdraw assets in different pages or networks.
  
### Low availability of BTC.
  Bitcoin is not programmable and lacks a decentralized trusted environment, so developers cannot create smart contracts for $BTC or improve its utilization. 
  We are convinced that Bitcoin can do more than value storage.


## 🛡Other supports
   For more detailed clarification,you can check out our gitbook,  
   https://omnibtclabs.gitbook.io/omnibtc/introduction/what-is-omnibtc  
   or join in our Discord and ask for help,  
   https://discord.gg/Z2EzZcJ72x  
  ### Contact us
  business@chainnet.tech
