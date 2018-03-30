#  IKU - A New Digital License

**Trade Clinical Trial Data Rights as a Method of Advancing Medicine**


by Gregory Rigano & Michael Kisselgof
<br /> Working Draft, Version 0.99 March 30, 2018

## Abstract 
IKU is building the first decentralized cooperative DC to accelerate clinical trials at scale by offering a new form of liquidity and risk mitigation. The DC establishes clinical trial data rights as cryptoassets to be issued and traded in an open, global market. This architecture will be supported by a distributed network of researchers and interested parties enforcing behavior, specifically efficient clinical development of medicines, amongst each other.  It uses a two token model to provide for decision making and fee derivation, maximizing global liquidity pools.

Currently, the marginial increase in lifespan is severely disproportionate to duration of research advancement. Drug development and clinical trials traditionally focus on brand new molecules that have never previously touched humans, resulting in over $1 billion spend and a ~15 year market entry point per drug - a very faulty, non-scalable process. In parallel, ~50% of existing medicines can be redeveloped to reach the market at a fraction of the cost and time<sup>[1](#f1)</sup>. Unfortunately, redevelopment initiatives fail to be capitalized due to a lack of incentivization, bounded by analogue patent policy.

Blockchain-based fintech enables incentive efficiencies where they were previously not possible. Specifically, smart contracts collapse capital, data and execution into one, providing a new digital incentive mechanism. By enabling global markets to facilitate smart contracts through a DC for redevelopment clinical trials, we can significantly increase the return in lifespan per unit of time conducted in research, no Big Pharma necessary. A digital, liquid clinical trial economy is a new paradigm, serving to improve capital formation and realization of pent up demand for new medical technology. This paper explains how to push science and medicine to boundaries yet unseen through (i) the deficiencies of the current legacy R&D model resulting in a low velocity of value, (ii) the mission of creating a digitally, liquid global market to scale clinical research and (iii) ultimately compounding value to achieve longer lifespans for as many humans as possible. 


## Table of Contents  
1. [Introduction](#introduction)
   1. [Problem Statement](#problem-statement)
   2. [IKU Approach](#iku-approach)
   3. [How](#how)
   4. [What are Smart Contracts?](#what-are-smart-contracts-?)
   5. [Why IKU?](#why-IKU)
   6. [What about Patents?](#what-about-patents?)
   7. [IKU Scales at Low Cost](#iku-scales-at-low-cost)
   8. [Token and License](#token-and-license)
   9. [The IKU Network](#the-IKU-network)
   10. [IKU Network Utility for R&D](#iku-network-utility)
2. [The Network Economy](#the-network-economy)
   1. [Research Target](#research-targets)
   2. [Dev Tools](#deve-tools)
   3. [IKU Network Participants](#iku-network-participants)
   4. [Request for Proposals](#request-for-proposals)
   5. [The Proposal Library](#the-proposal-library)
3. [Tokenization](#tokenization)
   1. [IKU](#iku)
   2. [RST](#rst)
   3. [IKU Value](#iku-value)
   4. [`RST[x]` Value](#`RST[x]`-value)
   5. [Burning](#burning)
   6. [The RST[x] permissionlessLicense](#the-rst[x]-permissionlessLicense)
   7. [Decentralized Key Management System](#decentralized-key-management-system)
   8. [The IKU Reserve](#the-elixr-reserve)
   9. [Future Development](#future-development)
5. [Conclusion](#conclusion)

## Introduction
### Problem Statement 

Medical research operates in analog fashion. And rightfully so as patents and capital formation operate under the same analog hood. Unfortunately, the patent system makes it close to impossible for the public to realize new medicines at scale.<sup>[2](#f2)</sup> Why? Patents are supported by outdated analog infrastructure that come with significant costs in trust and liquidity as there is no enforceable global record of data ownership without litigation. <sup>[3](#f3)</sup> This causes significant inefficiencies in clinical development that only large, well-capitalized corporations can sustain. These coprorations then  then seek rent from patients, insurance and the general public through high retail cost. Amazingly, the most expensive drugs in the world are for rare diseases, the smallest and most desperate patient populations, costing as much as $1 million+ per unit.<sup>[4](#f4)</sup>  Because of such inefficiency, scientists are incentivized to keep their data secret in hopes of a large corporation licensing their research data, as opposed to collaborating with their peers in an open environment.  The result is very limited investment, on a per capita basis, in clinical research and significant illiquidity as the necessary resources are firmly controlled by centralized institutions. 

Specifically, capital is nearly exclusively allocated to new molecular entities NME - molecules that have never been conceived nor had human exposure, as NME patents are most difficult to invalidate.<sup>[5](#f5)</sup> Unfortunately, NME's as are rather logistically difficult to achieve, requiring:

- ~$2.6 billion in R&D spend
- ~15 years to complete clinical trials for market access
- ~0.02% chance of obtaining FDA approval upon being discovered in the lab <sup>[6](#f6)</sup>

This model has proven to be very inefficient as pharma’s internal rate of return IRR on capital over the last ~30 years has been decreasing in a solid linear fashion, with IRR already below the cost of capital in 2017. <sup>[7](#f7)</sup> See Figure A:

**Figure A: Return on Investment in Pharma R&D**

<img width="900" alt="Return on Investment in Pharma R&D" src="https://github.com/marcgug/White-Paper/blob/master/Return%20on%20Investment%20on%20Pharma%20R%26D.png"></p>

Compound this with pharma R&D spend never outpacing non-R&D spend i.e. marketing, etc. in any given year since 1990.<sup>[8](#f8)</sup> We aslo see a decrease in medical research funding from the U.S. National Institute of Health.<sup>[9](#f9)</sup> See Figure B:

**Figure B: NIH Funding 2003-2015**

<img width="900" alt="NIH Funding 2003-2015" src="https://github.com/marcgug/White-Paper/raw/master/NIH%20Annual%20SPend.png">
 
The outcome is a ~20 year backlog of potential medicines waiting for funds to enter clinical trials - posing serious threats to life extension.<sup>[10](#f10)</sup> There are over 10,000 diseases afflicting humans of which less than 600 have known treatments.<sup>[11](#f11)</sup>  All the while generic medicines have proven to be safe and inexpensive, and can be redeveloped to treat many more diseases or conditions, for which there is currently no quality treatment.<sup>[12](#f12)</sup> Redeveloped medicines can be fully realized (e.g. FDA approved) in just one clinical trial for as little as $5 million, while significantly lowering any potential reason for future litigation.<sup>[13](#f13)</sup>  The industry model as it currently stands is clearly a failure and does not account for redevelopment of medicines.<sup>[14](#f14)</sup>  The holdup is not the science, but the incentive to efficiently mobilize resources to realize the science.  Blockchains enable digitally programmable incentive models to coordinate resources where it was not previously possible. 


### IKU Approach

A liquid clinical trial acceleration network focused on redeveloping medicines serving to efficiently achieve longer life expectancies while providing entry and exit opportunities through a fungible licensing mechanism enforced on the [Ethereum] blockchain. IKU is the Manhattan Project for clinical research efficiency. See Figure C:

**Figure C: Existing Medical Funding Models** 

<img width="900" alt="NIH Funding 2003-2015" src="https://github.com/ikunetwork/WhitePaper/raw/master/Existing%20Medical%20Funding%20Models.png">

### HOW?

By providing a global liquid architecture for redevelopment of medicines based in tokenized clinical trial data rights, transacted in a digital market. IKU leveragaes a liquid licensing protocol (see **The RST[x] `permissionlessLicense`** section below) in which all transactions are settled programmatically on a blockchain, as clinical trial R&D data rights are proved through existence of smart contract provenance. A certain threshold of tokens is required for a provable license to such rights.  This will serve to provide interested parties with rapid market entry and exit abilities, reducing transaction costs, ultimately providing coordination and liquidity advantages to parties who otherwise would not know nor trust each other. IKU essentially reinvents clinical trial R&D thru tokenization, providing transparent and open markets for the generation, tracking and exclusive usage of clinical trial R&D data sets to accelerate access to therapies. The IKU token provides value through the right to contribute to the IKU Network **IN**, more so to the IKU R&D consensus mechanism, to derive fees from the IN.  

### What are Smart Contracts?

Smart contracts are agreements with super powers, as they provide a deterministic environment that guarantee information fidelity and facilitates trusted value exchanges. Specifically, a smart contract is: (i) code that moves information and/or money based on a condition between as many parties as needed, regardless of jurisdiction (IKU will strive to obey by all applicable laws and regulations); (ii) an automatism that is guaranteed to execute as it uses algorithms (blockchain) for enforcement, not a legal system; and (iii) binding.<sup>[15](#f15)</sup>

Once a smart contract is set in motion, the blockchain is utilized to serve as an independent third party to make sure agreements are executed.<sup>[16](#f16)</sup> Efficiency increases, especially in markets that are fraught with litigation, allowing for new markets where too much overhead is required for trade and/or little exchange of information.<sup>[17](#f17)</sup> No third party is needed for escrow. Money is guaranteed to flow on contract resolution without the need to sue. Smart contracts provide justice without judges.

IKU is built on Ethereum, leveraging smart contracts to transact in clinical trial assets without the necessity of a middle man (VC, investment banks, Big Pharma, etc). This dramatically decreases barrier to entry, and allows (i) scientists and other learned persons to maximize scientific objectives by directly engaging p2p capital (for the creation and trade of peer reviewed clinical research proposals (see below) as Research Specific Tokens `RST` on the IN), (ii) anyone to participate in the market and (iii) the realization of global supply and demand of medical science as opposed to a few centralized entities with their own private interests. All transactions will be public on the Ethereum blockchain, allowing all stakeholders to collectively review and direct liquid research data, incentivizing one record of scientific truth.

### Why IKU?

IKU allows for multilateral transparency and programmatic settlement for value exchange, currently not possible within the legacy bio R&D system vulnerable to monopoly. By shifting traditional business processes from a few controlling entities to a global decentralized network, it is possible to provide a commercially valuable infrastructure for science and medicine that is both dynamic and open for all. Network participants will be able to capitalize, support and trade in efficient R&D assets through decentralized resource allocation and increased market transparency. The successful creation of this system will create a positive feedback loop both economically and scientifically. 

In addition, the IN will serve to attract R&D ideation through crowdsourced input from thought leaders and patients. Realistically, physicians and patients do not have the time, expertise or resources to commence clinical trials, resulting in drop off. The IN aims to correct this slump and inform the market of the most scientifically viable R&D initiatives. 

### What about Patents?

Typically, by the time a NME is ready to enter clinical trial, there is < 10 years left of patent life, often times only 5-6 years.<sup>[18](#f18)</sup> Jurisdictions throughout the world, including U.S., EU and Asia provide market/data exclusivity periods (independent of patents) for clinical trial data, regardless if NME or not, for up to ~10 years.<sup>[19](#f19)</sup> Generic medicines are built on the same active ingredients (as the patented drugs) once their patents or marketing exclusivities have expired.<sup>[20](#f20)</sup> They have the same dosage, effectiveness and - safety - profile as the original drug.<sup>[21](#f21)</sup> By definition, once the generic forms can be sold, the ingredient is on the market for many years and as such, generics themeselves are considered safe for patients.<sup>[22](#f22)</sup> Because their patents have expired, there is significantly less risk of infringement and significant freedom to operate. 

IKU `RSTx` holders have rights over the data they help generate and may agree to pursue a patent together as a DC, with sole ownership of rights by the DC. The `RSTx` Holder has pro-rata rights in the R&D data if they hold the respective `RST[x]`. While `RSTx` holders may pursue patent protection for inventions developed based on IN funded research, patents may not be used on the IN. IN is designed to provide global liquidity for R&D regardless of patent policy.

This will serve to provide more equitable foundations in the following:

- **Science**: As per U.S. NIH researchers, ~ 50% of generic medicines can be redeveloped to treat disease or a condition lacking viable treatment options.<sup>[23](#f23)</sup> Because existing medicines have already proven to be safe, the majority of redeveloping clinical trial intitiatives can skip Phase I (safety), move directly into Phase II (efficacy).<sup>[24](#f24)</sup> Costs to redevelop a drug for a phase II clinical trial is estimated to be as low as $5 million and takes as little as a few years for approval, as opposed to ~15 years for NME.<sup>[25](#f25)</sup> Compound this with (i) 20+ U.S. FDA medicine approvals in 2016 - 2017 on just one clinical trial (efficacy) and (ii) ~30% FDA approval rate for redevelopment medicines vs. ~ 5% FDA approval rate for NME (~.1% in lab, 10% upon entering clinical trial), the result is a higher probability of scientific success, eliminating years of uncertainty and dramatically reducing the cost.<sup>[26](#f26)</sup> Such strategy compresses the R&D pipeline, allowing for value inflection to be reached more efficienctly - accelerating market entry of inexpensive, safe medicines. Figure D illustrates how IKU streamlines research as compared to the traditional R&D pipeline:

- **Figure D: IKU vs. Traditional R&D Pipeline**

<img width="900" alt="R&D Pipeline" src="https://github.com/ikunetwork/WhitePaper/raw/master/R%26D%20Pipeline.png"> 

- **IP**: A license is required by regulatory bodies (i.e. FDA, EMA, CFDA) globally proving copyright title provenance to medical R&D data.<sup>[27](#f27)</sup> Without such a license, a party may not utilize such data for submission to a regulatory body and must start the research process anew (raising capital and performing an independent clinical trial). Licenses have proven to be worth billions of dollars to economic and medical systems worldwide.<sup>[28](#f28)</sup> IKU data will be hashed and stored on Inter Planetary File System IPFS through a NuCypher proxy-reecncryption scheme where the hash is proof of the data's existence, therefore proving genesis of the data and copyright title provenance.<sup>[29](#f29)</sup> This hash is tokenized and traded on the blockchain, enabling cryptographic, timestamped validation of each transaction, providing the current state of IKU. A license will be granted upon acquisition of a certain threshold of tokens, a proof-of-license mechanism, of which the licensee can put the redeveloped drug through already established manufacturing and distribution channels, which are abundantly available for contract. This allows for clinical trial data licenses to be liquid and accessible while also providing for efficient market access.  Parties may capitalize on data/market exclusivity periods (independent of patents) in many jurisdictions, including but not limited to:

	- Europe: up to ~10 years
	- Asia: up to ~10 years 
	- U.S.: up to ~7 years <sup>[30](#f30)</sup>
	
	Data and/or market exclusivity can be used by a `RST[x]DC` as a competitive advantage.  

- **Liquidity**: Medical research initiatives are generally inaccessible globally, remaining silo’d and permissioned as ROI on the significant R&D costs - in the order of 2-3 billion USD to bring a NME drug to markets - lead to exorbitant pricing per patient.<sup>[31](#f31)</sup> In addition, pharma companies carry significant non-R&D “baggage” i.e. marketing (as previously stated, R&D spend has never outpaced non-R&D spend i.e. marketing in any given year since 1990) as stock price is often dependent on sale volume, independent of patient effect.<sup>[32](#f32)</sup> By design, IKU's output yields (preclinical and) clinical data sets, open to any interested party, that build the basis for two related asset classes - (i) the IKU Network Token and (ii), Research Specific Token `RSTx`. The `RSTx` enables the `permissionlessLicense` as described below. Given that IKU focuses on generic drugs that are already on the market, R&D expenditures are expected to be minor by comparison, as we hypothesize that mainly Phase II should be required (see above) - hence no such demands on amortizing exorbitant R&D costs on patients have to be met. 

Cryptoassets allow for the collapse of money value and information into one, facilitating the liquid exchange of data - as opposed to few centralized entities with their own private interests to control.<sup>[31](#f31)</sup> IKU is providing the former for clinical R&D, allowing it to trade globally.  Through this architecture, we can realize global supply and demand of safe and impactful medical science at scale. 
 
Figure E further contextualizes the benefits of the IKU data approach:

**Figure E: IKU Data Approach**

<img width="899" alt="IKU Data Approach" src="https://github.com/ikunetwork/WhitePaper/raw/master/IKU%20vs.%20Patents.png">

### IKU Scales at Low Cost 
 
The current legacy model is costly as we explained above. IKU on the other hand can scale cost as IKU addresses a ~ $10 - $100  million requirement per redeveloped medicine approval vs. ~ $2.6B requirement per NME medicine approval . Figure F compares this for better context:

**Figure F: IKU Scales at Low Cost**

<img width="899" alt="IKU Scales at Low Cost" src="https://github.com/ikunetwork/WhitePaper/raw/master/IKU%20Scales.png">

At any given time, the scientific probability of a NME reaching approval is ~5%, at a cost of ~$2.6 billion over ~15 years.  

- **NME:** ~ $2.6 billion/~15 years = ~ $173 million per year spend.  

The scientific probability of a redeveloped drug achieving approval is ~30%, at a cost of ~10 - ~100 million (avg. ~$55 million) over < 5 years, the IKU model. 

- **IKU:** ~55 million/<5 years = ~ $11 million per year spend.  

We calculate the the IKU model to be ~17x less expensive with 6x greater scientific probability of approval.

### Token and License

The IN will be controlled by its users, **IKU** token holders, with no asset exchange third-party intervention, distributing the liquidity pool on a global basis to encourage and reward successful clinical trial development.  Token value on the IN can be derived from the following:

- Power to perform work for IN, including peer review R&D for capitalization
- IKU fee structure (defined below)

Licensees will either be in the form of a third party that acquires a certain threshold of tokens, engaging the `permissionlessLicense` protocol as described below, or the `RST[x]DC`. An `RST[x]DC` represents an ad-hoc, virtual collective capitalized through smart contract, open to the world at large. An `RST[x]DC` will be expected, through their project leads, to engage clinical research organizations CRO, certified manufacturing organizations CMO and distribution, all of which are established channels available for contract on a worldwide basis. 

### The IKU Network

The mission is to establish the IN as a public utility for medical research, driving efficiency through global capital formation and decentralized liquidity pools. The community will own the IN in a trustless fashion, connecting individuals, science, verified researchers/research organizations – collectively participants - and capital. The IN will operate with a core objective to establish and facilitate the IN, c
