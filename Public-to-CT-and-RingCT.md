---
layout: fr
network_vote: no
title: Public to CT and RingCT
author: particlmike33
date: February 2, 2022
amount: 0
milestones:
  - name: Discussion and Vote
    funds: 0
    done:
    status: unfinished
payouts:
  - date:
    amount:
---

This proposal is for the community to consider the privacy benefits of having only CT and ringCT transactions (no more public transactions or balances).

Taproot and LN are already compatible with CT.

The marketplace and DEX are compatible with CT and ringCT.

There are however, some things we have that currently rely on public balances.  These are:

1) wallet implementations shuch as Copay, Electrum, Trezor, and Ledger
2) marketplace moderation
3) community voting governance
4) staking

These 4 things rely on public balances, with number 1 probably being the easiest out of the 4 to be able to switch over to CT compatibliity (perhaps ringCT as well).

In my opinion, having a future roadmap goal of all these features being compatible with CT (and/or ringCT), would be a great privacy improvement.

If all 4 things were able to have CT (and/or ringCT compatibility) we would lose the need to have public balances, and could just have CT and ringCT balances.

This would greatly increase privacy, as opt-in privacy has shown to be less effective.  This is evident in zcash, which has a larger anonymity set than ring signatures (since they use zk-snarks) yet because so few transactions choose to utilize zk-snarks, the "private" transactions are generally traceable, acoording to chainalysis.

Yes, because the MP mandates ringCT transactions, hopefully we will have a higher percent of transactions being ringCT, but it would be ideal if we didn't need to pin our hopes on that (and what if the percent occasionally falls too low--then people wouldn't be private.)

Even if we can't get all 4 things compatible with CT and/or ringCT--and therefore remove public balances--it would still be a privacy improvement to make 1 or 2 compatible, and keep public balances.

If any of the 4 allow CT and/or ringCT, it will help increase our users' privacy.

CT is most likely easier to make compatible than ringCT, and will help protect against a possible attack vector of tracing people's public balances and the amounts sent, which can correlate when transferred out of ringCT balances.

With CT, this wouldn't be possible.

What do people think about adding these goals to the roadmap (and only ever removing public balances if all 4 compatibility requirements are met)?

Another possible feature we could add to increase privacy, would be to have an option in the GUI for people's balances to auto-convert to ringCT.

Note:  Any ad hominem attacks will be removed, if you'd like to attack me personally then you can do so in discord (my username is particlswap738), but ad hominem attacks just clog up the github and make it harder for other people to actually read and comment.  All opinions on the proposal itself are of course welcome.

Thanks for reading and let me know what you think!

If this proposal is well received by the general community, then we can start a fund for development for these features as well (or earmark some of the general treasury fund for this).

This is currently for discussion only and to gauge community support and opinions.

I am not a dev, but a community member.
