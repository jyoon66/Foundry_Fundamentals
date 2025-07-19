### Practicing Private Key Safety

Having a private key in plain text is extremely bad. The private key(s) we used in the last lesson are well-known keys for local testing, you shouldn't use those on mainnet and keeping them in plain text is ok, but any other private key should be kept hidden, especially your production key or keys associated with accounts that hold crypto.

Moreover, it's very bad to have private keys in bash history (hit the up arrow and see the key you used to deploy).

You can delete your history by typing:

```solidity
history -c
```

We will teach you more about how to secure private keys in one of the next lessons.

### Your Safety Promise

It's time now to articulate your promise for maintaining private key safety. Create a file titled `Promise.md`. In this file, make it a point to write down your promise:

```md
I promise to never use my private key associated with real money in plain text.
```

If you feel comfortable doing so, consider tweeting this to affirm and secure your pledge. Make sure to tag @PatrickAlphaC and @CyfrinUpdraft or any other professional in this field to hold yourself accountable.

Hacking private keys is one of the most important reasons people and projects lose absurd amounts. You don't even need to look that deep to find titles like this:

[The Ronin hack](https://www.halborn.com/blog/post/explained-the-ronin-hack-march-2022) - Social engineering of private keys

[Early Crypto Investor Bo Shen Says He Lost $42 Million in Wallet Hack](https://finance.yahoo.com/news/fenbushi-founder-bo-shen-loses-123005790.html?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAANhimpnaMBbbbqKgTFEUx56Sa9_jUTORTpMIVSn4HrAhJwuPEt9qK32f3vxR6em5IwZOIgpUSEBdVYghCxAvvR1wTIO7EcVF7seQJkhP9XwkITYPBsR2O87SkDRiGx21gtc-sSLAopKD0SkIdPIiaX1pgh1skB97zjfLCLeofrc4)

[The $477 million FTX hack](https://www.elliptic.co/blog/the-477-million-ftx-hack-following-the-blockchain-trail) where **The new CEO of FTX revealed that private keys allowing access to the firm's crypto assets were stored in unencrypted form, and a former eployee disclosed that over $150 million was stolen from Alameda Research, due to poor security.**

Don't be like that! Maybe you are not holding millions, but what you hold is yours, don't let it become theirs!

In the following lessons, we'll learn how to access RPC URLs for free using Alchemy for any blockchain. We will also delve into exploring safer methodologies for dealing with private keys. Stay tuned!