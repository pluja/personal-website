---
title: "The Future of Bitcoin"
date: 2020-11-03T12:27:18+01:00
draft: false
---

In this blog post I want to talk about the future of Bitcoin and, first off I want to say that I am not an expert on Bitcoin. I'm just a passionated user who wants to learn more about it. So please, if any of my points is incorrect or I'm wrong with something [contact me](mailto:pluja@r3d.red).

Lately the news that Paypal is allowing users to buy Bitcoin has spread all over the cryptospace. Most people saying it is a good thing and that the Bitcoin price will rise to the moon.

From my perspective, this is not even close to the truth. Paypal only allows users to **buy and sell** bitcoin inside Paypal. You can't send Bitcoin, you can't recieve Bitcoin and you can't sell any bitcoin that has not been bought inside Paypal. Also, it is a custodial wallet (more custodial even than most exchanges) so this means that all transactions that will happen on Paypal (buy/sell) will stay inside Paypal.

The truth is that, I think, it is a quite good thing that Paypal decided not to allow their ~300 million users to transact with the Bitcoin network right away. Bitcoin is not ready for this. Not at all.

At the time of writing this post (Nov 2nd 2020 at ~23:00h), the Bitcoin mempool is quite full. There are approximatelly about 110.000 transactions on the queue and fees are quite high. 110.000 transactions. And we're seeing high fees. I'm saying that sending $1 to someone with an approximate confirmation time of around 50 minutes would cost about $7 in fees (~260sat/Byte). (AS you know, transaction fees are what is used by miners to deremine which transactions will get on the next block first)

Imagine now if all users on Paypal could operate with the Bitcoin network. Just imagine that 1/4 of the total ammount of users would do it. **The mempool would saturate and fees would rise so high** that the network would be unsuable for most users. This would lead to a point where any Bitcoin transaction would no longer be worth it as you would be paying a lot in fees. So, would the price rise? How would Bitcoin community react to a massive wave of people coming to Bitcoin, saturating the mempools and rising the fees so high?

I think you get the hint of it. Bitcoin can not scale. Bitcoin will never serve as a global payment system for billions of humans. It just can't and you need to accept it. Well, not true. Bitcoin can't handle it, **not as is**.

So, **TLDR**; If millions of new users come to Bitcoin and start transacting, the Bitcoin mempool would saturate and network fees would rise to levels where a bitcoin payment would no longer be worth it. **Bitcoin can't scale** and we have to accept it. But we have a solution to this. But this solution also comes with some issues.

## The Lightning Network: Saving Bitcoin's Future, or not.

If you've been long enough around the Bitcoin community, you must have heard about [the Lightning Network](http://lightning.network/). I will not get into the details but i will make a summary of what it is:

The Lignting Network (**LN** from now on) is a Layer 2 network that operates upon the Bitcoin network. It allows P2P payments between users that are connected through what is called a payment channel. These channels are basically a multisig wallet which holds a certain ammount of Bitcoin funded by the two users of that channel and the LN takes care of which part corresponds to whom. This allows payments to be off the blockchain so there's no need for confirmations, you don't have to wait. LN payments are available in a matter of miliseconds to seconds. Also, there's no limit on the transactions rate (tx/min) that it can handle and it overpases the traditional electronic payments by orders of mangnitude. This is a scratch on the surface of what LN really is, but you get the idea.

The main virtues that can be found when usign the LN are:

* Fees are LOW. Exceptionally low.
* Fast payments. Payment speed measured in milliseconds to seconds.
* Due to low fees, allows instant micropayments.
* It can handle a massive ammount of transactions.

### So, we have a solution then
Yes and no. Lightning Network is a powerful tool and, if we imagine a future where Bitcoin is used as a global payment method by billions it would have to be based on a Layer 2 network such as LN. And yes, LN is awesome and everyone should be running a node and using it. But that's not the case and I don't know why. Why nobody is using the Lightning Netwok??

### Opinion and question: Why not?
If everyone is using the LN, a small ammount of transactions would be happening on the Bitcoin Network (channel breaks, and some off-LN transactions). Miners are what keep the Bitcoin network secure (along with full nodes, of course). So, if everyone is using LN and there are an small ammount of transactions, If we think of the time where block rewards are no longer a thing and miners are only motivated by the block fees reward... Wouldn't the LN make mining Bitcoin not worth it as for little rewards, miners shutting down, the network would be more insecure... What would be the result of a Bitcoin economy based on the Lightning Network?

This is an opinion and I haven't found a lot of info about this problem, nor I'm an expert on LN and I don't really know if this is a known issue with a known solution. I will try to investigate and update this post with the answer if there is one. If this is not updated, I haven't found anything so if you think you can answer this [contact me](mailto:pluja@r3d.red)