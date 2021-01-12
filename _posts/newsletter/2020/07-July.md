---
title: "July 2020"
date: 2020-07-31
last_modified_at: 2020-11-29
classes: wide
  
tags:
  - Address Reuse
  - Blockchain Analysis
  - Blockchain Surveillance
  - Chainalysis
  - Cypherpunk
  - Ciphertrace
  - Coinbase
  - Data Breach
  - Department of Treasury
  - Drug Enforcement Administration
  - Elliptic
  - Financial Action Task Force
  - Global Digital Finance
  - Intelligence Community
  - Internal Revenue Service
  - Jude Milhon
  - Ledger
  - Lightning Network
  - Neutrino
  - Plaid
  - Samourai Wallet
  - Schnorr Signatures
  - Secret Service
  - Shoshana Zuboff
  - Surveillance Capitalism
  - Taproot
  - Third-Party Doctrine
  - Tor Network
  
---

Welcome to the second issue of '[This Month in Bitcoin Privacy](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/about/)' newsletter. Enjoy!

<p style="font-size: 0.9rem;font-style: italic;"><img style="display: block;" src="https://live.staticflickr.com/7624/27618311225_37c3591445_b.jpg" alt="Moth"><a href="https://www.flickr.com/photos/114195717@N03/27618311225">"Moth"</a><span> by <a href="https://www.flickr.com/photos/114195717@N03">mark.tyndall1023</a></span> is licensed under <a href="https://creativecommons.org/licenses/by/2.0/?ref=ccsearch&atype=html" style="margin-right: 5px;">CC BY 2.0</a><a href="https://creativecommons.org/licenses/by/2.0/?ref=ccsearch&atype=html" target="_blank" rel="noopener noreferrer" style="display: inline-block;white-space: none;margin-top: 2px;margin-left: 3px;height: 22px !important;"><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc_icon.svg" /><img style="height: inherit;margin-right: 3px;display: inline-block;" src="https://search.creativecommons.org/static/img/cc-by_icon.svg" /></a></p>

### Table of Contents

