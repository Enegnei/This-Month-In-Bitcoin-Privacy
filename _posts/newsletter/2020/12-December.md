---
title: "December 2020"
date: 2020-12-31
last_modified_at: 2021-01-02
classes: wide
  
tags:
  - Atomic Swaps
  - Bank Secrecy Act
  - Blockchain Analysis
  - Blockchain Surveillance
  - Chainalysis
  - Ciphertrace
  - CoinSwap
  - Data Breach
  - Electronic Frontier Foundation
  - Elliptic
  - Financial Crimes Enforcement Network
  - Ledger
  - Lightning Network
  - PATRIOT Act
  - PET Symposium
  - Pseudonymity
  - Ring Signatures
  - Samourai Wallet
  - Schnorr Signatures
  - Taproot
  - WabiSabi
  - Wasabi Wallet
  
---

Welcome to the seventh issue of '[This Month in Bitcoin Privacy](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/about/)' newsletter. Enjoy!

<p style="font-size: 0.9rem;font-style: italic;"><img style="display: block;" src="https://live.staticflickr.com/1829/41957616285_aa1aa95506_b.jpg" alt="Cinnabar Moth"><a href="https://www.flickr.com/photos/48542598@N07/41957616285">"Cinnabar Moth"</a><span> by <a href="https://www.flickr.com/photos/48542598@N07">Doolallyally</a></span> is licensed under <a href="https://creativecommons.org/licenses/by-nd/2.0/?ref=ccsearch&atype=html" style="margin-right: 5px;">CC BY-ND 2.0</a><a href="https://creativecommons.org/licenses/by-nd/2.0/?ref=ccsearch&atype=html" target="_blank" rel="noopener noreferrer" style="display: inline-block;white-space: none;margin-top: 2px;margin-left: 3px;height: 22px !important;"><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc_icon.svg?image_id=37f8be28-0e6b-47f3-80e7-7a2ff1a39658" /><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc-by_icon.svg" /><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc-nd_icon.svg" /></a></p>

### Table of Contents

