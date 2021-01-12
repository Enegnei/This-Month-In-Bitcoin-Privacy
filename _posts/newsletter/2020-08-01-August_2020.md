---
title: "August 2020"
date: 2020-08-31
last_modified_at: 2020-10-30
classes: wide
  
tags:
  - Address Reuse
  - Atomic Swaps
  - Blockchain Analysis
  - Blockchain Surveillance
  - Bloom Filters
  - Chainalysis
  - Ciphertrace
  - Coinbase
  - CoinJoin
  - CoinSwap
  - Department of Homeland Security
  - Dust Attack
  - Human Rights Foundation
  - JoinMarket
  - Lightning Network
  - Lightning Torch
  - Multi-Path Payments
  - Network Privacy
  - PayJoin
  - PayNyms
  - Samourai Wallet
  - Schnorr Signatures
  - SIM Swap
  - Tor Network
  - Toxic Change
  - WabiSabi
  - Wasabi Wallet
  - xPub
  
---

Welcome to the third issue of '[This Month in Bitcoin Privacy](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/about/)' newsletter. Enjoy!

<p style="font-size: 0.9rem;font-style: italic;"><img style="display: block;" src="https://live.staticflickr.com/65535/49824354857_ef5787e553_b.jpg" alt="Emperor moth (Saturnia pavonia)"><a href="https://www.flickr.com/photos/92976263@N00/49824354857">"Emperor moth (Saturnia pavonia)"</a><span> by <a href="https://www.flickr.com/photos/92976263@N00">Roger Lancefield</a></span> is licensed under <a href="https://creativecommons.org/licenses/by-sa/2.0/?ref=ccsearch&atype=html" style="margin-right: 5px;">CC BY-SA 2.0</a><a href="https://creativecommons.org/licenses/by-sa/2.0/?ref=ccsearch&atype=html" target="_blank" rel="noopener noreferrer" style="display: inline-block;white-space: none;margin-top: 2px;margin-left: 3px;height: 22px !important;"><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc_icon.svg" /><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc-by_icon.svg" /><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc-sa_icon.svg" /></a></p>

### Table of Contents

