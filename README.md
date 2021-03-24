# hw_fintech_research

# TITLE

## Overview and Origin

* Name of company : AAVE

* When was the company incorporated? Autumn 2017

* Who are the founders of the company? Stani Kulechov - Founder and CEO - Aave | LinkedIn.

* How did the idea for the company (or project) come about? 
* The birth of the Aave Protocol marks Aave’s shift from a decentralized P2P lending strategy (direct loan relationship
between lenders and borrowers, like in ETHLend) to a pool-based strategy. Lenders provide liquidity by depositing
cryptocurrencies in a pool contract. Simultaneously, in the same contract, the pooled funds can be borrowed by
placing a collateral. Loans do not need to be individually matched, instead they rely on the pooled funds, as well as
the amounts borrowed and their collateral. This enables instant loans with characteristics based on the state of the
pool. A simplified scheme of the protocol is presented in figure 1 below.
Figure 1: The Aave Protocol
The interest rate for both borrowers and lenders is decided algorithmically:
• For borrowers, it depends on the cost of money - the amount of funds available in the pool at a specific time.
As funds are borrowed from the pool, the amount of funds available decreases which raises the interest rate.
• For lenders, this interest rate corresponds to the earn rate, with the algorithm safeguarding a liquidity reserve
to guarantee withdrawals at any time.


* How is the company funded? How much funding have they received?
*Organization Name 
Aave Logo
Aave
Announced Date Nov 25, 2017
Closed On Date Nov 30, 2017
Funding Type Initial Coin Offering
Money Raised $16.5M

* 


## Business Activities:

* What specific financial problem is the company or project trying to solve?
* At the heart of a lending pool is the concept of reserve: every pool holds reserves in multiple currencies, with
the total amount in Ethereum defined as total liquidity. A reserve accepts deposits from lenders. Users can
1
borrow these funds, granted that they lock a greater value as collateral, which backs the borrow position.
Specific currencies in the pooled reserves can be configured as collateral or not for borrow positions, only low risk
tokens should be considered. The amount one can borrow depends on the currencies deposited still available in the
reserves. Every reserve has a specific Loan-To-Value (LTV), calculated as the weighted average of the different
LTVs of the currencies composing the collateral, where the weight for each LTV is the equivalent amount of the
collateral in ETH; figure 3 shows an example of parameters.
Every borrow position can be opened with a stable or variable rate. Borrows have infinite duration, and there is
no repayment schedule: partial or full repayments can be made anytime.


* Who is the company's intended customer?  Is there any information about the market size of this set of customers?
What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)

The Aave protocol implements a tokenization strategy for liquidity providers. Upon deposit, the depositor receives a
corresponding amount of derivative tokens, called Aave Tokens (aTokens for short) that map 1:1 the underlying
assets. The balance of aTokens of every depositor grows over time, driven by the perpetual accrual of interest of
deposits. aTokens are fully ERC20 compliant.
aTokens also natively implement the concept of interest rate redirection. Indeed, the value accrued over time by
the borrowers’ interest rate payments is distinct from the principal value. Once there is a balance of aTokens, the
accrued value can be redirected to any address, effectively splitting the balance and the generated interest. We call
the continuous flow of accumulated interest over time the interest stream.

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)




## Landscape:

* What domain of the financial industry is the company in?
* Lending

* What have been the major trends and innovations of this domain over the last 5-10 years?
* e can all agree that 2020 has been a challenging year. Back in March last year, the cryptocurrency and legacy markets went downhill due to the COVID-19 pandemic. Things have been picking up with bitcoin reaching $12,000 in August, a significant jump from the $3,600 price plunge. Towards the end of 2020, Bitcoin made a comeback, reaching a new all-time high of $20,000 and as of early February 2021, it has doubled to over $40,000. It is certainly an impressive rally for cryptocurrency. However, economies around the world are still scrambling albeit slowly bouncing back with government interventions. The Covid-19 pandemic is not over and it continues to create volatility in the global markets.
In times like these, cryptocurrencies such as Bitcoin still stand out as valuable financial assets despite the tumultuous year. The outstanding growth and the recent record-breaking all-time highs have proven that Bitcoin is solidifying its position in the financial world. It is a non-inflationary digital currency that’s not governed by individuals or corporations but a protocol. As rumors about legacy markets reaching negative interest rates, it’s time for Bitcoin investors to keep preserving their assets and increase productivity by lending their assets and earn interest in the process.
Crypto lending is a type of trade where you lend out your cryptocurrency and earn interest from it. The trade is facilitated by crypto lending platforms that accept deposits of different cryptocurrencies like Bitcoin, Ether, or Stable Coins with some interest in return. The Bitcoin lending interest rates vary but often very competitive, with some offering up to 12% on Annual Percentage Yield (APY). These platforms also often loan the assets with collateral, usually with crypto, and thus called crypto-backed loans.
If you’re thinking about growing your crypto assets through crypto lending, here are five crypto lending platforms that worth considering.