1. [Privacy Enhancing Technologies Symposium](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-1st---privacy-enhancing-technologies-symposium)
2. [Taproot Ring Signatures](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-2nd---taproot-ring-signatures)
3. [Privacy in Cross-Layer Interactions](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-3rd---privacy-in-cross-layer-interactions)
4. [Comply First, Think Later](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-7th---comply-first-think-later)
5. [CoinSwap on Testnet](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-8th---coinswap-on-testnet)
6. [The PATRIOT Act: Share It All](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-10th---the-patriot-act-share-it-all)
7. [Wasabi Wallet 2.0 Update](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-12th---wasabi-wallet-20-update)
8. [User Experience Research Grant](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-14th---user-experience-research-grant)
9. [Coinkite Bitcoin School: JoinMarket](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-16th---coinkite-bitcoin-school-joinmarket)
10. [Ledger Data Dump](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-20th---ledger-data-dump)
11. [Financial Cancel Culture](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-21st---financial-cancel-culture)
12. [Release Candidate Testing](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-23rd---release-candidate-testing)
13. [Farcaster: Atomic Swaps with Monero](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-24th---farcaster-atomic-swaps-with-monero)
14. [Merry Mixmas](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-25th---merry-mixmas)
15. ["A Best Guess": BitBargain Closes](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/December_2020/#december-26th---a-best-guess-bitbargain-closes)

## December 1st - PRIVACY ENHANCING TECHNOLOGIES SYMPOSIUM

The [third submission deadline](https://petsymposium.org/cfp21.php) for the upcoming 21st [**Privacy Enhancing Technologies Symposium**](https://twitter.com/PET_Symposium/status/1329807864551141377) (PETS 2021) has now passed. If you would still be interested in publishing your research here, the final issue submission deadline is set for February 28th 2021. This [open-access journal](https://dblp.org/db/journals/popets/index.html) and conference has been accepting papers regarding "blockchain technologies applied to privacy / blockchain privacy" since their [19th symposium](https://petsymposium.org/cfp19.php).
{: style="text-align: justify;"}

## December 2nd - TAPROOT RING SIGNATURES

Developer [Jonas Nick](https://twitter.com/n1ckler/status/1334240709814136833) published a proof-of-concept [ring signature scheme for Taproot outputs](https://github.com/jonasnick/taproot-ringsig). Ring signatures are a type of digital signature "[which makes it possible to specify a set of possible signers without revealing which member actually produced the signature](https://sci-hub.se/https://doi.org/10.1007/3-540-45682-1_32)." Ring confidential transactions (RingCTs) have been [mandatory](https://github.com/monero-project/monero#monero-software-updates-and-consensus-protocol-changes-hard-fork-schedule) in Monero since 2017.
{: style="text-align: justify;"}

In [TMIBP06](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/November_2020/#november-27th---taproots-impact-on-bitcoin-privacy) I covered discussion about the privacy benefits of the upcoming Schnorr / Taproot soft fork. [Alejandro De La Torre](https://github.com/AlejandroDeLaTorre) and journalist [Aaron van Wirdum](https://twitter.com/AaronvanW/status/1328385587011874820) have been tracking miner support for activation; around 90% of the global hashrate has [signalled support](https://taprootactivation.com/) in some way. On December 10th, [**Braiins**](https://twitter.com/slush_pool/status/1337054726920302592), operator of the oldest Bitcoin mining pool, published a "[not overly-technical description of how blockchain analysis works and the implications of Taproot on Bitcoin user privacy](https://braiins.com/blog/explain-like-im-not-a-developer-taproot-privacy)." The first half of the article breaks down UTXOs and clustering.
{: style="text-align: justify;"}

> A great start would be exchanges using Taproot in mass, which they are incentivized to do considering that they are likely the most active users of multi-sig transactions which are made cheaper by Taproot. If exchanges do their part, it’s up to wallet service providers to also implement Taproot for their users, so that multi-sig exchange withdrawals to single-sig users are not distinguishable on-chain.
>
> This all starts with education. Most new adopters of Bitcoin will likely never know or care about address types and other technical aspects of the network. But we are the early adopters, the vocal and powerful minority in the future Bitcoin ecosystem. It is up to us to follow best practices, educate others, and support service providers who help move Bitcoin forward.

:information_source: For a summary of Schnorr and Taproot progress, see [**Bitcoin Optech**](https://twitter.com/bitcoinoptech/status/1341729741305507841)'s special edition [year-in-review](https://bitcoinops.org/en/newsletters/2020/12/23/) newsletter.
{: .notice--success}

## December 3rd - PRIVACY IN CROSS-LAYER INTERACTIONS

[Notifications for paper submissions](http://fc21.ifca.ai/cfp.html) to next year's 25th annual [Financial Cryptography and Data Security](http://fc21.ifca.ai/) (FC21) conference were sent out. One of the [accepted papers](https://twitter.com/bhaslhofer/status/1334753000611602432) concerns "[the first quantitative analysis of the security and privacy issues opened up by cross-layer interactions](https://arxiv.org/abs/2007.00764)" on Bitcoin, published back in [July](https://twitter.com/bhaslhofer/status/1278957134252826624). It was authored by [Matteo Romiti](https://twitter.com/MattRomiti), [Friedhelm Victor](https://twitter.com/friedhelmvictor), [Pedro Moreno-Sanchez](https://twitter.com/pedrorechez), [Bernhard Haslhofer](https://twitter.com/bhaslhofer), and [Matteo Maffei](https://twitter.com/matteo_maffei).
{: style="text-align: justify;"}

On the same day, co-author [Haslhofer](https://twitter.com/bhaslhofer/status/1334493452277575681) also shared that the [Austrian Institute of Technology](https://www.ait.ac.at/) (AIT) and the [Vienna Complexity Science Hub](https://www.csh.ac.at/complexity-science/Cryptofinance/) were "joining forces and aim at building an interdisciplinary team of scientists focusing on the analysis of Decentralized Finance (DeFi) protocols and services." They are looking to fill [part-time PhD](https://www.csh.ac.at/wp-content/uploads/2020/12/PhD-Decentralized-Finance_final.pdf) and [partner scientist](https://jobs.ait.ac.at/Job/139799) positions.
{: style="text-align: justify;"}

[István András Seres](https://twitter.com/Istvan_A_Seres), a co-developer of [WabiSabi](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-11th---wabisabi-and-coinpool), has been working on the [security and privacy](https://github.com/seresistvanandras/lnbook/blob/lnsecurityprivacy/security_privacy_ln.asciidoc#definitions-of-privacy) page of '[*Mastering the Lightning Network*](https://github.com/lnbook/lnbook).' As I previously covered in [TMIBP01](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-22nd---zkchannels-for-second-layer-privacy), [TMIBP03](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-3rd---junk-in-the-trunc-lightning-privacy), and [TMIBP05](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/#october-29th---like-a-clboss-lightning-privacy), many have been critically examining the Lightning Network's privacy guarantees.
{: style="text-align: justify;"}

## December 7th - COMPLY FIRST, THINK LATER

[ComplyFirst](https://twitter.com/Comply_First/status/1336390530528317447) [launched](https://www.newswire.com/news/complyfirst-launches-to-support-crypto-exchange-compliance-with-21273457) this month as a new "online resource for anti-money laundering (AML) and other digital assets-related compliance professionals," with contributions from [Tari Labs](https://tarilabs.com/), [DV Chain](https://dvchain.co/), Stoic Capital, and the blockchain surveillance firm [**CipherTrace**](https://ciphertrace.com).
{: style="text-align: justify;"}

> We aim to educate and support various members of the cryptocurrency ecosystem, including exchanges, wallets, custodians, developers, researchers, and more on supporting these valid, valuable and rapidly emerging technologies in a responsible manner that satisfies their compliance obligations.

One of their first [resources](https://www.complyfirst.org/resources/), published on December 7th, is "[Example Privacy Feature Enhanced Due Diligence Questionnaire](https://web.archive.org/web/20201213192152/https://s33483.pcdn.co/wp-content/uploads/2020/11/ComplyFirst-Example-Privacy-Feature-Enhanced-Due-Diligence-Questionnaire.pdf)," intended to be sent to customers and counterparties that "may be involved with privacy-enhancing activities such as mixing services, shielded transactions, or other unusual privacy-enhancing behaviors." Some of the questions include:
{: style="text-align: justify;"}

> Describe your process of using a privacy-enhancing feature to the best of your ability:
>
> Describe why you are using a privacy-enhancing feature:
> 
> What cryptocurrency addresses did you use before/during/after (as applicable) the privacy-enhancing feature?
>
> If the privacy-enhancing process was interactive, did you conduct due diligence (eg: collect IDs,physical addresses, etc.) or otherwise know any of the counterparties you interacted with to use this privacy-enhancing feature? If so, provide as much information as possible, including names and wallet addresses:
>
> Do you intend to use these or similar privacy-enhancing features in the future? If so, why?

Honestly, this questionaire is far too long. [I laughed so hard that I struggled to even read it](https://youtu.be/KuVLQGMTfnE?t=651). If they would like a more succinct version, keeping the original spirit of the document, I would re-write it as: "*Hey there! I see that you want to preserve your financial privacy. Do you mind if we just strip it away completely? Please keep in mind that if you answer incorrectly, you might never get your money back*. :smiley:"
{: style="text-align: justify;"}

Ask me for the identities of relay operators along my Tor onion circuit, why don'tcha?

## December 8th - COINSWAP ON TESTNET

In [TMIBP01](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-10th---human-rights-foundation-launches-dev-fund) and [TMIBP03](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-11th---design-sketch-for-first-version-of-coinswap), I covered the early development of a working [CoinSwap](https://en.bitcoin.it/wiki/CoinSwap) protocol. Chris Belcher has since conducted "[the first ever multi-transaction CoinSwap on bitcoin testnet](https://twitter.com/chris_belcher_/status/1336322923800322049)." On December 14th, he also published a Rust implementation "[for developers to play around with](https://github.com/bitcoin-teleport/teleport-transactions)," including a detailed list of tasks and goals.
{: style="text-align: justify;"}

## December 10th - THE PATRIOT ACT: SHARE IT ALL

The Financial Crimes Enforcement Network (FinCEN) published a news release titled "[Director Blanco Emphasizes Importance of Information Sharing Among Financial Institutions](https://www.fincen.gov/news/news-releases/director-blanco-emphasizes-importance-information-sharing-among-financial)." These [prepared remarks](https://www.fincen.gov/news/speeches/prepared-remarks-fincen-director-kenneth-blanco-delivered-virtually-american-bankers) for the ABA’s annual Financial Crimes Enforcement Conference were accompanied by [a fact sheet](https://www.fincen.gov/sites/default/files/shared/314bfactsheet.pdf) on Section 314(b) of the [USA PATRIOT Act](https://www.govinfo.gov/content/pkg/PLAW-107publ56/pdf/PLAW-107publ56.pdf):
{: style="text-align: justify;"}

> Section 314(b) of the USA PATRIOT Act provides financial institutions with the ability to share information with one another, under a safe harbor that offers protections from liability, in order to better identify and report activities that may involve money laundering or terrorist activities.  Participation in information sharing pursuant to Section 314(b) is voluntary, and FinCEN strongly encourages financial institutions to participate.

In [TMIBP02](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-20th---how-i-knew-your-customer-fatf-compliance) and [TMIBP05](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/#october-20th---bank-secrecy-act-and-the-travel-rule), I covered the development of an inter-VASP customer data sharing system for compliance with the Bank Secrecy Act (BSA) Travel Rule, and how FinCEN was seeking to lower the threshold (a proposal for which they received "roughly 2,900 comments"); in [TMIBP02](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-15th---fourth-amendment-lawsuit-against-irs), [TMIBP04](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/September_2020/#september-2nd---eff-calls-for-coinbase-transparency) and [TMIBP06](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/November_2020/#november-17th---how-private-is-my-pay-app), I've followed challenges to the use of the third-party doctrine regarding financial records; in [TMIBP05](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/#october-8th---cryptocurrency-enforcement-framework), I also highlighted how the effectiveness of anti-money laundering policies came under scrutiny with the release of the '[FinCEN Files](https://www.icij.org/investigations/fincen-files/)', and interest in identifying '[crypto-exposed persons](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/#october-19th---chainalysis-and-crypto-exposed-persons).'
{: style="text-align: justify;"}

According to the fact sheet, financial institutions "need not have specific information indicating that the activity... relates to proceeds of [specified unlawful activities] SUA... nor must a financial institution or association have reached a conclusive determination that the activity is suspicious." Furthermore, the "regulations impose no limitations on the sharing of personally identifiable information." In an interview with [**CoinDesk**](https://www.coindesk.com/fincen-encourages-banks-to-share-customer-information-with-each-other), associate law professor Nizan Geslevich Packin, author of a pending paper on "[data aggregators’ relationships with banks, tech companies, and consumers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3620025)," said this is "a major concern."
{: style="text-align: justify;"}

> This has led to what one compliance officer called an "avalanche of data" because financial institutions have been filing more and more to FinCEN. 
>
> "Many questions about the safety of the information collected by FinCEN, as well as the bureau’s failure to provide clear guidelines regarding how and when it eventually deletes the data it has, remain unanswered,” Packin said. “This is concerning ... in an era in which cybersecurity [has] become a major concern."

On December 18th, Director Kenneth Blanco filed [a notice of proposed rulemaking](https://web.archive.org/web/20201218212406/https://public-inspection.federalregister.gov/2020-28437.pdf) "to require banks and money service businesses ('MSBs') to submit reports, keep records, and verify the identity of customers in relation to transactions involving convertible virtual currency ('CVC') or digital assets with legal tender status ('legal tender digital assets' or 'LTDA') held in unhosted wallets" when the transaction is valued "above the equivalent of $3,000." The document notes that they would be limiting the notice-and-comment period to fifteen days "because this proposal involves a foreign affairs function of the United States" and must not have "undue delay in the implementation." [**Coin Center**](https://twitter.com/jerrybrito/status/1340061691833446403) [commented](https://www.coincenter.org/a-midnight-rule-for-cryptocurrency-transaction-reports/) that "rushing this rule" was "problematic," and "time constraints of the so-called midnight period should never be an acceptable justification for imposing rules on Americans and innovative American businesses."
{: style="text-align: justify;"}

> Make no mistake, CTRs are a form of warrantless search and seizure of private financial records. Fifty years ago, the Supreme Court narrowly upheld the constitutionality of these reporting requirements, arguing that Americans lose their right to a warrant with individual suspicion when they hand their private information over to third parties. We’ve [written extensively](https://www.coincenter.org/electronic-cash-decentralized-exchange-and-the-constitution/) why the continued constitutionality of these policies is in doubt.

On December 1st, [**Elliptic**](https://twitter.com/elliptic/status/1333770216375980041) had published the '[takeaways](https://archive.vn/K8I2Y)' from [a conversation](https://archive.vn/4cvQ0) between their CEO [Simone Maini](https://archive.vn/NmwRZ) and Blanco. He claimed that FinCEN "has received 96,000 crypto-related SARs since 2013." Maini warned that "it’s best to stay on FinCEN’s good side and be proactive in following their guidance."
{: style="text-align: justify;"}

> “If you do business in whole or in substantial part in the United States, you fall under our regulations. Period,” Director Blanco said. “If you’ve got to think about it, that means you fall under our regulations and we expect not only that you’re going to register, but that you’re going to comply with all the AML/CFT obligations in the United States.”
>
> Director Blanco’s message was clear: crypto businesses need to ask for permission, not forgiveness, when expanding into new markets and business lines. 
>
> “Asking for forgiveness is going to be a big problem,” he said.

Of course, the original American [patriots](https://www.merriam-webster.com/dictionary/patriot) who protested [general searches of private property and invasions of privacy](https://www.law.cornell.edu/constitution/fourth_amendment) by the British asked neither for permission nor forgiveness. Permissionlessness is the reason that Bitcoin, and the United States, came to exist at all. Even [**Chainalysis**](https://twitter.com/chainalysis/status/1341466904964296714)' regulatory team, while still engaging in some [ass-kissing](https://twitter.com/chainalysis/status/1341466934580293633), commented that "[efforts to improve enforcement should be driven by what would actually improve the effectiveness of the system, not by adding box-checking compliance requirements](https://blog.chainalysis.com/reports/treasury-department-nprm-unhosted-wallets-2020)."
{: style="text-align: justify;"}

> The proposed requirements go beyond the level of reporting and verification that exists in traditional financial services. The collection of large amounts of personal data on citizens transacting normally will not further the fight against illicit proceeds, as demonstrated by the use of unhosted wallets. It places an undue burden on regulators and the industry to collect and manage this data when there are more urgent vulnerabilities in cryptocurrencies, which can be addressed using the power and transparency of the blockchain. 

On December 9th, U.S. congressmen [Warren Davidson](https://twitter.com/WarrenDavidson/status/1336804544320327683), [Tom Emmer](https://twitter.com/RepTomEmmer), [Ted Budd](https://twitter.com/RepTedBudd), and [Scott Perry](https://twitter.com/RepScottPerry) wrote a letter to U.S. Treasury Secretary Mnuchin "regarding reports that the Treasury Department is considering issuing regulations that would restrict the use of self-hosted wallets." **Update:** Emmer and seven other members of Congress, including [Tulsi Gabbard](https://twitter.com/TulsiGabbard), sent [an additional letter](https://www.coincenter.org/app/uploads/2020/12/Congressional-Letter-to-Treasury-123120.pdf) on New Year's Eve "[requesting an extension of the truncated 15 day comment period](https://www.coincenter.org/congress-warns-treasury-on-unusually-short-cryptocurrency-short-rulemaking/)" to 60 days.
{: style="text-align: justify;"}

> The contemplated regulation would not meaningfully support law enforcement, while it would raise privacy concerns and place impractical regulatory burdens on digital asset users and companies... Eliminating the middleman through the use of self-hosted wallets means that consumers can maintain privacy and transact freely, which is critically important as individuals increasingly conduct their financial lives digitially. Such freedom stands in stark contrast to China's digital yuan, where citizens' transactions are surveilled and transactions involving disfavored individuals or activities can be censored."

On December 21st, Bitcoin developer [Matt Corallo](https://twitter.com/TheBlueMatt/status/1341084526123102208), the [**Electronic Frontier Foundation**](https://www.eff.org/deeplinks/2020/12/us-government-targeting-cryptocurrency-expand-reach-its-financial-surveillance), and [**Kraken**](https://twitter.com/krakenfx/status/1341082074107752448) published similar objections to FinCEN's proposed rulemaking, focusing on the detrimental effects to financial privacy and inclusion:
{: style="text-align: justify;"}

> Twenty-five percent of the U.S. population is currently unbanked or underbanked. Sadly, existing requirements do indeed prohibit financial institutions from opening accounts for homeless people, refugees and others in this 25% who do not have enough money to afford a mailing address.
>
> Existing requirements do, however, permit them to receive money from those who can afford to pay account maintenance fees and live in neighborhoods that attract physical branches. The proposed rule would go beyond existing requirements to literally outlaw people sending money to the less fortunate using their financial institutions.
>
> The proposed rule does not just reserve today’s financial system for the wealthy. It also seeks to wall off tomorrow’s financial system from the poor. Beyond just prohibiting transactions with humans without home addresses, the proposed rule would prohibit financial institutions from sending virtual currency to smart contracts, which have no name or physical location to begin with.

On the same day, it was [reported](https://archive.is/8FHWW) by Senator [Ron Wyden](https://twitter.com/RonWyden/status/1341417455541837828) that the Treasury Department had "suffered a serious breach, beginning in July, the full depth of which isn’t known" -- though at least "dozens of email accounts were compromised,” including those of "the most senior officials." Wyden noted that this should "put an end to any plan that weakens encryption." [Andrea O'Sullivan](https://twitter.com/anjiecast/status/1341378699954970625) also wrote for [**Reason**](https://reason.com/2020/12/22/the-massive-solarwinds-hack-wont-stop-the-feds-from-wanting-all-your-data/): "Now that we see the Treasury Department is apparently riddled with cybersecurity holes, we have even greater reason to resist the expansion of its financial surveillance programs."
{: style="text-align: justify;"}

[**Fight For The Future**](https://twitter.com/fightfortheftr/status/1341778531026649088) launched [a campaign for easily sending comments to FinCEN](https://www.stopfinancialsurveillance.org/). Compounding the reported cybersecurity breach and midnight period time constraints, lawyer [Jake Chervinsky](https://twitter.com/jchervinsky/status/1343951378281082881) discovered that "on Tuesdays & Thursdays," the government's website "redirects to a new beta site & breaks existing links in the process." The notification message indeed reads:
{: style="text-align: justify;"}

> Regulations.gov will redirect users to beta.regulations.gov on Tuesdays and Thursdays for 24 hours starting at 8am ET. Please note that all comments submitted through Beta, both during the redirect and regular operations, are provided to agencies. 

:information_source: For legal discussion on these policy changes that may affect Bitcoin privacy, see [episode #292](https://www.whatbitcoindid.com/podcast/fincens-discriminatory-rulemaking) of the [**What Bitcoin Did**](https://twitter.com/WhatBitcoinDid/status/1343181238002061314) podcast with [Jerry Brito](https://www.coincenter.org/people/jerry-brito/) and [Peter van Valkenburgh](https://www.coincenter.org/people/peter-van-valkenburgh/) from **Coin Center**.
{: .notice--success}

## December 12th - WASABI WALLET 2.0 UPDATE

In [TMIBP06](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/November_2020/#november-5th---wasabi-wallet-20), I covered [**Wasabi**](https://twitter.com/wasabiwallet/status/1338155867972177921)'s announcement of their next-generation wallet software with "a complete UI redesign and significant UX improvements." This month, Ficsór provided [more information on the status of the work](https://blog.wasabiwallet.io/wasabi-wallet-2-update/) and a preview of the new interface, still estimating that the release will be ready in 8 to 9 months.
{: style="text-align: justify;"}

> We're currently trying to [come to consensus](https://github.com/zkSNACKs/WabiSabi/pull/88) on just how many of our ideas we should include in the first version. But what I can already say, is that our starting results are miraculous: we are already able to create coinjoins that are both orders of magnitude cheaper and faster than Wasabi 1.0 coinjoins. Red changes will rarely be created, nor will there be a need to have a minimum amount to coinjoin anymore. At last, the UTXO set of wallets will be more diverse and coinjoins won't inflate the number of coins in wallets anymore.

Regarding WabiSabi, they are "still awaiting peer review from the Academic community." Ficsór talked more about these "UI and protocol changes" in Wasabi, as well as base layer changes coming to Bitcoin, on [episode #112](https://www.unhashedpodcast.com/episodes/wasabi-wallet-privacy-adam-ficsor) of the [**Unhashed**](https://twitter.com/UnhashedPodcast/status/1334901697064411137) podcast. [Yuval Kogman](https://github.com/nothingmuch), another co-developer, spoke on [a panel](https://podcast.advancingbitcoin.com/1450198/6730393-bridging-the-gap-with-daniel-nordh-yuval-kogman-bosch) about UX design for the [**Advancing Bitcoin**](https://twitter.com/advbitcoin/status/1335977107571298304) podcast.
{: style="text-align: justify;"}

On December 28th, **Wasabi** also published [a year-end review](https://blog.wasabiwallet.io/wasabis-year-end-review/).

## December 14th - USER EXPERIENCE RESEARCH GRANT

[**Square Crypto**](https://twitter.com/sqcrypto/status/1338529455636172803) announced their 20th grant to UX designer [Patrícia Estevão](https://twitter.com/patestevao/status/1338540274629349377), to "help answer fundamental questions about how bitcoin is used to guide future design and development decisions." Estevão has previously published several infographics and [videos](https://twitter.com/patestevao/status/1154117549547823104) related to Bitcoin privacy, including '[Privacy and UTXO](https://web.archive.org/web/20201109023450/https://www.bitcoindesigned.com/infographics/privacy-and-utxo-part-1/),' '[Privacy and Light Wallets](https://twitter.com/patestevao/status/1045393299966775296),' and '[Wasabi Wallet](https://patestevao.com/work/wasabi/).' The results of her research will appear in the [Bitcoin Design Guide](https://github.com/BitcoinDesign/Guide).
{: style="text-align: justify;"}

In November, software engineer [Conor Okus](https://twitter.com/ConorOkus) had interviewed [Johns Beharry](https://github.com/johnsBeharry) for the [fourth episode](https://podcast.advancingbitcoin.com/1450198/6612919) of the [**Advancing Bitcoin**](https://twitter.com/advbitcoin/status/1333442707352670209) podcast. He spoke about his personal experience in the Caribbean with bitcoin, in comparison to wire transfers and PayPal. Beharry had also received [a grant](https://twitter.com/sqcrypto/status/1299013694639271938) to work on the design guide, focusing on the payment protocols section and making it easier "to grapple with on-chain, layer 2, CoinJoins, PayJoins, and PSBTs."
{: style="text-align: justify;"}

> Why is it important to look at the user experience of privacy, also in the context of bitcoin? So that those people can have a choice in the matter. It is about choice, being able to choose how private [I want to be].

## December 16th - COINKITE BITCOIN SCHOOL: JOINMARKET

[**Coinkite**](https://twitter.com/COLDCARDwallet/status/1339299857509609474), in collaboration with '[Keep It Simple Bitcoin](https://twitter.com/KISBitcoin),' published another installment in their educational video series: "[How To Use JoinMarket - Bitcoin Privacy Software](https://youtu.be/9COdlsh4inY)." It covers installation via the command line, setup, participating in CoinJoins, and the yield generator.
{: style="text-align: justify;"}

## December 20th - LEDGER DATA DUMP

In [TMIBP02](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-29th---ledger-data-breach), I covered the discovery of a data breach from the [e-commerce and marketing database(s)](https://support.ledger.com/hc/en-us/articles/360015559320-E-commerce-and-Marketing-data-breach-FAQ) of hardware wallet company [**Ledger**](https://www.ledger.com/addressing-the-july-2020-e-commerce-and-marketing-data-breach). At the time, they asserted it consisted "mostly of email addresses, but with a subset including also contact and order details such as first and last name, postal address, email address and phone number." While it is not known whether they obtained it firsthand or secondhand, a hacker has since dumped over one million email addresses and 272,853 shipping orders on [RaidForums](https://archive.is/RdBtk), claiming that the dataset had been selling for 5 BTC. To help customers check whether they were affected by the breach, it was [mirrored](https://haveibeenpwned.com/PwnedWebsites#Ledger) on [**HaveIBeenPwned**](https://twitter.com/haveibeenpwned/status/1340770769106731008).
{: style="text-align: justify;"}

[**Ledger**](https://twitter.com/Ledger/status/1340769565639233536) soon tentatively confirmed that this was real customer information. They claimed to have "hired a new Chief Information Security Officer (CISO)," "thoroughly reviewed our data policy," "executed penetration tests and forensic analysis with external security firms," and "are continuously working with law enforcement to prosecute hackers and stop these scammers." In the days that followed, they [shared advice](https://twitter.com/Ledger/status/1341451918309273600) about what to do, acknowledging that "[some of you are being personally threatened](https://www.ledger.com/blog/6-ways-to-face-the-data-breach)." CEO [Pascal Gauthier](https://twitter.com/_pgauthier/status/1341084660953194497) published [a letter to customers](https://www.ledger.com/message-ledgers-ceo-data-leak/) and spoke on [episode #290](https://www.whatbitcoindid.com/podcast/ledger-hack-what-happened-with-pascal-gauthier) of [**What Bitcoin Did**](https://twitter.com/WhatBitcoinDid/status/1341347347121328129). While he blamed tax reporting regulations as the cause of why they held on to such data long-term, he admitted that they could have stored it offline instead.
{: style="text-align: justify;"}

:warning: If you know or suspect that you were impacted by this breach, I recommend reading Kraken's "[Security Advisory: Mobile Phones](https://blog.kraken.com/post/219/security-advisory-mobile-phones/)," Jameson Lopp's "[A Home Defense Primer](https://blog.keys.casa/a-home-defense-primer/)," and "[A Modest Privacy Protection Proposal](https://blog.lopp.net/modest-privacy-protection-proposal/)."
{: .notice--warning}

## December 21st - FINANCIAL CANCEL CULTURE

I gave a one-hour presentation for the [Bitcoin Munich meetup](https://www.meetup.com/Bitcoin-Munich/events/273866737/) on "[Financial Cancel Culture](https://youtu.be/ql-HhzG4cQE)," a term that I used while [covering](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/#october-19th---chainalysis-and-crypto-exposed-persons) the growing interest of traditional financial surveillance and compliance businesses in blockchain analysis. My slides are available [here](https://einzelgaengerinmotte.files.wordpress.com/2020/12/financial-cancel-culture.pdf). The second half of the meetup consisted of questions and group debate.
{: style="text-align: justify;"}

> The focus of the discussion will be financial censorship: how and why people are being "cancelled" from having bank accounts, often without due process or allegations of illegality, and whether Bitcoin may be of help. We will also discuss resisting regulatory capture, the emergence of "blockchain analysis" aka blockchain *surveillance* companies, and much more.

On December 29th, [Matt Odell](https://twitter.com/matt_odell/status/1344055687400189952) hosted a similar discussion in the second episode of [**Citadel Dispatch**](https://youtu.be/9t8WsT9NpUU) with analyst [Ergo](https://twitter.com/ErgoBTC) and the creator of the [Bitcoin Q+A](https://twitter.com/BitcoinQ_A) guides. In addition to reviewing various privacy tools and strategies, they talked about their experience using pseudonyms and why it's important -- as [Satoshi](https://bitcoin.org/bitcoin.pdf) originally advised -- to keep your identity and financial history separate as much as possible.
{: style="text-align: justify;"}

> KYC is fucking insidious. What we see is, KYC is infecting our whole lives. Bitcoiners don't realise, they think it's a 'bitcoin issue.' It's not a 'bitcoin issue,' you've just come to accept it in every other aspect of your life. Where bitcoin is the one aspect where maybe you questioned it, maybe you think, "Is it wrong?"

:information_source: For more on the culture of pseudonymity and Bitcoin, see [Gigi](https://twitter.com/dergigi)'s essay "[True Names Not Required: On Identity and Pseudonymity in Cyberspace](https://www.citadel21.com/true-names-not-required)," inspired by Vernor Vinge's classic cyberpunk science fiction novel "[True Names](https://ia801004.us.archive.org/0/items/truenamesvingevernor/True%20Names%20-%20Vinge%2C%20Vernor.pdf)."
{: .notice--success}

## December 23rd - RELEASE CANDIDATE TESTING

In [TMIBP05](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/#october-11th---bip155-and-tor-onions-v3), I highlighted that Bitcoin Core v0.21 would add support for Tor's v3 hidden service addresses. On December 23rd, the [**Bitcoin Core PR Review Club**](https://twitter.com/BitcoinCorePRs/status/1341159717146677249) hosted [a special edition meeting](https://bitcoincore.reviews/rc-testing) with [Jarol Rodriguez](https://github.com/jarolrod) to organise release candidate testers. The [second release candidate](https://lists.linuxfoundation.org/pipermail/bitcoin-core-dev/2020-November/000094.html) had been published at the end of November. The final version has not been [scheduled](https://bitcoincore.org/en/lifecycle/#schedule) for release yet, though it had previously been [targeted](https://github.com/bitcoin/bitcoin/issues/18947) for sometime this month.
{: style="text-align: justify;"}

## December 24th - FARCASTER: ATOMIC SWAPS WITH MONERO

Monero researcher Joël ‘[h4sh3d](https://github.com/h4sh3d)’ Gugger gave an update via [Reddit](https://www.reddit.com/r/Monero/comments/kjgi5g/farcaster_atomicswap_community_update_december/) on the cross-chain atomic swap client and protocol between Bitcoin and Monero, "codename Farcaster," which I covered in [TMIBP03](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2020/#august-8th---cross-chain-atomic-swaps-with-monero) and [TMIBP05](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/#october-16th---crowdfunding-atomic-swaps-with-monero). He wrote that a "bitcoin-genie" had encouraged them to work on "how to use Taproot outputs and Schnorr signatures" first instead of ECDSA:
{: style="text-align: justify;"}

> That improves privacy of the swaps: in the most common swap outcome -- the successful case -- no script, nor the existence of a script hidden behind that pubkey, will ever be revealed to the Bitcoin blockchain, and makes Bitcoin transactions cheaper. Beat that! For more details, visit here. Another benefit: Schnorr adaptor signatures are simple, and easy to get to production-level, audited code -- that is harder to accomplish using ECDSA adaptor signatures.
>
> That said, the genie's wild prediction for Schnorr/Taproot softfork activation on bitcoin is "Q4 2021".
>
> These changes will influence our list of deliverables: possibly no ECDSA, but instead Schnorr signatures -- before it was only ECDSA signatures.

You can follow the project [here](https://github.com/farcaster-project).

## December 25th - MERRY MIXMAS

[**Samourai Wallet**](https://twitter.com/SamouraiWallet/status/1342044130206244865) is offering a 50% [discount](https://support.samourai.io/article/88-add-a-discount-code-scode-to-whirlpool) on [Whirlpool](https://www.samouraiwallet.com/whirlpool) mixing fees until January 1st 2021.
{: style="text-align: justify;"}

:information_source: If you are new to CoinJoins and Whirlpool, see [Bitcoin Q+A](https://twitter.com/BitcoinQ_A/status/1292095078752813059)'s user guide "[Whirlpool + Postmix Spending FAQ](https://www.bitcoinqna.com/post/whirlpool-faq)."
{: .notice--success}

## December 26th - "A BEST GUESS": BITBARGAIN CLOSES

The U.K.-based marketplace [**BitBargain**](https://twitter.com/BitBargain) ceased to allow trading and deposits, following a previously published [closure schedule](https://blog.bitbargain.com/post/636272790445637632/closing-down-before-regulations) that aligned with deadlines for registering (or else) according to the [fifth European anti-money laundering directive](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32018L0843), and the [Financial Conduct Authority](https://archive.is/I7MB2) (FCA) "advising customers of cryptoasset firms which should have applied to the FCA, but have not done so, to withdraw their cryptoassets or money before 10 January 2021."
{: style="text-align: justify;"}

In [a long goodbye letter](https://blog.bitbargain.com/post/638504004285054976/goodbye) published on Christmas Day, the CEO wrote about his experience running the platform since 2012, and why "it did not feel right at all" to continue operating. He also commented on the role and (in)effectiveness of blockchain surveillance companies: "Most of the requests we did not comply with originated from blockchain analysis based information."
{: style="text-align: justify;"}

> Blockchain analysis is essentially a best guess of a proprietary algorithm which scans the blockchain, the web, the dark web and all kinds of data sources, then tries to connect different addresses, group them into clusters, make a guess as to what entity owns the cluster, then present information about where those wallets sent coins and where they received coins from. Busting down the front door of someone based on such approximations is highly inappropriate and unreasonable in my opinion, though it is an accepted practice in the United States for example. It is important to mention that some of the BA based requests asked for information we did not have. This means that the specific tool they used incorrectly claimed that a transaction or address belonged to us.
>
> Those in power want as much control over crypto as they have over your personal bank account. Some of them want this with good intentions without much consideration about balancing their power against constitutional rights of the people, others need it only to stay in power. They demanded a solution. Predictably, the industry jumped right on it and came up with something that would pass. And it’s good business. Some of these companies ask for tens of thousands of dollars a year to give you access to their database and tools. And they’re not all bad. Most of the time you can figure out the name of the exchange by simply providing a transaction ID. You can check out an exchange and see how much coin is going to dark web suspects. Overall, it’s a good tool to have, but at the end of the day it’s still just a best guess by a computer software.

**Thanks for reading!** Feel free to :bookmark: [bookmark](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/feed.xml) or [subscribe](https://github.com/Enegnei/This-Month-In-Bitcoin-Privacy) to catch the next edition of 'This Month in Bitcoin Privacy.'
{: .notice--info}