1. [IRS Seeking to Trace Privacy Coins, Lightning](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#june-30th---irs-seeking-to-trace-privacy-coins-lightning)
2. [Class Action Lawsuit Against Plaid Inc.](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-1st---class-action-lawsuit-against-plaid-inc)
3. [The End of Surveillance Capitalism?](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-6th---the-end-of-surveillance-capitalism)
4. [Chainalysis and the Boiling Frog](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-7th---chainalysis-and-the-boiling-frog)
5. [Hyperonionization](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-8th---hyperonionization)
6. [Coinbase Contracting with Secret Service, IRS](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-11th---coinbase-contracting-with-secret-service-irs)
7. [Cybergrrrls: The Origin of "Cypherpunk"](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-12th---cybergrrrls-the-origin-of-cypherpunk)
8. [Junk in the Trunc: Lightning Privacy](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-13th---junk-in-the-trunc-lightning-privacy)
9. [Samourai Wallet Address Reuse](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-14th---samourai-wallet-address-reuse)
10. [Fourth Amendment Lawsuit Against IRS](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-15th---fourth-amendment-lawsuit-against-irs)
11. [How I Knew Your Customer: FATF Compliance](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-20th---how-i-knew-your-customer-fatf-compliance)
12. [Schnorr / Taproot Activation](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-24th---schnorr--taproot-activation)
13. [Ledger Data Breach](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/July_2020/#july-29th---ledger-data-breach)

## June 30th - IRS SEEKING TO TRACE PRIVACY COINS, LIGHTNING

The same IRS division we highlighted in [the last edition](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-5th---coinbase-offers-blockchain-surveillance-to-irs-dea) published a [request for information](https://archive.is/Vrcce) regarding "systems that will allow developers and testers to conduct investigative research of distributed ledger transactions involving privacy cryptocurrency coins," "Layer 2 off-chain protocol networks," "Side-chains," and "tracing challenges following the integration of the Schnorr Signature algorithm."
{: style="text-align: justify;"}

They [write](https://einzelgaengerinmotte.files.wordpress.com/2020/07/cryptocurrencytracing-rfifinal.pdf) that they are seeking "an interactive prototype that provides a GUI for clustering transactions involving a user (similar to tools provided by companies like Chainalysis, CipherTrace, Coinbase, and Elliptic but for the privacy coins and obfuscation technologies)," with "OSINT information/research about identified users," and "a mechanism for sharing investigative research between investigators."
{: style="text-align: justify;"}

Regarding the Lightning Network, they suggest that "there is potential to develop solutions for tracking illicit actors" by "building off of monitoring code" like Lightning Lab's [Lndmon](https://github.com/lightninglabs/lndmon). As for Schnorr signatures, they present "a new challenge for investigative support services with no COTS [commercial off-the-shelf] solutions publicly available." Though [Schnorr signatures](https://github.com/sipa/bips/blob/bip-schnorr/bip-schnorr.mediawiki) have not been added to Bitcoin yet, "this integration has multiple benefits to users including a reduction in the distributed ledger storage requirements as well as enhanced privacy to protect users, but this also inhibits the effectiveness of certain traditional tracing clustering algorithms."
{: style="text-align: justify;"}

The deadline for responding to their request was July 14th.

:information_source: Check out the [Bitcoin Optech Schnorr Taproot Workshop](https://bitcoinops.org/en/schorr-taproot-workshop/) resources to learn more about Schnorr signatures.
{: .notice--success}

## July 1st - CLASS ACTION LAWSUIT AGAINST PLAID INC.

Class action lawsuits have been filed against [**Plaid**](https://plaid.com/), a financial technology and identity verification company [recently acquired by Visa](https://www.cnbc.com/2020/01/13/visa-to-acquire-plaid-the-fintech-powering-venmo-and-other-banking-apps-for-5point3-billion.html) for $5.3 billion. Their service "provides an easy way for you to connect your bank account and other financial accounts to software applications that can help you do things like save for retirement, manage your spending, streamline credit applications, or transfer money." While it is still unclear how many payment applications have embedded Plaid (hence the lawsuit), a few of the known integrations include [Venmo](https://help.venmo.com/hc/en-us/articles/221073067-Verifying-Your-Bank-Account), [Coinbase](https://help.coinbase.com/en/coinbase/privacy-and-security/other/how-is-my-bank-account-information-protected), [Gemini](https://blog.plaid.com/gemini-customer-story/), [Square Cash](https://plaid.com/what-is-plaid/), [Stripe](https://plaid.com/docs/stripe/), [Uphold](https://support.uphold.com/hc/en-us/articles/360033539172-What-is-Plaid-), and [Gusto](https://support.gusto.com/account-setup-maintenance/enter-account-info/banking/1066219681/Verify-your-bank-account-using-instant-bank-verification-IBV.htm).
{: style="text-align: justify;"}

> Imagine there is a company that knows every dollar you deposit or withdraw, every dollar you charge or pay to your credit card, and every dollar you put away for retirement, within hours after you make the transaction. Imagine this includes every book or movie ticket or meal you purchase, every bill you pay to a doctor or hospital, and every payment you make (or miss) on your mortgage, student loan or credit card bill. Imagine this company maintains a file on you containing all of this information going back five years.
>
> ... Imagine you never heard of this company at all. ([*National Law Review*](https://www.natlawreview.com/article/fintech-startup-plaid-inc-hit-5m-class-action-lawsuit))

The first, launched in May by [Herrera Purdy LLP](https://herrerapurdy.com/consumer-banking-data-privacy-violations-lawsuit-filed-against-plaid-inc-on-behalf-of-users-of-venmo-and-other-fintech-applications/), [Lieff Cabraser Heimann & Bernstein LLP](https://www.lieffcabraser.com/privacy/smartphone-pay-apps/), and [Burns Charest LLP](https://www.burnscharest.com/news/consumer-banking-data-privacy-violations-lawsuit-filed-against-plaid-inc-on-behalf-of-users-of-venmo-and-other-fintech-applications/), alleges that Plaid "violates consumer privacy and computer data protection laws by collecting consumers’ sensitive bank login information" and using "the credentials to access and capture years of transaction and other confidential data from all of the consumers’ accounts with the bank, all without consumers’ knowledge or consent."
{: style="text-align: justify;"}

> Plaid was founded in 2012 by Zach Perret and William Hockey. The two initially founded Plaid with the intention of building a consumer-facing fintech app. By early 2013, however, they pivoted to building a behind-the-scenes data aggregator and data brokerage operation.

The initial complaint [*Cottle et al. v. Plaid Inc.*](https://www.classaction.org/media/cottle-et-al-v-plaid-inc.pdf) relates how the plaintiffs were unaware of Plaid's involvement or "extensive data collection" practices when they connected their bank accounts to Venmo during 2019 and 2016 respectively. Since becoming informed, they both claim to regularly monitor their credit and bank accounts for "evidence of identity theft and fraud" while dealing with "emotional distress, including anxiety, concern, and unease about unauthorized parties accessing, storing, selling, and using [their] most private financial information and intruding upon [their] private affairs and concerns."
{: style="text-align: justify;"}

Their concerns are well-founded, given that depending on the extent of permissions granted by the payment application, [Plaid](https://plaid.com/legal/#end-user-privacy-policy) potentially has access to "the following types of identifiers, commercial information, and other personal information" that they collect "in general":
{: style="text-align: justify;"}

> Account information, including financial institution name, account name, account type, account ownership, branch number, IBAN, BIC, and account and routing number; Information about an account balance, including current and available balance; Information about credit accounts, including due dates, balances owed, payment amounts and dates, transaction history, credit limit, repayment status, and interest rate; Information about loan accounts, including due dates, repayment status, balances, payment amounts and dates, interest rate, guarantor, loan type, payment plan, and terms; Information about investment accounts, including transaction information, type of asset, identifying details about the asset, quantity, price, fees, and cost basis; Identifiers and information about the account owner(s), including name, email address, phone number, date of birth, and address information; Information about account transactions, including amount, date, payee, type, quantity, price, location, involved securities, and a description of the transaction; and Professional information, including information about your employer, in limited cases where you’ve connected your payroll accounts.

> The data collected from your financial accounts includes information from all your accounts (e.g., checking, savings, and credit card) accessible through a single set of account credentials.

In addition to collecting "electronic network activity information" such as "IP address, hardware model, operating system," they "may use the information we collect about you to derive inferences. For example, we may infer your location or your projected income." In other words, complete knowledge of your financial history "going back up to five years," and the means to project your financial future.
{: style="text-align: justify;"}

On July 12th, I participated in [an interview](https://castbox.fm/episode/Block-Digest-Special-Edition---Jack-Mallers-(Strike)-id1192324-id287209099) with [Jack Mallers](https://twitter.com/JackMallers), founder of [Zap Solutions](https://zaphq.io/), and discussed [Strike's privacy policy](https://beta.strike.me/privacy) in the latter half. Regarding his integration of Plaid, Mallers said this relationship had formed "entirely separate" from the partnership with Visa. They "don't install those permissions in our Plaid widget," but rather "the very bare minimum of what we need," suggesting that payment app providers have some choice as to how extensive the data collection should be. He also stated that Plaid had recently put them through a more extensive vetting process for data handling. "Clearly, someone came down on them."
{: style="text-align: justify;"}

On July 17th, [another complaint](https://www.courtlistener.com/recap/gov.uscourts.cand.362606/gov.uscourts.cand.362606.1.0.pdf) was filed by [Tostrud Law Group](http://tostrudlaw.com) and [Glancy Prongay & Murray LLP](https://www.glancylaw.com), on behalf of four plaintiffs who were customers of Venmo. The allegations are very similar.

> In a 2019 interview, Perret revealed that the name Plaid refers to an algorithm he and Hockey devised to conduct “cross-user comparisons”: comparing users’ transaction patterns to those of other users against the backdrop of Plaid’s database of merchants. The overlapping patterns resembled a crosshatch pattern — hence the name.[<sup>6</sup>](https://youtu.be/sgnCs34mopw?t=643)

If you are a customer who has "linked your bank account for use with a pay app or other online service and have concerns about the security and privacy," at least one of the law firms has [an open contact form](https://www.lieffcabraser.com/privacy/smartphone-pay-apps/) and "welcome[s] the chance to talk to you about your experience and your legal rights," with "no charge or obligation for our review of your potential case."
{: style="text-align: justify;"}

## July 6th - THE END OF SURVEILLANCE CAPITALISM?

Tyler Winklevoss, co-founder and CEO of the Gemini exchange, tweeted that "[Bitcoin marks the beginning of the end for surveillance capitalism](https://twitter.com/tylerwinklevoss/status/1280135411503857664)." Of course, it was swiftly pointed out that Gemini has been [a client of Chainalysis](https://twitter.com/Gemini/status/1121121504991825921); they are also [a client of Plaid](https://blog.plaid.com/gemini-customer-story/). The following day, commenting on the response he had received, Winklevoss said he found it "[staggering how many folks on my feed think that surveillance capitalism = government surveillance](https://twitter.com/tylerwinklevoss/status/1280267858015109120)," because governments "[may consume but don’t commoditize or profit](https://twitter.com/tylerwinklevoss/status/1280271454093881344)."
{: style="text-align: justify;"}

While it may seem like a red herring to bring up the reality of Gemini's operations, I think it is relevant given their prior arguments about the necessity of regulation for mass adoption of bitcoin, regulations requiring the collection and sharing of as much personally identifying information about customers as possible. So let's look at how blockchain "analysis" fits within surveillance capitalism, a term popularised by [Shoshana Zuboff](https://shoshanazuboff.com/book/). (Since the twins are fond of pointing out that they are "men of Harvard," they may care to note that [Zuboff is also a Harvard graduate](https://www.hbs.edu/faculty/Pages/profile.aspx?facId=6582).)
{: style="text-align: justify;"}

Before releasing her massive 700-page tome last year, "[The Age of Surveillance Capitalism: The Fight for a Human Future at the New Frontier of Power](https://www.publicaffairsbooks.com/titles/shoshana-zuboff/the-age-of-surveillance-capitalism/9781610395694/)," Zuboff had published [a research article](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2594754) exploring surveillance capitalism and how its "architecture produces a distributed and largely uncontested new expression of power that I christen: ‘Big Other.’" The surveillance capitalist essentially "aims to predict and modify human behavior as a means to produce revenue and market control," through an "extractive project founded on formal indifference to the populations that comprise both its data sources and its ultimate targets."
{: style="text-align: justify;"}

> The extractive processes that make big data possible typically occur in the absence of dialogue or consent, despite the fact that they signal both facts and subjectivities of individual lives. These subjectivities travel a hidden path to aggregation and decontextualization, despite the fact that they are produced as intimate and immediate, tied to individual projects and contexts (Nissembaum, 2011).

Such businesses are founded on "‘computer-mediated’ work from earlier generations of mechanization and automation designed to substitute for or simplify human labor." What is blockchain surveillance if not one facet of the growing trend to automate compliance, crime investigation, and law enforcement tasks, even if it entails great sacrifices of privacy, financial freedom, and due process along the way? Government surveillance simultaneously supports and rests on the shoulder of the surveillance capitalist (or should I say surveillance [Cantillonist](https://mattstoller.substack.com/p/the-cantillon-effect-why-wall-street)): companies maintain the tools that the state would have otherwise not had the skill or knowledge to build, and in return the state protects them from true public scrutiny and accountability as long as their service can "overlap state security interests."
{: style="text-align: justify;"}

> The automated ubiquitous architecture of Big Other, its derivation in surveillance assets, and its function as pervasive surveillance, highlights other surprising new features of this logic of accumulation. It undermines the historical relationship between markets and democracies, as it structures the firm as formally indifferent to and radically distant from its populations. Surveillance capitalism is immune to the traditional reciprocities in which populations and capitalists needed one another for employment and consumption. In this new model, populations are targets of data extraction. This radical disembedding from the social is another aspect of surveillance capitalism’s anti-democratic character. Under surveillance capitalism, democracy no longer functions as a means to prosperity; democracy
threatens surveillance revenues.

Financial surveillance of the Bitcoin blockchain is an example of "the informating of the economy," as "a pervasive and continuous recording of the details of each transaction." While the conflation of surveillance capitalism and government surveillance may seem "staggering" to some, their cooperative relationship is quite evident.
{: style="text-align: justify;"}

> In this vision, computer mediation renders an economy transparent and knowable in new ways... It was precisely the unknowability of the universe of market transactions that anchored Hayek’s claims for the necessity of radical freedom from state intervention or regulation.

Besides the fact that blockchain surveillance companies and their custodial clients are doing the opposite of proving Tyler's point thus far, I do believe that [Bitcoin can impact](https://einzelgaengerinmotte.files.wordpress.com/2019/10/lightning-talk-final-draft.pdf) the supremacy of [the prevailing monetization model of the internet](https://youtu.be/a-5pqxrLScY?t=416), which remains dependent "upon the acquisition of user data as the raw material for proprietary analyses and algorithm production that could sell and target advertising through a unique auction model with ever more precision and success." The attempts of the fiat banking system to merge with the internet come bundled with extreme centralization, privacy holes, and censorship. May we reach the day when [*402 Payment Required*](https://tools.ietf.org/html/rfc7231#section-6.5.2) is no longer merely "reserved for future use."
{: style="text-align: justify;"}

## July 7th - CHAINALYSIS AND THE BOILING FROG

[**Chainalysis**](https://twitter.com/chainalysis/status/1280516288775847946) announced via [PR Newswire](https://www.prnewswire.com/news-releases/chainalysis-expands-series-b-to-49m-with-investment-from-ribbit-capital-and-sound-ventures-301089238.html) that they had "raised an additional $13M to expand its Series B round to $49M" from two California-based venture capital firms. [Ribbet Capital](https://www.linkedin.com/organization-guest/company/ribbit-capital) "invests globally in unique individuals and brands who aim to disrupt the financial services industry," with [portfolio companies](https://archive.is/1R2Q3) including Coinbase, Robinhood, and Xapo. [Sound Ventures](https://www.linkedin.com/organization-guest/company/sound-ventures) focuses "on early and mid stage private technology platforms."
{: style="text-align: justify;"}

> Over the past year, the company has continued to enhance its unrivaled blockchain data and foundational investigative product, Chainalysis Reactor, providing insights into how and why people move money across the world and growing revenue from new government customers by almost 400%.

The announcement also highlighted that Ribbet Capital's new [general partner](https://archive.vn/LjWtA), Sigal Mandelker, would become part of Chainalysis' board of advisors. According to [Forbes](https://archive.is/UbAtj), she "will meet with the Chainalysis team on an as-needed basis to share with them insights gleaned from her own past experience investigating crime that relies on blockchain." Prior to joining Ribbet in April, Mandelker had been serving as [under-secretary](https://web.archive.org/web/20180416215037/https://www.treasury.gov/about/organizational-structure/Pages/sigal_mandelker.aspx) for the [U.S. Department of Treasury's Office of Terrorism and Financial Intelligence](https://www.treasury.gov/about/organizational-structure/offices/Pages/Office-of-Terrorism-and-Financial-Intelligence.aspx) (TFI) from June 2017 until sometime near October 2019. [Reuters](https://www.reuters.com/article/us-usa-treasury-sanctions-idUSKBN1WH1Z0) reported that "Mandelker had approached Mnuchin," Secretary of the Treasury, "over the summer about her desire to return to the private sector." She was most well known for being "[one of the most powerful officials designing](https://www.theatlantic.com/politics/archive/2019/07/mandelker-iran-sanctions/594412/)" the Trump administration's "financial warfare" strategies against countries like Iran and Venezuela -- to the point where [**Codepink**](https://twitter.com/codepink/status/1179493509872660480) anti-war activists were [disrupting her talk](https://www.codepink.org/activists_disrupt_us_and_israeli_officials_at_nyc_event_calling_for_war_with_iran) only a week prior to her resignation announcement.
{: style="text-align: justify;"}

During CoinDesk's Consensus Conference last year, Mandelker had [delivered a speech](https://home.treasury.gov/news/press-releases/sm687) about how "bad actors are trying to leverage virtual currencies to make an end-run around our laws and regulations," and urged "the industry to prioritize compliance before choosing to bring a product or service to the market." She cited her prior experience leading "a team of prosecutors at the Department of Justice more than a decade ago that successfully prosecuted the digital currency E-Gold." Coincidentally, on July 2nd, the E-gold defendants have [petitioned](https://legalupdate.e-gold.com/2020/07/petition-for-writ-of-error-coram-nobis.html) [the court](https://einzelgaengerinmotte.files.wordpress.com/2020/07/211.pdf) "to issue a writ of error" [*coram nobis*](https://definitions.uslegal.com/w/writ-of-coram-nobis/) "and vacate, with prejudice, Petitioners’ convictions."
{: style="text-align: justify;"}

As [Deputy Assistant Attorney General in the Criminal Division of the Department of Justice](https://web.archive.org/web/20180416215037/https://www.treasury.gov/about/organizational-structure/Pages/sigal_mandelker.aspx), she had overseen "four major prosecutorial sections and a number of significant cross-border prosecutions involving cybersecurity, human rights, money laundering, and other national security and law enforcement priorities." She does not list any of them specifically. However, a year ago this month, the [Washington Post](https://archive.is/f4Luu) had reported that Mandelker was named as one of the "high-ranking Justice Department officials" who "approved of or were otherwise involved" in Jeffrey Epstein's so-called '[Florida deal](https://web.archive.org/web/20181128153832/https://www.miamiherald.com/news/local/article220097825.html).'
{: style="text-align: justify;"}

> Epstein, 66, was arrested about a week ago and charged federally with sexually abusing dozens of children from 2002 to 2005. His case has riveted the nation, in part because of his wealth and connections, and partly because of a plea deal he reached in 2008 to resolve similar allegations.
>
> The deal allowed Epstein to spend only about a year in jail and plead guilty only to state crimes, avoiding federal charges entirely. It was approved by then-U.S. Attorney Alex Acosta, who was later tapped to be President Trump’s labor secretary. Acosta resigned Friday amid the metastasizing controversy surrounding his handling of the case.
>
> ... Defense attorneys also argued, as they have in the past, that prosecutors are rehashing allegations for which Epstein has already served time. They noted that high-ranking Justice Department officials approved of or were otherwise involved in his agreement to avoid federal charges, including Mark Filip, [who was] deputy attorney general at the time; Alice Fisher, who led the department’s criminal division; John Roth, who worked in the criminal division and the deputy attorney general’s office; and Sigal Mandelker, who worked in the criminal division and now works at the Treasury Department.

In an interview with [National Public Radio](https://www.npr.org/2019/07/10/740159741/former-u-s-prosecutor-discusses-jeffrey-epsteins-2008-plea-deal) (NPR), former U.S. federal assistant attorney [Berit Berger](https://www.nbcnews.com/think/opinion/jeffrey-epstein-s-deal-federal-prosectors-wasn-t-normal-men-ncna974911) stated that "non-prosecution agreements are fairly common within the Department of Justice," but for a human / child sex trafficking case they "are not common at all; in fact, I would say they're almost unheard of." In February 2019, U.S. District Judge Kenneth A. Marra had described "the Government’s decision to conceal the existence of the NPA and mislead the victims to believe that federal prosecution was still a possibility" as "particularly problematic," and [ruled](https://www.politico.com/f/?id=00000169-11f3-d0be-adfb-75fff4490000) that "there was a violation of the victims rights under the CVRA" [[Crime Victims' Rights Act](https://www.law.cornell.edu/uscode/text/18/3771)].
{: style="text-align: justify;"}

While these officials have not clearly confirmed or denied their involvement in the decision, the time of departure for both Mandelker and [Acosta](https://web.archive.org/web/20190712142740/https://www.usatoday.com/story/news/politics/2019/07/12/labor-secretary-alex-acosta-resigned-amid-jeffrey-epstein-fallout/1681245001/) is worth noting. In defense of Acosta, Trump had said, "I do hear there were a lot of people involved in that decision, not just him." Furthermore, [The Associated Press](https://apnews.com/60faa70ed835f7b0e7c5f15f84355c0a) reported that Epstein's alleged confidante and co-conspirator, [Ghislaine Maxwell](https://www.justice.gov/usao-sdny/pr/ghislaine-maxwell-charged-manhattan-federal-court-conspiring-jeffrey-epstein-sexually), may attempt to claim immunity under Epstein's non-prosecution agreement. This would explain why the Justice Department's [focus](https://www.justice.gov/usao-sdny/press-release/file/1291491/download) is strangely limited to "1994 through at least 1997."
{: style="text-align: justify;"}

In April 2008, a few months before Epstein was sentenced under those lenient charges, Mandelker had spoken before the [U.S. Senate Committee on Foreign Relations](https://www.justice.gov/sites/default/files/criminal-hrsp/legacy/2010/07/29/04-09-08nelson-hearing.pdf) about "closing legal loopholes" for "citizens employed as United States government personnel and contractors" who had been accused of sexual assault.
{: style="text-align: justify;"}

> Sexual assault cases often involve the most vulnerable victims and must be treated with the utmost seriousness.  Whether this conduct occurs with in the United States or overseas and in a dangerous military zone, these offenders must be brought to justice.   

Within the announcement that Mandelker had been acquired as an advisor to [Chainalysis](http://web.archive.org/web/20200701085855/https://www.chainalysis.com/), she stated that the company "has done terrific work providing blockchain analysis and tools to financial institutions, government agencies, and exchanges," and is "excited" to work with them in "root[ing] out illicit networks."
{: style="text-align: justify;"}

On the same day, the [New York State Department of Financial Services](https://www.dfs.ny.gov/reports_and_publications/press_releases/pr202007071) announced that [Deutsche Bank](https://twitter.com/DeutscheBank/status/1280490499007283201) had "agreed to pay $150 million in penalties" for "significant compliance failures in connection with the Bank’s relationship with Jeffrey Epstein" between August 2013 until December 2018. The attached [consent order](https://www.dfs.ny.gov/system/files/documents/2020/07/ea20200706_deutsche_bank_consent_order.pdf) alleged that despite being aware of the "previous plea deal and prison sentence," senior management was made to believe "that Mr. Epstein was a potential client who could generate millions of dollars of revenue as well as leads for other lucrative clients to the Bank."
{: style="text-align: justify;"}

> AML OFFICER 2 only instructed the relevant transaction monitoring team to verify, using internet searches, that any woman involved with transactions related to the Epstein relationship was at least 18 years old and to only flag transactions if they could not discern a rational reason for the transaction...

According to the [New York Post](https://nypost.com/2020/07/07/deutsche-bank-hit-with-150m-penalty-over-jeffrey-epstein-ties/), the bank has "invested nearly $1 billion in 'training, controls and operational processes' amid the Epstein scandal and boosted the ranks of its anti-financial crime team to more than 1,500 people." But clearly, this is mere lip service in an expanding "[pot calling the kettle black](https://idioms.thefreedictionary.com/the+pot+calling+the+kettle+black)" escapade. Sure, fine another bank that can afford to swallow it whole. What is the U.S. government going to do as punishment, ̶f̶i̶n̶e̶ ̶i̶t̶s̶e̶l̶f̶ use taxpayer money to pay the victims into silence? More and more, we are learning [how many powerful figures and organizations](https://unlimitedhangout.com/epstein/) from both the [public](https://twitter.com/Techno_Fog/status/1289020613852635136) and private sector knew about Epstein's behaviour for years. Despite such scandals happening again and again, we have yet to learn that shoving more money, more people, more [financial surveillance](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-1st---blockchain-analysis-or-financial-surveillance) into corrupt incentive structures will ultimately fix nothing.
{: style="text-align: justify;"}

*The '[boiling frog](https://idioms.thefreedictionary.com/boiling+frog)' is a metaphor for "a problematic situation that will gradually increase in severity until it reaches calamitous proportions, such that the people involved or affected by it will not notice the danger until it is too late to act."*

:information_source: For an interesting related read, see the U.S. Army Special Operations Forces (ARSOF)'s ‘[Unconventional Warfare](https://web.archive.org/web/20190110092445/https://file.wikileaks.org/file/us-fm3-05-130.pdf)‘ (UW) field manual, describing various international financial organizations as "financial weapons" of U.S. foreign policy.
{: .notice--success}

## July 8th - HYPERONIONIZATION

The **Tor Project** announced [a one-month campaign](https://blog.torproject.org/more-onions-porfavor) dubbed [#MoreOnionsPorfavor](https://twitter.com/search?q=%23MoreOnionsPorfavor&src=typed_query) to "raise awareness about onion sites, that is, websites available over onion services." [Hidden services](https://support.torproject.org/onionservices/), with the [special-use domain](https://web.archive.org/web/20151007232340/https://www.ietf.org/proceedings/92/slides/slides-92-dnsop-8.pdf) ".onion," are only accessible through the Tor network, protecting the IP address not only of the visiting user but also the website / service operator.
{: style="text-align: justify;"}

> Recently, we implemented a way to announce and publicize your onion site using Onion-Location. When a user visits a website that has both onion services and Onion-Location enabled, Tor Browser will display an information pill telling them that there's a more secure version of the website, and the user will be asked to opt-in to upgrade to the onion service on their first use. If the user already opted-in for their network security upgrade, they will get directly to the onion site.

Bitcoin-related websites which run a hidden service and have enabled Onion-Location include [Bitcoin Client VirusTotal Tracker](https://bitcoinissafe.com/), [Blockchair](https://blockchair.com/), [Blockstream.info](https://blockstream.info/), [BTCPay Server](mainnet.demo.btcpayserver.org), [Mempool.Space](https://mempool.space/), [RoninDojo](https://ronindojo.io/), and [Wasabi Wallet](https://wasabiwallet.io/).
{: style="text-align: justify;"}

## July 11th - COINBASE CONTRACTING WITH SECRET SERVICE, IRS

[**The Block**](https://twitter.com/TheBlock__/status/1281960766388801536) reporter [Yogita Khatri](https://twitter.com/Yogita_Khatri5) published an [article](https://www.theblockcrypto.com/post/71261/coinbase-is-selling-blockchain-analytics-software-to-the-us-secret-service) pointing to awards in the federal contracting and grant-making databases [USAspending.gov](https://www.usaspending.gov/#/award/CONT_AWD_70US0920C70090044_7009_-NONE-_-NONE-) and [SAM](https://beta.sam.gov/awards/90905932%2BAWARD#general-information), which show that Coinbase has landed a multi-year contract with the U.S. Secret Service (USSS).
{: style="text-align: justify;"}

The [Secret Service](https://www.secretservice.gov/about/faqs) is an agency within the Department of Homeland Security tasked with the dual role of protecting current, former, and potential presidential families, as well as carrying out financial crimes investigations related to "counterfeiting of U.S. currency or other U.S. Government obligations; forgery or theft of U.S. Treasury checks, bonds or other securities; credit card fraud; telecommunications fraud; computer fraud, identify fraud and certain other crimes affecting federally insured financial institutions." Between 1933 and 1974, when the agency still fell under the Department of Treasury, they were enforcers of [Executive Order 6102](https://www.presidency.ucsb.edu/documents/executive-order-6102-requiring-gold-coin-gold-bullion-and-gold-certificates-be-delivered), forbidding the "hoarding" of gold.
{: style="text-align: justify;"}

The contract, which could award Coinbase up to $183,750, will last from May 11th 2020 until May 10th 2024. It falls under the [product service code](https://www.acq.osd.mil/dpap/sa/FDEs/electronics-and-comm-services/top-20-portfolios.html) (PSC) D319, "IT And Telecom - Annual Software Maintenance Service Plans." There are no attached documents offering more information about the nature of the contract, but both pages note "Coinbase Analytics" under the service description. As I pointed out in [last month's newsletter](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-5th---coinbase-offers-blockchain-surveillance-to-irs-dea), Coinbase Analytics is the re-branded blockchain surveillance company Neutrino that they acquired in February 2019.
{: style="text-align: justify;"}

A [subscription purchase order](https://web.archive.org/web/20200717151412/https://beta.sam.gov/awards/91148315%2BAWARD) from the [IRS](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-5th---coinbase-offers-blockchain-surveillance-to-irs-dea) has also since been signed on July 14th. The action obligation value is $124,950, and the total contract value is noted as $237,405.
{: style="text-align: justify;"}

Armstrong published a long tweet thread to "[share my thoughts](https://archive.is/k3UO4)" on these stories.

> In the early days, Coinbase started off by using some of the existing blockchain analytics services out there. This worked out ok, but the issue with it was that we don't like sharing data with third parties when we can avoid it, and they didn't support all the features/chains we needed. So we realized at some point we would need to bring this capability in house.
>
> We did this via an acquisition (which did not go very well honestly, and we had to cycle out some team members). But we were able to rebuild the team, and set up this functionality in house. It's expensive to build this capability, and we want to recoup costs. There is an existing market for blockchain analytics software, so we sell it to a handful of folks as well. It also helps us build relationships with law enforcement which is important to growing crypto.

Their [institutional sales manager](https://www.linkedin.com/in/ndebontin), Nicolas de Bontin, said this thread "[set the record straight](https://twitter.com/Ndebontin/status/1282110166721277952)."

In an interview for [**What Bitcoin Did**](https://www.whatbitcoindid.com/podcast/coinbase-ceo-on-bitcoin-with-brian-armstrong), Armstrong gave a bit more detail about how Coinbase came to acquire Neutrino, and then the decision to fire them (1:32:47 to 1:40:51).
{: style="text-align: justify;"}

> We went out and did some diligence on the team, but most of our diligence was around the technology itself and the team we would get, the engineers. What we failed to do was the diligence more around our values and our culture. When we did make the acquisition, we started to see a lot of noise online, with people asking, "Hey, do you know who you just acquired?"[<sup>("It's-a me, Mario!")</sup>](https://twitter.com/J9Roem/status/1098187424478490624) That's when I started to look into it, along with the team, and we realized, 'Okay, we might have hired some black hats here.' ... We tried to create a win-win exit agreement with them, where we took responsibility for it.
>
> ... Then we had a tough job of rebuilding that team with new people, and getting to a place where we had the technology working as described. I think the main thing we learned from that is, there are additional diligence steps we've got to do in [merger and acquisition deals]... Since that happened, we have revamped our diligence process to include these kinds of reputational checks. There is really no excuse I can give you.

**Kraken** co-founder and CEO [Jesse Powell](https://twitter.com/jespow/status/1282179956466790401) had pointed out last year that [his compliance team had rejected Neutrino](https://twitter.com/jespow/status/1102346122138333184) from a technology and "culture fit" perspective. In response to the news about Coinbase Analytics' contract deals, he mentioned how they had made a different choice regarding in-house or third-party blockchain analysis tools. Prior to founding Chainalysis, [Michael Gronager](https://twitter.com/gronager) had been the co-founder and chief operating officer of Kraken.
{: style="text-align: justify;"}

> We chose not to develop this business internally, and we chose not to invest in analytics firms because I never wanted to have a conflict of interest with our clients. I didn't want to profit from selling out your financial privacy.
>
> Is there [government] demand? Obviously. We have our internal tools that we use but productizing those tools and selling them, driving competition and accelerating development in the anti-privacy space is at odds with our values. How could one resist using client data to gain an edge?

## July 12th - CYBERGRRRLS: THE ORIGIN OF "CYPHERPUNK"

[Clara Shikhelman](https://twitter.com/ClaraShik/status/1282684812315295745) and I were interviewed for "[Listen: What a Bitcoin Researcher Says About Lightning](https://www.coindesk.com/listen-what-a-bitcoin-researcher-says-about-lightning)," regarding the status of privacy in the Lightning Network and Bitcoin overall. While I want to confirm that my quotes are otherwise accurate, and the portrayal is positive, I would like to clarify the framing and attribution of some statements. Since the **CoinDesk** CMS and / or post-publication editorial process can take multiple days, I will point them out here, given it's just a git commit away.
{: style="text-align: justify;"}

> “A lowercase ‘c’ cypherpunk,” she joked, acknowledging she was never involved with the movement’s founding fathers.
>
> This social movement is not preoccupied with overthrowing or altering governments, in stark contrast with Bitcoin Twitter’s anarchist undertones. Instead, Römer said, rather than seizing power the movement is focused on “working to make things un-take-over-able.” In short, unseizable assets, self-sovereign data and other types of independence in a digital world.

I do not believe that I indicated I was 'joking' (I did not use emotive language there). I make this distinction as a token of respect for those who founded the Cypherpunks, and are / were coders by trade (which I am not). I also do not believe I implied that there was a "stark contrast" between my focus, the original cypherpunk ethos, and "Bitcoin Twitter's anarchist undertones."
{: style="text-align: justify;"}

The line about “working to make things un-take-over-able" is a quote from 'St. Jude' Milhon's "The Cypherpunk Movement" (1992) in the eighth issue of [**Mondo 2000**](https://archive.org/details/mondo.2000.issue.08.1992/page/n39/mode/2up), which I had cited. It contains a sci-fi-esque short story where she encounters a couple guys wearing chadors; they talk about encryption and digital cash while waiting for a band dubbed "The Screamin' Memes" to perform at the "Black Hole" club. (I do declare, a band with this name would fit right in with the attention black hole known as Bitcoin Twitter! :wink:) Here is an excerpt from the story:
{: style="text-align: justify;"}

> The cello resumed, an annoyed cello: "We don't believe in takeovers. In fact, we are working to make things UNTAKEOVERABLE."
>
> A theremin quivered, "And to make the world safe for anarchy. We want the air-waves, baby." It snickered across many frequencies.
>
> The Tejana saxophone chuckled, (and an eerie treat that was, too): "Problem is, how to guarantee privacy for pseudonyms. So you can have a pseudonymous economy."

It is similar to the sentiment expressed by that famous quote attributed ([perhaps incorrectly](https://en.wikiquote.org/wiki/Talk:Buckminster_Fuller)) to systems theorist Buckminster Fuller: "You never change things by fighting the existing reality. To change something, build a new model that makes the existing model obsolete."
{: style="text-align: justify;"}

Milhon coined "[cypherpunk](https://www.wired.com/1995/02/st-jude/)" and was a founding member of their mailing list, frequented by a mixture of programmers, engineers, cryptographers, academics, activists, and writers alike. In September of the same year, Timothy May read the iconic "[Crypto-Anarchist Manifesto](https://activism.net/cypherpunk/crypto-anarchy.html)" at the founding IRL meeting. It spells out the potential effect of this technology on government:
{: style="text-align: justify;"}

> These developments will alter completely the nature of government regulation, the ability to tax and control economic interactions, the ability to keep information secret, and will even alter the nature of trust and reputation.
>
> ... Just as the technology of printing altered and reduced the power of medieval guilds and the social power structure, so too will cryptologic methods fundamentally alter the nature of corporations and of government interference in economic transactions.

While not all self-described cypherpunks are also self-described crypto-anarchists, there was a clear link between the two from the very beginning. In March 1993, Eric Hughes published the equally iconic "[A Cypherpunk's Manifesto](https://www.activism.net/cypherpunk/manifesto.html)," which proclaims:
{: style="text-align: justify;"}

> We cannot expect governments, corporations, or other large, faceless organizations to grant us privacy out of their beneficence...
>
> We must defend our own privacy if we expect to have any.
>
> ... Cypherpunks deplore regulations on cryptography, for encryption is fundamentally a private act. The act of encryption, in fact, removes information from the public realm. Even laws against cryptography reach only so far as a nation's border and the arm of its violence.

The underlying ethos expressed by both manifestos leans [agorist](https://en.wikipedia.org/wiki/Agorism), focused on developing the means to engage in voluntary association and exchange despite state suppression and oppression. The cypherpunks aren't and never were focused on "seizing power," but protecting privacy as a fundamental principle of open society. They believed that cryptography could be a powerful tool for social, political, and economic change — not through a strategy of violent revolution but rather by writing code and "deploy[ing] these systems for the common good."
{: style="text-align: justify;"}

July 19th will have been the 17th anniversary of Milhon's [death](https://www.sfgate.com/bayarea/article/Judith-Milhon-computer-writer-and-hacker-2599187.php) from cancer in 2003. One of the books she had co-authored, "[The Real Cyberpunk Fakebook](http://www.gutenberg.org/ebooks/929)" (1995), included this introduction of her by science fiction writer [Bruce Sterling](https://www.britannica.com/biography/Bruce-Sterling):
{: style="text-align: justify;"}

> Then there's this saint person. Never draw to an inside straight. Never eat at a place called Mom's. And never eat a bag of ephedrine and a pumpkin pie ('the *whip* of vegetables!') from a California blonde who doesn't even have a real name. This female personage is so appallingly cagey that even her main squeeze delights in cryptographically baffling the NSA. If Pat Buchanan ever gets his not-so-secret wish and sets up a domestic American gulag for counterculture thought-criminals, the Judester's gonna be way, *way* up on the list — maybe even number two, right after Bob Dobbs. Her trial's likely to prove rather interesting, however, as she only commits 'crimes' in areas of social activity that haven't even been defined yet, much less successfully criminalized. A serious legal study of this woman's spectrum of activities would be like a CAT-scan of the American unconscious.

Nor should we forget the section on 'Terminally Hip Jargon and Useful Expressions,' where *digital cash* was defined as such: "**The Philosopher's Stone of the nineties. Or maybe the Brooklyn Bridge. And good luck with it.**"
{: style="text-align: justify;"}

## July 13th - JUNK IN THE TRUNC: LIGHTNING PRIVACY

The [**Lightning Junkies**](https://twitter.com/LNJunkies/status/1282876220376571904) podcast released [episode LNJ033](https://lightningjunkies.net/lightning-sucks-2-electric-boogaloo/), an interview with [Elias Rohrer](https://twitter.com/_tnull), who is a co-author of the timing attacks paper that I covered in the [last edition](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-22nd---zkchannels-for-second-layer-privacy). He first heard about Bitcoin in 2012, and began catching up in 2016 with the development frenzy around payment channel networks. "My main research interests are basically security and privacy. I am always looking at it from a network perspective... I've been interested in privacy-enhancing technologies and distributed systems, or peer-to-peer systems, for quite a long time."
{: style="text-align: justify;"}

> In recent years, there have been quite a number of attacks on the privacy of the main Bitcoin network, on the consensus layer ('Layer 1') and the networking layer ('Layer 0'). We had correlation attacks at the transaction level, with people analyzing which transactions matched to others and to whom addresses belonged. There was, of course, the possibility for nodes to observe where transactions were first announced in the network... In Lightning, you have to consider that it is taking all of these transactions off-chain, and thereby directly increasing privacy guarantees, just due to the fact that the state transitions are negotiated locally instead of globally.

Rohrer reported that Lightning's various challenges are being "openly discussed within the community" and the developers "are constantly working towards mitigation," at which point we must "decide which mitigations are worth the cost." Stressing that it is important to define your adversary before making general determinations about whether a system was private 'enough,' he agreed that the offering by Lightning and CoinJoins against chain analysis was "pretty solid."
{: style="text-align: justify;"}

During the interview, he described the mechanisms by which Lightning currently protects the privacy of users (source routing, onion routing, hidden channels), as well as the methods by which adversaries could decrease the anonymity set for payments, including [the timing attack](https://arxiv.org/pdf/2006.12143.pdf) presented in his paper. He and his co-author had concluded that by controlling "roughly ten nodes or more," a malicious intermediary would have a 50% chance of correctly determining which nodes were the sender and receiver. "If some implementations would introduce randomization techniques," such as through latency and message batching, "it could potentially mitigate, to some degree, these kinds of deanonymization attacks."
{: style="text-align: justify;"}

## July 14th - SAMOURAI WALLET ADDRESS REUSE

[**Samourai Wallet**](https://twitter.com/SamouraiWallet/status/1283145015124996098) published their [review](https://medium.com/samourai-wallet/investigating-address-reuse-within-post-mix-spend-transactions-44b0647dee65) of a vulnerability disclosure, identifying instances of both intentional and unintentional address reuse by their users. While they considered both categories, their analysis was "concerned primarily with Unintentional Address Reuse."
{: style="text-align: justify;"}

> Of the 1,518 reused addresses 1,127 are likely external addresses not derived by the wallet — instead provided by the user. These instances can be further categorized into the broad category of Intentional Address Reuse.
> **This leaves 391 addresses that have been likely derived by the wallet indicating potential Unintended Address Reuse that warrants further investigation.**

In conclusion, "this is nowhere near the alleged 5,000+ transactions described in the original disclosure but as we have stated many times before, no address reuse is acceptable." Of particular interest was the address reuse among [Stowaway](https://samouraiwallet.com/stowaway) and post-mix [STONEWALL](https://samouraiwallet.com/stonewall) or STONEWALLx2 transactions, "the most clear case of Unintentional Address Reuse due to no fault or action of the user." They repeatedly empart that "any address reuse is not desirable."
{: style="text-align: justify;"}

Both their own backend and the latest version of [Dojo](https://code.samourai.io/dojo/samourai-dojo/-/blob/master/RELEASES.md#samourai-dojo-v170) have been updated to address this unwanted behavior by enforcing a Strict Mode pushTx policy, and "keep[ing] track of the consumed indexes" for [Ricochet](https://www.samouraiwallet.com/ricochet) transactions.
{: style="text-align: justify;"}

On July 15th, [Shinobi](https://twitter.com/brian_trollz/status/1283525347007442944) revealed that he was the author of the disclosure, and stated that he "still want[ed] to provide my side of the picture" through excerpts of his report, additional explanation and commentary. He believes that the instances of unintentional address reuse could be triggered due to "lack of error handling mechanisms for data requests from external sources" and "network connection disruption." The next day, he created [an addendum](https://twitter.com/brian_trollz/status/1283858720234057729) to acknowledge that "Samourai’s analysis of false positives in the overall set of address reuse is 100% correct."
{: style="text-align: justify;"}

> This however does not change the nature of the bug in the client, or the severity of it for individual affected users. I still strongly believe an appropriate patch would be to persist the relevant wallet indexes locally in the same manner the Whirlpool desktop client does... I have no intent of engaging in slap fights or arguments on social media, everything necessary to verify this issue is right here, and what any individual chooses to do with that is their decision to make.

Address reuse was previously reported via [a GitHub issue](https://github.com/Samourai-Wallet/samourai-wallet-android/issues/381) on January 17th, though it is unclear whether it had a similar cause as both the user and '[TDev](https://twitter.com/SamouraiDev)' were unable to replicate it.

*Disclosure: To counter some ongoing speculation, I want to note that Shinobi is my co-host on **Block Digest**; 'Nopara' Ádám Ficsór was a co-host between [May 2018](https://twitter.com/nopara73/status/994585646059601920) and February 2020. Our [short video series](https://www.youtube.com/watch?v=ike8Tex442M&list=PLbdPWjvnsOMwkvayjyJFfjmNmq_xBpZZn) inspired the name of [zkSNACKs](https://zksnacks.com/). Otherwise, neither of us are affiliated with or financially supported by Wasabi or their investors.*
{: style="text-align: justify;"}

## July 15th - FOURTH AMENDMENT LAWSUIT AGAINST IRS

[Jim Harper](https://twitter.com/Jim_Harper/status/1283448554099482632), visiting fellow at the [American Enterprise Institute](https://www.aei.org/profile/jim-harper/) (AEI) and [former senior fellow at the Cato Institute](https://www.cato.org/people/jim-harper), announced that he would be "suing the IRS today for violation of my Fourth Amendment and Due Process rights." He is the author of "[Identity Crisis: How Identification Is Overused and Misunderstood](https://www.amazon.com/Identity-Crisis-Identification-Overused-Misunderstood-ebook/dp/B005HITTNE/)" (2006).
{: style="text-align: justify;"}

> I was a recipient of a warning letter sent to cryptocurrency users last summer suggesting that they hadn't paid their taxes. I have. We believe the IRS's acquisition of my private financial information was contrary to law. They may have acquired it through a summons issued to crypto platform Coinbase -- we don't know that for sure -- a defective process that denied me the opportunity to contest the seizure of my data. I'll be seeking destruction of the records in the IRS's control. A win would allow all recipients of the letter to seek the same.
>
> This suit is an effort to make the law match up with our times. When the 4th Amendment was adopted, people kept financial information on paper within the home. Now the same information resides on the servers of service providers who are pledged to maintain it in confidence. The law doesn't recognize that, though. It treats information in the hands of financial services providers as fair game for seizure without even notifying the affected party. Hopefully, the suit will protect me and my family from having our private financial information taken from us again, empower others to protect themselves, and put pressure on or reverse some legal doctrines that are too permissive of government access to private information.

He will be represented by [Caleb Kruckenberg](https://twitter.com/Kruckenberg_Esq) and [The New Civil Liberties Alliance](https://nclalegal.org/about/) (NCLA), "a nonpartisan, nonprofit civil rights group founded by prominent legal scholar Philip Hamburger to protect constitutional freedoms from violations by the Administrative State." In an interview with [**The American Spectator**](https://spectator.org/bitcoin-investor-sues-irs-for-unlawful-seizure-of-private-financial-data/), Harper said that he had been "a victim of the U.S. Office of Personnel Management [OPM] data breach" and was "worr[ied] about the possibility of a data breach that could expose my financial information to criminals."
{: style="text-align: justify;"}

The [United States District Court for the Western District of Texas](http://www.ca5.uscourts.gov/opinions/pub/19/19-50492-CR0.pdf) recently countered a defendant's argument, which cited [*Carpenter v. United States*](https://www.aclu.org/cases/carpenter-v-united-states) (2018), that he had a reasonable expectation of privacy for his Bitcoin transactions or Coinbase account. Under "the third-party doctrine, the Supreme Court in *United States v. Miller* held that bank records were not subject to Fourth Amendment protections." Due to "Coinbase records" being "more akin to the bank records," and the "publicity" of transaction information on the Bitcoin blockchain, the circuit judges concluded that "Gratkowski thus lacked a privacy interest."
{: style="text-align: justify;"}

> Bitcoin users have the option to maintain a high level of privacy by transacting without a third-party intermediary. But that requires technical expertise, so Bitcoin users may elect to sacrifice some privacy by transacting through an intermediary such as Coinbase.

## July 20th - HOW I KNEW YOUR CUSTOMER: FATF COMPLIANCE

[The Block](https://twitter.com/TheBlock__/status/1285319062386507776) assistant editor [Aislinn Keely](https://twitter.com/AislinnKeely/status/1285357442805751810) and managing editor [Michael McSweeney](https://twitter.com/mpmcsweeney) highlighted that various custodial exchanges have formed a working group to "design a collective solution for complying with Financial Action Task Force (FATF) rules on sharing customer data."
{: style="text-align: justify;"}

During the Zoom-hosted [Global Digital Finance Travel Rule summit](https://www.eventbrite.co.uk/e/gdf-travel-rule-summit-tickets-110596290482#) on July 15th, Coinbase chief compliance officer [Jeff Horowitz](https://twitter.com/coinbase/status/1024233227387629570) spoke during [two presentations](https://us02web.zoom.us/rec/play/tMd_c7ugqz83HtOX5ASDU_MvW9S9L_ms0iEWqPAOy0u8W3AEMVquNbIRYbPo-kKMCbBQG9X56ORKYInO), "The Unseen Solutions: The Travel Rule Protocol" (51:30-59:15) and "KYV: Know Your VASP and Why This Matters" (1:35:15-1:45:50). He stated that a consortium of U.S. based companies would be releasing a whitepaper on this inter-VASP bulletin board system "most likely in the next two weeks."
{: style="text-align: justify;"}

> There are a lot of trade-offs in solving the travel rule. First off, we're trying to solve transparency for law enforcement, but what we don't want to do as an industry is create new challenges, such as data leakage, data hacks. Taking two steps backward for taking one step forward. We will be meeting with the U.S. Treasury and FinCEN, and trying to describe what our approach to this solution is. 

Horowitz spoke about the pressure from regulators to build a "global solution" for [travel rule compliance](https://www.coincenter.org/the-upcoming-fatf-interpretive-note-is-not-doomsday-for-cryptocurrency/) among virtual asset service providers (VASPs). For the time being, they would be limiting these data sharing partnerships to domestic and regional businesses following similar compliance and privacy policies. While Horowitz did not specify which companies outside of Coinbase were already involved, [Bittrex](https://twitter.com/BittrexExchange) has confirmed that it is "an active member of the United States Travel Rule Working Group (USTRWG)." Gemini and Kraken have also been named but "did not respond to requests for comment by press time." [CoinDesk](https://archive.vn/WrPAT) added BitGo to the list. Given that [ShapeShift](https://shapeshift.com/library/shapeshift-has-partnered-with-global-digital-finance) joined the Global Digital Finance (GDF) Advisory Council in October 2019, it is possible that they are also involved.
{: style="text-align: justify;"}

> The VASPs will post to the bulletin board to see who may own an address, and once another participant claims an address, the two parties can engage in peer-to-peer sharing of the necessary information. This approach ensures that the information isn't stored somewhere — exposing that data to possible hackers — but is instead transmitted directly from the sending VASP to the receiving VASP.

[Lightning Labs](https://lightning.engineering/team/) CEO and co-founder [Elizabeth Stark](https://twitter.com/starkness/status/1285348564449755137) pointed out the weakness of such a claim: "Um, this means it's stored in two places. Sounds like a privacy disaster to me." Remember, kids, there is no cloud... just other people's computers. The only surefire way to prevent another party from storing data that you don't want them to store, is to not give it them in the first place.
{: style="text-align: justify;"}

On July 27th, the [**Stephan Livera Podcast**](https://stephanlivera.com/episode/196/) hosted a conversation between lawyer [Rafael Yakobi](https://twitter.com/CACryptoLawyer), [Alex Gladstein](https://twitter.com/gladstein), and [Matt Odell](https://twitter.com/matt_odell) about what the Task Force is, how the Travel Rule may apply to Bitcoin / cryptocurrency businesses, and how this will impact privacy. Yakobi noted that while "the law rewards non-custodial solutions or limited custodial solutions," the compliance consequences for custodial exchanges will lead to significant privacy risks, yet "none of them seem to weigh that as a serious consideration."
{: style="text-align: justify;"}

>  I think one of the main things that I’m concerned about with this is that there’s just going to be a ton more information sharing between exchanges. Whatever custodial privacy risks, like Matt mentioned, you have just grew exponentially. I don’t even know how many exchanges will eventually be part of this network. And then if they’re all sharing information, you KYC once and now everybody on the whole planet has got it. Or, you know, 50 exchanges in 30 countries. It could be global. It could be all the exchanges in every country eventually.

## July 24th - SCHNORR / TAPROOT ACTIVATION

The [Bitcoin Core PR Review Club](https://twitter.com/BitcoinCorePRs/status/1286655148358610945) announced their third meeting in a series, hosted by [John Newberry](https://twitter.com/jfnewbery), regarding the implementation of the Schnorr and Taproot BIPs: [340](https://github.com/bitcoin/bips/blob/master/bip-0340.mediawiki), [341](https://github.com/bitcoin/bips/blob/master/bip-0341.mediawiki), and [342](https://github.com/bitcoin/bips/blob/master/bip-0342.mediawiki). On the 29th, over one hundred people joined to ask, read, and respond to questions specifically about the Taproot transaction hashing algorithm. You can read the meeting log [here](https://bitcoincore.reviews/17977).
{: style="text-align: justify;"}

> Interest in merkelized scriptPubKeys (e.g. MAST) is driven by two main areas: efficiency and privacy. Efficiency because unexecuted forks of a script can avoid ever hitting the chain, and privacy because hiding unexecuted code leaves scripts indistinguishable to the extent that their only differences are in the unexecuted parts.

"[Taproot: Privacy Preserving Switchable Scripting](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2018-January/015614.html)" was originally proposed by Greg Maxwell in January 2018, with the goal of "making fancier contract use cases" in Bitcoin that were "as indistinguishable as possible from the most common and boring payments." In December 2018, Anthony Towns made a "[concrete proposal](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2018-December/016556.html)" that the Schnorr signature scheme – discussed for implementation [at least since 2014](https://bitcointalk.org/index.php?topic=511074.msg5660888#msg5660888) and [formalized into a BIP earlier this year](https://github.com/sipa/bips/commit/1faa4b19bcfaec44a964a665f68a5bdaba85337e#diff-a8f00626d544ebf6969005a133da911e) by [Pieter Wuille](https://twitter.com/pwuille) and [Jonas Nick](https://twitter.com/n1ckler) – should be activated with Taproot in a bundled soft fork of script upgrades. There are currently [several options](https://en.bitcoin.it/wiki/Taproot_activation_proposals) for this being considered.
{: style="text-align: justify;"}

:information_source: For overviews of Schnorr and Taproot, see [Aaron van Wirdum](https://twitter.com/AaronvanW)'s [article](https://bitcoinmagazine.com/articles/taproot-coming-what-it-and-how-it-will-benefit-bitcoin) and [Lucas Nuzzi](https://twitter.com/LucasNuzzi)'s "[Schnorr Signatures & The Inevitability of Privacy in Bitcoin](https://medium.com/digitalassetresearch/schnorr-signatures-the-inevitability-of-privacy-in-bitcoin-b2f45a1f7287)." Check out [Bitcoin Optech Newsletter #107](https://bitcoinops.org/en/newsletters/2020/07/22/) and [#108](https://bitcoinops.org/en/newsletters/2020/07/29/) for their summaries.
{: .notice--success}

## July 29th - LEDGER DATA BREACH

[**Ledger**](https://twitter.com/Ledger/status/1288372785098764288), a popular [hardware wallet company](https://www.ledger.com/the-company/) based out of the Parisian [*La Maison du Bitcoin*](https://www.capital.fr/entreprises-marches/la-maison-du-bitcoin-levangelisateur-de-la-crypto-en-france-1275110), released the results of [an internal investigation](https://www.ledger.com/addressing-the-july-2020-e-commerce-and-marketing-data-breach) into a data breach of their website.
{: style="text-align: justify;"}

> On the 14th of July 2020, a researcher participating in our [bounty program](https://donjon.ledger.com/bounty/) made us aware of a potential data breach on the Ledger website. We immediately fixed this breach after receiving the researcher’s report and underwent an internal investigation. A week after patching the breach, we discovered it had been further exploited on the 25th of June 2020, by an unauthorized third party who accessed our e-commerce and marketing database – used to send order confirmations and promotional emails – consisting mostly of email addresses, but with a subset including also contact and order details such as first and last name, postal address, email address and phone number.

Approximately one million email addresses were exposed, as well as the "first and last name, postal address, phone number or ordered products" of "a subset of 9500 customers." They claim that "no payment information, no credentials (passwords)" were affected, and there was "no impact whatsoever with our hardware wallets nor Ledger Live security and your crypto assets."
{: style="text-align: justify;"}

After [BlockFi](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-16th---blockfi-hires-new-chief-security-officer) and [Coinsquare](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/#june-2nd---coinsquare-data-breach), this is the third time in the last two months that a cryptocurrency company has disclosed a data breach of their marketing database, underlining a need for the industry to improve their handling of sensitive customer information.
{: style="text-align: justify;"}

:warning: If you know or suspect that you were impacted by this breach, I recommend reading Kraken's "[Security Advisory: Mobile Phones](https://blog.kraken.com/post/219/security-advisory-mobile-phones/)," Jameson Lopp's "[A Home Defense Primer](https://blog.keys.casa/a-home-defense-primer/)," and "[A Modest Privacy Protection Proposal](https://blog.lopp.net/modest-privacy-protection-proposal/)."
{: .notice--warning}

**Thanks for reading!** Feel free to :bookmark: [bookmark](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/feed.xml) or [subscribe](https://github.com/Enegnei/This-Month-In-Bitcoin-Privacy) to catch the next edition of 'This Month in Bitcoin Privacy.'
{: .notice--info}