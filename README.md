#  IKU - Better Drugs. Better Tricks.

Working Draft, Version 0.99 March 25, 2018

## Abstract 
IKU is building the first decentralized cooperative DC to accelerate clinical trials at scale by offering a new form of liquidity and risk mitigation. The DC establishes clinical trial data rights as cryptoassets to be issued and traded in an open, global market. This architecture will be supported by a distributed network of researchers and interested parties enforcing behavior, specifically efficient clinical development of medicines, amongst each other.  It uses a two token model to provide for decision making and fee derivation, maximizing global liquidity pools.

Currently, the marginial increase in lifespan is severely disproportionate to duration of research advancement. Drug development and clinical trials traditionally focus on brand new molecules that have never previously touched humans, resulting in over $1 billion spend and a ~15 year market entry point per drug - a very faulty, non-scalable process. In parallel, ~50% of existing medicines can be redeveloped to reach the market at a fraction of the cost and time [FN: and time to treat a disease or condition for which there is currently not a quality treatment option] (cite: According to U.S. National Institute of Health researchers and supported by various computational frameworks). Unfortunately, redevelopment initiatives fail to be capitalized due to a lack of incentivization, bounded by analogue patent policy.

Blockchain-based fintech enables incentive efficiencies where they were not previously possible. Specifically, smart contracts collapse capital, data and execution into one, providing a new digital incentive mechanism. By enabling global markets to facilitate smart contracts through a DC for redevelopment clinical trials, we can significantly increase the return in lifespan per unit of time conducted in research. No Big Pharma necessary. A digital, liquid clinical trial economy is a new paradigm, serving to improve capital formation and realization of pent up demand for new medical technology. This paper explains how to push science and medicine to boundaries yet unseen through (i) the deficiencies of the current legacy R&D model resulting in a low velocity of value, (ii) the mission of creating a digitally, liquid global market to scale clinical research and (iii) ultimately compounding value to achieve longer lifespans for as many humans as possible. 


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
   10.[IKU Network Utility for R&D](#iku-network-utility)
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
   5. [The RST[x]permissionlessLicense](#the-rst[x]-permissionlessLicense)
   6. [Decentralized Key Management System](#decentralized-key-management-system)
   6. [The IKU Reserve](#the-elixr-reserve)
   7. [Future Development](#future-development)
5. [Conclusion](#conclusion)

## Introduction
### Problem Statement 

Medical research operates in analog fashion. And rightfully so as patents and capital formation operate under the same analog hood. Unfortunately, the patent system makes it close to impossible for the public to realize new medicines at scale.[FN]  Why? Patents are supported by outdated analog infrastructure that come with significant costs in trust and liquidity as there is no enforceable global record of data ownership without litigation. [FN - bracket below] This causes significant inefficiencies in clinical development that only large, well-capitalized corporations can sustain. These coprorations then  then seek rent from patients, insurance and the general public through high retail cost. Amazingly, the most expensive drugs in the world are for rare diseases, the smallest and most desperate patient populations, costing as much as $1 million+ per unit.[FN]  Because of such inefficiency, scientists are incentivized to keep their data secret in hopes of a large corporation licensing their research data, as opposed to collaborating with their peers in an open environment.  The result is very limited investment, on a per capita basis, in clinical research and significant illiquidity as the necessary resources are firmly controlled by centralized institutions. 

 [FN: Such inefficiencies have caused significant  IP law has attempted to enforce, but enforceability is difficult, time consuming and expensive as:

- patent litigation costs ~ $30 billion per year
- ~80% of the litigation comes from patent trolls 
- 50%+ of U.S. patents are being invalidated in post-grant proceedings,

All of which lead to significant issues in transaction finality, exacerbating an already illiquid market.]

Specifically, capital is nearly exclusively allocated to new molecular entities NME - molecules that have never been conceived nor had human exposure, as NME patents are most difficult to invalidate. Unfortunately, NME's as are rather logistically difficult to achieve, requiring:

- ~$2.6 billion in R&D spend
- ~15 years to complete clinical trials for market access
- ~0.02% chance of obtaining FDA approval upon being discovered in the lab [FN]

This model has proven to be very inefficient as pharma’s internal rate of return IRR on capital over the last ~30 years has been decreasing in a solid linear fashion, with IRR already below the cost of capital in 2017. [FN] See Figure A:

**Figure A: Return on Investment in Pharma R&D**

<img width="900" alt="Return on Investment in Pharma R&D" src="https://github.com/marcgug/White-Paper/blob/master/Return%20on%20Investment%20on%20Pharma%20R%26D.png"></p>

Compound this with pharma R&D spend never outpacing non-R&D spend i.e. marketing, etc. in any given year since 1990.[FN] We aslo see a decrease in medical research funding from the U.S. National Institute of Health.[FN] See Figure B:

**Figure B: NIH Funding 2003-2015**

<img width="900" alt="NIH Funding 2003-2015" src="https://github.com/marcgug/White-Paper/raw/master/NIH%20Annual%20SPend.png">
 
The outcome is a ~20 year backlog of potential medicines waiting for funds to enter clinical trials - posing serious threats to life extension.[FN] There are over 10,000 diseases afflicting humans of which less than 600 have known treatments.[FN]  All the while generic medicines have proven to be safe and inexpensive, and can be redeveloped to treat many more diseases or conditions, for which there is currently no quality treatment.[FN] Redeveloped medicines can be fully realized (e.g. FDA approved) in just one clinical trial for as little as $5 million, while significantly lowering any potential reason for future litigation.[FN]  The industry model as it currently stands is clearly a failure and does not account for redevelopment of medicines.[FN]  The holdup is not the science, but the incentive to efficiently mobilize resources to realize the science.  Blockchains enable digitally programmable incentive models to coordinate resources where it was not previously possible. 


### IKU Approach

A liquid clinical trial acceleration network focused on redeveloping medicines serving to efficiently achieve longer life expectancies while providing entry and exit opportunities through a fungible licensing mechanism enforced on the [Ethereum] blockchain. IKU is the Manhattan Project for clinical research efficiency. See Figure C:

**Figure C: Existing Medical Funding Models** 

<img width="900" alt="NIH Funding 2003-2015" src="https://github.com/marcgug/White-Paper/raw/master/Existing%20Medical%20Funding%20Models.png">

### HOW?

By providing a global liquid architecture for redevelopment of medicines based in tokenized clinical trial data rights, transacted in a digital market. IKU leveragaes a liquid licensing protocol (see permissionlessLicense section below) in which all transactions are settled programmatically on a blockchain, as clinical trial R&D data rights are proved through existence of smart contract provenance. A certain threshold of tokens is required for a provable license to such rights.  This will serve to provide interested parties with rapid market entry and exit abilities, reducing transaction costs, ultimately providing coordination and liquidity advantages to parties who otherwise would not know nor trust each other. IKU essentially reinvents clinical trial R&D thru tokenization, providing transparent and open markets for the generation, tracking and exclusive usage of clinical trial R&D data sets to accelerate access to therapies. The IKU token provides value through the right to contribute to the IKU Network **IN**, more so to the IKU R&D consensus mechanism, to derive fees from the IN.  

### What are Smart Contracts?

Smart contracts are agreements with super powers, as they provide a deterministic environment that guarantee information fidelity and facilitates trusted value exchanges. Specifically, a smart contract is: (i) code that moves information and/or money based on a condition between as many parties as needed, regardless of jurisdiction (IKU will strive to obey by all applicable laws and regulations); (ii) an automatism that is guaranteed to execute as it uses algorithms (blockchain) for enforcement, not a legal system; and (iii) binding.[FN]

Once a smart contract is set in motion, the blockchain is utilized to serve as an independent third party to make sure agreements are executed.[FN] Efficiency increases, especially in markets that are fraught with litigation, allowing for new markets where too much overhead is required for trade and/or little exchange of information.[FN] No third party is needed for escrow. Money is guaranteed to flow on contract resolution without the need to sue. Smart contracts provide justice without judges.

IKU is built on Ethereum, leveraging smart contracts to transact in clinical trial assets without the necessity of a middle man (VC, investment banks, Big Pharma, etc). This dramatically decreases barrier to entry, and allows (i) scientists and other learned persons to maximize scientific objectives by directly engaging p2p capital for the creation and trade of peer reviewed clinical research proposals (see below) as Research Specific Tokens `RST` on the IN, (ii) anyone to participate in the market and (iii) the realization of global supply and demand of medical science as opposed to a few centralized entities with their own private interests. All transactions will be public on the Ethereum blockchain, allowing all stakeholders to collectively review and direct liquid research data, incentivizing one record of scientific truth.

### Why IKU?

IKU allows for multilateral transparency and programmatic settlement for value exchange, currently not possible within the legacy bio R&D system vulnerable to monopoly. By shifting traditional business processes from a few controlling entities to a global decentralized network, it is possible to provide a commercially valuable infrastructure for science and medicine that is both dynamic and open for all. Network participants will be able to capitalize, support and trade in efficient R&D assets through decentralized resource allocation and increased market transparency. The successful creation of this system will create a positive feedback loop both economically and scientifically. 

In addition, the IN will serve to attract R&D ideation through crowdsourced input from thought leaders and patients. Realistically, physicians and patients do not have the time, expertise or resources to commence clinical trials, resulting in drop off. The IN aims to correct this slump and inform the market of the most scientifically viable R&D initiatives. 

### What about Patents?

Typically, by the time a NME is ready to enter clinical trial, there is < 10 years left of patent life, often times only 5-6 years.[FN] Jurisdictions throughout the world, including U.S., EU and Asia provide market/data exclusivity periods (independent of patents) for clinical trial data, regardless if NME or not, for up to ~10 years.[FN] Generic medicines are built on the same active ingredients (as the patented drugs) once their patents or marketing exclusivities have expired.[FN] They have the same dosage, effectiveness and - safety - profile as the original drug [1]. By definition, once the generic forms can be sold, the ingredient is on the market for many years and as such, generics themeselves are considered safe for patients.[FN] Because their patents have expired, there is significantly less risk of infringement and significant freedom to operate. 

IKU `RSTx` holders have rights over the data they help generate and may agree to pursue a patent together as a DC, with sole ownership of rights by the DC. The `RST` Holder has pro-rata rights in the R&D data if they hold the respective `RST[x]`. While `RSTx` holders may pursue patent protection for inventions developed based on IN funded research, patents may not be used on the IN. IN is designed to provide global liquidity for R&D regardless of patent policy.

This will serve to provide more equitable foundations in the following:

- **Science**: As per U.S. NIH researchers, ~ 50% of generic medicines can be redeveloped to treat disease or a condition lacking viable treatment options.[FN] Because existing medicines have already proven to be safe, the majority of redeveloping clinical trial intitiatives can skip Phase I (safety), move directly into Phase II (efficacy).[FN] Costs to redevelop a drug for a phase II clinical trial is estimated to be as low as $5 million and takes as little as a few years for approval, as opposed to ~15 years for NME.[FN] Compound this with (i) 20+ U.S. FDA medicine approvals in 2016 - 2017 on just one clinical trial (efficacy) [FN: The large scale, and very expensive multicenter Phase III trials (assessing safety and efficacy in comparison to standard treatment) are generally acknowledged to be very difficult to set up for rare diseases (< 200,000 patients/year [2]), for which also often no therapy exists (~7000 rare diseases, affecting 25-30 million Americans alone, for which there are 400+ drugs and biologics [2]); drugs targeting rare diseases are therefore commonly approved with Phase II data only such as in the case of 20+ different FDA approvals in 2016 - 2017 - END FN]. and (ii) ~30% FDA approval rate for redevelopment medicines vs. ~ 5% FDA approval rate for NME upon entering clinical trial, the result is a higher probability of scientific success, eliminating years of uncertainty and dramatically reducing the cost.[FN] Such strategy compresses the R&D pipeline, allowing for value inflection to be reached more efficienctly - accelerating market entry of inexpensive, safe medicines. 

- **IP**: A license is required by regulatory bodies (i.e. FDA, EMA, CFDA) globally proving copyright title provenance to medical R&D data.[FN] Without such a license, a party may not utilize such data for submission to a regulatory body and must start the research process anew (raising capital and performing an independent clinical trial). Licenses have proven to be worth billions of dollars to economic and medical systems worldwide.[FN] IKU data will be hashed and stored on Inter Planetary File System IPFS through a NuCypher proxy-reecncryption scheme where the hash is proof of the data's existence, therefore proving genesis of the data and copyright title provenance. This hash is tokenized and traded on the blockchain, enabling cryptographic, timestamped validation of each transaction, providing the current state of IKU. A license will be granted upon acquisition of a certain threshold of tokens, a proof-of-license mechanism, of which the licensee can put the redeveloped drug through already established manufacturing and distribution channels, which are abundantly available for contract. This allows for clinical trial data licenses to be liquid and accessible while also providing for efficient market access.  Parties may capitalize on data/market exclusivity periods (independent of patents) in many jurisdictions, including but not limited to:

	- Europe: up to ~10 years
	- Asia: up to ~10 years 
	- U.S.: up to ~7 years [FN]
	
Data and/or market exclusivity can be built on top of an `RST[x]DC` and/or `permissionlessLicense` (which confers timed data exclusivity) as it is collectively owned by the DC as a competitive advantage.  

- **Liquidity**: Medical research initiatives are generally inaccessible globally, remaining silo’d and permissioned as ROI on the significant R&D costs [4] - in the order of 2-3 billion USD to bring a NME drug to markets - lead to exorbitant pricing per patient.[FN] In addition, pharma companies carry significant non-R&D “baggage” i.e. marketing (as previously stated, R&D spend has never outpaced non-R&D spend i.e. marketing in any given year since 1990) as stock price is often dependent on sale volume, independent of patient effect.[FN] By design, IKU's output yields (preclinical and) clinical data sets, open to any interested party, that build the basis for two related asset classes - (i) the IKU Network Token and (ii), Research Specific Token `RST`. The `RST` enables the `permissionlessLicense` as described below. Given that IKU focuses on generic drugs that are already on the market, R&D expenditures are expected to be minor by comparison, as we hypothesize that mainly Phase II should be required (see above) - hence no such demands on amortizing exorbitant R&D costs on patients have to be met. 

Cryptoassets allow for the collapse of money value and information into one, facilitating the liquid exchange of data - as opposed to few centralized entities with their own private interests to control. IKU is providing the former for medical R&D allowing R&D to trade globally.  Through this architecture, we can realize global supply and demand of safe and impactful medical science, at scale. 
 
Figure D further contextualizes the benefits of the IKU data approach:

**Figure D: IKU Data Approach**

<img width="900" alt="IKU Data Approach" src="https://github.com/marcgug/White-Paper/raw/master/IKU%20Data%20Approach.png">

[Show visual of compressing the pipline - stripping the pipline of preclinical and at least half of Phase I - keep Phase II - and strip Phase III.  - use this from th francis collins NIH director talk] @MIKE

### IKU Scales at Low Cost 
 
The current legacy model is costly as we explained above. IKU on the other hand can scale cost as IKU addresses a ~ $10 - $100 [FN] million requirement per medicine approval (redeveloping generic) vs. ~ $2.6B patent NME market per medicine approval (NME). Figure E compares this for better context:

**Figure E: IKU Scales at Low Cost**

<img width="900" alt="IKU Scales at Low Cost" src="https://github.com/ikunetwork/WhitePaper/raw/master/IKU%20Scales.png">
The expectation is for IKU to scale at low cost as the same number of approved medicines addressed by IKU will be at least 88% more efficient. As ~30 medicines are approved by the FDA annually at a ~$5.2B Total Average R&D Spend per Year, IKU is epected to address the same number at a fraction of the cost (~10x - 100x more cost efficient). 

### Token and License

The IN will be controlled by its users, **IKU** token holders, with no asset exchange third-party intervention, distributing the liquidity pool on a global basis to encourage and reward successful clinical trial development.  Token value on the IN can be derived from the following:

- Power to perform work for IN, including peer review R&D for capitalization
- IKU fee structure (defined below)

Licensees will either be in the form of a third party that acquires a certain threshold of tokens, engaging the `permissionlessLicense` protocol as described below, or the `RST[x]DC`. An `RST[x]DC` represents an ad-hoc, virtual collective capitalized through smart contract, open to the world at large. An `RST[x]DC` will be expected, through their project leads, to engage clinical research organizations CRO, certified manufacturing organizations CMO and distribution, all of which are established channels available for contract on a worldwide basis. 

### The IKU Foundation

The mission is to establish the IN as a public utility for medical research, driving efficiency through global capital formation and decentralized liquidity pools. The community will own the IN in a trustless fashion, connecting individuals, science, verified researchers/research organizations – collectively participants - and capital. The IN will operate as the IKU Foundation, a Singapore [nonprofit] organization whose core objective is to establish and facilitate the IN, create IKU, maintain the IKU reserve and evangelize R&D efficiencies.  In addition, the IN will maintain a grants program in which bounties will be issued for (i) eliminating issues in the IKU code and (ii) accomplishing specific medical innovations i.e. developing effective cancer treatments, aging treatments, etc. Circulating IKU will vote on the priority of bounties, capital allocation, and have the right to perform work for IN. To be clear, after the IN is live as described below, there will be no difference between the IN and the IKU Foundation.  

### IKU Network Utility

The following sequence of events illustrate the IKU Network utility and ability to facilitate global capital formation for medical R&D initiatives:

**Figure E: IKU Network Utility**

<img width="600" alt="IKU Data Approach" src="https://github.com/ikunetwork/WhitePaper/raw/master/IKU%20Network%20Utility.png">

IKU strives to achieve  for the `permissionlessLicense` to be created and traded in liquid fashion, ultimately accelerating the path to medicine and drug discovery. The following Network Economy and Tokenization sections explain how achieve such a license.

## The Network Economy
The IN combines the wisdom of crowds with the wisdom of science thru participant communication, capital and data exchange. The following tools will give life to the IN: `researchTarget`, `devTools`, Request for Proposals `RFP`, and the `permissionlessLicense`. 

### Research Target

Any person with internet access may frictionlessly submit a `researchTarget` which may be a concrete, verifiable objective or broad target. For example:
- Verifiable Object: Repurposing generic X in a slow release formulation to treat pancreatic cancer
- Broad Target: Advancing research against aging

Among other aspects, the `researchTarget` may specify medical conditions, technology type i.e therapy, device, vaccine, etc., mechanism of action, or any other known R&D metric. The `researchTarget` will be visible and sortable to the public, allowing for thorough analysis and determination of demand. The public will be able to upvote a `researchTarget` - spam protected thru captcha.

### Dev Tools

Participants will access the IN through a `devTools` integrated interface. The `devTools` consist of the following:
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

Friends, message, and upvote access will require an IN profile, but will not require holding IKU in the Network Digital Wallet NDW - allowing anyone to use the IN. This type of access is classified as `devTools A`.  RFP submissions, comments, peer review, reputation scoring and upgrading to clinical trial subject will require an IN profile AND holding at least 1 IKU in the NDW - `devTools B`.  

### IKU Network Participants

Below are the players in the IKU Network. They are not mutually exclusive:

- **`IKU` Holder**: IKU token holder; can be an individual, institution, private company, etc. (described further below)
- **`RST[x]` Holder**: Research Specific Token holder; can be an individual, institution, private company, etc. (described further below)  
- **VR**: Verified Researcher i.e. MD, PhD, etc. whose expertise is credentialed through the IN. The VR can propose and respond to  a `researchTarget`, vote on their viability and review proposals. He/she is fundamental to the IKU peer review process.  
- **ADV** Anonymous data viewer - the public, who freely contributes a `researchTarget`, views projects on the IN and has the option to create an IN profile to access `devTools A`. The IN will make information ethically and publicly available as current clinical trial results are typically not open to the public - even though they are required to be.  In addition all `RST[x]DC` initiatives will post a gnatt chart for how advanced their research initiative is as well as the top line de-identified research data they have generated on a quarterly basis.

Participants will be subject to a `reputationScore`:

- `reputationScore` is part of `devTools`. All participants will be subject to a profile linked `reputationScore` which accounts for utilization of IN resources and behavior, allowing for meritocratic decision-making based in scientific liquidity. All IN participants start with the same `reputationScore`, but will be separated by VR and non-VR. `reputationScore` may increase to `power`, `super_power` and `grand_maester`.  This enables the best ideas to flow freely, producing efficient and rapid evolution based on merits.[FN] Participants will be obligated to provide `reputationScore` to other participants they have digitally engaged.  The `reputationScore` will be publicly available.

### Request for Proposals

The IN will serve to produce requests for peer reviewed proposals `RFP` in response to the `researchTarget`. A VR will be able to submit proposals at any time as paid for by the IN reserve, whereas non-VR will be required to post a bond to submit a proposal, in response to a `RFP`.  

RFP Template: https://docs.google.com/document/d/1vIZyS90e-aiWynNalBplVmUAJPtMZajXw7gdfjjBozk/edit
RFP Score: https://docs.google.com/document/d/1gnY8KdrvTtcWzok7rYUPKsL7mh-nCyyaMEdcEd5yosU/edit

An `RFP` is required to consist of (i) a principal investigator PI that leads the R&D team along with the `RST[x]` Holders that the PI and his/her team will have to answer to (see below `RST[x]` value), (ii) how much capital is being raised and for what percentage of `RST[x]`, with proposers encouraged to not issue 100% of `RST[x]` to account for future capital requirements and (iii) the scientific justification, etc (see google doc above). A standard `RST[x]` Proposal template will be provided by the IN for `RFP`. Further `RFP` value may be determined by the IKU user submitting the proposal, allowing for a flat environment in which value proposition may be programmed into an `RST[x]`. This leaves significant room for `RST[x]` value creativity.

### The Proposal Library

Network-based computational biology analysis has become a widely used strategy for determining drug redevelopment piplines due to the ever-increasing pace of bio and chemical information available.[FN]  Various different computational approaches, including deep learning, matrix factorization methods and various algorithms have proved beneficial in navigating the wealth of information to uncover potential drug redevelopment leads.[FN] Unfortunately, this information is often fragmented and to date, has lacked economic incentive for the proper capital formation to enable clinical trials.[FN]

The IN will serve to be a hub for such information allowing for a unified workflow of the most promising redevelopment initiatives along with the economic incentives to bring such initiatives to clinical trial. The IKU peer review will “stand on the shoulders” of the computational analysis that has been completed to date to provide a highly predictive, robust repurposing pipeline. VR and non-VR are incentivized to ‘bruteForce’ peer review (described below) to earn fees from the IN in the form of BTC, ETH and `RST` - encouraging and incentivizing the the most promising redevelopment initiatives to be capitalized. 

IKU peer review serves as the IKU R&D consensus mechanism, with the ultimate goal of achieving the longer lifespans for as many humans as possible. 

Participants will use the `devTools` to peer review.  The IN peer review process to score an `RFP` can be defined as a function:

	`β` = `f(α,φ,θ)` = `RFP` score - PUBLIC
	`α` =  pariticipant`reputationScore` (a VR's `α` is weighted 2x)
	`φ`: Sum of `RFP` upvotes  
	`θ`: IKU balance weight 
	`λ`: A random threshold value
	
`β` is expected to be optimized overtime with IN demand.  As this process generates data and continues to grow, it will serve to provide open source algorithims for potential new uses of existing medicines.  

Upon `β` > `λ`, 2 smart contracts will be deployed to the Ethereum Blockchain:
1) `RST[x]` - An ERC20 token representing the specific research
2) `RSTCrowdsale[x]` (based on https://github.com/OpenZeppelin/zeppelin-solidity), which responsible for minting `RST[x]` and in exchange send tokens to contributors
  
Upon `RSTCrowdsale[x]` achieving its softcap - minimum `RST[x]` required to achieve milestone:

1. [y%] of the funds will be released to the R&D team,
2. All `RST[x]` Holders will be able to participate in an `RST[x]DC` on a per project basis, and
3. IKU Token Holders earn fees in `RST[x]` as described below under **Fees and the Network Digital Wallet**.

Funds released to the R&D team in BTC, ETH and IKU can be converted to fiat, through a trusted third party crypto to fiat provider such as Coinbase. In addition, prior to initiating a clinical trial, an `RST[x]DC` will be responsible for ensuring ethical compliance through an institutional review board.

**Smart contract code for `RSTCrowdsale`**

```solidity
pragma solidity ^0.4.18;

import 'zeppelin-solidity/contracts/crowdsale/validation/CappedCrowdsale.sol';
import 'zeppelin-solidity/contracts/crowdsale/distribution/RefundableCrowdsale.sol';
import 'zeppelin-solidity/contracts/crowdsale/emission/MintedCrowdsale.sol';
import 'zeppelin-solidity/contracts/token/ERC20/MintableToken.sol';


contract RSTCrowdsale is CappedCrowdsale, RefundableCrowdsale, MintedCrowdsale {
    

  function RSTCrowdsale(
    uint256 _openingTime, 
    uint256 _closingTime, 
    uint256 _rate, 
    address _wallet,
    uint256 _cap, 
    MintableToken _token,
    uint256 _goal
  ) public
    Crowdsale(_rate, _wallet, _token)
    CappedCrowdsale(_cap)
    TimedCrowdsale(_openingTime, _closingTime)
    RefundableCrowdsale(_goal)
  {

    //As goal needs to be met for a successful crowdsale
    //the value needs to less or equal than a cap which is limit for accepted funds
    require(_goal <= _cap);
    
  }

}

```

## Tokenization 

The IN creates two classes of native tokens:

- **`IKU`**: The IN token `IKU` serves to secure the IN with consensus on R&D, allow for IN decision making and fee 	derivation as further explained under IKU Value. The supply of IKU is finite. 
	
- **`RST`**: The Research Specific Token `RST` is representative of the R&D `[x]` it was specifically created to fund. `RST[x]` supply is determined by proposers and is dependent on the project economics it is used to fund and facilitate. `RST[x]` bundles, `RST[i]` may  be developed as per a future bounty, allowing for scientific and economic risk diversification where `i` represents the number of `RST[x]` bundled. 


### IKU Value

Wallet verification of a minimum of balance of 1 IKU enables access to the `devTools B` and fees as explained under **Fees and the Network Digital Wallet**. Value in the IKU token can be ascribed to access to the following:

- `devTools B`
- power to make decisions and perform work for IN
- 2nd priority to upgrade to clinical trial subject
- Fees
	Establishing a profile on the EN provides access to the Network Digital Wallet NDW.  The NDW will serve to hold BTC, ETH, IKU and all `RST[x]`, and is expected to also hold digitalized fiat, providing for efficient capital formation and communication. In addition the NDW enables IKU holders to earn fees in `RST[x]` as [x%] of all of the R`STCrowdsale`, pro-rata, will flow to IKU holders in exchange for preforming a certain threshold of work on the IN, e.g. participating in the peer review process. Such model gives an IKU holder the opportunity to have rights to all the research on IN. 

### `RST[x]` Value

An `RST[x]` carries pro-rata rights to its specific R&D `[x]` initiative and such rights are cryptographically maintained with the ability to (i) access the `RST[x]DC` and (ii) be transacted in an `permissionlessLicense` smart contract. Value in the `RST[x]` token can be ascribed to the following:

- `permissionlessLicense` threshold
- 1st priority to upgrade to clinical trial subject
- Access to medicine upon regulatory approval at a discounted (or free) rate [FN: compliant to jurisdiction]
- power to make decisions and perform work for`RST[x]DC` including voting rights to release funds for the next stage of the roadmap, remove/replace PI, etc.

R&D data will be made available to `RST[x]` holders and updated by the `RST[x]DC` team through the IN infrastructure on an ongoing basis. `RST[x]DC` R&D data will be de-identified and stored on IPFS. Access to the data and specific `RST[x]DC` will be made available with possession of a minimum, predetermined `RST[x]` threshold and private key, unless otherwise made public thru IKU. A transaction involving `RST[x]` is the cryptographic validation of rights transfer to `RST[x]` hashed data, timestamped by the blockchain. This is transparently irrefutable evidence of both proof of the data's existence and rights provenance on IPFS at a given point in time, protecting against reasons for litigation.

**`RST[x]` Smart Contract**

```solidity

pragma solidity ^0.4.18;

import 'zeppelin-solidity/contracts/token/ERC20/MintableToken.sol';

 contract ResearchSpecificToken is MintableToken {
    uint8 public  decimals;
    string public  name;
    string public  symbol;
   
    function ResearchSpecificToken(
        uint8 _decimalUnits,
        string _tokenName,
        string _tokenSymbol
    ) public{
        decimals = _decimalUnits;
        name = _tokenName;
        symbol = _tokenSymbol; 
    }
}


```
IPFS will serve to provide infrastructure for the `RST[x]DC`. The R&D team will provide updates to the `RST[x]` Holders in their DC on a regular basis, in which `RST[x]` holders will have ability to:

(i) Determine whether R&D team should have access to remainder of funds for continuing research (upon reaching or not reaching R&D milestone x - oracle),
(ii) Upgrade to clinical trial subject,
(iii) Provide reputation scores to fellow `RST[x]` holders and the R&D team
(iv) remove/replace R&D operations personnel (e.g. PI) upon achieving `RST[x]DC` majority consensus.

The `RST[x]DC` is incentivized to provide timely and relevant information to both its own DC and the public as the `RST[x]` and also IKU will be at the mercy of market sentiment. IKU and `RST[x]` tokens are expected to trade in real time, globally in the cryptourrency market place. If an `RST[x]DC` does not operate in efficient scientific fashion, this is expected to be reflected accordingly. 

### Burning

IKU aligns its burning strategy with the creation of `RST[x]`, where a % of IKU tokens contributed to a specific `RST[x]` are burned from the IKU Reserve. The same percentage of the specific `RST[x]` pool are also offered to IKU Token holders. Burning may occur as follows:

- A `researchTarget` is submitted for Levodopa Trials - Cure Parkinson’s. The Alice Foundation submits an RFP for the `researchTarget` of which the IN accepts and an associated fundraise commences. The fundraise is successful and the associated `RST[x]DC` Levodopa Trials - Cure Parkinson’s is created. [x%] of the total contributed IKU tokens are burned from the IKU Foundation Reserve pool, and the same [x%] in `RST[x]` are evenly distributed to all IKU Token holders, pro-rata based on IKU holdings.

- Let’s say Bob contributed 500 IKU tokens to `RST[x]DC` Levodopa Trials - Cure Parkinson’s. The Alice Foundation receives all 500 IKU tokens of which they can exchange for FIAT. Bob’s contributed IKU tokens are not burned.The Alice Foundation’s IKU Tokens received from BOB are not burned as well, but rather [x%] of the total contributed IKU tokens are burned from the IKU Reserve pool. The same [x%] of the `RST[x]` pool is transferred back to all funders who held IKU tokens at the time of funding, pro-rata based on IKU holdings. Thus Bob receives a piece of that [x%].

### The `RST[x]` `permissionlessLicense`

The `permissionlessLicense` facilitates digital scarcity as an additional efficienct economic incentive vehicle. The `permissionlessLicense` protocol allows for global trade of any data or IP, that has scarcity properties, as cryptographic assets. Acquisition of a certain threshold of cryptographic assets - a token supply number which is predetermined at the time of the `RFP` creation - triggers an automatic license to the data or IP generated by the `RST[x]DC`. This allows for a license to be highly available, fungible and auditable as it is a datapoint on a blockchain. In IKU's case, a `permissionlessLicense` would be granted upon a certain Ethereum address holding z% of outstanding `RST[x]`. The party who holds the private key to such Ethereum address now has a license to utilize and exploit the clinical trial data, e.g. completed Phase II clinical trial data,  to potentially submit to the U.S. FDA for approval. The more scientifically advanced the R&D initiative, the greater the expected demand as the data and its corresponding license and therefore `RST[x]` becomes more scientifically valuable i.e. completing Phase II clinical trials - therefore more value will be required by one who desires a `permissionlessLicense` to achieve the `RST[x]` threshold.

The IN will provide a standard `permissionlessLicense` with drop down variables such as territory, `RST[x]` license threshold, required efforts for good faith development (e.g. FDA approval within [x time]), amongst others.  This will enable proposers to click through, filling in variables at their discretion, likely dramatically reducing the need for negotiation, lawyers and other middlemen, enabling an open streamlined licensing process.  In addition, parties will have the opportunity to provide their own customized license, subject to market demand.

Specifically, the `permissionlessLicense` enables exit opportunities for `RST[x]` Holders to license `RST[x]`-backed data which can be obtained by any interested party (e.g. health insurance distributor, venture, foundation, etc.).  If the `permissionlessLicense` threshold is not achieved after a succcessful Phase II clinical trial, the `RST[x]DC` may become a collective ad hoc venture team around its cryptoasset, e.g. an approved ALS treatment with 7 years of market exclusivity in the U.S., for further development, market distribution, etc.  This creates a self perpetuating ecosystem of innovation and multiple opportunities for IKU and `RST[x]` holders, as well as other parties interested in licensing.

Upon the public release of the IN, IKU token holders will be able to decide what happens to `RST[x]` that are not part of the `permissionlicense`. This may include creating a software bounty thats allows for royalties to flow to the remaining outstanding `RST[x]` in exchange for work or in the alternative, as a securitized asset.  Because `RST[x]` is traded on the Ethereum blockchain, provenance of `RST[x]` data rights are known, facilitating potential trustless royalty distribution to `RST[x]` holders from the licensee.  Note that this will be up to IKU token holders to decide.

### Decentralized Key Management System 

As the `RST[x]DC` is incentivized to upload relevant and appropriate research data to IPFS, the associated private key to trigger the `permissionlessLicense` must be encrypted and only available to `RST[x]` Holders at a specified balance threshold. In no way will the IKU Foundation own or control any private key to `RST[x]` associated data in IPFS of which the `permissionlessLicense` unlocks. Instead, IKU will employ a NuCypher proxy re-encryption mechanism where the `RST[x]DC` will delegate re-encryption of the private key to a proxy in the NuCypher proxy re-encryption node upon `RST[x]` Holder request of the `RST[x]` in the `devtools`.  

### The IKU Reserve
The IN will maintain its funds, along with IKU as necessary for incentivizing VR peer review, liquidity and community bounties in both software and medicine.  [FN: The funds will be stored in an Ethereum MultiSigWallet (https://github.com/Gnosis/MultiSigWallet) which is built on top of ConsenSys Ethereum MultiSigWallet (https://github.com/ConsenSys/MultiSigWallet).] All foundation transactions and bounties will be public, enabling anyone to see its balance sheet in real time. 
   
### Future Development

While IKU in its initial phase will focus on redeveloping drugs, we anticipate focusing on for adjacent opportunties to achieve longevity escape velocity including rejuvenation tech, biomarker analysis and age-related disease prevention.

As to the platform itself, additional IN features are expected to be developed and/or integrated based on IKU decision making to further enable medical R&D efficiency, which may include but are not limited to advanced analytic and platform navigation tools, as well as links to language agnostic relevant public and private content through APIs (e.g., PubMed, IP Databases). This will improve workflow efficiency and thus lead to enhanced platform performance. 

As to specific anticipated service components, dependent on IKU token holder decision making, a software bounty may be deployed for `RST[i]` bundling, `i` representing the number of `RST[x]` bundled, as stated below:

Bundling may serve to enable various medical R&D financial products to mitigate economic and scientific risk exposure as well as provide horizontal, or vertical, research collaboration. As opposed to a traditional centralized corporation, the `RST[i]` bundle lowers the cost of both trust and risk.

How to bundle:
- Declare `RST[x]` eligible to bundle with `i-1` in the `RFP`, during token sale, or later point in time
- Declare `RST[x]` seeking bundle

All IN R&D initiatives would have the option to actively bundle `RST[x]` into `RST[i]`, or allow for `RST[i]` to choose to bundle with an `RST[x]`, with atomic swap capability, allowing for high performant assets to be transacted globally across, or in the same R&D verticals. Atomic exchange serves as a mechanism to reduce risk and stabilize IKU/`RST[i]` in a frictionless fashion, as atomic assets do not need to be traded on a centralized exchange, but can be swapped for one another through direct p2p algorithmic execution.

This would be especially important for clinical trials in the same research vertical i.e. condition, disease, mechanism of action, molecule, etc. as it mitigates scientific and economic risk. Capital resources would be allocated purely towards R&D with the ability to algorithmically bond with each other thru smart contract. 

Pricing a bundle can be defined by the expected value:

<img width="200" alt="Expected Value" src="https://github.com/marcgug/White-Paper/raw/master/Expected%20Value.PNG">

## Conclusion
IKU will serve to enable unprecedented global organization and deployment of resources for safe and impactful clinical trial research. Decentralizing resource allocation and asset transactions allows for increased transparency of market activity which is expected to lead to significant medical innovation in the near future. The foregoing working draft has sketched a paradigmatically novel vision of the structural and organizational means by which this can dramatically increase the reward for efficient medical R&D, reduce the risk of failure, all the while enabling global, decentralized liquidity. We expect the IN to be a critical infrastructure piece to spark and launch the entire patent agnostic digital medical R&D system.  This is the fundamental intention and the essence of the IN.

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