* What are the other major companies in this domain?
* #1 Hodlnaut
* #2 YouHodler
* #3 BlockFi
* #4 Nexo
* #5 Celsius Network


## Results

* What has been the business impact of this company so far?
* The Aave Protocol relies on a lending pool model to offer high liquidity. Loans are backed by collateral and
represented by aTokens, derivative tokens which accrue the interests. The parameters such as interest rate and
Loan-To-Value are token specific.
Aave improves Decentralized Finance’s current offering, bringing two key innovations to the lending ecosystem:
• Stable Rates to help borrowers’ financial planning;
• Flash Loans to borrow without collateral during a single transaction.
Following the launch of the mainnet, Aave will uphold its commitment to decentralization through additional features.
The Pool Factory will allow anyone to launch their own lending pool based on our smart-contracts. Governance will
be on-chain with rights represented by:
• The LEND token at Protocol level for updates of the smart contract;
• aTokens at Pool level for pool specific parameters

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?
* ompound (COMP) has been the most popular DeFi lending protocol since its launch in 2018, but according to the latest data trends, Aave (AAVE) has an excellent chance to take its crown.
Back on August 10, 2020, we explained what the burgeoning project is all about. At the time, the Aave share price was still trading under the acronym LEND and reached a market capitalization of $500 million in no time, and even then we wondered if a compound killer had been born with AAVE. Less than half a year later, its market capitalization has increased eightfold to more than 6 billion US dollars.
In terms of performance, the AAVE share price has thus surpassed that of COMP by a long way. This young year, the COMP share price started at about $145, while the AAVE share price was about $88. Currently, both the COMP and AAVE share prices are trading at around $500. This means that the challenger has grown by over 450% since the beginning of January, while COMP has seen a comparatively small (but still impressive) growth of 240%.

The market capitalization metrics tell an even more exact story. Currently, Compound’s market capitalization is $2 billion. Accordingly, AAVE exceeds it by a factor of three.
Of course, it should be noted here that just 43% of all COMP tokens are circulating. For the challenger, it is already 77%. If one were to calculate the fully diluted market cap (= market capitalization if the entire supply of tokens were in circulation at the current price) for both, Compound with $5,000,000,000 would already be closer to Aave with $8,000,000,000. Still, the $3 billion difference speaks volumes here as well.
But is Aave’s winning run over Compound justified? That’s precisely what we’ll examine in this article by contrasting the two lending protocols using significant metrics.

* How is your company performing relative to competitors in the same domain?
Aave vs. Compound: which is the more innovative protocol?
While both are conceptually quite similar protocols, the challenger proved to be more innovative and faster in implementing additional services. Aave supports over 20 different assets, while Compound supports only 11. The protocol also offers stable interest rates, while Compound does not.
Aave has pioneered developments in DeFi, including flash loans and delegated loan vaults. In December, Compound announced plans to launch Compound Chain, a standalone blockchain that would offer money market functionality across multiple chains. However, the announcement of the exact launch date has so far remained elusive.
Compound’s founder, Robert Leshner, did not comment on specific numbers. He was diplomatic, however, saying:
Compound and Aave are both gaining momentum; 2021 will be a year of phenomenal growth for both protocols.
So far, he has been proven right.
Conclusion
While Aave Compound is not necessarily going to go out of business anytime soon, the current numbers suggest that Aave could replace Compound as DeFi’s most popular credit protocol in all respects in the future due to its faster growth. The newcomer is already well ahead in many metrics. It also impresses with its more attractive token design for investors.
Nevertheless, the last word has not yet been spoken here. The sales to date suggest that the current valuation is mainly due to the future potential that the market attributes to Aave due to its innovative development. After all, the cash flow itself, compared to other DeFi protocols, is not yet very impressive.

## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
* Lending 

* Why do you think that offering this product or service would benefit the company?
* Raise capital

* What technologies would this additional product or service utilize?
* ETH

* Why are these technologies appropriate for your solution?
