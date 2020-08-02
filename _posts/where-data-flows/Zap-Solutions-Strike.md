Strike is a consumer and merchant services application that allows people to make and receive Lightning payments with a bank account or debit card. While the [Zap wallet](https://zaphq.io/) is non-custodial and open-source, Strike is a custodial, regulated, and proprietary product of Zap Solutions Inc., entering public beta as of July 2nd 2020.

> Zap holds all USD deposits with an FDIC banking partner which services “many cryptocurrency companies,” Mallers said. On the Bitcoin side, all transactions are handled by Zap using the infrastructure it erected for Olympus — so, the original tech stack is still being used, it’s just going on behind the scenes. This work behind the curtain “not only handles application and protocol interaction but also real-time risk management and automated trading/hedging,” Mallers said. ([Bitcoin Magazine](https://bitcoinmagazine.com/articles/with-strike-zap-rethinks-its-olympus-fiat-to-bitcoin-feature))

In his [announcement](https://medium.com/@JimmyMow/announcing-strike-public-beta-325877a79f87) of Strike, founder and CEO Jack Mallers wrote:

> With our public launch, I am unbelievably proud to announce the only requirement for most users to use Strike is your name and phone number. That is not a typo. You read that correctly. We care about you a lot. We care about Bitcoin a lot. We were not going to let regulation get in the way of Bitcoin’s relationship with the world.

The Strike [homepage](https://beta.strike.me/) describes their service as 'private.'

> Strike is your payment proxy to the world. Your information is kept private and never shared.

However, it is apparent that there is a striking dissonance between this marketing, the privacy policy, and their partnerships.

### Terms of Service

Strike's [terms-of-service](https://beta.strike.me/tos) (ToS) includes the following regarding their privacy policy:

> You acknowledge that the information you upload or submit to the Services may be personal information from or about other individuals or companies ("Third-Party Information"). We will not use or disclose such information, except as set forth in our Privacy Policy. You will comply with all applicable laws in connection with your use and handling of Third-Party Information and you will not use the Services to collect, duplicate, store, disseminate or disclose Third Party Information without any required permissions

Under the 'Account Registration' terms:

> If you wish to access the Services, you must create an account with Zap (" Account"). When registering your Account, you must provide current, complete, and accurate information for all required elements on the registration page, including your **full legal name, email address, phone number, a designated bank account (" Bank Account") if applicable to your use of the Services, and any other information we may require to open an Account.** If any of this information changes, it is your obligation to update such information immediately. From time to time, we may also require you to provide further information as a condition for continued use of the Services to confirm your identity and the purpose of using our Services.

> We may also request, and you will provide, proof of identity and other substantiation of the accuracy of your account information. You agree that you won't disclose your Account password to anyone and you'll notify us immediately of any unauthorized use of your Account. You're responsible for all activities that occur under your Account, whether or not you know about them.

They also reserve the right to "block access to the Services from certain **IP addresses and unique device identifiers**."

Under the 'Transactions' terms:

> We will establish and may change certain limits for Transactions based on the risk assessment, provided, however, that we will have the right to establish and change certain reasonable limits for transactions in accordance with laws and regulations.

Under the 'Third Party Account' terms:

> Depending on the functions that you seek to utilize with respect to transactions associated with your Account, and Zap's risk determination, Zap may, in its sole discretion, require identity verification, screening procedures, or enhanced verification using our Third-Party Partner (" Enhanced Account Verification"). As a result, you may be required to provide our Third Party Partner with certain personal information, including, but not limited to, your **name, address, telephone number, email address, date of birth, taxpayer identification number, government identification number, photograph of your government-issued ID or other photographic proof of your identity, and information regarding your bank account**. You hereby authorize zap, directly or through our Third Party Partner, to make any inquiries necessary to verify your identity and/or protect against fraud, including but not limited to: (a) query identity information contained in public reports (e.g., your name, address, past addresses, or date of birth); (b) query account information associated with your linked bank account (e.g., name or account balance); and (c) take reasonably necessary actions to comply with applicable law. You further authorize any and all third parties to which such inquiries or requests may be directed to fully respond to such inquiries or requests. Zap will have no liability or responsibility for any permanent or temporary inability to access or use any Services, including your inability to withdraw the balance of your account or execute Transactions, as a result of any identity verification or other screening procedures.

The list of businesses which are 'prohibited' from using Strike include "Regulated Products and Services" such as as marijuana dispensaries, pharmaceutical services, and broadly any "products and services with varying legal status," such as adult content. Mallers has [clarified](https://twitter.com/JackMallers/status/1279479261720645634?s=20) that in practice, this is prohibited on a state-by-state basis, and "legal" dispensaries are permitted to use Strike.

### Privacy Policy

Strike's [privacy policy](https://beta.strike.me/privacy) includes the following regarding their collection and processing of personal information. In accordance with the claim in the announcement, account creation indeed requires "information such as your **name, email address, phone number, and username**." However they also use "pixel tags / web beacons," and engage in other automated collection activities: 

> Automatic Data Collection. We may collect certain information automatically when you use the Services. This information may include your **Internet protocol (IP) address, user settings, MAC address, operating system or device, location information (including inferred location based off of your IP address), information about how you interact with the Services, including the frequency and duration of your activities**, and other information about how you use the Services. Information we collect may be associated with accounts and other devices.

Under the 'Verification Procedures through Third Party Providers' terms:

> You acknowledge that before you receive Services from us, you will be required to complete certain verification procedures (such as KYC and AML) through our third party service providers such as Cognito. You can access Cognito's terms of service and privacy policy at: https://privacy.cognitohq.com/.

Cognito is a customer identity and business verification service for compliance and fraud protection. In September 2019, they wrote about [how they perform identity verification without social security numbers](https://cognitohq.com/identity-verification-without-ssn/):

> By asking for as little as a name and phone number, Cognito can stitch together an identity record from powerful regulated data sources, instantaneously confirming if someone is who they say they are.

While they are not transparent about how they do this, Cognito does admit that they screen customers of financial services companies "[against lists of high-risk individuals issued by various government agencies around the globe](https://cognitohq.com/what-is-required-to-know-your-customer/)," including Politically Exposed Persons (PEPs) watchlists. Cognito's privacy policy states that they "use service providers and other third party services to help perform essential business functions on our behalf."

## Visa and Plaid

While Visa is not mentioned in either the terms-of-service or privacy policy, the beta launch of Strike included a [press release](https://www.coindesk.com/bitcoin-startup-zap-is-working-with-visa) that Zap Solutions Inc. would be [partnering with Visa](https://partner.visa.com/homepage.html):

> “Zap, Inc. has joined Visa’s Fast Track program,” Mallers said in an email about the startup’s plan for 2020. “Visa works with members of the Fast Track program to help them go to market in the most efficient way possible, providing them support and resources every step of the way.” 
>
> He said his primary focus this year is launching a Strike card for consumer app users and integrating Visa Direct into the consumer app, which is the program that makes Venmo payments so fast. There’s no date yet for the upcoming Strike card. 
>
> “They [Visa] are a partner for our consumer issuance offering and are not involved in our merchant offering at all,” Mallers added.

In January, it was [reported](https://www.cnbc.com/2020/01/13/visa-to-acquire-plaid-the-fintech-powering-venmo-and-other-banking-apps-for-5point3-billion.html) that Visa had acquired Plaid, a financial technology company, for $5.3 billion.

> Plaid’s API software, often referred to as the “plumbing” behind fintech companies, lets start-ups connect to users’ bank accounts. It’s well-known among financial technology developers, but the average person interacting with it most likely wouldn’t recognize the name. High-profile Plaid customers include popular peer-to-peer payment app Venmo, mobile investing app Robinhood and cryptocurrency exchanges Coinbase and Gemini.

Plaid's [privacy policy](https://plaid.com/legal/#end-user-privacy-policy) includes the following regarding their collection and processing of personal information:

> When you connect your financial accounts with a developer application or otherwise connect your financial accounts through Plaid, where applicable, we collect identifiers and login information required by the provider of your account, such as your username and password, or a security token. In some cases, we also collect your phone number, email address, security questions and answers, and one-time password (OTP) to help verify your identity before connecting your financial accounts.

> But, in general, we collect the following types of identifiers, commercial information, and other personal information from your financial product and service providers:
>
> Account information, including financial institution name, account name, account type, account ownership, branch number, IBAN, BIC, and account and routing number; Information about an account balance, including current and available balance; Information about credit accounts, including due dates, balances owed, payment amounts and dates, transaction history, credit limit, repayment status, and interest rate; Information about loan accounts, including due dates, repayment status, balances, payment amounts and dates, interest rate, guarantor, loan type, payment plan, and terms; Information about investment accounts, including transaction information, type of asset, identifying details about the asset, quantity, price, fees, and cost basis; Identifiers and information about the account owner(s), including name, email address, phone number, date of birth, and address information; Information about account transactions, including amount, date, payee, type, quantity, price, location, involved securities, and a description of the transaction; and Professional information, including information about your employer, in limited cases where you’ve connected your payroll accounts.
>
> The data collected from your financial accounts includes information from all your accounts (e.g., checking, savings, and credit card) accessible through a single set of account credentials.

In addition to collecting similar "electronic network activity information," they also state that they "may use the information we collect about you to derive inferences. For example, we may infer your location or your projected income."

During [our interview with Mallers](https://castbox.fm/episode/Block-Digest-Special-Edition---Jack-Mallers-(Strike)-id1192324-id287209099) about Strike, he said that they “don’t install those permissions in our Plaid widget,” but rather “the very bare minimum of what we need,” suggesting that payment app providers have some choice as to how extensive the data collection should be. Since the app is closed-source, it is not possible to independently verify this, and Plaid has still not been mentioned in their Terms of Service or Privacy Policy. Mallers also stated that Plaid had recently put them through a more extensive vetting process for data handling. “Clearly, someone came down on them.”

On July 1st, the [National Law Review](https://twitter.com/natlawreview) wrote about how [Plaid is facing class-action lawsuits](https://www.natlawreview.com/article/fintech-startup-plaid-inc-hit-5m-class-action-lawsuit) filed by the [Lieff Cabraser Heimann & Bernstein law firm](https://www.lieffcabraser.com/2020/05/new-data-theft-class-action-by-users-of-venmo-stripe-and-payment-platforms-against-plaid-financial-alleges-violations-of-data-privacy-laws/) for violating "consumers’ reasonable expectations" of privacy. [Cottle et al. v. Plaid Inc.](https://www.classaction.org/media/cottle-et-al-v-plaid-inc.pdf) says that the founders of Plaid had the initial "intention of building a consumer-facing fintech app," but "by early 2013, however, they pivoted to building a behind-the-scenes data aggregator and data brokerage operation." The initial case management conference is [scheduled](https://apps.cand.uscourts.gov/CEO/cfd.aspx?71BQ) for August 2020.

> As early as February 2013, when Perret and Hockey introduced Plaid at the insular “NYC Data Business Meetup,” the co-founders made clear that Plaid’s true purpose is to monetize consumer transactional and other banking data. Collecting and aggregating data from financial institutions was merely the “table stakes,” as Plaid’s real goal was to “resolve data and make that something interesting.” They emphasized the “immense” amount of consumer spending data the company could collect from banks — going back up to five years — and the “awesome” things Plaid could do with the data.

Another [class action complaint](https://www.courtlistener.com/recap/gov.uscourts.cand.362606/gov.uscourts.cand.362606.1.0.pdf), filed on July 17th by [Tostrud Law Group](http://tostrudlaw.com/) and [Glancy Prongay & Murray LLP](https://www.glancylaw.com/) on behalf of four plaintiffs who were customers of Venmo, makes very similar allegations.

> Any consent that Plaid claims to have obtained from Plaintiffs and Class Members is further called into question by the fact that most consumers do not recognize  that Plaid is an entity distinct from the Participating App that they are using, or even — as Plaid boasts — that Plaid exists at all. Co-Founder Hockey has said in interviews that “most people will never know we exist.”[<sup>21</sup>](http://www.alumni.emory.edu/emorywire/issues/2013/august/of_interest/story_1/index.html) Perret has stated, “we don’t need every consumer to know what Plaid is.”[<sup>22</sup>](https://www.saastr.com/build-a-platform-ecosystem/) One of Plaid’s investors at Goldman Sachs Investment Partners told CNBC, “Plaid has quietly created a very big infrastructure without the consumer knowing that they’re powering it.”[<sup>23</sup>](https://www.cnbc.com/2018/10/04/meetthe-startup-that-powers-venmo-robinhood-and-other-big-apps.html)
