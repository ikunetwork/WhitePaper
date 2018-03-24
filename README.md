#  IKU - Global Liquidity for Cures             
Working Draft, Version 0.99 March 23, 2018

## Abstract 
IKU is building the first decentralized cooperative DC to accelerate clinical trials at scale by offering a new form of liquidity and risk mitigation. The DC establishes clinical trial data rights as cryptoassets to be issued and traded in an open, global market. This architecture will be supported by a distributed network of researchers and interested parties enforcing behavior, specifically efficient clinical development of medicines, amongst each other.  It uses a two token model to provide for decision making and fee derivation maximizing global liquidity pools.

Currently, the marginial increase in lifespan is severely disproportionate to duration of research advancement. Drug development and clinical trials traditionally focus on brand new molecules that never touch humans, resulting in over $1 billion spend and a 15 year market entry point - a very faulty, non-scalable process. In parallel, ~50% of existing medicines can be redeveloped to reach the market at a fraction of the cost [FN: and time to treat a disease or condition for which there is currently not a quality treatment option] (cite: According to U.S. National Institute of Health researchers and supported by various computational frameworks). Unfortunately, redevelopment initiatives fail to command capital due to a lack in incentivization, bounded by analogue patent policy.

Blockchain-based fintech enables incentive efficiencies where they were not previously possible. Specifically, smart contracts collapse capital, data and execution into one, providing a new digital and math based incentive mechanism. This will serve to increase the marginal return in lifespan per unit of time conducted in research - longevity escape velocity - by enabling global markets to facilitate redevelopment clinical trials through a DC. No Big Pharma necessary. A digital, liquid clinical trial economy is a new paradigm, serving to improve capital formation and realization of pent up demand for new medical technology. This paper explains how to push science and medicine to boundaries yet unseen through (i) the deficiencies of the current legacy R&D model resulting in a low velocity of value, (ii) the mission of creating a digitally, liquid global market to scale clinical research and (iii) ultimately compounding value to achieve longevity escape velocity - . IKU's goal is to help acheive life extension. 


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
   9. [The IKU Foundation](#the-IKU-foundation)
2. [The Network Economy](#the-network-economy)
   1. [Research Targets](#research-targets)
   2. [Dev Tools](#deve-tools)
   3. [Participants](#participants)
   4. [Request for Proposals](#request-for-proposals)
3. [Tokenization](#tokenization)
   1. [ELX Utility](#elx-utility)
   2. [RST Utility](#rst-utility)
   3. [The RST permissionlessLicense](#the-rst-permissionlessLicense)
   4. [SMART K for permissionlessLicense](#smart-k-for-permissionlessLicense)
   5. [Royalties](#royalties) [CONSIDER DELETING THIS]------------------------------------------ OR SAVING FOR LATER
   6. [Fees and the Network Digital Wallet](#fees-and-the-network-digital-wallet)
   7. [Network Utility for R&D](#network-utility-for-rd)
   8. [The IKU Reserve](#the-elixr-reserve)
   9. [Phased Rollout + The RST Bundle](#phased-rollout-the-rst-bundle)
4. [Token Distribution](#token-distribution) (TODO)
5. [Conclusion](#conclusion)

## Introduction
### Problem Statement 

Medical research operates in analog fashion. And rightfully so. Even patents and capital formation operate under the same analog hood. Unfortunately, the patent system makes it close to impossible for the public to realize new medicines at scale.  Why? Patents are supported by outdated analog infrastructure that come with significant costs in trust and liquidity as there is no enforceable global record of data ownership without litigation. [FN - bracket below] This causes significant inefficiencies in clinical development that large, well-capitalized corporations can only sustain. These coprorations then  then seek rent from patients, insurance and the general public through high retail cost. Amazingly, the most expensive drugs in the world are for rare diseases, the smallest disease patient populations, costing as much as $1 million+ per unit.  Because of such inefficiency, scientists are incentivized to keep their data secret in hopes of a large corporation licensing their research data, as opposed to collaborating with their peers in an open environment.  The result is very limited investment, on a per capita basis, in clinical research and significant illiquidity as capital is firmly controlled by centralized institutions. In addition:

 [Drop this to a FN: Such inefficiencies have caused significant  IP law has attempted to enforce, but enforceability is difficult, time consuming and expensive as:

- patent litigation costs ~ $30 billion per year
- ~80% of the litigation comes from patent trolls [insert: what is a patent troll footnote]
- 50%+ of U.S. patents are being invalidated in post-grant proceedings,

All of which lead to significant issues in transaction finality, exacerbating an already illiquid market.

Capital is nearly exclusively allocated to new molecular entities NME - molecules that have never been conceived nor had human exposure, as NME patents are most difficult to invalidate. Unfortunately, NME's as are rather logistically difficult to achieve, requiring:

- ~$2.6 billion in R&D spend
- ~15 years to complete clinical trials for market access
- ~0.02% chance of obtaining FDA approval 

This model has proven to be very inefficient as pharma’s internal rate of return IRR on capital over the last ~30 years has been decreasing in a solid linear fashion, with IRR already below the cost of capital in 2017. See Figure A:

**Figure A: Return on Investment in Pharma R&D**

<img width="900" alt="Return on Investment in Pharma R&D" src="https://github.com/marcgug/White-Paper/blob/master/Return%20on%20Investment%20on%20Pharma%20R%26D.png"></p>

Compound with pharma R&D spend never outpacing non-R&D spend i.e. marketing, etc. in any given year since 1990. We aslo see a decrease in medical research funding from the U.S. National Institute of Health. See Figure B:

**Figure B: NIH Funding 2003-2015**

<img width="900" alt="NIH Funding 2003-2015" src="https://github.com/marcgug/White-Paper/raw/master/NIH%20Annual%20SPend.png">
 
The issues addressed thus far pose serious threats to drug discovery and thus, life extension - IKU's ultimate goal. There are over 10,000 diseases afflicting humans, 7,000 of which are rare disease and less than 600 with known treatments. The outcome is a ~20 year backlog of potential medicines waiting for funds to enter clinical trials. All the while generic medicines have proven to be safe and inexpensive, and can be redeveloped to treat many more diseases or conditions for which there is currently no quality treatment. The industry model does not account for redevelopment of medicines, which has proven to be safe and inexpensive. Redeveloped medicines can be fully realized (e.g. FDA approved) in just one clinical trial for as little as $10 million, while significantly lowering any potential reason for future litigation. The holdup is not the science, but the incentive to mobilize resources to efficiently realize the science. Blockchain is a solution as it enables coordination through multilateral agreements where they were not previously possible. 


### IKU Approach

A liquid clinical trial acceleration network, serving to efficiently achieve longevity escape velocity while providing liquid exit opportunities through a fungible, licensing mechanism enforced on the Ethereum blockchain. IKU is the Manhattan Project for clinical research efficiency. See Figure C:

**Figure C: Existing Medical Funding Models** 

<img width="900" alt="NIH Funding 2003-2015" src="https://github.com/marcgug/White-Paper/raw/master/Existing%20Medical%20Funding%20Models.png">

### HOW?

By providing a global liquid architecture for redevelopment of medicines based in tokenized clinical trial data rights, transacted in a digital market. IKU leveragaes a liquid licensing protocol in which all transactions are settled programmatically on a blockchain as clinical trial R&D data rights are proved through existence of smart contract provenance.  This will serve to provide interested parties with rapid market entry and exit abilities, reducing transaction costs, ultimately providing coordination and liquidity advantages to parties who otherwise would not know nor trust each other to engage in capital formation and trade. IKU essentially reinvents clinical trial R&D thru tokenization, providing transparent and open markets for the generation, tracking and exclusive usage of clinical trial R&D data sets to accelerate access to treatments and anti-aging technology. The IKU token provides value through the right to contribute to the IKU Network **IN**, more so to the IKU R&D consensus mechanism, to derive fees from the IKU Network.  

### What are Smart Contracts?

Ethereum is the internet's government, and smart contracts are its laws. Smart contracts are agreements with super powers, as they facilitate programmtic settlement of information value transfer. They are the enforcers of the law and are exceuted exactly as they are defined. A smart contract is: (i) code that moves information and/or money based on a condition between as many parties as needed, regardless of jurisdiction (IKU will strive to obey by all applicable laws and regulations); (ii) an automatism that is guaranteed to execute as it uses algorithms (blockchain) for enforcement, not a legal system; and (iii) binding.

Once a smart contract is set in motion, the blockchain is utilized to serve as an independent third party to make sure agreements are executed. Efficiency increases, especially in markets that are fraught with litigation, allowing for new markets where too much overhead is required for trade and/or little exchange of information. No third party is needed for escrow. Money is guaranteed to flow on contract resolution without the need to sue. Smart contracts provide justice without judges, lawyers and court fees.

IKU is built on Ethereum, leveraging smart contracts to transact in clinical trial assets without the necessity of a middle man. This dramatically decreases barrier to entry, and allows (i) scientists and other learned persons to directly engage capital for the creation and trade of peer reviewed clinical research proposals (see below) as Research Specific Tokens **RST** on the IN, (ii) anyone to participate in the market and (iii) the realization of global supply and demand of medical science as opposed to a few centralized entities with their own private interests. All transactions will be public on the Ethereum blockchain, allowing all stakeholders to collectively review and direct liquid research data, incentivizing one record of scientific truth.

### Why IKU?

IKU allows for multilateral transparency and contractual settlement for R&D, currently not possible within the legacy bio R&D system, vulnerable to monopoly. By shifting traditional business processes from a few controlling entities to a global decentralized network, it is possible to provide a commercially valuable infrastructure for science and medicine that is both dynamic and open for all. Network participants will be able to capitalize, support and trade in efficient R&D assets through decentralized resource allocation and increased market transparency. The successful creation of this system should create a positive feedback loop both economically and scientifically. 

In addition, the IN will serve to attract R&D ideation through crowdsourced input from thought leaders and patients. Realistically, physicians and patients do not have the time, expertise or resources to commence clinical trials, resulting in drop off. The IN aims to correct this slump and inform the market of the most scientifically viable R&D initiatives. 

### What about Patents?

Typically, by the time a NME is ready to enter clinical trial, there is < 10 years left of patent life, often times only 5-6 years. Jurisdictions throughout the world, including U.S., EU and Asia provide market/data exclusivity periods (independent of patents) for clinical trial data, regardless if NME or not, for up to ~10 years. Generic medicines are built on the same active ingredients (as the branded drugs) once their patents or marketing exclusivities have expired. They have the same dosage, effectiveness and - safety - profile as the original drug [1]. By definition, once the generic forms can be sold, the ingredient is on the market for many years and as such, generics themeselves are considered safe for patients. Because their patents have expired, there is significantly less risk of infringement and significant freedom to operate. 

RST Holders have rights over the data and may agree to pursue a patent together as a DC, with sole ownership of rights by the DC. The RST Holder has pro-rata rights in the R&D data if they hold the respective RST. Participants may pursue patent protection for inventions developed based on IN funded research, but such patents may not be used on the IN. IN is designed to provide global liquidity for R&D data regardless of patent policy.

This will serve to provide more equitable foundations in the following:

- **Science**: As per U.S. NIH researchers, ~ 50% of generic medicines can be redeveloped to treat disease or a condition lacking viable treatment options, including aging. Because existing medicines have already proven to be safe, the majority of redeveloping clinical trial intitiatives can skip Phase I (safety), move directly into Phase II (efficacy). Costs to redevelop a drug for a phase II clinical trial is estimated to be as low as $5 million and takes as little as a few years for approval, as opposed to 13-15 years for NME [6]. Compound this with (i) 20+ FDA medicine approvals in 2016 - 2017 on just one clinical trial (efficacy) [FN: The large scale, and very expensive multicenter Phase III trials (assessing safety and efficacy in comparison to standard treatment) are generally acknowledged to be very difficult to set up for rare diseases (< 200,000 patients/year [2]), for which also often no therapy exists (~7000 rare diseases, affecting 25-30 million Americans alone, for which there are 400+ drugs and biologics [2]); drugs targeting rare diseases are therefore commonly approved with Phase II data only such as in the case of 20+ different FDA approvals in 2016 - 2017 - END FN]. and (ii) ~30% FDA approval rate for redevelopment medicines vs. ~ 5% FDA approval rate for NME upon entering clinical trial, the result is a higher probability of scientific success while eliminating years of uncertainty, dramatically reducing the cost. Such strategy compresses the R&D pipeline, allowing for value inflection to be reached sooner and at lesser cost - accelerating market entry of inexpensive, safe medicines. 

- **IP**: A license is required by regulatory bodies (i.e. FDA, EMA, CFDA) globally proving copyright title provenance to medical R&D data. Without such a license, a party may not utilize such data for submission to a regulatory body and must start the research process anew (raising capital and performing an independent clinical trial). Licenses have proven to be worth billions of dollars to economic and medical systems worldwide. IKU data will be hashed and stored on Inter Planetary File System IPFS through a NuCypher proxy-reecncryption scheme where the hash is proof of the data's existence, therefore proving genesis of the data and copyright title provenance. This hash is then tokenized and traded on the blockchain, enabling cryptographic, timestamped validation of each transaction, providing the current state of IKU. A license will be granted upon acquisition of a certain threshold of tokens, a proof-of-license mechanism, of which the licensee can put the redeveloped drug through already established manufacturing and distribution channels, which are available for contract. This allows for clinical trial data licenses to be liquid and accessible while also providing for efficient market access.  Parties may capitalize on market/data exclusivity periods (independent of patents) in many jurisdictions, including but not limited to:

	- Europe: up to ~10 years
	- Asia: up to ~10 years 
	- U.S.: up to ~7 years 
	
	New data and/or market exclusivity can be built on top of an RST DC and/or `permissionlessLicense` (which confers timed data exclusivity) as it is collectively owned by the DC as a competitive advantage.  

- **Liquidity**: Medical research initiatives are generally inaccessible globally, remaining silo’d and permissioned as ROI on the significant R&D costs [4] - in the order of 2-3 billion USD - to bring a NME drug to markets lead to exorbitant pricing per patient. In addition, pharma companies carry significant non-R&D “baggage” i.e. marketing (as previously stated, R&D spend has never outpaced non-R&D spend i.e. marketing in any given year since 1990) as stock price is often dependent on sale volume, independent of patient effect. By design, IKU's output yields (preclinical and) clinical data sets, open to any interested party, that build the basis for 2 related asset classes - (i) the IKU Network Token and (ii), Research Specific Token RST. The RST enables the `permissionlessLicense` as described below. Given that IKU focus on non-branded drugs that are already on the market, R&D expenditures are expected to be minor by comparison, as we hypothesize that mainly Phase II should be required (see above), hence no such demands on amortizing exorbitant R&D costs on patients have to be met. By allowing R&D to trade globally, we can realize global supply and demand of medical science. Cryptoassets allow for the collapse of money value and information into one, facilitating the liquid exchange of data - as opposed to few centralized entities with their own private interests to control. IKU is providing the former for medical R&D. 
 
Figure D further contextualizes the benefits of the IKU data approach:

**Figure D: IKU Data Approach**

<img width="900" alt="IKU Data Approach" src="https://github.com/marcgug/White-Paper/raw/master/IKU%20Data%20Approach.png">

[Show visual of compressing the pipline - stripping the pipline of preclinical and at least half of Phase I - keep Phase II - and strip Phase III.  - use this from th francis collins NIH director talk]

### IKU Scales at Low Cost 
 
The current legacy model is costly as we explained above. IKU on the other hand an scale cost as IKU addresses a $100 million non-patent market vs. $2.6B patent market (redeveloping generic NME vs. conservative mode). Figure E compares non-patent vs. patent for better context:

**Figure E: IKU Scales at Low Cost**

<img width="900" alt="IKU Data Approach" src="https://github.com/marcgug/White-Paper/raw/master/IKU%20Scale%20Cost.png">

At 100% saturation (maximum share the network will take of its target market), IKU estimates to potentially address a market of 200 projects on average per year with a 30% chance of FDA approval. Thus 60 approved medicines on average per year. In fact, IKU can scale even higher with non-patent projects costing less than $100 million.

### Token and License

IKU will be controlled by its users with no asset exchange third-party intervention, distributing the liquidity pool to encourage and reward successful clinical trial development. The IN will be bootstrapped by token **IKU**. Token value on the IN can be derived from the following:

- Power to make decisions and perform work for IN, including peer reviewed R&D for capitalization
- IKU fee structure (defined below)

Licensees will either be in the form of a third party that acquires a certain threshold of tokens, engaging the `permissionlessLicense` protocol as described below, or the `RST[x]DC`. An `RST[x]DC` represents an ad-hoc, virtual collective capitalized through smart contract, open to the world at large. An `RST[x]DC` will be expected, through their project leads, to engage clinical research organizations CRO, certified manufacturing organizations CMO and distribution, both of which are established channels available for contract on a worldwide basis. 

### The IKU Foundation

The IN will operate as IKU Foundation, a Singapore [nonprofit] organization whose core objective is to establish and facilitate the IN, create IKU, maintain the IKU reserve and evangelize R&D efficiencies.  In addition, the IN will maintain a grants program in which bounties will be issued for (i) eliminating issues in the IKU code and (ii) accomplishing specific medical innovations i.e. developing effective cancer treatments, aging treatments, etc. Circulating IKU will vote on the priority of bounties, capital allocation, and have the right to perform work for IN. To be clear, after the IN is live as described below, there will be no difference between the IN and the IKU Foundation.  The mission is to establish the IN as a public utility for medical research, driving efficiency through global capital formation and decentralized liquidity pools. The community will own the IN in a trustless fashion, connecting individuals, science, verified researchers/research organizations – collectively participants - and capital. 

## The Network Economy
The IN combines the wisdom of crowds with the wisdom of science thru participant communication, capital and data exchange. The following tools will give life to the IN: `researchTarget`, `devTools`, Request for Proposals `RFP`, and the `permissionlessLicense`. 


### `researchTarget`

Any person with internet access may frictionlessly submit a `researchTarget` which may be a concrete, verifiable objective or broad target. For example:
- Verifiable Object: Repurposing generic medicine X in a slow release formulation to treat pancreatic cancer
- Broad Target: Advancing research against ALS 

Among other aspects, the `researchTarget` may specify medical conditions, technology type i.e therapy, device, vaccine, etc., mechanism of action, or any other known R&D metric. The `researchTarget` will be visible and sortable to the public, allowing for thorough analysis and determination of demand. The public will be able to upvote a `researchTarget` - spam protected thru captcha.

### `devTools`

Participants will access the EN through a `devTools` integrated interface. The `devTools` consist of the following:
- `RFP` submission forms
- Wallet registration
- Topic forums
- Friends (facebook style network)
- Direct messaging
- Reputation
- Upvote
- Share
- Comment
- Peer Review
- Upgrade to clinical trial subject 
- Participate in pricing of medicine/technology

Friends, message, and upvote access will require an IN profile, but will not require holding IKU in the Network Digital Wallet NDW. This type of access is classified as `devTools A`.  RFP submissions, comments, peer review, reputation scoring and upgrading to clinical trial subject will require an IN profile AND holding at least 1 IKU in the NDW - `devTools B`.  

### IKU Network Participants

Below are the players in the IKU Network. They are not mutually exclusive:

- **IKU Holder**: IKU token holder; can be an individual, institution, private company, etc. (described further below)
- **RST Holder**: Research Specific Token holder; can be an individual, institution, private company, etc. (described further below)  
- **VR**: Verified Researcher i.e. MD, PhD, etc. whose expertise is credentialed through the IN. The VR can propose and respond to  a `researchTarget`, vote on their viability and review proposals. He/she is fundamental to the IKU Peer Review process.  
- **ADV** Anonymous data viewer - the public, who freely contributes a `researchTarget`, views projects on the IN and has the option to create an IN profile to access `devTools A`. The IN will make information ethically and publicly available as current clinical trial results are typically not open to the public - even though they are required to be.  In addition all RST initiatives will post a gnatt chart for how advanced their research initiative is as well as the top line de-identified research data they have generated on a quarterly basis.

Participants will be subject to a `reputationScore`:

- `reputationScore` is part of `devTools`. All participants will be subject to a profile linked `reputationScore` which accounts for utilization of IN resources and behavior, allowing for meritocratic decision-making based in scientific liquidity. All IN participants start with the same `reputationScore`, but will be separated by VR and non-VR. `reputationScore` may increase to `power`, `super_power` and `grand_maester`.  This enables the best ideas to flow freely, producing efficient and rapid evolution based on merits. Participants will be obligated to provide `reputationScore` to other participants they have digitally engaged.  The `reputationScore` will be publicly available.

### Request for Proposals

The IN will serve to produce requests for peer reviewed proposals `RFP` in response to the `researchTarget`. A VR will be able to submit proposals at any time as paid for by the IN reserve, whereas non-VR will be required to post a bond to submit a proposal, in response to a `RFP`.  

RFP Template: https://docs.google.com/document/d/1vIZyS90e-aiWynNalBplVmUAJPtMZajXw7gdfjjBozk/edit
RFP Score: https://docs.google.com/document/d/1gnY8KdrvTtcWzok7rYUPKsL7mh-nCyyaMEdcEd5yosU/edit

**BRUNO - RFP THRESHOLD MET - SMART CONTRACT SPAWNED - RST**

An `RFP` is required to consist of (i) a principal investigator PI that leads the R&D team along with the RST Holders that the PI and his/her team will have to answer to (see below RST value), (ii) how much capital is being raised and for what percentage of RST, with proposers encouraged to not issue 100% of RST's to account for future capital requirements and (iii) the scientific justification, etc (see google doc above). A standard RST Proposal template will be provided by the IN for `RFP`. Further `RFP` value may be determined by the IKU user submitting the proposal, allowing for a flat environment in which value proposition may be programmed into an RST. This leaves significant room for RST value creativity.

## The Proposal Library

Network-based computational biology analysis has become a widely used strategy for determining drug redevelopment piplines due to the ever-increasing pace of bio and chemical information available (Costa, 2014).  Various different computational approaches, including deep learning, matrix factorization methods and various algorithms have proved beneficial in navigating the wealth of information to uncover potential drug redevelopment leads. Unfortunately, this information is often fragmented and to date, has lacked economic incentive for the proper capital formation to enable proper clinical trials.

The IN will serve to be a hub for such information allowing for a unified workflow of the most promising redevelopment initiatives along with the economic incentives to bring such initiatives to clinical trial. The IKU Peer Review will “stand on the shoulders” of the computational analysis that has been completed to date to provide a highly predictive, robust repurposing pipeline. VR and non-VR are incentivized to ‘bruteForce’ peer review (described below) to earn fees from the IN in the form of BTC, ETH and RST - incentivizing the the most promising redevelopment initiatives to be capitalized. As this process generates data and continues to grow, it will serve to provide open source algorithims for potential new uses of existing medicines.  

IKU peer review serves as the IKU R&D consensus mechanism, with the ultimate goal of achieving the longevity escape velocity for as many humans as possible. Participants will use the `devTools` to peer review, allowing for a community R&D demand oracle and prediction index, encouraging capitalization of highly rated proposals.  

The review period requires the IN peer review process to score an `RFP`, which can be defined as a function:

	`β` = `f(α,φ,θ)` = `RFP` score - PUBLIC
	`α` =  pariticipant`reputationScore` (a VR's `α` is weighted 2x)
	`φ`: Sum of `RFP` upvotes  
	`θ`: IKU balance weight 
	`λ`: A random threshold value
	
`β` is expected to be optimized overtime with IN demand.

Upon `β` > `λ`, an RST smart contract is created, `RST[x]`, responsible for minting `RST[x]` which in turn is used to fund `RFP`.  Upon `RST[x]` achieving its softcap - minimum `RST[x]` required to achieve milestone:

1. [y%] of the funds will be released to the R&D team,
2. All RST Holders will be able to participate in an `RST[x]DC` on a per project basis, and
3. ELX Holders earn fees in RST as described below under **Fees and the Network Digital Wallet**.

Funds released to the R&D team in BTC, ETH and IKU can be converted to fiat, through a trusted third party crypto to fiat provider such as Coinbase. In addition, prior to initiating a clinical trial, an RST DC will be responsible for ensuring ethical compliance through an institutional review board.

## Tokenization 

The IN creates two classes of native tokens:

- **IKU**: The IN token IKU serves to secure the IN with consensus on R&D, allow for IN decision making and fee 	derivation as further explained under IKU Utility. The supply of IKU is finite. [Note to Greg: insert from consoliated notes]
	
- **RST**: The research specific token RST is representative of the R&D it was specifically created to fund.  RST supply is determined by proposers and is dependent on the project economics it is used to fund and facilitate. RST bundles, RSTi, are expected to be developed, allowing for scientific and economic risk diversification where *i* represents the number of RST’s bundled. 

**Insert Token Smart Contract**

### IKU Value

Wallet verification of a minimum of balance of 1 IKU enables access to the `devTools B` and fees as explained under **Fees and the Network Digital Wallet**. Value in the IKU token can be ascribed to access to the following:

- `devTools B`
- power to make decisions and perform work for IN
- 2nd priority to upgrade to clinical trial subject
- Fees

### RST Value

An RST carries pro-rata rights to its specific R&D initiative and such rights are cryptographically maintained with the ability to (i) access the `RST[x]` DC and (ii) be transacted in an `permissionlessLicense` smart contract. Value in the `RST[x]` token can be ascribed to the following: 

- `permissionlessLicense` threshold
- 1st priority to upgrade to clinical trial subject
- Access to medicine upon regulatory approval at a discounted (or free) rate [with prescription from a licensed MD]
- RST DC governance including **Voting rights to release funding for next stage of RST roadmap** (must achieve security to do this b/c this will be a target for hacking) + remove PI, etc. [Note to Bruno: See DAICO/Aragon smart contracts?]

R&D data will be made available to `RST[x]` holders and updated by the `RST[x]` team through the IN infrastructure on an ongoing basis. RST R&D data/IP will de-identified and be stored on IPFS. Access to the data/IP will be made available with possession of a minimum, predetermined RST threshold and private key, unless otherwise made public thru IKU. A transaction involving RST is the cryptographic validation of rights transfer to RST hashed data, timestamped by the blockchain. This is transparently irrefutable evidence of both proof of the data's existence and rights provenance on Inter Planetary File Systems/Inter Planetary Linked Data IPFS at a given point in time, protecting against reasons for litigation.

*Insert RST smart contract code*

IPFS will serve to provide infrastructure for the `RST[x]` DC. The R&D team will provide updates to the RST Holders in their DC on a regular basis, in which `RST[x]` holders will have ability to:

(i) Determine whether R&D team should have access to remainder of funds for continuing research (upon reaching or not reaching R&D milestone x - oracle),
(ii) Upgrade to clinical trial subject,
(iii) Provide reputation scores to fellow RST[x] holders and the R&D team
(iv) remove R&D operations personnel upon achieving RST DC majority consensus.

The RST DC is incentivized to provide timely and relevant information to both its own DC and the public as the RST and also IKU will be at the mercy of market sentiment. IKU and RST tokens are expected to trade in real time, globally in the cryptourrency market place.  If an RST DC does not operate efficiently, the value of their RST will likely decrease and likely further affect IKU value. 

### The RST `permissionlessLicense`

The `permissionlessLicense` facilitates digital scarcity as an additional efficienct economic incentive vehicle. The `permissionlessLicense` protocol allows for global trade of any data or IP, that has scarcity properties, as cryptographic assets. Acquisition of a certain threshold of cryptographic assets - a token supply number which is predetermined at the time of the `RFP` creation - triggers an automatic license to the data or IP generated by the DC. This allows for a license to be highly available and auditable as it is a datapoint on a blockchain. In IKU's case, a `permissionlessLicense` would be granted upon a certain Ethereum address holding z% of outstanding Cannabis Pain Treatment/MAPS RST’s. The party who holds the private key to such Ethereum address now has a license to utilize and exploit the clinical trial data, e.g. completed Phase II clinical trial data,  to potentially submit to the U.S. FDA for approval. The more scientifically advanced the R&D initiative, the greater the potential demand as the data and its corresponding license and therefore RST becomes more scientifically valuable i.e. completing Phase II clinical trials and therefore more value will be required by one who desires a `permissionlessLicense` to achieve the RST threshold.

The IN will provide a standard `permissionlessLicense` with drop down variables such as territory, RST license threshold, required efforts require good faith development (e.g. marketing approval within [x time]), amongst others [period of time and royalty rate].  This will enable proposers to click through, filling in variables at their discretion. This dramatically reduces the need for negotiation, lawyers and other middlemen, enabling an open streamlined licensing process.     In addition, parties will have the opportunity to provide their own customized license which will be subject to market demand.

Specifically, the `permissionlessLicense` license enables exit opportunities for RST holders to license RST-backed data which can be obtained by any interested party (e.g. health insurance distributor, traditional pharma, venture, etc.).  If the `permissionlessLicense` threshold is not achieved after a succcessful Phase II clinical trial, the RST DC may become a collective ad hoc venture team around its cryptoasset, e.g. an approved rare disease treatment with 7 years of market exclusivity in the U.S., for further development, market distribution, etc.  This creates a self perpetuating ecosystem of innovation and multiple opportunities for IKU and RST holders, as well as other parties interested in licensing.

Upon the public release of the IN, IKU token holders will be able to decide what happens to RSTs that are not part of the `permissionlicense`.  This may include creating a software bounty thats allows for royalties to flow to the remaining outstanding RSTs in exchange for work or in the alternative, as a securitized asset.  Because RSTs are traded on the [ethereum] blockchain, provenance of RST data rights are known, facilitating potential trustless royalty distribution to RST holders from the licensee.  Note that this will be up to IKU token holders to decide and may never come to fruition.

### NuCypher KMS - `permissionlessLicense`
*placeholder*

### Fees and the Network Digital Wallet

Establishing a profile on the EN provides access to the Network Digital Wallet NDW.  The NDW will serve to hold BTC, ETH, IKU and all RST's, and is expected to also hold digitalized fiat, providing for efficient capital formation and communication. In addition the NDW enables IKU holders to earn fees in RST as [x%] of all of the **fundedProposal** RSTs, pro-rata, will flow to IKU holders in exchange for preforming a certain threshold of work on the IN, e.g. participating in the peer review process. Such model gives an IKU holder the opportunity to have rights to all the research on the iku.network. 

### Network Utility for R&D 

The following sequence of events illustrate Network utility and ability to facilitate global capital formation for medical R&D initiatives:

**Figure E: The Network Utility**

<img width="900" alt="Global capital formation" src="https://github.com/marcgug/White-Paper/raw/master/Network%20Utility.png">

1. Submit a `researchTarget` for consideration. The `researchTargets` is public, accessible,  and can be upvoted captcha.  
2. Login to EN to use the `devTools A`. If participant possess IKU, he/she can login and access `devTools B`. A VR is guaranteed access to ‘devTools B’, as funded by the elixrONE reserve. An non-VR must purchase IKU and must post bond of to make submit RFP, protecting against spam. 
3. RFP:
- RFP submissions must include their scientific, economic and strategic approach to their R&D initiative.
- RFP submissions must utilize IKU smart contract templates.
4. Peer review commences.  Upon `β` > λ, an RST contract is created, `RST[x]`, responsible for minting `RST[x]` to fund proposal.  Upon `RST[x]` achieving its softcap :
(i) funds will be released to the R&D team,
(ii) all RST Holders can participate in the RST DC,
(iii) IKU Holders that have a Network Digital Wallet (and VR) earn fees in RST.
5. R&D team commences and stores all data on IPFS only available for RST team protected thru proxy re-encryption.
6. `RST[x]` available for `permissionlessLicense` and RSTi, globally liquid.

**NOTE: SHOULD WE DELETE THE LIST AND JUST KEEP THE FLOW CHART?  THE FLOW CHART SHOULD BE CONDENSED TO MAXIMUM 5 BUBBLES**

### The IKU Reserve
The IN will maintain all funds raised from the token sale, along with IKU as necessary for incentivizing VR peer review, liquidity and community bounties in both software and medicine.  All foundation transactions and bounties will be public, enabling anyone to see its balance sheet in real time. [we cannot hold this as custody - we could keep it in an ethereum multisig w a certain threshold of votes to unlock it - does OZ have a multisig contract we can use?] -BRUNO
   
### Future Development

While IKU in its initial phase will focus on redeveloping drugs, we anticipate focusing on for adjacent opportunties to achieve longevity escape velocity including rejuvenation tech, biomarker analysis, age-related disease prevention and nanotechnology

As to the platform itself, additional IN features are expected to be developed and/or integrated based on IKU decision making to further enable medical R&D efficiency, which may include but are not limited to advanced analytic and platform navigation tools, as well as links to language agnostic relevant public and private content through APIs (e.g., PubMed, IP Databases). This will improve workflow efficiency and thus lead to enhanced platform performance. 

As to specific anticipated service components, dependent on IKU token holder decision making, a software bounty may be deployed for RSTi bundling, *i* representing the number of RST’s bundled, as stated below:

Bundling may serve to enable various medical R&D financial products to mitigate economic and scientific risk exposure as well as provide horizontal, or vertical, research collaboration. As opposed to a traditional centralized corporation, the RST bundle lowers the cost of both trust and risk.

How to bundle:
- Declare RST eligible to bundle with *i-1* in the `RFP`, during token sale, or later point in time
- Declare RST seeking bundle

All IN R&D initiatives would have the option to actively bundle their RST’s into RSTi, or allow for RSTi to choose to bundle with an RST, with atomic swap capability, allowing for high performant assets to be transacted globally across, or in the same, R&D verticals. Atomic exchange serves as a mechanism to reduce risk and stabilize IKU/RSTi in a frictionless fashion, as atomic assets do not need to be traded on a centralized exchange, but can be swapped for one another through direct p2p algorithmic execution.

*Insert Atomic Swap code*. 

This would be especially important for clinical trials in the same research vertical i.e. condition, disease, mechanism of action, molecule, etc. as it mitigates scientific and economic risk. Capital resources would be allocated purely towards R&D with the ability to algorithmically bond with each other thru smart contract. 

Pricing a bundle can be defined by the expected value:

<img width="200" alt="Expected Value" src="https://github.com/marcgug/White-Paper/raw/master/Expected%20Value.PNG">

### Burning - mike lets go thru this - see Kyle Samani token burning - this must already be programmed into the contract

IKU aligns its burning strategy with the creation of RST, where [x%] of IKU tokens contributed to a specific RST are burned from the IKU Reserve. The same percentage of the specific RST pool are also offered to IKU Token holders. Burning serves to increase the economic and utility value of the IKU Token, and build on the liquidity mechanism. 

For example: 

- A researchTarget is submitted for Levodopa Trials - Cure Parkinson’s. The Alice Foundation submits an RFP for the researchTarget of which the IN accepts and an associated fundraise commences. The fundraise is successful and the associated RST  Levodopa Trials - Cure Parkinson’s is created. [x%] of the total contributed IKU tokens are burned from the IKU Foundation Reserve pool, and the same [x%] in RST are evenly distributed to all IKU Token holders, pro-rata based on IKU holdings.

- Let’s say Bob contributed 500 IKU tokens to RST Levodopa Trials - Cure Parkinson’s. The Alice Foundation receives all 500 IKU tokens of which they can exchange for FIAT. Bob’s contributed IKU tokens are not burned.The Alice Foundation’s IKU Tokens received from BOB are not burned as well, but rather [x%] of the total contributed IKU tokens are burned from the IKU Reserve pool. The same [x%] of the RST pool is transferred back to all funders who held IKU tokens at the time of funding, pro-rata based on IKU holdings. Thus Bob receives a piece of that [x%].


## Conclusion
iku.network will serve to enable unprecedented global organization and deployment of resources. Decentralizing resource allocation and asset transactions allows for increased transparency of market activity which is expected to lead to significant medical innovation in the near future. The foregoing working draft has sketched a paradigmatically novel vision of the structural and organizational means by which this can dramatically increase the reward for efficient medical R&D, reduce the risk of failure, all the while enabling global, decentralized liquidity. We expect the IN to be a critical infrastructure piece to spark and launch the entire patent agnostic digital medical R&D system.  This is the fundamental intention and the essence of the IN.

## Footnotes
<b id="f1">1</b> 21st Century Cures Whitepaper, A Path to Discovery, Development, Deli very, https://energycommerce.house.gov/cures/ (2016).[↩](#a1)

<b id="f2">2</b> Roger Stein, MIT Research Associate, A Bold New Way to Fund Drug Research, TED Talk (2013).[↩](#a2)

<b id="f3">3</b> NIH Budgets Office, NIH Funding FYs 2000 – 2016, Association of American Medical Colleges, (2016).[↩](#a3)

<b id="f4">4</b> Andrew Lo, Jose Maria Fernandez, et. al., Can Financial Engineering Cure Cancer, MIT, American Economic Review (2013).[↩](#a4)

<b id="f5">5</b> James Bessen, The Evidence is in: Patent trolls do hurt innovation, Harvard Business Review (2014). Gene Quinn, et. al., Are More than 90% of Patents Challenged at the PTAB Defective?, IPWatchdog (2017).  Robert Sachs, Fenwick & West LLP, Patent Invalidity Rates: The Summertime Blues Continue, Law 360 (2015).[↩](#a5)

<b id="f6">6</b> Tufts Center for the Study of Drug Development, How the Tufts Center for the Study of Drug Development Pegged the Cost of a New Drug at $2.6 Billion (2014).  James W. Henderson, Health and Economics Policy (2017).[↩](#a6)

<b id="f7">7</b> J. Hudson et. al., Into the valley of death: from research to innovation, https://www.ncbi.nlm.nih.gov/pubmed/23402848 (2013).[↩](#a7)

<b id="f8">8</b> Vitalik Buterin, A NEXT GENERATION SMART CONTRACT & DECENTRALIZED APPLICATION PLATFORM, ethereum/Wiki.[↩](#a8)

<b id="f9">9</b> Nick Szabo, Formalizing and Securing Relationships on Public Networks (1997), http://firstmonday.org/ojs/index.php/fm/article/view/548/469-publisher=First#introduction. [↩](#a9)

<b id="f10">10</b> Bruce Bloom, Cures Within Reach, http://www.the-scientist.com/?articles.view/articleNo/47744/title/Repurposing-Existing-Drugs-for-New-Indications/ (2017).  Bernard Munos, Faster Cures, https://www.nature.com/news/can-you-teach-old-drugs-new-tricks-1.20091 (2016).[↩](#a10)

<b id="f11">11</b> Vikas P. Sukhatme, MD, Global Cures, Repurposing Existing Drugs for New Indications (2017).  Bernard Munos, Faster Cures, https://www.nature.com/news/can-you-teach-old-drugs-new-tricks-1.20091 (2016).[↩](#a11)

<b id="f12">12</b> DCAT, Drug Repurposing and Repositioning: Making New Out of Old (2016), http://connect.dcat.org/blogs/patricia-van-arnum/2016/07/05/drug-repurposing-and-repositioning-making-new-out-of-old#.WdYwShNSwU0. [↩](#a12)

<b id="f13">13</b> Grandview Research, Medical Marijuana Market Size To Reach USD 55.8 Billion By 2025 (2017).[↩](#a13)

<b id="f14">14</b> NIH Medical Marijuana, https://nccih.nih.gov/health/marijuana .[↩](#a14)

<b id="f15">15</b> Irena Melnikova, Orphan drug approvals by therapeutic area, Nature (2012). Global Genes, RARE Diseases: Facts and Statistics (2017).[↩](#a15)

<b id="f16">16</b> Vitalik Buterin, Keynote, Ethereum Singapore Meetup (Aug. 16, 2017).[↩](#a16)

<b id="f17">17</b> Joseph Poon, et. al., OmiseGo Decentralized Exchange and Payments Platform (2017).[↩](#a17)

<b id="f18">18</b> Dominic Williams, A recipe for creating fully decentralized cryptocurrency exchanges today, DFINITY network (2017).[↩](#a18)
