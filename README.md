# LOOP DEFI


The project consists in offering a minimalist yet efficient trade/swap mechanism and take an approach that a lot of solidity developers fear, loops.

- The project will use Open Zeppelin Upgradeable library (we will try UUPS not because it sounds like loops) 
- Gnosis Safe app 
- Hardhat
- ethers/web3
- WalletConnect
- React
- and anything else we might need

## What can we achieve with a loop and DEFI in mind?

The goal is to incentive liquidity orders that are swappable and reusable, making repetitive transactions cheaper by using a single argument to change the state of the order. A single argument to activate an order already written on the blockchain.

Yes, the initial cost is still there. However, the next time a user would like to perform a trade, he does not need to fill an entire order again. If he was the first person ever to make an order. The order 0 spot would belong to him. Make sense since he paid for it. If the price needs to be changed. let us just change the price.


- makers/takers reward is based off the amount on active trades. This will be favorable for small players that provide smaller volume of multiple assets.

- The way the makers can earn is by providing liquidity in a single asset and set the asset he wants in return. This technically create an order. However, this order can become swappable and let the maker earn over time instead of just once. The balance of this order can change over time from one asset to the other. The amount in the order will not increase but the maker balance will.

- Takers get another reward mechanism, they interact more with the loop. Filling one single order does not reward the taker. The taker must fill multiple orders at once (loop) to earn. 

- Swappers that come in to swap an asset to another might or might not get a reward. The process will automatically reward the account after it reach the second order. 

**Now let us get in the loop**

 What if I could use a loop to skip an order that is already filled. Instead of reverting, let us just skip it. Now since we skipped an order, we could have an extra order to replace the skipped one. That extra order becomes our slippage. This also gives us more flexibility over slippage. Because the price of the trade is based off an order book. The user can (but don't have to) pick which order should be used for slippage. This process would apply the slippage on the amount that was skipped rather than the entire order amount.


## Can but don't have to!

This is where the UI comes in. My vision of displaying the loop to the front end, could look somewhat like Furucombo. Where we build our loop of orders. 

- The UI should let the user swap quickly but also extend the order book to mix and match orders and assets to build the loop.

- The UI will let the user chose if he wants the funds transferred to the wallet or remain on DEX. 




## Tokenomics 

I am no financial adviser but here are a few ideas.

- Early bird incentive to encourage early liquidity providers
- Lock and Load. Hold a balance of the token to earn more or pay less.
- Establish the fees redistribution to community (Reserve/Governance).
- Farm interest on Sponsored protocols. (Familiar with Compound, Aave, Uniswap)
- Uses strategies from Sponsored protocols. (FlashLoans, Arbitrage, ?)


## 7 days left to start!


Phase one?
