# Boson Protocol Bug Bounty

Boson Protocol enables the tokenization, transfer and trade of any physical thing as a redeemable NFT in a trust-minimized manner.

For more information about Boson Protocol, please visit https://www.bosonprotocol.io/. 

We are reshaping commerce for the new Web3 era and we need your help to succeed! If you have discovered a security bug, please contact us and join the Boson Protocol Bug Bounty as soon as possible and we will make sure that you get your reward!

## The Bounty Program

All Smart Contract bug reports require a proof-of-concept (PoC) to be eligible for a reward. Explanations and statements are not accepted as PoC, instead code is required. All web/app bug reports must come with a PoC with an end-effect impacting assets in-scope in order to be considered for a reward.

> Payouts are handled by the Boson Protocol team directly and are denominated in USD. However, payouts are done in $BOSON token.
> 
> Reports with severity Critical will be streamed over a 3-month period.

## Rewards - Smart Contracts

|Low |Medium|High    |Critical      |
|----|------|--------|--------------|
|$1,000 |$4,000 |$10,000 |Up to $25,000 |

## Rewards - SDK and dApps

|Low  |Medium|High    |Critical     |
|-----|------|--------|-------------|
|$500 |$1,000  |$4,000  |Up to $15,000|

Your report will be assessed by the Boson Protocol team and scored using the Common Vulnerability Scoring Scheme (CVSS).

The critical asset bounty will only be awarded where there is a serious and potentially permanent impact to a user's funds, or to the core protocol itself.

The bug bounty program considers a number of variables in determining rewards. Determinations of eligibility, score and all terms related to an award are at the sole and final discretion of Boson Protocol. 

Issues that have already been submitted by another user or are already known to Boson Protocol are not eligible for bounty rewards.

## SLA

Boson Protocol will make a best effort to meet the following SLAs for security researchers participating in our program:

* Time to first response (from report submission) - 3 business days
* Time to triage (from report submission) - 5 business days
* Time to bounty (from triage) - 30 business days

We’ll try to keep you informed about our progress throughout the process.

## Participation Requirements 

Participation in the Boson Protocol Bug Bounty program requires you to adhere to “Responsible Disclosure”. Responsible Disclosure includes:

*  Providing a reasonable amount of time to fix a vulnerability prior to sharing details of the said vulnerability with any other party.
*  Make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our service. Only interact with accounts you own or with the explicit permission of the account holder.
*  Not defrauding Boson Protocol users, partners or Boson Protocol itself in the process of participating.
*  Not profiting from or allowing any other party to profit from a vulnerability outside of the payouts made by this program.
*  Reporting vulnerabilities with no conditions, demands, or ransom threats.
Social Engineering attacks against Boson Protocol contributors is deemed a violation with respect to this program. Researchers engaging in Social Engineering attacks against Boson Protocol contributors will be banned from this program. We define Social Engineering as acts that influence people to perform security-impacting actions or divulge confidential information.
*  Asking our permission before disclosing the vulnerability.

## How to submit your vulnerability

Please provide us with the following information when submitting a bug to this program:

*  Summary of the bug
*  Severity of the bug
*  Steps to reproduce
*  Working proof of concept + any support materials (code, screenshots, logs etc)
*  Is any private personal data exposed?
*  Is any partner data exposed
*  Are user or partner funds at risk of being lost or irretrievable?
*  Optional: recommendation to address the bug.

Email your report to [security@bosonprotocol.io](mailto:security@bosonprotocol.io)
 
Please consult our Privacy Policy for further details on how we handle submissions.

## What we are interested in

The most important class of bugs we’re looking for are ones that would cause our users to lose access to their funds. Whether this be through gaining admin privileges on the protocol or through a mechanism that renders funds frozen and unusable within the escrow system. These along with any vulnerabilities that could be used to to defraud potential buyers and sellers are deemed the most important class of exploits* for example, vulnerabilities within the NFT Voucher that is used to commit to a sale or purchase.

Of lesser importance but still of interest are any vulnerabilities in the Boson dApp interface that may allow users to gain unauthorized advantage in any of the Quests or to obtain private information about other users or Boson Protocol’s partners.