1. [Full Node Deep Dive: RoninDojo](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-2nd---full-node-deep-dive-ronindojo)
2. [Junk in the Trunc: Lightning Privacy](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-3rd---junk-in-the-trunc-lightning-privacy)
3. [HRF Grants to JoinInBox, Zeus, Fully Noded](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-4th---hrf-grants-to-joininbox-zeus-fully-noded)
4. [PayJoin Support in Wasabi and JoinMarket](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-5th---payjoin-support-in-wasabi-and-joinmarket)
5. [Cross-Chain Atomic Swaps with Monero](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-8th---cross-chain-atomic-swaps-with-monero)
6. [Malicious Tor Exit Relays](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-9th---malicious-tor-exit-relays)
7. [Design Sketch for First Version of CoinSwap](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-11th---design-sketch-for-first-version-of-coinswap)
8. [Schnorr SignatureCheckers](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-12th---schnorr-signaturecheckers)
9. [Dust Attacks](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-18th---dust-attacks)
10. [OXT Research Vulnerability Disclosure](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-19th---oxt-research-vulnerability-disclosure)
11. [Dirtcoin Diaries' PayNym Torch](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-20th---dirtcoin-diaries-paynym-torch)
12. [The Solution to SIM Swapping?](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-21st---the-solution-to-sim-swapping)
13. [What is an xPub?](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-27th---what-is-an-xpub)
14. [Debating Blockchain Analysis](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-28th---debating-blockchain-analysis)

## August 2nd - FULL NODE DEEP DIVE: RONINDOJO

The [**Orange County (OC) Bitcoin Network**](https://www.meetup.com/oc-btc/), hosted by [Stephen Cole](https://twitter.com/sthenc) and [Brian Harrington](https://twitter.com/BrainHarrington), held their [fifth online event](https://youtu.be/ebv0aN8opIc) in a series exploring Bitcoin full node devices and software. This session, sponsored by [Bitcoin Magazine](https://twitter.com/BitcoinMagazine/status/1289987717921562630), featured [RoninDojo](https://twitter.com/RoninDojoUI/status/1289591165298204673) developers [Zelko](https://twitter.com/BTCxZelko) and [Guerra Moneta](https://twitter.com/GuerraMoneta), who debuted their [new website](https://ronindojo.io/) during the stream. As I mentioned in [TMIBP01](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-7th---running-ronindojo), this is an installation assistant and user interface for [**Samourai Wallet**](https://samouraiwallet.com/dojo)'s self-hosted Dojo full node backend.
{: style="text-align: justify;"}

> [This Bitcoin thing is a lot more than "number go up."](https://youtu.be/ebv0aN8opIc?t=4070)

Zelko and Guerra talked about how the project originated in the creation of Dojo [user](https://github.com/s2l1/Headless-Samourai-Dojo) [guides](https://github.com/BTCxZelko/Guides), which grew into an initiative to simplify and automate some of the processes involved as (eventually) a plug-and-play solution. They covered the [existing features](https://youtu.be/ebv0aN8opIc?t=1987) and explained why they made certain build decisions, such as not adding Lightning support. Zelko briefly discussed [a future premium offering](https://youtu.be/ebv0aN8opIc?t=2578) of RoninDojo for around $100 in order to sustain development. He gave [a live demonstration](https://youtu.be/ebv0aN8opIc?t=4463) of the GUI, designed by [Pavel Ševčík](https://twitter.com/pajasevi/status/1290038410598445056). For the last twenty minutes, they rolled through the roadmap, hardware specifications, and answered miscellaneous questions.
{: style="text-align: justify;"}

As of August 31st, [RoninDojo v1.6](https://code.samourai.io/ronindojo/RoninDojo/-/releases/v1.6) and the UI were [officially released](https://twitter.com/RoninDojoUI/status/1300463158620876800).

:information_source: For help to start, see [Bitcoin Q+A](https://twitter.com/BitcoinQ_A/status/1299006474962776064)'s user guide on "[Connecting or Migrating your Samourai Wallet to RoninDojo](https://www.bitcoinqna.com/post/connecting-or-migrating-your-samourai-wallet-to-ronindojo)."
{: .notice--success}

## August 3rd - JUNK IN THE TRUNC: LIGHTNING PRIVACY

The [Lightning Junkies](https://twitter.com/LNJunkies/status/1290394165323247616) podcast released [episode LNJ034](https://lightningjunkies.net/lnj034-rene-pickhardt-talks-ln-blackmail-attacks/), an interview with [data scientist and educator](https://www.rene-pickhardt.de/index.html%3Fp=22.html) [René Pickhardt](https://twitter.com/renepickhardt). He is a co-author of '[*Mastering the Lightning Network*](https://github.com/lnbook/lnbook)' and currently working on a PhD for the [Norwegian University of Science and Technology](https://www.ntnu.edu/employees/rene.m.pickhardt) (NTNU).
{: style="text-align: justify;"}

After relaying his background, how he came to Bitcoin, and the reality of Lightning adoption, the focus of the episode was Pickhardt's [blackmail attack disclosure](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-June/002735.html) from June, and other past attack vectors. In the last fifteen minutes (52:10), he plugged his own proposed [BOLT14](https://github.com/lightningnetwork/lightning-rfc/pull/780), "a collection of recommendations that help nodes to improve their abilities to discover payment paths with sufficient liquidity." This is based on [a paper](https://arxiv.org/abs/1912.09555) he [published](https://twitter.com/renepickhardt/status/1209061429917179904) with NTNU [associate professor](https://www.ntnu.edu/employees/mariusz.nowostawski) [Mariusz Nowostawski](https://twitter.com/praeteritio) in December 2019.
{: style="text-align: justify;"}

> Looking at different strategies of finding rebalancing cycles we suggest, for the sake of speed, that nodes share with their neighbors on which local channels they would like to have inbound or outbound capacity. This information could easily be probed anyway and will not worsen the privacy of the nodes involved in re-balancing.
>
> ... The developed rebalancing algorithm uses a heuristic in which participants use the local knowledge and make local adjustments to estimate the optimization problem of finding [balance function] **b** such that [the imbalance of the network] **G** is minimized. The algorithm therefore is privacy-aware.
>
> ... As privacy aware payment channel networks use source-based path finding without knowing the constraints of the channels along an attempted path, the likelihood of conducting a successful payment with few attempts becomes considerably higher in a balanced network. Our results show that nodes do not need to strive for ν<sub>u</sub> = 0.5 and perfect local balance of their channels in order to produce high success rate of random payments. It is sufficient for the overall network to be balanced if every node tries to optimize their channel balance coefficients [to] be almost equal. This can be achieved by making circular rebalancing payments.

Pickhardt said that while it sounds "a little bit counter-intuitive that when you share information, you actually hide more information with this," he hopes that he can "convince the developer community that [BOLT14] is a good idea." He also discussed [Just in Time (JIT) Routing](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-March/001891.html), which he had proposed back in [March 2019](https://twitter.com/renepickhardt/status/1109437934720204801). In April of this year, he and [Tikhomirov et al.](https://arxiv.org/abs/2004.00333) argued that "an attacker can easily discover channel balances using probing," but "[JIT routing mitigates the attack while improving pathfinding!](https://twitter.com/renepickhardt/status/1245626118985531393)"
{: style="text-align: justify;"}

> When I did this experiment, I actually wanted to show- it was my hypothesis in research, that there is a trade-off between privacy and reliability. I argued that JIT routing is more reliable, but it lacks privacy. Instead, it turned out that it is more reliable and increases the privacy. I [thought], 'Wow, this is a really great result.'
>
> ... My PhD is mainly focused around pathfinding. That is obviously also an issue, because pathfinding currently isn't that reliable.. The more I am doing my research, the more I find privacy problems in Lightning, or attack vectors, stuff like that. I think that is very natural; the better you understand a technology, the more you find its flaws and drawbacks.

Later in the month, he [expressed concern](https://twitter.com/renepickhardt/status/1298918019159207942) that "there are so many misconceptions about the privacy of Lightning in the wild for which often just the opposite seems to be true," and worried "we won't be able to fix that" in '[*Mastering the Lightning Network*](https://github.com/lnbook/lnbook).' However, it is clear that an effort is being made to counter misunderstanding. For example, in the third chapter on '[How the Lightning Network Works](https://github.com/lnbook/lnbook/blob/97a83e2405b353f5d308a3a9cb985e150cc0c143/03_how_ln_works.asciidoc#announcing-the-channel),' they refer to so-called "private channels" as "unannounced" channels instead, to avoid creating "a false sense of privacy."
{: style="text-align: justify;"}

(Sidenote: The [timing attacks paper](https://arxiv.org/abs/2006.12143) by [Prof. Dr. Florian Tschorsch](https://twitter.com/flotschorsch) and [Elias Rohrer](https://twitter.com/_tnull), featured in [TMIBP01](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-22nd---zkchannels-for-second-layer-privacy) and [TMIBP02](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-13th---junk-in-the-trunc-lightning-privacy), has been "[accepted for publication](https://twitter.com/_tnull/status/1291659476043431939)" with the second conference on [Advances in Financial Technologies](https://aft.acm.org/)).
{: style="text-align: justify;"}

## August 4th - HRF GRANTS TO JOININBOX, ZEUS, FULLY NODED

In June, the [**Human Rights Foundation** (HRF)](https://hrf.org/) launched their ‘[Bitcoin Development Fund](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-10th---human-rights-foundation-launches-dev-fund),’ focused on “making the Bitcoin network more private, decentralized, and resilient." Their [next round](https://twitter.com/HRF/status/1290680292756332544) of grants, "1 bitcoin each, worth over $11,000 at the time of writing," has gone to "[JoinInbox](https://github.com/openoms/joininbox) creator [Openoms](https://twitter.com/openoms), [Zeus](https://zeusln.app/) creator [Evan Kaloudis](https://twitter.com/evankaloudis) and [Fully Noded](https://apps.apple.com/us/app/fully-noded/id1436425586) creator [Fontaine](https://twitter.com/Fonta1n3)." Openoms [tweeted](https://twitter.com/openoms/status/1290790731616006144), "It is a great honour to have my work appreciated by a Foundation standing for the values I'd like to live."
{: style="text-align: justify;"}

> “The whole point of privacy is hiding in the crowd, and using JoinMarket as a maker required you to dwell deep in the command line,” Openoms, who’s also a contributor to the RaspiBlitz project, told [Bitcoin Magazine](https://bitcoinmagazine.com/articles/the-human-rights-foundation-awards-grants-to-three-more-bitcoin-projects). “By making it easier to be a maker, we can increase the liquidity and anonymity set available for CoinJoins significantly.”

As I covered in [TMIBP01](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-21st---introducing-joininbox), JoinInBox is a terminal-based graphical menu for the CoinJoin implementation [JoinMarket](https://github.com/JoinMarket-Org/joinmarket-clientserver). While JoinMarket have had [their own GUI](https://github.com/JoinMarket-Org/joinmarket-clientserver/blob/master/docs/JOINMARKET-QT-GUIDE.md) for four years now, he has been optimizing this menu as part of an effort to expand the application suite for [RaspiBlitz](https://shop.fulmo.org/raspiblitz/). Adam Gibson has also been looking into [supporting maker functions for GUI-only users](https://github.com/JoinMarket-Org/joinmarket-clientserver/pull/487) and recently [started work](https://x0f.org/@waxwing/104711319655673159) on a [JoinMarket Control Center prototype](https://github.com/JoinMarket-Org/jmcontrolcenter/releases/tag/v0.0.1dev) with "richer UI" and "easier cross platform binary distribution."
{: style="text-align: justify;"}

[Zeus](https://github.com/ZeusLN/zeus) is a Lightning mobile app for iOS and Android via [F-Droid](https://f-droid.org/), supporting [connections to your own node](https://youtu.be/XStiTJosklY) over a VPN or Tor. Kaloudis' latest [v0.3.1](https://github.com/ZeusLN/zeus/releases/tag/v0.3.1) release also enabled [multi-path payments](https://github.com/lnbook/lnbook/blob/99ded495703be229dbe356db2859f2a72d9b0a9b/03_how_ln_works.asciidoc) (MPP) sending, a feature that was [added to LND](https://github.com/lightningnetwork/lnd/releases/tag/v0.10.0-beta) at the end of April. As [**Lightning Labs'**](https://lightning.engineering/team/) protocol engineer [Joost Jager](https://twitter.com/joostjgr) [explained](https://lightning.engineering/posts/2020-05-07-mpp/), this comes with some privacy benefits:
{: style="text-align: justify;"}

> A final benefit of multi-path payments is that it obfuscates payment amounts. If a routing node is connected to a well-known source or destination of payments, it could guess at what the payment amount distribution looks like. Without the assumption that each payment consists of a single HTLC, the guessing becomes harder, enhancing privacy on the network.

[Christian Decker](https://twitter.com/Snyke) talked about [Point Timelock Contracts](https://suredbits.com/payment-points-part-3-escrow-contracts/) (PTLCs), multi-path payments – which he had recently [implemented in c-lightning](https://github.com/ElementsProject/lightning/pull/3809) – and privacy for [Livera's](https://twitter.com/stephanlivera/status/1293894462700023813) [SLP200](https://stephanlivera.com/episode/200/).

> (1:12:06) We are making traffic analysis a lot harder for ISP-level attackers. By really increasing the chattiness of the network itself, we make it much harder for observers to associate or to collate individual observations into one payment. It is definitely not the perfect solution, to tell a wider part of the network about a payment being done, but it is an incremental step towards the ultimate goal of making basically every payment indistinguishable from each other, which we are getting with Schnorr and the Point Timelock Contracts.
>
> Once we have the Point Timelock Contracts, we truly have a system where we are sending back-and-forth payments that are not collatable by payment hash, as you correctly pointed out. And not even by amount, because all of the payments have roughly the same amounts; it is the combination of multiple partial payments that gives you the actual transferred amount. It is not a clear loss or a clear win for privacy, that we're now telling a larger part of the network. But I do think that the pre-splitter and the adaptive splitting, combined with PTLCs, will be an absolute win no matter where you look at it.

(Note: Pickhardt offered a counter-perspective on MPPs starting around 56:14 [here](https://anchor.fm/lightning-junkies/episodes/LNJ034---Rene-Pickhardt-Talks-LN-Fee-Blackmail-Attacks-ehkqhv).)

:information_source: Check out [**Lightning Labs'** new newsletter](https://lightninglabs.substack.com/people/10472167-lightning-labs) to learn more about second-layer development and tools beyond privacy.
{: .notice--success}

## August 5th - PAYJOIN SUPPORT IN WASABI AND JOINMARKET

[**zkSNACKs**](https://twitter.com/Zksnacks_LTD) released [1.1.12](https://github.com/zkSNACKs/WalletWasabi/releases/tag/v1.1.12) of [Wasabi Wallet](https://twitter.com/wasabiwallet/status/1291057818536222725). In the release notes organized by CTO [Dávid Molnár](https://twitter.com/molnardavid84/status/1290977265430548481), and the accompanying [blog post](https://blog.wasabiwallet.io/wasabi-wallet-1-1-12-is-out/) by marketing strategist [Riccardo Masutti](https://twitter.com/RiccardoMasutti), they note that a merchant-oriented implementation of [PayJoin](https://docs.wasabiwallet.io/using-wasabi/PayJoin.html) is now supported.
{: style="text-align: justify;"}

> **PayJoin is a collaborative transaction between the sender and the receiver** of a payment, for example the merchant and the customer. The goal of the protocol is to **break the common input ownership heuristic**, while making it difficult to fingerprint that the transaction is in fact a CoinJoin. Further, it reduces the transaction fees paid by the merchant due to the consolidation of coins.

On August 20th, [JoinMarket](https://twitter.com/joinmarket/status/1296540482156322816) released [0.7.0](https://github.com/JoinMarket-Org/joinmarket-clientserver/releases/tag/v0.7.0), which also supports this type of [PayJoin](https://github.com/JoinMarket-Org/joinmarket-clientserver/blob/master/docs/release-notes/release-notes-0.7.0.md).

Otherwise known as [pay-to-end-point](https://en.bitcoin.it/wiki/PayJoin) (P2EP), this implementation – based on [Nicolas Dorier](https://twitter.com/NicolasDorier)'s [BIP-78](https://github.com/bitcoin/bips/blob/master/bip-0078.mediawiki) – works with [BTCPay Server](https://docs.btcpayserver.org/Payjoin/), and should be compatible with future releases of [Blockstream Green](https://www.blockstream.com/2020/04/16/en-bitcoin-privacy-improves-with-btcpay-servers-p2ep-implementation/) and [Blue Wallet](https://github.com/BlueWallet/BlueWallet/pull/1085). [Samourai](https://support.samourai.io/article/73-creating-a-stowaway-transaction) and [JoinMarket](https://github.com/Joinmarket-Org/joinmarket-clientserver/blob/master/docs/PAYJOIN.md) had previously implemented their own versions of peer-to-peer PayJoin, but limited to the pool of their own users; once they have added receiver support, [JoinMarket](https://github.com/JoinMarket-Org/joinmarket-clientserver/blob/master/docs/release-notes/release-notes-0.7.0.md) intends to "deprecate and remove" the "pre-existing Joinmarket-Joinmarket payjoin function." Regarding Samourai, there [is](https://twitter.com/nwoodfine/status/1251034376961290242) [ongoing](https://stephanlivera.com/episode/149/) [discussion](https://stephanlivera.com/episode/150/) about how / whether to pursue compatibility.
{: style="text-align: justify;"}

## August 8th - CROSS-CHAIN ATOMIC SWAPS WITH MONERO

Computer scientist and Monero researcher Joël '[h4sh3d](https://github.com/h4sh3d)' Gugger published a paper titled "[Bitcoin-Monero Cross-chain Atomic Swap](https://github.com/h4sh3d/xmr-btc-atomic-swap/blob/master/whitepaper/xmr-btc.pdf)." On July 31st, he had announced the completion of the research via [Reddit](https://www.reddit.com/r/Monero/comments/i1fknt/ccs_results_monero_atomic_swaps_research/). He had made a funding request for 18 XMR back in May through the [Community Crowdfunding System (CCS)](https://ccs.getmonero.org/proposals/h4sh3d-atomic-swap-research.html), though he notes that he started researching "a Bitcoin/Monero atomic swap three and a half years ago." Following review by the Monero Research Lab (MRL), the [announcement](https://twitter.com/monero/status/1290347500856115202) was shared widely on August 3rd.
{: style="text-align: justify;"}

> This protocol describes how to achieve atomic swaps between Bitcoin and Monero with two transactions per chain without trusting any central authority, servers, nor the other swap participant.
>
> ... Monero does not require any particular on-chain primitives (hashlocks, timelocks), all building blocks are off-chain primitives.. The Monero private spend key is split into two secret shares.. Participants will not use any multi-signature protocol; instead, the private spend key shares are distributed during initialization of the swap process where one participant will gain knowledge of the full key.. at the end of the protocol execution, either for a completed swap or for an aborted swap.

The paper remains purely technical, without making arguments about how swapping between Bitcoin and Monero benefits privacy. The introduction emphasizes that, being atomic, this will allow "two strangers to trade without risks nor the help of a third-party." Unlike [Zcash](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-22nd---zkchannels-for-second-layer-privacy), [Monero](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-22nd---zkchannels-for-second-layer-privacy) at least has an anonymity set to offer due to [ring signatures](https://youtu.be/zHN_B_H_fCs) being mandatory since 2017.
{: style="text-align: justify;"}

In the past, one of the most popular portals for swapping between these two cryptocurrencies was [**ShapeShift**](https://twitter.com/ShapeShift_io), the Denver-based crypto-to-crypto exchange. A [**Wall Street Journal**](https://archive.is/qe7Z9) investigation, which [accused them of money laundering](https://www.youtube.com/watch?v=Bx0UAFY76W8&t=1978s), noted that "in the case of Monero, recipient addresses and transaction amounts remain secret and the trail is severed." Once ShapeShift [decided to discard their account-less model](https://www.youtube.com/watch?v=Bx0UAFY76W8&t=1978s) and impose a requirement for [mandatory membership](https://info.shapeshift.io/blog/2018/09/04/introducing-shapeshift-membership/) in October 2018, following "[direct or indirect threats from regulators](https://www.coindesk.com/crypto-exchange-shapeshift-erik-voorhees-kyc-proactive)," [trading volume in XMR/BTC](https://bravenewcoin.com/insights/monero-price-analysis-consensus-algorithm-change-slated-for-october) was reported to be shifting towards decentralised exchanges like [Bisq](https://twitter.com/bisq_network/status/1230292480551260165).
{: style="text-align: justify;"}

On August 31st, [**Ciphertrace**](https://twitter.com/ciphertrace/status/1300485354181595136) announced that they had "[developed tools for the U.S. Department of Homeland Security (DHS) to track transactions of notoriously difficult-to-trace privacy coin Monero (XMR)](https://ciphertrace.com/ciphertrace-announces-worlds-first-monero-tracing-capabilities/)," laying "the groundwork for future implementation of entity transactions clustering, wallet identification, exchange attribution, and other functionality." As [Riccardo Spagni](https://twitter.com/fluffypony/status/1300623513796194304) and [Matt Odell](https://anchor.fm/tales-from-the-crypt/episodes/Rabbit-Hole-Recap-Week-of-2020-08-31-ej3g46) (49:49) later pointed out, this announcement may be based more on marketing than math.
{: style="text-align: justify;"}

## August 9th - MALICIOUS TOR EXIT RELAYS

A security researcher and Tor server operator known as [Nusenu](https://nusenu.github.io/) published the first part of a report titled "[How Malicious Tor Relays are Exploiting Users in 2020](https://medium.com/@nusenu/how-malicious-tor-relays-are-exploiting-users-in-2020-part-i-1097575c0cac)." They claim to have "uncovered a malicious actor running more than 23% of the entire Tor network’s exit capacity," and that the attacker specifically targeted "cryptocurrency related websites — namely multiple bitcoin mixer services."
{: style="text-align: justify;"}

> They replaced bitcoin addresses in HTTP traffic to redirect transactions to their wallets instead of the user provided bitcoin address. Bitcoin address rewriting attacks are not new, but the scale of their operations is.

They explain that the attacker engaged in selective [SSL stripping](https://en.wikipedia.org/wiki/Moxie_Marlinspike#SSL_stripping), removing "HTTP-to-HTTPS redirects to gain full access to plain unencrypted HTTP traffic." Websites that do not use "established countermeasures, namely [HSTS Preloading](https://hstspreload.org/) and [HTTPS Everywhere](https://www.eff.org/https-everywhere)," make this attack possible, and it is "not specific to Tor Browser. Malicious relays are just used to gain access to user traffic." [**ZDNet**](https://www.zdnet.com/article/a-mysterious-group-has-hijacked-tor-exit-nodes-to-perform-ssl-stripping-attacks/) noted that a similar attack using Tor-to-web proxies had been performed in 2018; computer scientist [Neal Krawetz](https://www.hackerfactor.com/about.php) pointed to [an earlier attack from 2014](https://twitter.com/hackerfactor/status/1292802644659052546). Nusenu did not report which mixing services were targeted and how much, if any, bitcoin was successfully hijacked this way.
{: style="text-align: justify;"}

[Fully Noded](https://twitter.com/FullyNoded/status/1293540826350415872) clarified that they were not affected, and [Wasabi](https://twitter.com/wasabiwallet/status/1293898875334537217) published a blog post in more detail about why "[replacement attacks are not possible due to the architecture of Wasabi](https://blog.wasabiwallet.io/wasabi-wallet-tor-ssl-stripping-attack/)." But these attacks do highlight the value of features like [Onion-Location](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-8th---hyperonionization), helping users to stay within the Tor network, rather than relying on exit nodes to access clearnet content.
{: style="text-align: justify;"}

## August 11th - DESIGN SKETCH FOR FIRST VERSION OF COINSWAP

After announcing a work-in-progress [implementation of CoinSwap](https://gist.github.com/chris-belcher/9144bd57a91c194e332fb5ca371d0964) in May and receiving [a grant](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-10th---human-rights-foundation-launches-dev-fund) in June, Chris Belcher emailed [a more detailed design sketch](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-August/018080.html) to the Bitcoin-dev mailing list, including "multi-transaction Coinswap, routed Coinswap, fidelity bonds, a liquidity market and private key handover," as well as potential attack vectors.
{: style="text-align: justify;"}

Belcher had been interviewed by [Max](https://twitter.com/Maxbuybit/status/1291495496553582592) for the [Bit-Buy-Bit](https://www.bit-buy-bit.com/podcast-1/episode/371d671c/ep37-bitcoin-podcast-with-chris-belcher) podcast, published on August 6th, and we also [interviewed](https://www.youtube.com/watch?v=t3rehVW_hDk) Belcher on August 10th. '[ZmnSCPxj](https://twitter.com/ZmnSCPxj)' replied to the mailing list that the maker / taker relationship in CoinSwaps potentially "[has a massive advantage over CoinJoin](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-August/018106.html)."
{: style="text-align: justify;"}

> In CoinJoin, since all participants sign a single transaction, every participant knows the total number of participants. Thus, in CoinJoin, it is fairly useless to have just one taker and one maker, the maker knows exactly which output belongs to the taker. Even if all communications were done via the single paying taker, the maker(s) are shown the final transaction and thus can easily know how many participants there are (by counting the number of equal-valued outputs).
>
> With CoinSwap, in principle no maker has to know how many other makers are in the swap.

[Nadav Kohen](https://twitter.com/nadav_kohen) commented that some of the "[complexity more or less goes away once we have Schnorr signatures and can use MuSig with adaptor signatures](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-August/018108.html)." He [wrote](https://twitter.com/Suredbits/status/1298270070582341633) about how adaptor signatures work in "[Schnorr Applications: Scriptless Scripts](https://suredbits.com/schnorr-applications-scriptless-scripts/)."
{: style="text-align: justify;"}

## August 12th - SCHNORR SIGNATURECHECKERS

Following last month's meeting highlighted in [TMIBP02](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-24th---schnorr--taproot-activation), the [Bitcoin Core PR Review Club](https://twitter.com/BitcoinCorePRs/status/1291845907512786946) held their fourth meeting, hosted by [John Newberry](https://twitter.com/jfnewbery), to discuss "[support for Schnorr signatures and integration in SignatureCheckers](https://github.com/bitcoin-core-review-club/bitcoin/commit/125318b68a)." You can read the meeting log [here](https://bitcoincore.reviews/17977-2).
{: style="text-align: justify;"}

:information_source: Check out [Nadav Kohen](https://twitter.com/nadav_kohen)'s "[Introduction to Schnorr Signatures](https://suredbits.com/introduction-to-schnorr-signatures/)," [Lucas Nuzzi](https://twitter.com/LucasNuzzi)'s "[Schnorr Signatures & The Inevitability of Privacy in Bitcoin](https://medium.com/digitalassetresearch/schnorr-signatures-the-inevitability-of-privacy-in-bitcoin-b2f45a1f7287)," Bitcoin Optech's [Schnorr Taproot Workshop](https://bitcoinops.org/en/schorr-taproot-workshop/) and [Newsletter #111](https://bitcoinops.org/en/newsletters/2020/08/19/) to learn more.
{: .notice--success}

## August 18th - DUST ATTACKS

[**CoinDesk**](https://twitter.com/CoinDesk/status/1295753495195324416) journalist [Colin Harper](https://twitter.com/AsILayHodling) reported on [an ongoing dust attack](https://www.coindesk.com/dust-attacks-bitcoin-wallets) that started around August 4th, attributed to "an entity that appears to be advertising an obscure Bitcoin SV messaging application," [Memo SV](https://web.archive.org/web/20200520111735/https://memo.sv/). Days earlier, [Samourai Wallet](https://twitter.com/SamouraiWallet/status/1293657948280033281) had dubbed this "the most organized dusting we have seen for some time."
{: style="text-align: justify;"}

As [explained](https://bitcoin.stackexchange.com/questions/10986/what-is-meant-by-bitcoin-dust) elsewhere by [Murch](https://twitter.com/murchandamus) and [Yahiheb](https://twitter.com/yahiheb_), "The definition of dust is client-specific and not a network rule. Bitcoin Core considers a transaction output to be dust, when its value is lower than the cost of spending it." While receiving a tiny amount of free money may sound harmless, dust can cause a variety of problems, even for custodial wallet users. Following [the acquisition of Neutrino last year](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-5th---coinbase-offers-blockchain-surveillance-to-irs-dea), some Coinbase customers who sought to leave the service encountered a [Catch-22](https://www.merriam-webster.com/dictionary/catch-22): closing your account [requires having zero remaining balance](https://help.coinbase.com/en/coinbase/managing-my-account/account-information/how-can-i-close-my-account), but if you had a "dust balance," i.e. an amount too small to be withdrawn, you were stuck. These frustrated customers [developed a work-around](https://twitter.com/udiWertheimer/status/1100864154443776000), [passing along their dust balances to each other](https://breakermag.com/why-crypto-twitter-is-on-fire-with-deletecoinbase/) via Coinbase's internal account system, until the amount was large enough to finally be withdrawn.
{: style="text-align: justify;"}

Dust also has privacy consequences. In March 2019, [Ádám "Nopara" Ficsór](https://twitter.com/nopara73/status/1105779583410946049) noted that Wasabi wallet users were being dusted. In an attempt to make the dust economical, bitcoin users will often consolidate them together during low-fee periods, which can result in multiple addresses becoming linked to a common owner. "About half of them don't mind joining together some of their dusts, exposing the links between their mixed outputs (not the mixes though)." During that week's [**Tales from the Crypt**](https://twitter.com/MartyBent/status/1106241188628189185) [Rabbit Hole Recap](https://anchor.fm/tales-from-the-crypt/episodes/Rabbit-Hole-Recap-Week-of-2019-03-11-e3f6ef), he said he did not know what the attackers were trying to achieve, but the dust had been interfering with their ability to accurately measure the anonymity set. Since their [1.1.3](https://github.com/zkSNACKs/WalletWasabi/releases/tag/v1.1.3) release, as a countermeasure, the wallet automatically hides / separates UTXOs which are less than or equal to 0.0001BTC from spendable coins.
{: style="text-align: justify;"}

[Ergo](https://twitter.com/ErgoBTC/status/1293273159165267977), an analyst for Samourai's "[separate, yet complimentary](https://blog.samouraiwallet.com/post/168785913782/samourai-oxt)" visualization and publication platform [OXT Research](https://www.oxtresearch.com/), has been sharing data points on this latest 'promotional dusting' behaviour since August 11th. He claims to have "traced some 84,000 dust outputs from 146 transactions," and thinks that raising the dust limit may act as "a deterrent." Others have suggested revitalising [coin management tools](https://twitter.com/SamouraiWallet/status/1293659464634073096) that can deal with these UTXOs in a privacy-preserving way, such as Peter Todd's '[Dust-B-Gone](https://github.com/petertodd/dust-b-gone).' Since November 2017, [Samourai Wallet](https://blog.samouraiwallet.com/post/167306611667/wallet-update-097-coin-control-dust-tx-alerts) has had a "Dust Alerting" feature and allowed their users to label any UTXO as 'Do Not Spend.'
{: style="text-align: justify;"}

And while there are currently no grounds to believe that the culprit behind this dust attack was either a malicious chain analytics company or exchange, Harper highlighted why such actors could be motivated to pull an attack like this.
{: style="text-align: justify;"}

> CoinDesk reached out to Chainalysis and CipherTrace to ask if they use dust in their analytics. Both companies denied using this technique, though Chainalysis Manager of Investigation Justin Maile added that dusting is “more often [used] by investigators” to trace illicit funds. Maile continued that exchanges may use dusting to trace stolen funds following a hack.
>
> Dave Jevans, the CEO of blockchain analytics company CipherTrace, told CoinDesk that “hackers may use dusting as a strategy for identifying individuals who can then be phished or extorted.”

## August 19th - OXT RESEARCH VULNERABILITY DISCLOSURE

The research arm of [**Samourai Wallet**](https://twitter.com/oxt_btc/status/1296146298471624706) announced that they had "[discovered two potential privacy vulnerabilities](https://medium.com/oxt-research/a-statement-on-two-discovered-vulnerabilities-in-wasabi-wallet-6e11e29a6ea8)" in Wasabi Wallet. A pastebin of the [private disclosure](https://pastebin.com/4tDh3ueW) was published later.
{: style="text-align: justify;"}

> When a mixed output is remixed, these vulnerabilities break the ZeroLink guarantee for the previous mix, cancelling its benefits. These vulnerabilities break a core assumption of mixing, with each remix effectively canceling out the privacy gains of the previous mix.

The first alleged vulnerability related to a "lack of strong endogenous randomness" when the client or coordinator is selecting UTXOs for a mix, requiring the attacker to have "knowledge of events related to the mixing process and of the composition of the targeted wallet" in order to exploit it. The second alleged vulnerability related to "the existence of peel chains composed of toxic change outputs propagating across the mixes." Toxic (or '[doxxic](https://www.bitcoinqna.com/post/dealing-with-coinjoin-change-outputs)') change is any unmixed UTXO created and sent back to your wallet; if not segregated, they can [potentially damage the privacy gains](https://joinmarket.me/blog/blog/the-445-btc-gridchain-case/#change-peeling) by creating deterministic links with postmix funds.
{: style="text-align: justify;"}

> As a consequence, the anonymity set after remix becomes 50 instead of the expected and reported 99. "But 50 seems fine!" Privacy enhancing tools shouldn't produce results that are a lottery. A good mixer should provide constant and predictable outcomes.

About [48 hours later](https://twitter.com/SamouraiWallet/status/1297047521429270529) as [promised](https://twitter.com/oxt_btc/status/1296146305593618437), they released [a full disclosure report](https://research.oxt.me/alerts/2020/08/21/Wasabi-Wallet/full) publicly. In the [summary](https://research.oxt.me/alerts/2020/08/21/Wasabi-Wallet), they recommended that "the best solution is obviously to introduce consistent randomness into the coin selection process." The researchers noted that "the Wasabi Wallet team did not accept the results in this disclosure."
{: style="text-align: justify;"}

On August 21st, while not a direct response to the report, [Ficsór](https://twitter.com/nopara73/status/1296760506255015940) answered [some relevant questions](https://pastebin.com/i3tvFT2Y). He argued that the "mathematical metrics" for calculating the anonymity sets "are terribly misleading the users" because they work "quite well for a single transaction" but not "multiple transactions." He also advised that while Wasabi has labeling tools and separates new coins from postmix funds by default, they currently don't have a "technical solution" for what users should do "with your ugly red coins" (unmixed UTXOs, including change). Samourai has previously written about [how they measure anonymity](https://medium.com/samourai-wallet/diving-head-first-into-whirlpool-anonymity-sets-4156a54b0bc7) during the [Whirlpool mixing](https://support.samourai.io/article/91-mixing-on-mobile-with-whirlpool) process, though they agree such numbers can be misunderstood and therefore [deliberately do not display anonymity set metrics](https://youtu.be/_xk2Iy6f2VA?t=1673). Their wallet segregates toxic change into a so-called "[bad bank](https://twitter.com/SamouraiWallet/status/1293659938422652935)."
{: style="text-align: justify;"}

As I covered in [TMIBP01](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-11th---wabisabi-and-coinpool), a new variable-amount CoinJoin protocol, dubbed “[WabiSabi](https://github.com/zkSNACKs/WabiSabi),” is being developed. [Ficsór](https://twitter.com/nopara73/status/1298726014856491009) confirmed that when it is ready, "[Wasabi Wallet's CoinJoin algorithm will be replaced](https://twitter.com/nopara73/status/1298726014856491009)." He later [added](https://twitter.com/nopara73/status/1299106432311275520) that this "isn't strictly news as I've [been] planning for and talking about it since 2018," referencing a [ZeroLink issue thread](https://github.com/nopara73/ZeroLink/issues/73) on extensions to [Chaumian](https://bitcoin.stackexchange.com/questions/9544/how-does-chaum-style-e-cash-work-all-the-wiki-links-are-broken) [CoinJoin](https://github.com/nopara73/ZeroLink#ii-chaumian-coinjoin) (CCJ).
{: style="text-align: justify;"}

On August 24th, [**Cointelegraph**](https://cointelegraph.com/news/expert-weighs-in-on-wasabis-response-to-wallet-security-issues) writer [Adrian Żmudziński](https://twitter.com/CriptoAZ) published comments from Ficsór and [Mário Havel](https://twitter.com/_TaxMeIfYouCan_), co-founder of [Paralelná Polis](https://twitter.com/Paralelni_polis/status/1298659447712239616) and "[considered one of Slovakia’s experts in cryptocurrencies](https://spectator.sme.sk/c/20939150/meet-slovakias-expert-on-cryptocurrencies-he-is-18.html)." Havel believes that the vulnerability report is "technically correct but not so critical as initially presented," and that they "affect only [the anonymity in] some CoinJoin scenarios in which the user is mixing more [unspent transaction outputs]."
{: style="text-align: justify;"}

> “Doing privacy correctly, especially with tools like coin control requires some learning and attention. In this case, the user has to be aware of possible attack scenarios and avoid them by managing UTXOs correctly."
>
> “Personally, I use both wallets since both have different features and perks. [...] Both are great wallets even without the CoinJoin feature and it is only up to the user how he uses it and what features of the wallet he needs.”

On August 28th, [OXT Research](https://twitter.com/oxt_btc/status/1299462036905230341) published [a follow-up post](https://medium.com/oxt-research/an-update-on-the-disclosed-vulnerabilities-in-wasabi-wallet-4ac0e228acb9) to address comments and criticisms of their report. They argue that it is "unreasonably optimistic" to assert that "the premix activity of a wallet" would be "beyond the reach of any adversary," and "we do not believe relying on user induced randomness is a satisfactory solution."
{: style="text-align: justify;"}

## August 20th - DIRTCOIN DIARIES' PAYNYM TORCH

The [Bitcoin Enemies](https://bitcoinenemies.com/) virtual meetup hosted their second session of '[Dirtcoin Diaries](https://twitter.com/biTcOinEneMiEs/status/1295004118516342786)' group discussion, with a focus on [PayNyms](https://support.samourai.io/section/32-paynym). In the four days leading up to the meeting, they had [organised](https://twitter.com/biTcOinEneMiEs/status/1295005099371028480) a [PayNym torch](https://twitter.com/i/events/1295315096445411329) with [proceeds](https://twitter.com/biTcOinEneMiEs/status/1298131934782971904) going to support development of [RoninDojo](https://twitter.com/RoninDojoUI/status/1296532321118507008).
{: style="text-align: justify;"}

[PayNyms](https://support.samourai.io/article/68-what-are-paynyms) are an implementation of [BIP-47](https://github.com/bitcoin/bips/blob/master/bip-0047.mediawiki), which specifies creating "a payment code which can be publicly advertised and associated with a real-life identity without creating the loss of security or privacy inherent to P2PKH address reuse." Instead of publishing a single donation address that all donors send money to, you share a pseudonymous identity (representing the payment code) that can be used to generate a fresh address for each payment. Not only can this obscure your donation address to the public, as each donor will only know the particular receive address they've paid to, but it significantly reduces address reuse. [Ravi Patel](https://twitter.com/Ravi_21M/status/1292865090350325760) has written about how you can also [avoid address reuse by setting up a donation page or store](https://medium.com/@Ravi_21M/how-to-accept-bitcoin-donations-the-correct-way-fb2ecda58dad) with BTCPay Server. At least one shop, [MINE.FARM.BUY](https://twitter.com/minefarmbuy/status/1298482559509291009), uses both in their checkout.
{: style="text-align: justify;"}

During the [meetup](https://twitter.com/biTcOinEneMiEs/status/1296515405477851136), they talked about why BIP-47 hasn't been more widely adopted yet, how complex it is under the surface, and strategies for using coins received through PayNyms. [Samourai Wallet](https://twitter.com/SamouraiWallet) reported that 82,800 PayNyms have been registered so far in [their directory](https://paynym.is/).
{: style="text-align: justify;"}

The idea for a PayNym torch originated in issues with last year's [Lightning Torch](https://web.archive.org/web/20191217074307/https://takethetorch.online/Torch) event, a fun way to test channel capacity across the Lightning Network. While this transaction relay was being described as "[a worldwide marathon](https://bitcoinmagazine.com/articles/lightning-torchs-bitcoin-payment-is-running-a-worldwide-marathon)," American participants were shy about [passing the torch to those living in parts of the world under U.S. sanctions](https://twitter.com/real_vijay/status/1099867809889214464). On February 26th 2019, [OXT](https://twitter.com/oxt_btc) developer and researcher [Laurent](https://twitter.com/LaurentMT/status/1100496030267789312) initiated a PayNym torch with Iranian bitcoiner [Ziya Sadr](https://twitter.com/Ziya_Sadr/status/1100526665275506689). Similar to the Lightning torch, whoever [received the PayNym torch](https://twitter.com/brian_trollz/status/1100540426602336263) would add a small amount, 0.001 BTC, and then pass it on to another PayNym of their choice.
{: style="text-align: justify;"}

## August 21st - THE SOLUTION TO SIM SWAPPING?

**Chainalysis**' public sector outreach and sales engineer Scott Johnston [published an article](https://twitter.com/UKFtweets/status/1296831886346653696) to the blog of [**UK Finance**](https://twitter.com/UKFtweets), a three-year-old trade association representing the UK financial services sector. The piece, aimed at "compliance professionals and financial investigators," is titled "[How to fight back against SIM swapping with blockchain analysis](https://www.ukfinance.org.uk/news-and-insight/blogs/how-fight-back-against-sim-swapping-blockchain-analysis)."
{: style="text-align: justify;"}

> In cases involving stolen cryptocurrency, they can use blockchain analysis to trace stolen funds to a cryptocurrency service they can subpoena for information on the attacker. [An example of this is on our blog](http://blog.chainalysis.com/reports/sim-swap-attacks), from a recent SIM swapping attack we investigated in which the victim had roughly $25,000 worth of cryptocurrency stolen. The attacker moves the funds through several intermediary wallets before depositing them across several different cryptocurrency services including exchanges, merchant services providers and darknet markets.

If the problem of SIM swapping was a weed, then applying blockchain analysis would be like trimming some leaves: this does nothing to address any of the root causes. Low-paid mobile service provider employees and contractors [who are easy to socially engineer](https://www.wired.com/story/phone-spear-phishing-twitter-crime-wave/). [Fundamental weaknesses in mobile network security](https://twitter.com/J9Roem/status/859913918122274821). Widespread misuse of phone numbers as identifiers, when the user doesn't actually control them. Data brokers having easy access to personally identifying mobile subscription and GPS data that is abused for everything from [tax investigations](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-5th---coinbase-offers-blockchain-surveillance-to-irs-dea) to [stalking](https://www.fastcompany.com/90310803/here-are-the-data-brokers-quietly-buying-and-selling-your-personal-information) to [extra-judicial drone strikes](https://twitter.com/J9Roem/status/813784796505735168).
{: style="text-align: justify;"}

It is concerning that people with potential influence in the UK government and banking sector would be giving out advice that more financial surveillance and control is the solution to this problem. But it would also be unsurprisng given [their trajectory over recent years](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/557861/IP_Bill_-_Draft_EI_code_of_practice.pdf), handicapping individual privacy and safety in favour of a surveillance state that has repeatedly [failed to deliver](https://www.theguardian.com/uk-news/2020/jun/21/reading-stabbings-libyan-held-after-three-killed-in-park-attack) on its promises of so-called national security.
{: style="text-align: justify;"}

:warning: If you have been a victim of SIM swapping or worry about becoming one, I recommend reading the EFF's article on "[The Problem with Mobile Phones](https://ssd.eff.org/en/module/problem-mobile-phones)," Kraken's "[Security Advisory: Mobile Phones](https://blog.kraken.com/post/219/security-advisory-mobile-phones/)," and Jameson Lopp's "[A Modest Privacy Protection Proposal](https://blog.lopp.net/modest-privacy-protection-proposal/)."
{: .notice--warning}

## August 27th - WHAT IS AN XPUB?

> Cryptography is not a magic spell that solves all security problems. Cryptography can provide solutions to cleanly defined problems that often abstract away important but messy real-world concerns. Cryptography can give guarantees about what happens in the presence of certain well-defined classes of attacks. These guarantees may not apply if real-world attackers “don’t follow the rules” of a cryptographic security model.

— "[The Joy of Cryptography](http://web.engr.oregonstate.edu/~rosulekm/crypto/)" by Mike Rosulek
{: style="text-align: right;"}

[Public key cryptography](https://www.garykessler.net/library/crypto.html#pkc) has been around since the 1970s and functioned on a few simple premises: the public key encrypts, the private key decrypts; share the public key, hide the private key; the public key can be derived from the private key, but the private key cannot be derived from the public key. As [many people](https://twitter.com/rusty_twit/status/1300015123579375617) may have realised for the first time in the past week, [the picture is a bit more complicated](https://twitter.com/PeterMcCormack/status/1298883346324389888) in Bitcoin.
{: style="text-align: justify;"}

[BIP-32](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki) introduced [hierarchical deterministic wallets](https://github.com/nvk/wallets-recovery#explainer-wallet-types) using a tree of [extended key pairs](https://github.com/bitcoinbook/bitcoinbook/blob/182c7f7ae0abc23f06eee25def68d835431ce050/ch05.asciidoc#extended-keys). These wallets were [much easier](https://twitter.com/dannydiekroeger/status/1300154226123984896) to use because you don't have to update your wallet backup every time a new address is generated. In [BIP-39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki) compliant wallets, the master key pair is generated from your mnemonic seed words. The master extended public key (xPub) can be used to derive all "[descendant](https://github.com/bitcoinbook/bitcoinbook/blob/182c7f7ae0abc23f06eee25def68d835431ce050/ch05.asciidoc#public-child-key-derivation)" public keys, often referred to as [child and grand-child keys](https://github.com/bitcoinbook/bitcoinbook/blob/182c7f7ae0abc23f06eee25def68d835431ce050/ch05.asciidoc#hd-wallets-bip-32bip-44). (Note: If you are using [BIP-49 wrapped](https://github.com/bitcoin/bips/blob/master/bip-0049.mediawiki) or [BIP-84 native](https://github.com/bitcoin/bips/blob/master/bip-0084.mediawiki) SegWit, then technically these are the [yPub and zPub](https://support.samourai.io/article/49-xpub-s-ypub-s-zpub-s).) Addresses are then derived from these public keys, and these addresses are what you actually send bitcoin to.
{: style="text-align: justify;"}

> Because of this construction, knowing an extended private key allows reconstruction of all descendant private keys and public keys, and knowing an extended public key allows reconstruction of all descendant non-hardened public keys.

In [simple terms](https://medium.com/@nopara73/what-is-an-xpub-4b60e63ec22d), while anyone who has access to your xPub alone *cannot* spend your bitcoin funds, they *can* see all addresses derived from it, all the coins you control at those addresses, and any transaction history. This is why the label "public key" can be a little misleading, as this information should not be shared with untrusted parties if you care about financial privacy. As Belcher has suggested, from a UX perspective, it may be helpful to refer to the xPub as a "[view key](https://twitter.com/chris_belcher_/status/1299281870757257218)," similar (though not technically equivalent) to how Zcash [viewing keys](https://z.cash/technology/) are explicitly designed to expose transaction details that are otherwise obscured.
{: style="text-align: justify;"}

If you use a light wallet and [aren't connecting to your own node](https://samouraiwallet.com/dojo), you may have shared your x/y/zPub with the wallet service operators. This presents a serious privacy trade-off, though this design decision is not necessarily malicious. In order to display your balance, your wallet needs to query a blockchain explorer to count the coins it holds, and having the xPub is a very convenient way to find out which addresses have been used.
{: style="text-align: justify;"}

Of course, that can be done without the xPub. For example, in their [support documentation](https://support.ledger.com/hc/en-us/articles/360011069619-Extended-public-key), [**Ledger**](https://twitter.com/Ledger) asserts that "Ledger Live stores the xpub locally on your computer when you add the account. Your xpub is never sent to Ledger's servers. It is encrypted by your Ledger Live password if you have set one." In practice, this method offers some protection compared to services that do access xPubs: if a Ledger user were to switch to using their own node instead, Ledger the company would only be aware of the relationship between addresses that the user queried the balance for *prior* to migrating to their own node. They could not associate them with newly generated addresses going into the future (assuming the user can avoid linking them through spending patterns).
{: style="text-align: justify;"}

Some attempts have been made to preserve the privacy of light wallet users' address ownership, using filters that don't explicitly tell the provider or peer nodes which addresses belong to them. Requests using [BIP-37](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) bloom filters will contain false positives, "meaning the remote peer cannot accurately know which transactions belong to the client and which don't." However, it was soon found that this ambiguity [breaks down](https://en.bitcoin.it/wiki/Privacy#Wallet_history_retrieval_from_third-party) after [multiple filters](https://ethz.ch/content/dam/ethz/special-interest/infk/inst-infsec/system-security-group-dam/research/publications/pub2014/acsac_gervais_slides.pdf). [BIP-157](https://github.com/bitcoin/bips/blob/master/bip-0157.mediawiki) / [158](https://github.com/bitcoin/bips/blob/1cc657dddae2a82336aee66598fe57c1b62076c5/bip-0049.mediawiki) "[Neutrino](https://blog.lightning.engineering/posts/2018/10/17/neutrino.html)" client-side filtering, still in the draft stage, aims to rectify this by having "full nodes generate deterministic filters on block data that are served to the client. A light client can then download an entire block if the filter matches the data it is watching for."
{: style="text-align: justify;"}

> Finally, client privacy is improved because blocks can be downloaded from any source, so that no one peer gets complete information on the data required by a client. Extremely privacy conscious light clients may opt to anonymously fetch blocks using advanced techniques such a Private Information Retrieval.<sup>[6](https://github.com/bitcoin/bips/blob/master/bip-0157.mediawiki#cite_note-6)</sup>

We had interviewed Ficsór, Dorier, and [Pierre Rochard](https://twitter.com/pierre_rochard) about their views on [Neutrino filters](https://youtu.be/Ipjp61HBm-w) back in March 2019. Ficsór then wrote about how Wasabi, "a BIP157-ish client side filtering light wallet," handles '[Network Level Privacy](https://medium.com/@nopara73/bitcoin-core-vs-wasabi-wallet-network-level-privacy-bdca1d501387).'
{: style="text-align: justify;"}

> The vision of a light wallet that does not leak too much information while establishing the user’s UTXO set had haunted Bitcoin developers for centuries.

## August 28th - DEBATING BLOCKCHAIN ANALYSIS

[**The Blockchain Debate Podcast**](https://twitter.com/BlockDebate/status/1299416443344375809) hosted by [Richard Yan](https://twitter.com/gentso09) held a debate between [Alex Gladstein](https://twitter.com/gladstein/status/1299811160389120000) and [Dave Jevans](https://twitter.com/davejevans), founder and CEO of [**Ciphertrace**](https://ciphertrace.com/). Similar to Gladstein's debate with **Elliptic**'s [Tom Robinson](https://twitter.com/tomrobin) featured in [TMIBP01](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-1st---blockchain-analysis-or-financial-surveillance), the motion was: "[Blockchain analysis companies are bad for bitcoin](https://open.spotify.com/episode/5qryMUpsE0IKv0c4RF4ESV?si=tfSnHFkORdayXUDvoDsLVg&context=spotify%3Ashow%3A1NWyr8sBR0aKW5EnXFDfkN)." Needless to say, Gladstein agreed with the motion, while Jevans disagreed. Describing himself as an ex-cypherpunk, he had published "[On Cryptocurrency Tracing Companies and Privacy on the Blockchain](https://web.archive.org/web/20200522075355/https://ciphertrace.com/on-cryptocurrency-tracing-companies-and-privacy-on-the-blockchain/)" in May, arguing that "CipherTrace has always been an advocate of user privacy" and such companies are not "violating human rights."
{: style="text-align: justify;"}

In his opening statement, Gladstein cited an article from [**The Atlantic**](https://twitter.com/TheAtlantic) titled "[The Panopticon Is Already Here](https://www.theatlantic.com/magazine/archive/2020/09/china-ai-surveillance/614197/)," about the role of artificial intelligence in China's endeavor to "build an all-seeing digital system of social control, patrolled by precog algorithms that identify potential dissenters in real time," systems that are gaining favour with other states around the world. "Whether or not Dave's company would work with those governments, I'm sure his competitors will."
{: style="text-align: justify;"}

In Jevan's opening statement, he argued that if these financial surveillance tools were not available, "within six to eight months, at least thirty countries would ban cryptocurrencies," echoing Robinson's sentiment. He still disagreed with the allegation that they collect personally identifiable information or deanonymize "individual identities," and framed their work as similar to 'reporting that someone made a purchase at Target,' rather than 'identifying who made the purchase and what items were purchased.'
{: style="text-align: justify;"}

Gladstein countered that even if Ciphertrace or someone like them wasn't collecting that information, they would still be a vital cog in the machine of multiple actors who are trying to do so. Given that Jevans claimed to merely identify businesses and exchange entities (particularly VASPs), he asked whether Ciphertrace's tools were effective against peer-to-peer activity. "I wouldn't say it's useless, but we certainly don't focus on it," Jevans responded.
{: style="text-align: justify;"}

Jevans attempted to downplay the significance of their actions in a "realistic" world where "financial investigation and tracking is not new." He had made the decision many years ago to act as "a bridge between the crypto community" and the compliance industry surrounding traditional finance. When Gladstein suggested a third option – dedicating their resources and knowledge to support privacy-enchancing technology – Jevans noted that his business worked "almost every week" with teams at [Zcash](https://z.cash/) and Monero. Ciphertrace and Zcash are both members of the [**Blockchain Alliance**](https://blockchainalliance.org/) coalition. What this collaboration entailed, he did not say.
{: style="text-align: justify;"}

Gladstein plugged [Belcher's work on CoinSwap](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-10th---human-rights-foundation-launches-dev-fund), Liquid's testing of [confidential transactions](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-11th---wabisabi-and-coinpool), the [Lightning Network](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-13th---junk-in-the-trunc-lightning-privacy), and [the Schnorr / Taproot upgrade](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-24th---schnorr--taproot-activation) as ongoing efforts to render blockchain surveillance ineffective. Jevans did not comment on [whether these techniques would hinder their work](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#june-30th---irs-seeking-to-trace-privacy-coins-lightning), but rather took credit for incentivising the development and adoption of privacy technology. He later asserted that it should be assumed just "putting your stuff on the internet" would be accompanied by mass surveillance. They concluded the debate by discussing [FATF](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-20th---how-i-knew-your-customer-fatf-compliance)'s [Travel Rule](https://twitter.com/ciphertrace/status/1296470288448851968) and what distinguished Ciphertrace from other blockchain surveillance companies.
{: style="text-align: justify;"}

> We don't need compliance. We don't need blockchain analytics companies. They are tools of those in power. Bitcoin exists as a tool for the powerless. Blockchain analytics companies, or as I like to call them 'financial surveillance' companies, are bad for Bitcoin.

**Thanks for reading!** Feel free to :bookmark: [bookmark](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/feed.xml) or [subscribe](https://github.com/Enegnei/This-Month-In-Bitcoin-Privacy) to catch the next edition of 'This Month in Bitcoin Privacy.'
{: .notice--info}
