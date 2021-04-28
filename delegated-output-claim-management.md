---
layout: fr
network_vote: yes
title: Delegated Output Claim Management
author: Cryptoguard
date: April 28, 2021
amount: 0 PART
milestones:
  - name: Delegate a group of output claim managers
    funds: 100% (0 PART)
    done:
    status: unfinished
payouts:
  - date:
    amount:
---

# Summary

This proposal is to implement a streamlined and more efficient way to process manual output claims and reactivate temporarily disabled anon and blind balances.

# Rationale

On the 25th of February, the Particl team implemented an [https://particl.news/emergency-hardfork-announcement/] (emergency hardfork) to halt an ongoing vulnerability exploit that allowed an attacker to create PART coins fraudulently. To prevent the attacker from moving exploited coins after the hardfork, all anon and blind outputs have been temporarily disabled until the upcoming hardfork.

To re-enable these outputs, the team came up with a strategy involving a low-pass filter and a manual claim process. To learn more about it, please follow [https://particl.news/roadmap-to-post-inflation-hardfork/](this link).

Initially, the team proposed that any user with disabled outputs that can’t go through the low-pass filter would have to individually put up a claim on the CSS for their outputs to be re-enabled. This would preserve a good level of decentralization and ensure the team does not have an ultimate say over what outputs can be re-enabled or not, but it also introduces its fair share of inconveniences.

Following that announcement, the community firmly asked for a more streamlined, simple, efficient, and sure fire method to reactivate outputs, one that would not ultimately be dependent upon the assumed participation and goodwill of stakers. The community asked for the Particl team to be more involved in that process due to the trust relationship between the two parties (community and team). 

As a response to this request, the team opted to adopt a middle-ground approach. This approach, namely the election of a group of claim managers through a CCS vote by the community, is what’s being proposed here.

## How the Process Will Work

**If this proposal is approved**, a group of people from the Particl team will receive and process claims on behalf of users and determine whether the outputs can be verified through its tracer script and blockchain evidence or not.

Then, the team will submit the proof to a second group composed of trusted community members who’ll then validate the claim’s authenticity independently. This additional layer of checks and balances is required to inject more confidence into the process and reassure the community that no output gets reactivated without sufficient authenticity proof.

If one of the participating community members spots odd claims being reactivated, their task is to inform the community of their skepticism. If there’s any contested set of outputs, it will need to be pushed as an independent CCS proposal.

Any output validated by both the team and the community group will then be included in a whitelist and re-enabled as soon as the upcoming hardfork occurs.

### Note

Any user facing a rejected claim can, on their own, prepare a CCS proposal and plead their case to the community. In that sense, this proposal does not seek to give full authority of the claim process to the Particl team but rather ease and facilitate the process for the vast majority of users by reducing their burden.

## How to Submit a Claim

To submit a claim, follow these steps carefully.

- Download and install [https://github.com/particl/particl-desktop/releases/tag/v2.3.6](Particl Desktop 2.3.6).
- If not already done, import all your wallets with disabled outputs.
- Wait for the blockchain to finish syncing up.
- **Unlock every wallet** loaded on Particl Desktop, one by one.
- Click on the **printer icon** at the top right corner of your desktop client.
- In the window that appears, enter the location you want to save your output file by clicking on **Select Folder**.
- Click on **Export** to generate the output file, which will be saved at your chosen location.
- Wait for further instructions on how to submit your claim. This proposal will be updated with this information in the next few days.

After you submit your claim, the team will receive it and try to validate it. The team will then submit the evidence of the authenticity of your outputs to the community group tasked to verify the team’s findings. Once that process is complete, you’ll then receive an email confirming whether it’s been approved or not.

If your claim is rejected, you will still be able to plead your case directly to the community by creating a CCS proposal. In that proposal, you may have to provide additional information to convince the community that your claim is valid. What information is provided (i.e., transaction history, proof of purchase, etc.) is up to you. 

### Note 1

If your outputs can’t be verified using the tracer script developed for that specific purpose, you may receive an email asking for additional information. What other additional data may be required will be determined on a case-by-case basis.

### Note 2

If you have already submitted your outputs by email, you currently don’t need to do anything. The team will verify your claim and reach back to you if any additional information is required. 

# Key Points

The benefits of this proposal are many:

- You wouldn’t have to publicly provide personal, financial, or blockchain information (better privacy).

- You wouldn’t have to worry about whether or not stakers will validate your claims even if you can fully prove your outputs’ authenticity.

- You wouldn’t have to spend valuable time creating a proposal and convincing the community of the authenticity of your claim.

- Delegating the output verification process to a smaller and more streamlined group of managers will ensure a faster resolution and return to normal, after which the project will be able to move forward.

# Timeframe

- This proposal will be opened up for discussion for the next seven (7) days, after which it will move to the voting phase. 

- There will be a set deadline for you to submit your outputs. Failure to submit outputs within that deadline will result in your outputs not being included in the next hardfork. You will still be able to submit outputs after this time, but if they get validated, they will be re-enabled whenever Particl does another hardfork.

- The deadline for submitting your outputs will depend on a few factors (i.e., the volume of submitted claims) but will be clearly announced a few days or weeks before. **We recommend that you submit your claim as soon as you can and don’t wait too long for it.**

# Parties Involved

## From the Particl team

- **Tecnovert** - Claim analysis and output validation
- **Cryptoguard** - Claim management, proposal ownership, and communications
- **Kewde** and **Dasource** - Proposal lifecycle management and assistance, if needed, provided to Tecnovert

## Community Group for Proof Verification

- **Kapoor** (Joskye)
- **Gloria** (KateLady)
- **Dros** (Dros)

## Note

The management and validation of claims is provided as an entirely independent initiative. It is not related to any official Particl Foundation or team contribution but is done voluntarily by individual people.

# AMA/FAQ

If you have any questions regarding this proposal, the process of claiming disabled outputs, the vulnerability itself, or the solutions put in place to move forward, please visit the AMA/FAQ post currently stickied on Particl’s sub-Reddit and post it there. A member of the Particl team will be answering your questions which will double the thread as an FAQ resource for other people with similar questions.

- **Access the AMA/FAQ by clicking on [https://www.reddit.com/r/Particl/comments/n0ld5d/amafaq_delegated_output_claim_management_proposal/](this link).**