## Scope

We are primarily inviting vulnerability reports relating to the Boson Protocol Contracts repo and to the Boson dApp user interface.

[This document](https://github.com/bosonprotocol/boson-protocol-contracts/blob/main/addresses/137-polygon-prod.json) contains the most up to date production deployment contract addresses.

Note that we are only interested in bugs on the releases tagged “Latest”, not in pre*releases or any other branches:
* https://github.com/bosonprotocol/boson-protocol-contracts/
* https://github.com/bosonprotocol/chat-sdk/
* https://github.com/bosonprotocol/core-components/
* https://github.com/bosonprotocol/interface/ 

## Out of scope

The following vulnerabilities (bugs) are not eligible for a reward:
* All vulnerabilities marked in https://github.com/bosonprotocol/boson-protocol-contracts/issues
* All vulnerabilities marked in https://github.com/bosonprotocol/chat-sdk/issues
* All vulnerabilities marked in https://github.com/bosonprotocol/core-components/issues
* All vulnerabilities marked in https://github.com/bosonprotocol/interface/issues
* All vulnerabilities outside of the list of repos stated in the Scope section (e.g. project's home website and documentation websites)

These are out of scope as well:
* Misconfigurations or operational issues
* Browser vulnerabilities
* OS vulnerabilities
* Spam, Phishing, Vishing, Smishing, Social Engineering of users, partners and contributors
* (D)DoS attacks
* Issues that have already been submitted, which are known or which are pending review
* Our web properties, including but not limited to our website, blog and documentation site
* Vulnerabilities or attacks on third*party providers (unless otherwise specified)
* Vulnerabilities on third party libraries without showing specific impact to the target application
* Scanner output or Scanner generated reports, including any automated or active exploit tool
* Information leaks via code repositories, transparency logs etc
* Vulnerabilities on third-party platforms, for example, Decentraland
* Vulnerabilities in underlying blockchain network itself, or in client applications such as wallets
* Vulnerabilities submitted by individuals who have contributed to the code in the repositories specified directly or indirectly (including external auditors) are not eligible for rewards.
 
## Legal Notice

The Boson Protocol Bug Bounty Program is a discretionary rewards program provided by BVoucher Limited for our active community to encourage and reward those who are helping to improve our software. It is not a competition. We can cancel the program at any time and awards are at our sole discretion. We are not able to issue any rewards to persons who are on any sanction lists maintained by the United Nations, Singapore, the EU, UK or the US or who are in a jurisdiction sanctioned by the same. The payment of rewards to you shall not render you our employee, worker, agent or partner or imply a similar relationship. We make no representation regarding any tax obligations (“Tax”) arising out of or connected to your participation, including the receipt of any rewards, and at no time shall we be liable for payment of the same. You are responsible for all Tax payable in connection therewith. 

By submitting your content (your “Submission”) to us, you agree that we may take all steps needed to validate, mitigate, and disclose the vulnerability and that you grant us any and all rights to your Submission needed to do so.

Your testing must not violate any law or compromise any data that is not yours. 

We will do our best to respond to your submission as quickly as possible, keep you updated on the fix, and award a bounty where appropriate. Any conduct by you that appears to be unlawful, malicious, or criminal in nature will immediately disqualify any Submission from the Boson Protocol Bug Bounty Program. Please do not engage in extortion. Please be aware that testing can be designated as a criminal act by the relevant authorities if you are violating Singapore or any other laws. Our rules do not supersede any applicable laws. If you do your best to follow these guidelines in discovering and disclosing a vulnerability, we will not consider your actions as an attack and won’t take any legal action against you.

Any obligations arising out of or in connection with this Bug Bounty Program or its subject matter will be governed by and construed in accordance with the laws of Singapore, and the courts of Singapore shall have exclusive jurisdiction to settle any dispute or claim arising out of or in connection with this Boson Protocol Bug Bounty Program.

## THANK YOU!

Thank you for helping build the world’s future commerce infrastructure!
