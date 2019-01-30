# IKU - Biotech Redefined   

Principal Authors          

Gregory J. Rigano, Esq. - Advisor SPARK, Stanford School of Medicine, tech lawyer<br/>
Michael Kisselgof - Credit Suisse, Private Banking - SAP, Global Marketing<br/>
Thomas Deisboeck, MD - Associate Professor Harvard Medical School, Mass General Hospital

February 2019

## Abstract

IKU is the first DAO to accelerate bio-innovation, allowing anyone to create, license, and trade bio r&d. It is a public utility employing the blockchain and smart contracts to collapse capital and copyright exclusivity into a fundable data asset
that can be traded and licensed permissionlessly. All proposed assets are vetted with i) ELI, an artificial neural network trained to predict regulatory approval and project success, and ii) the wisdom of the bio-medical crowd. Both methods
are used to de-risk and reduce barrier to entry for the consumer and institution. IKU will provide for democratized access to biotech assets costing up to 1,000x less than those in the traditional legacy system, while accelerating market entry by years and still maintaining exclusivity periods to generate significant returns. This is moneyball for biotechnology.

The marginal increase in lifespan is severely disproportionate to research duration as drug development and clinical trials traditionally focus on new molecular entities ("NME"). NME's typically take over 15 years per market entry, with high rates of failure and cost over $2 billion - a faulty, non-scalable process. Why? Patent friction. The IKU model combined with recent developments in globalization of clinical trials allow for an arbitrage in which market entry of cutting edge biotech can cost 500x less than the traditional patent-based pharma model. This paper explains (i) the deficiencies of the current legacy R&D incentive structure, (ii) the mission to create a digital, liquid global market to scale bio R&D/trials and (iii) how IKU ultimately compounds value through global arbitrage to push science and medicine to boundaries yet unseen.

## Table of Contents

1. [Introduction](#introduction)
   1. [Problem Statement](#problem-statement)
   2. [Rediscovery A Solution](#rediscovery-is-a-solution)
   3. [Copyright vs Patent](#copyright-vs.-patent)
2. [The IKU Model](#the-iku-model)
   1. [How](#how)
   2. [Smart Contracts](#smart-contracts)
   3. [Direct Monetization of Research](#direct-monetization-of-research)
   4. [ELI The Artificial Neural Network](#eli-the-artificial-neural-network)
   5. [Why IKU?](#why-iku)
   6. [The IKU Network](#the-iku-network)
3. [The Network Economy](#the-network-economy)
   1. [Research Target](#research-target)
   2. [`devTools`](#devtools)
   3. [IKU Network Participants](#iku-network-participants)
   4. [Request for Proposal](#request-for-proposal)
   5. [Information Market](#a-computational-pipeline)
   6. [IKU Network Utility](#iku-network-utility)
4. [Tokenization](#tokenization)
   1. [`IKU` Value](#iku-value)
   2. [`LIC` Value](#lic-value)
   3. [Burning](#burning)
   4. [The `permissionlessLicense`](#the-permissionlessLicense)
   5. [The `IKU` Reserve](#the-iku-reserve)
   6. [Future Development](#future-development)
5. [Conclusion](#conclusion)

## Introduction

### Problem Statement

Bio R&D operates in analog fashion. And rightfully so as patents and capital formation conform under the same hood. Unfortunately, the patent system makes it close to impossible for the public to realize new biotech at scale.<sup>[1](#f1)</sup> Why? Because of its analog infrastructure and associated cost in trust and liquidity. There is no enforceable global record of R&D rights without fault (litigation), resulting in significant inefficiencies in clinical development.<sup>[2](#f2)</sup> Only large, well-capitalized corporations can sustain such inefficiencies, whom then seek rent from patients, insurance and the general public through high retail cost - rare disease drugs often come with high price tags, limited human exposure, and can cost as much $1 million per regimen.<sup>[3](#f3)</sup> The result is a permissioned market with high friction. Researchers are then incentivized to conceal their research in hopes of a large corporation pursuing a license, as opposed to peer collaboration within the scientific community. The result is (i) very limited R&D investment per capita and (ii) significant illiquidity as the necessary resources are firmly controlled by centralized institutions.

In addition, capital is almost exclusively allocated to new molecular entities NME (molecules never conceived nor had human exposure), as NME's are a more enforceable record of R&D.<sup>[4](#f4)</sup> Unfortunately, NME's are logistically difficult to achieve, requiring:

* $2.6 billion in R&D spend
* 15 years to complete clinical trials for market access
* 0.02% chance of obtaining FDA approval upon being discovered in the lab.<sup>[5](#f5)</sup>

This model has proven to be very inefficient as pharma’s internal rate of return IRR on capital over the last ~30 years has been decreasing in linear fashion, with IRR already below the cost of capital in 2017.<sup>[6](#f6)</sup> See Figure A:

**Figure A: Return on Investment in Pharma R&D**

 ![Return on Investment in Pharma RD](https://github.com/ikunetwork/WhitePaper/raw/master/Return-on-Investment-in-Pharma-R%26D.png)

Sadly, pharma companies carry significant non-R&D “baggage," where non-R&D spend has outpaced R&D for the last 20 years. We've also seen a decrease in medical research funding from the U.S. National Institute of Health.<sup>[7](#f7)</sup> See Figure B:

**Figure B: NIH Funding 2003-2015**

![NIH Funding 2003-2015](https://github.com/ikunetwork/WhitePaper/raw/master/NIH-Funding.png)

The outcome is a 20 year backlog of potential drugs waiting for funds to enter clinical trials.<sup>[8](#f8)</sup> In fact, there are over 10,000 diseases/conditions afflicting humans of which less than 600 have known treatments.<sup>[9](#f9)</sup> While it costs over $2 billion to develop a NME in the U.S., there are multiple R&D efficiencies in which it can cost 500x less to get a treatment approved, including but not limited to drug rediscovery and pursuing clinical trials in the eastern part of the world, specifically Asia and Australia.  

### Rediscovery is a Solution

Already approved drugs/therapies can be redeveloped aka rediscovered to treat many more conditions, for which no quality treatment exist.<sup>[10](#f10)</sup>  U.S. National Institute of Health researchers speculate that 75% of existing drugs can be rediscovered to reach the market at a fraction of the cost and time.<sup>[11](#f11)</sup> Generic medicines are, and can be, built on the same active ingredients as their previously patented version.<sup>[12](#f12)</sup>. By the time a drug becomes generic the ingredients would have already been on the market for many years and as such, the generic themselves are considered safe for patients.<sup>[13](#f13)</sup> Many high end scientists, inluding Nobel Laureates, agree that redisovery is a preferred method:

_The most fruitful basis for the discovery of a new drug is to start with an old drug_ - Sir James W. Black, Nobel Prize in Medicine 1988.   
   
Rediscovery can take the form of new formulations or patient populations, and clinical trials can commence for as little as $1.5 million USD, requiring only a few years for approval, as opposed to ~15 years for NME.<sup>[14](#f14)</sup> How? eliminating significant time and cost spent replicating studies. Because the drug has already proven to be safe, it can get directly into Ph. II clinical trials (efficacy) - potentially approved thereafter on just this one trial.<sup>[15](#f15)</sup> In addition, rediscovery has a 30% FDA approval rate for drug rediscovery vs. < 1%  approval rate for NME upon being discovered in the lab.<sup>[16](#f16)</sup>  

Rediscovery has lacked economic incentive for development because of the patent landscape. IKU is designed to change this, providing the direct economic incentive for rediscovery while leveraging recent breakthroughs in globalization of clinical trials (more below). To further prove the rediscovery research model: as per a recently published rediscovery trial presented at the premier cancer research conference worldwide (ASCO), as covered by Forbes, the biggest surprise of the whole conference was the effect of Metformin, a generic diabetes drug, rediscovered for treatment against lung cancer.  
   
*Biggest Surprise: Metformin*

*Since Metformin went off patent, the diabetes drug has become one of the favorite treatments of life-extension types. So add this to its magic aura: In a small randomized trial of 140 patients conducted in Mexico City, adding metformin to drugs for lung cancer patients whose tumors had mutations in a gene called EGFR seemed to slow disease progression and survival ... a warning to industry to dot i's and cross t's.* <sup>[17](#f17)</sup> 

### Copyright vs Patent

Historically, by the time an NME enters clinical trials, its patent life has under 10 years, often times only 5-6 years remaining.<sup>[18](#f18)</sup> Jurisdictions including U.S., EU and Asia provide copyright data exclusivity periods \(independent of patents\), for clinical trial data for up to 12 years, regardless if it is an NME.<sup>[19](#f19)</sup> Copyrights applies when original research data is put in writing, proof of existence - registration is not necessary. Patents require filing an application with a patent office and subjective analysis by a government - resulting in multiple tens of billions USD litigation and patent invalidation rates as high as 90%.<sup>[20](#f20)</sup> Furthermore, patents cannot be granted unless a party has a copyright to the respective research data.<sup>[21](#f21)</sup>   

A copyright license is required by bio regulatory bodies globally \(i.e. FDA, EMA, CFDA\) proving copyright title provenance to R&D/clinical trial data sets.<sup>[22](#f22)</sup> Without such a license, a party may not utilize data sets for submission to a regulatory body and must start the research process anew \(raising capital and performing independent research and clinical trial).<sup>[23](#f23)</sup>  Licenses have proven to be worth billions of dollars to economic and medical systems worldwide.<sup>[24](#f24)</sup> Jurisdictions provide for clinical trial copyright data exclusivity periods (independent of patents), including but not limited to:

* Europe: up to ~12 years
* Asia: up to ~10 years
* U.S.: up to 12 years<sup>[25](#f25)</sup>

IKU is designed to directly monetize biotech research data, regardless of patent policy, as rights are based in the copyright of the research data generated. By design, the IKU model is much less expensive in capital and time, with significantly greater probability of scientific success. 

**FIGURE C: CLINICAL TRIALS AT SCALE**
![CLINICAL TRIALS AT SCALE](https://github.com/ikunetwork/WhitePaper/raw/master/CLINICAL%20TRIALS%20AT%20SCALE.png)



High quality science, low cost.  Such strategy compresses the R&D pipeline, allowing for value inflection to be reached more efficiently - accelerating market entry of inexpensive, safe biotechnologies.<sup>[25a](#f25a)</sup> In short, patents stifle innovation. Copyrights do not. 

We anticipate these efficiencies allow for longevity escape velocity — the point at which, for every year you're alive, science is able to extend your life for more than a year.  The holdup to achieve these efficiencies is not the science, but the incentive to mobilize resources to realize the science. Blockchains enable digitally programmable incentive models to coordinate resources where it was not previously possible. 

## The IKU Model

IKU provides the infrastructure for a liquid, bio R&D network to advance productivity by orders of magnitude. The IKU Network (the "Network") will serve to provide value exchange entry and exit opportunities through a fungible digital licensing mechanism enforced on a blockchain. Figure D contextualizes IKU's benefits:

**Figure D: Existing R&D Models**

![Existing R&D Models](https://github.com/ikunetwork/WhitePaper/raw/master/Existing-R%26D-Models.png)

### How?

IKU establishes a marketplace for the exchange of bio R&D generated datasets. Sub markets within the IKU marketplace are represented by unique tokens in which acquisition of a token threshold grants a license - proof-of-license mechanim. The license acts as the fundamental market facilitator. By tokenizing the license, copyright to R&D is proved through existence of smart contract provenance, allowing all transactions to settle programmatically as immutable data points on chain. 

IKU's output yields preclinical and clinical research data sets, open to any interested party globally, building the basis for two related asset classes - \(i\) the IKU Network Token `IKU` and \(ii), the License Token `LIC[x]`. `IKU` represents the bandwidth that powers the Network, providing R&D efficiencies and eligibility to stake for fee-derivation. `LIC[x]` is the license bandwidth of the R&D data specific to market `[x]` of which a balance threshold of `LIC[x]` is necessary for proof-of-license. Both `IKU` and `LIC[x]` collapse value and information into one, facilitating the liquid exchange of R&D - as further outlined below.  

IKU reinvents bio R&D data markets through tokenization, providing transparent and open markets for the generation, tracking and exclusive usage of R&D data sets to accelerate access to the future of medicine. This will serve to provide interested parties with rapid market entry and exit abilities, reducing transaction costs, ultimately providing coordination and liquidity advantages for R&D between parties who otherwise would not know or trust each other. 

### Smart Contracts

Smart contracts are agreements with super powers, as they provide a deterministic environment guaranteeing information fidelity and trusted exchange of value. Specifically, a smart contract is: (i) code that moves information and/or money based on a condition between as many parties as needed, regardless of jurisdiction; (ii) an automatism that is guaranteed to execute as it uses algorithms (blockchain) for enforcement, not a legal system; and (iii) binding.<sup>[26](#f26)</sup>

Once a smart contract is set in motion, the blockchain is utilized to serve as an independent third party to verify agreement execution.<sup>[27](#f27)</sup> Ultimately, overhead is reduced, trust improves, and efficiency increases with no third party necessary for escrow.<sup>[28](#f28)</sup> Money is guaranteed to flow on contract resolution without the need to sue - smart contracts provide justice without judges.

IKU leverages blockchain-based smart contracts to transact in digital R&D assets without the necessity of a middle man \(VC, investment banks, Big Pharma, etc.\). Specifically, research data will be stored on Inter Planetary File System IPFS and then hashed.<sup>[29](#f29)</sup> The hash is proof of data existence - therefore proving genesis of the data and copyright title provenance. <sup>[30](#f30)</sup> The research data itself is openly available for anyone to see, but is protected from a third party's commercial explotiation through the copyright. This hash is tokenized as license bandwidth and traded on the blockchain which enables cryptographic, timestamped validation of each transaction, providing provenance of intellectual property rights and the current state of IKU. See Figure E below:

**Figure E: IKU Smart Contracts & IPFS**

![IKU Smart Contract & IPFS](https://github.com/ikunetwork/WhitePaper/raw/master/IKU-IPFS-Smart-Contract.png)


Because of this architecture, for the first time, intellectual property rights can become fully fungible thereby allowing for direct monetization and trade of R&D.  This can be applied to any scientific initiative in which there is a value in the scientific data generated.  All transactions will be public on the Ethereum blockchain incentivizing one record of scientific truth.  A license is granted through the proof-of-license mechanism, of which the licensee can put the redeveloped drug through already established manufacturing and distribution channels, which are abundantly available for contract. 

### Direct Monetization of Research

Smarts contracts bypass the middle man, allowing for research and clinical trial data to be directly monetized, as opposed to the current industry strategy which is indirect: research --> patent --> company --> sell equity in company.  Direct monetization of data is the foundation of Bitcoin and cryptoassets - providing globally liquid and accessible markets to anyone with internet. IKU's mission is to bring this model to biotech research dramatically decreasing barriers to entry,  allowing (i) researchers and other learned persons to maximize scientific objectives by directly engaging p2p markets, (ii) anyone with internet access to participate and (iii) the realization of global supply and demand of medical science as opposed to a few centralized entities with their own private interests. 

Figure F further illustrates the benefits of the IKU data approach as opposed to the current, patent system:

**Figure F: IKU vs. Currenty Industry**

![IKU vs. Currenty Industry](https://github.com/ikunetwork/WhitePaper/raw/master/IKU-vs-Current-Industry.png)


### ELI The Artificial Neural Network

ELI is IKU’s Artificial Neural Network ANN specifically designed to predict regulatory approval of clinical trials and project success for proposed LIC[x] assets. We employ ML with the goal to achieve a robust A.I. in determining probability of success POS for consumer and institutional evaluation - a method to derisk asset creation and prioritization. 

Why use an ANN for clinical trial POS? It is a scalable and increasingly accurate solution in calculating probability, bypassing years of labor necessary in constructing a traditional algorithm for the same task. ML techniques in reputable papers, as well as in industry i.e. InSilico Medicine, have proven to be robust in estimating clinical trial success rates and regulatory approval.31 Bycollecting historicla clinical trial data since January 2000 and expanding on similar methodology, we were able to construct our own propietary ANN to be used to vet all proposed projects.


### Why IKU?

IKU allows for multilateral transparency and programmatic settlement for value exchange, currently not possible within the legacy bio R&D system. By shifting traditional business processes from a few controlling entities to a global decentralized network, it is possible to provide a commercially valuable infrastructure for scientific R&D that is both dynamic and open for all. Network participants will be able to capitalize, support and trade in R&D assets through decentralized resource allocation and increased market transparency. Access to R&D data and licenses are unlocked to the community at large which is expected to result in new discoveries and biotechnologies. The successful creation of this system will create a positive economic and scientific feedback loop. <sup>[31](#f31)</sup> 

The Network will serve to attract R&D ideation through crowdsourced input from thought leaders, researchers and the general public. Realistically, they do not have the time, expertise or resources to commence clinical trials. The Network aims to correct this slump and inform the market of the most scientifically viable R&D initiatives.

### The IKU Network

The mission is to establish the Network as a public utility for bio R&D, driving efficiency through global resource formation and decentralized liquidity pools. The community will own the Network in a trustless fashion, connecting individuals, science, verified researchers/research organizations – collectively participants - and funding. The Network will operate with a core objective to establish and facilitate the Network's R&D efficiencies. In addition, the IKU foundation may maintain a grants program in which bounties will be issued for (i) eliminating issues in the IN code and (ii) accomplishing specific innovations i.e. developing effective cancer treatments, aging treatments, etc. 

## The Network Economy

The Network combines the wisdom of crowds with the wisdom of science through participant capital information exchange. The following tools will give life to the IN: `researchTarget`, `devTools`, Request for Proposals `RFP`, and the `permissionlessLicense`.

### Research Target

Any person with internet access may submit a `researchTarget` which may be a concrete, verifiable objective or broad target. For example:

* Verifiable Object: Rediscovery of Metformin in a slow release formulation to treat lung cancer.
* Broad Target: Advancing research of aging and age-related diseases.

Among other aspects, the `researchTarget` may specify medical conditions, technology type i.e. therapy, device, mechanism of action, or any other known R&D metric. The `researchTarget` will be visible and sortable to the public, allowing for thorough analysis and determination of demand. The public will be able to upvote a `researchTarget` - spam protected thru captcha.

### `devTools`

Participants will access the Network through a `devTools` integrated interface. The `devTools` may include the following:

* `RFP` submission forms
* Wallet registration
* Topic forums
* Friends
* Direct messaging
* Reputation
* Upvote
* Share
* Comment
* Prediction Market 
* Upgrade to clinical trial subject 

Friends, messaging, and upvote access will require an Network profile, but will not require holding IKU in the Network Digital Wallet NDW - allowing anyone to use the Network. This type of access is classified as `devTools A`. RFP submissions, comments, prediction market for peer review, reputation scoring, and upgrading to clinical trial subject will require a Network profile AND holding at least 1 IKU in the NDW - `devTools B`.

### IKU Network Participants

Below are the players in the IKU Network. They are not mutually exclusive:

* `IKU` **Holder**: IKU token holder; can be an individual, institution, private company, etc. \(described further below\)
* `LIC[x]` **Holder**: License Token holder; can be an individual, institution, private company, etc. \(described further below\)
* **VR**: Verified Researcher i.e. MD, PhD, etc. whose expertise is credentialed through the Network. The VR can propose and respond to  a `researchTarget`, vote on their viability and review proposals. He/she is fundamental to IKU peer review.  
* **ADV** Anonymous data viewer - the public, who can freely contribute a `researchTarget`, views projects on the Network and has the option to create a Network profile to access `devTools A`. The Network will make information ethically and publicly available as current clinical trial results are typically not open to the public - even though they are required to be.  In addition, all `LIC[x]` sub-network initiatives will post a gantt chart for how advanced their research initiative is as well as the research data they have generated on a quarterly basis.

`reputationScore`:

* `reputationScore` is part of `devTools`. All participants may be subject to a profile linked `reputationScore` which accounts for utilization of Network resources and behavior, allowing for meritocratic decision-making based in scientific liquidity. All Network participants start with the same `reputationScore`, but will be separated by VR and non-VR. `reputationScore` may increase to `power`, `super_power` and `grand_maester`.  This enables the best ideas to flow freely, producing efficient and rapid evolution based on merits.<sup>[32](#f32)</sup> Participants will be obligated to provide `reputationScore` to other participants they have digitally engaged.  The `reputationScore` will be publicly available.

### Request for Proposal

The Network will serve to produce requests for peer reviewed proposals `RFP` in response to `researchTargets`. A VR will be able to submit proposals at any time as paid for by the IKU foundation, whereas non-VR will be required to post a bond to submit a proposal.

A proposal is required to consist of 

\(i\) a principal investigator PI and/or Project Lead that leads the R&D team along with the `LIC[x]` Holders that the PI and his/her team will have to answer to \(see below `LIC[x]` value\), 
\(ii\) how much funds are being raised and for what percentage of `LIC[x]`, with proposers encouraged to not issue 100% of `LIC[x]` to account for future funding requirements and 
\(iii\) the scientific justification of proposed R&D. 

A standard `LIC[x]` proposal template will be provided. Further value may be determined by the IKU user submitting the proposal, allowing for a flat environment in which value proposition may be programmed into an `LIC[x]`.  This leaves significant room for `LIC[x]` value creativity.

### An Information Market for Peer Review

Information markets enable the synthesis of vasts amount of information held by individuals into a useful data point, without the biases that plague traditional forecasting methods, such as polls or "expert" analysis.<sup>[33](#f33)</sup>. The price of an information market  serves as indication of the value of information. <sup>[34](#f34)</sup>. The transactions traders make to maximize their profits effectively reveal their private information to the marketplace. <sup>[35](#f35)</sup> Ultimately, Information market assessments are reported to be more accurate than an uninformed information prediction model 85% of the time.<sup>[36](#f36)</sup>  Fortune 500 companies use information markets to produce more efficient outcomes for enterprise including utility by Google, Intel, Microsoft, Motorola, Qualcomm, banking systems, Eli Lilly, Pfizer, Siemens, to name a few. <sup>[37](#f37)</sup> 

The current pharma industry does not prioritize R&D opportunities based on public health outcomes, but based in patent positions and corporate profits. The Network will serve to correct this by enabling Participants to predict outcomes of R&D proposals using `IKU`, sortable by VR. R&D proposals require scientific support data. Proposals with the highest `IKU` balances effectively  reveals otherwise private scientific and market demand information to the public at large. Participants are incentivized to engage the information market to earn fees \(more on fees below\) - to provide highly predictive, robust R&D pipelines.  We incentivize the uncovering and advancement of efficient R&D, thereby creating justification for their funding. Stakeholders can become a node in a R&D network - collectively feeding the network with information serving to fuel innovation while at the same time owning the value.  Through this utility, IKU serves to achieve open information markets.

Upon a proposal achieving a specified threshold value, 2 smart contracts will be deployed to the Ethereum Blockchain: \(i\) `LIC[x]` - An ERC20 token representing the license to `[x]` and \(ii\) `LICCrowdsale[x]` \(based on [https://github.com/OpenZeppelin/zeppelin-solidity](https://github.com/OpenZeppelin/zeppelin-solidity)\), which responsible for minting `LIC[x]` and in exchange send tokens to contributors.

Upon `LICCrowdsale[x]` achieving its softcap - minimum funds required to achieve milestone:

1. A `LIC[x]` sub-network is created in which `LIC[x]` holders hold digital keys 
2. All `LIC[x]` Holders will be able to participate in their respective `LIC[x]` sub-network and work with the R&D team to achieve the mission of the proposal, e.g. complete clinical trials for _____________
3. [y%] of the funds will be released to the R&D team,
4. IKU Token Holders earn `LIC[x]` as described below.

A `LIC[x]` sub-network is an ad hoc virtual collective capitalized through smart contracts to power a specific R&D initiative.  It consists of a R&D team (principal investigator and/or project lead, etc.) and its token holder network to ultimately progress through clinical trials together by interacting and communicating through their sub-network with IKU infrastructure.

The IKU foundation will provide legal support to convert funds raised in BTC, ETH, etc. to fiat.  All capital resources are to be allocated purely towards R&D support.  In addition, prior to initiating a clinical trial, `LIC[x]` R&D team will be responsible for ensuring ethical research compliance through an institutional review board.


**Smart contract for`LICCrowdsale`**

```text
pragma solidity ^0.4.18;

import 'zeppelin-solidity/contracts/crowdsale/validation/CappedCrowdsale.sol';
import 'zeppelin-solidity/contracts/crowdsale/distribution/RefundableCrowdsale.sol';
import 'zeppelin-solidity/contracts/crowdsale/emission/MintedCrowdsale.sol';
import 'zeppelin-solidity/contracts/token/ERC20/MintableToken.sol';


contract LICCrowdsale is CappedCrowdsale, RefundableCrowdsale, MintedCrowdsale {


  function LICCrowdsale(
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

### IKU Network Utility

The following sequence of events illustrate the IKU Network utility to facilitate global resource formation and trade for R&D:

**Figure G: IKU Network Utility**

![IKU Network Utility](https://github.com/ikunetwork/WhitePaper/raw/master/IKU%20Network%20Utility.png)


The Network will serve to be a library-hub for the generation, tracking and exchange of superior scientific R&D assets allowing for an incentivized, open workflow for the most promising research and clinical trials.  


## Tokenization

The IN creates two classes of native tokens:

* `IKU`: Serves as Network bandwidth. `IKU` enables access to R&D and clinical trial proposals to mediate participation in the Network as described above. The supply of IKU is finite.
* `LIC[x]`: The License Token serves as license keys.  If a certain amount of license keys are registered to one address, that private key can unlock an exclusive license to the R&D data set - `permissionlessLicense` (more below); as well as a copyright license to participate in the sub-network (more below).  Supply is dependent on demand. `LIC[x]` bundles, `LIC[i]` may be developed as per a future bounty, allowing for scientific and economic risk diversification where `i` represents the number of `LIC[x]` bundled.  

`IKU` and `LIC[x]` token holders may retain custody, with no asset exchange third-party intervention. The two token incentive model is designed to provide scientists and the general public with agency in determining the future of biotech, regardless of patent policy and large corporations - a radically different model that enables global liquidity for research assets.  


### `IKU` Value

Wallet verification of a minimum of balance of 1 IKU enables access to the `devTools B` and fees as explained below. Value in the IKU token can be ascribed to access the following:

* `devTools B`
* 2nd priority to upgrade to clinical trial subject
* Fees in `LIC[x]`

Establishing a profile on the Network provides access to the Network Digital Wallet NDW.  The NDW may serve to hold BTC, ETH, IKU and all `LIC[x]`, and is expected to also eventually hold digitalized fiat, providing for efficient capital formation and value exchange. In addition, the NDW enables IKU holders to earn fees in `LIC[x]` as \[z%\] of all of the `LICCrowdsale`, pro-rata, will flow to `IKU` holders in exchange for registering their IKU bandwidth in the information market. Such model gives an IKU holder the opportunity to contribute and have rights to all R&D initiatives on the Network. 

### `LIC` Value

A `LIC[x]` is the license bandwidth of an R&D initiative, pro-rata specific to that research initiative (clinical trials, etc.) and such rights are cryptographically maintained.  Value in the `LIC[x]` token can be ascribed to the following:

* Right to access, use, publish, develop R&D, contribute to the `LIC[x]` sub-network with possession of a minimum, predetermined `LIC[x]` threshold. 
* `permissionlessLicense` smart contract
* 1st priority to upgrade to clinical trial subject
* Early access to realized biotechnology upon regulatory approval \[at a discounted \(or free\) rate\]

Parties that own `LIC[x]` private keys effectively own a fungible piece of the R&D as the rights inusre to the benefit of `LIC[x]` holders. A transaction involving `LIC[x]` is the cryptographic validation of keys to (i) participate in the sub-network and (ii) `LIC[x]` hashed data, timestamped by the blockchain. This is transparently irrefutable evidence of R&D intellectual property rights provenance at a given point in time, protecting against reasons for litigation.  The R&D team will provide updates to the `LIC[x]` Holders in their sub-network on a regular basis, in which `LIC[x]` holders will have ability for contributing in the sub-network to:

* \(i\) Determine whether R&D team should have access to remainder of funds for continuing research \(upon reaching or not reaching R&D a milestone\), based on reputation.
* \(ii\) publish R&D, provide commentary, review and discuss R&D actions, make recommendations, propose development amendments, coordinate presentations and publications and generally facilitate the flow of information through the Portal between the Parties.
* \(iii\) reproduce and create derivative works based upon R&D for the purposes of marketing, advertising and promoting development, especially for cultural localization to drive adoption, retention and general support for public benefit, globally.

A `LIC[x]` sub-network may capitalize on the copyright data exclusivity periods the keys provide access to.  In addition, `LIC[x]` holders may pursue patent protection for inventions developed based on Network funded research, together as a sub-network as owned by `LIC[x]` holders, but patents may not be used in the Network. <sup>[38](#f38)</sup> 

The `LIC[x]` sub-network is incentivized to provide timely and relevant information to both its own sub-network and the public as the `LIC[x]` and `IKU` will be at the mercy of market sentiment. `IKU` and `LIC[x]` tokens are expected to trade in real time, globally in the cryptoasset market place. If an `LIC[x]` sub-network does not operate in efficient scientific fashion, it is expected to be reflected accordingly.

**Smart Contract for `LIC[x]`**

```text
pragma solidity ^0.4.18;

import 'zeppelin-solidity/contracts/token/ERC20/MintableToken.sol';

 contract LIC is MintableToken {
    uint8 public  decimals;
    string public  name;
    string public  symbol;

    function LIC(
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

### Burning 

IKU aligns its burning strategy with the creation of `LIC[x]`.  A % of `IKU` tokens are burned from the `IKU` Reserve upon a `LIC[x]` softcap being achieved.  This is expected to occur on a regular basis.


### The `permissionlessLicense`

The IKU architecture facilitates an ongoing real time auction market around R&D data through the `permissionlessLicense` protocol.  The `permissionlessLicense` protocol allows for global trade of any dataset or IP, that has scarcity properties, as cryptographic license keys (not just limited to biotech). Registration of a certain threshold of cryptographic license keys - a number which is predetermined at the time of the `RFP` creation - unlocks a copyright license to the `LIC[x]` sub-network license. This allows for a license to be highly available, fungible and auditable as it is a datapoint on a blockchain. 

The party who registers the threshold of private keys now has a license to utilize and exploit the R&D data, e.g. completed Phase II clinical trial data, to potentially submit to the U.S. FDA for approval. The more scientifically advanced the R&D initiative, the greater the expected demand for its respective license and therefore `LIC[x]` becomes more scientifically valuable i.e. completing Phase II clinical trials - more value will be required by one who desires a `permissionlessLicense` to achieve the `LIC[x]` license threshold.

For example, recent research has shown that Rapamycin, a generic small molecule in tablet form used prevent organ transplant rejection and to treat a rare lung disease, may have potent effects against aging.<sup>[41](#f41)</sup>  A researcher may create a modified release Rapamycin anti-aging formulation for Phase II clinical trials, leveraging extensive existing generic Rapamycin safety data in both animals and humans.  The new formulation and successful clinical trial data enable copyrights for a new data set that comes with the data exclusivity periods previously mentioned.  See Figure H:

**Figure H: Rapamycin License Data Stack**

![IRapamycin License Data Stack](https://github.com/ikunetwork/WhitePaper/raw/master/RAP-License-Data-Stack.png)

In the Rapamycin example, the new data package (formulation + clinical trials) stored on IPFS, hashed, and tokenized as license - `LIC[RAP]`. The data can be licensed by registering a certain threshold of `LIC[RAP]` license private keys, then utilized in a data package for potential approval. See figure I:

**Figure I: LIC RAP Market**

![LIC[RAP] Market](https://github.com/ikunetwork/WhitePaper/raw/master/LIC-RAP-Market.png)

The Network will provide a standard `permissionlessLicense` with drop down variables such as territory, registration threshold, required efforts for good faith development \(e.g. Phase II clincal trial commence in 6 months\), amongst others. This will enable proposers to click through, filling in variables at their discretion, likely dramatically reducing the need for negotiation, lawyers and other middlemen - enabling an open streamlined licensing process. In addition, parties will have the opportunity to provide their own customized license, subject to market demand.  


### The IKU Reserve

The IKU foundation will maintain its assets as necessary for incentivizing VR peer review, liquidity and community bounties in both software and bio R&D.  Resources may be stored in an Ethereum MultiSigWallet: \([https://github.com/Gnosis/MultiSigWallet](https://github.com/Gnosis/MultiSigWallet)\) which is built on top of ConsenSys Ethereum MultiSigWallet \([https://github.com/ConsenSys/MultiSigWallet](https://github.com/ConsenSys/MultiSigWallet)\).\] All foundation transactions and bounties will be public.

### Future Development

Additional features are expected to be developed to further efficiencies, which may include but are not limited to advanced analytic and platform navigation tools including human data inputs, as well as links to language agnostic relevant public and private content through APIs \(e.g., PubMed, IP Databases\). This will improve workflow efficiency and thus lead to enhanced platform performance.

As to specific anticipated service components, a software bounty may be deployed for `LIC[i]` bundling, `i` representing the number of `LIC[x]` bundled, as stated below:

Bundling may serve to enable various bio R&D assets to mitigate economic and scientific risk exposure as well as provide horizontal, or vertical licensed research collaboration. As opposed to a traditional centralized corporation, the `LIC[i]` bundle lowers the cost of both trust and risk.

How to bundle:

* Declare `LIC[x]` eligible to bundle with `i-1` in the `RFP`, or later point in time
* Declare `LIC[x]` seeking bundle

All Network R&D initiatives would have the option to actively bundle `LIC[x]` into `LIC[i]`, or allow for `LIC[i]` to choose to bundle with an `LIC[x]`, with atomic swap capability, allowing for high performant assets to be transacted globally across, or in the same R&D verticals. Atomic exchange serves as a mechanism to reduce risk and stabilize IKU/`LIC[i]` in a frictionless fashion, as atomic assets do not need to be traded on a centralized exchange, but can be swapped for one another through direct p2p algorithmic execution.

This would be especially important for clinical trials in the same research vertical i.e. condition, disease, mechanism of action, molecule, etc. as it mitigates scientific and economic risk through the ability to algorithmically bond with each other through smart contract.

As to potential expansion R&D areas - specific cannabis-based medicines.  NIH scientists believe that cannabis-based medicines can treat various conditions that currently lack quality treatment options, but proper clinical trial data is needed.<sup>[39](#f39)</sup>  Furthermore, the verified data provided by licensed cannabis distributors is just the Tetrahydrocannabinol (THC) and Cannabinoid (CBD) content, whereas the medicinal claims are anecdotal. The global medicinal cannabis market is ~$11 billion and expected to grow to ~$100 billion by 2025.<sup>[40](#f40)</sup>   The Network may serve as an authoritative source for official cannabis R&D and peer reviewed publications, allowing for stakeholders to make well- informed cannabis-related decisions. 

## Conclusion

IKU will serve to enable unprecedented global creation and deployment of resources for safe and impactful clinical trial research. Decentralizing resource allocation and asset transactions allows for increased transparency of market activity which is expected to lead to significant bio innovation in the near future. The foregoing working draft has sketched a paradigmatically novel vision of the structural and organizational means by which this can dramatically increase the reward for efficient R&D, reduce the risk of failure, all the while enabling global, decentralized liquidity. We expect the Network to be a critical infrastructure piece to spark and launch the entire system of digital R&D rights. This is the fundamental intention and the essence of the IKU.

## Footnotes

<b id="f1">1</b> James Bessen, The Evidence is in: Patent trolls do hurt innovation, Harvard Business Review \(2014\). Gene Quinn, et. al., Are More than 90% of Patents Challenged at the PTAB Defective?, IPWatchdog \(2017\). J. Hudson et. al., Into the valley of death: from research to innovation, [https://www.ncbi.nlm.nih.gov/pubmed/23402848](https://www.ncbi.nlm.nih.gov/pubmed/23402848) \(2013\).Tufts Center for the Study of Drug Development, How the Tufts Center for the Study of Drug Development Pegged the Cost of a New Drug at $2.6 Billion \(2014\).

<b id="f2">2</b> See Id. Robert Sachs, Fenwick & West LLP, Patent Invalidity Rates: The Summertime Blues Continue, Law 360 \(2015\). Such inefficiencies have caused significant IP law has attempted to enforce, but enforceability is difficult, time consuming and expensive as:

* patent litigation costs ~ $30 billion per year
* ~80% of the litigation comes from patent trolls 
* 50%+ of U.S. patents are being invalidated in post-grant proceedings.

All of which lead to significant issues in transaction finality, exacerbating an already illiquid market. Id.

<b id="f3">3</b> FiercePharma, The world's most pricey drugs, from a $1.2M gene therapy to a $450K lymphoma med, [https://www.fiercepharma.com/marketing/world-s-most-pricey-drugs-from-a-1-2m-gene-therapy-to-a-450k-lymphoma-med](https://www.fiercepharma.com/marketing/world-s-most-pricey-drugs-from-a-1-2m-gene-therapy-to-a-450k-lymphoma-med) \(2017\).

<b id="f4">4</b> See FN 1.

<b id="f5">5</b> Tufts Center for the Study of Drug Development, How the Tufts Center for the Study of Drug Development Pegged the Cost of a New Drug at $2.6 Billion \(2014\).

<b id="f6">6</b> K. Stott, Pharma’s broken business model: An industry on the brink of terminal decline, [https://endpts.com/pharmas-broken-business-model-an-industry-on-the-brink-of-terminal-decline/](https://endpts.com/pharmas-broken-business-model-an-industry-on-the-brink-of-terminal-decline/) \(2017\).

<b id="f7">7</b> Congressional Research Service, NIH Funding: FY1994-FY2016, [https://fas.org/sgp/crs/misc/R43341.pdf](https://fas.org/sgp/crs/misc/R43341.pdf).

<b id="f8">8</b> Roger Stein, MIT Research Associate, A Bold New Way to Fund Drug Research, TED Talk \(2013\).

<b id="f9">9</b> 21st Century Cures Whitepaper, A Path to Discovery, Development, [https://energycommerce.house.gov/cures/](https://energycommerce.house.gov/cures/) \(2016\).

<b id="f10">10</b> Bernard Munos, Can you teach old drugs new tricks, [https://www.nature.com/news/can-you-teach-old-drugs-new-tricks-1.20091](https://www.nature.com/news/can-you-teach-old-drugs-new-tricks-1.20091) \(2016\).

<b id="f11">11</b> Id.

<b id="f12">12</b> FDA, What are generic drugs?, [https://www.fda.gov/Drugs/ResourcesForYou/Consumers/QuestionsAnswers/ucm100100.htm](https://www.fda.gov/Drugs/ResourcesForYou/Consumers/QuestionsAnswers/ucm100100.htm).

<b id="f13">13</b> Id.

<b id="f14">14</b> Bruce Bloom, Cures Within Reach, [http://www.the-scientist.com/?articles.view/articleNo/47744/title/Repurposing-Existing-Drugs-for-New-Indications/](http://www.the-scientist.com/?articles.view/articleNo/47744/title/Repurposing-Existing-Drugs-for-New-Indications/) \(2017\).

*<b id="f15">15</b> Id.  FDA Approvals 2016, https://www.fda.gov/drugs/developmentapprovalprocess/druginnovation/ucm483775.htm.  FDA Approvals 2017, https://www.fda.gov/Drugs/DevelopmentApprovalProcess/DrugInnovation/ucm537040.htm.

<b id="f16">16</b> JJ Hernandez, et. al., Giving Drugs a Second Chance: Overcoming Regulatory and Financial Hurdles in Repurposing Approved Drugs As Cancer Therapeutics, https://www.ncbi.nlm.nih.gov/pubmed/29184849 (2017).

<b id="f17">17</b> Matthew Herper, Forbes, Winners And Losers From Cancer Research's Biggest Event, https://www.forbes.com/sites/matthewherper/2018/06/04/winners-and-losers-from-cancer-researchs-biggest-event/#277c612961bf (2018).

<b id="f18">18</b> The Economist, Patents that kill, [https://www.economist.com/blogs/freeexchange/2014/08/innovation](https://www.economist.com/blogs/freeexchange/2014/08/innovation) \(2014\).

<b id="f19">19</b> Lisa Diependaele, et. al., Raising the Barriers to Access to Medicines in the Developing World – The Relentless Push for Data Exclusivity, [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5347964/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5347964/) \(2017\). CFDA, Provisions for Drug Registration, [http://eng.sfda.gov.cn/WS03/CL0768/61645.html](http://eng.sfda.gov.cn/WS03/CL0768/61645.html). International Federation of Pharmaceutical and Manufacturers Association, [https://www.ifpma.org/wp-content/uploads/2016/01/IFPMA\_2011\_Data\_Exclusivity\_\_En\_Web.pdf](https://www.ifpma.org/wp-content/uploads/2016/01/IFPMA_2011_Data_Exclusivity__En_Web.pdf).

<b id="f20">20</b> G. Quinn and S. Brachmann, Are more than 90 percent of patents challenged at the PTAB defective?, http://www.ipwatchdog.com/2017/06/14/90-percent-patents-challenged-ptab-defective/id=84343/ (2017).  See FN 1 and FN 2.


<b id="f21">21</b> Copyright Basics, https://www.uspto.gov/learning-and-resources/ip-policy/copyright/copyright-basics.

<b id="f22">22</b> FN 19.

<b id="f23">23</b> Id. 

<b id="f24">24</b> Id.

<b id="f25">25</b> Id.

<b id="f25a">25a</b> K. Grimes, MD and Daria Mochly-Rosen, Stanford Medical School, A Practical Guide to Drug Development in Academia, The SPARK Approach (2014).  Andrew Lo, Esther S. Kim, Paige M.C. Omura, MIT Accelerating Biomedical Innovation: a case study of SPARK program at Stanford University, School of Medicine, Drug Discovery Today, Volume 22, Number 7 (July 2017), available at http://alo.mit.edu/wp-content/uploads/2017/06/SPARK_pub_final.pdf). Jose Maria Fernandez, et. al., MIT Can Financial Engineering Cure Cancer?: A New Approach to Funding Large-Scale Biomedical Innovation,  (January 18, 2013), available at https://ssrn.com/abstract=2203203 .

<b id="f26">26</b> Nick Szabo, Formalizing and Securing Relationships on Public Networks, [http://firstmonday.org/ojs/index.php/fm/article/view/548/469-publisher=First\#introduction](http://firstmonday.org/ojs/index.php/fm/article/view/548/469-publisher=First#introduction) \(1997\).  Tom Ding, e-mail communication (2018).

<b id="f27">27</b> Vitalik Buterin, A NEXT GENERATION SMART CONTRACT & DECENTRALIZED APPLICATION PLATFORM, ethereum/Wiki.

<b id="f28">28</b> H. Diedrich, IBM Liason to Ethereum, Ethereum: Blockchains, Digital Assets, Smart Contracts, Decentralized Autonomous Organizations \(2016\).

<b id="f29">29</b> J. Benet, IPFS - Content Addressed, Versioned, P2P File System \(DRAFT 3\). 

<b id="f30">30</b> R. Merkle, A Certified Digital Signature, http://www.merkle.com/papers/Certified1979.pdf (1979).  S. Nakamoto, Bitcoin: A Peer to Peer Electronic Cash System, https://bitcoin.org/bitcoin.pdf (2008).

<b id="f31">31</b> Santiago Roel Santos, e-mail communication (2018).

<b id="f32">32</b> R. Dalio, Principles (2017).

<b id="f33">33</b> A. Mann, The Power of Prediction Markets, Nature (October 2016, discussing Austrian economist Friedrich Hayek).

<b id="f34">34</b> P. Polgreen, et. al., Using Prediction Markets to Forecast Trends in Infectious Diseases, Microbe, Vol. 1, Number 10 (2006).

<b id="f35">35</b> Id.

<b id="f36">36</b> SciCast Annual Report, May 2015, http://mason.gmu.edu/~rhanson/SciCast2015.pdf.

<b id="f37">37</b> Wikipedia, Prediction Markets.

<b id="f38">38</b> Defensive Patent Licensing, https://defensivepatentlicense.org/. Matt Corallo, e-mail communication (2018).

<b id="f39">39</b> U.S. National Institute of Health, Medical Marijuana, https://nccih.nih.gov/health/marijuana.

<b id="f40">40</b> Grand View Research, Medical marijuana emerged as the largest marijuana type segment in 2016 and is estimated to be valued at USD 100.03 billion by 2025, https://www.grandviewresearch.com/press-release/global-legal-marijuana-market (2018).

<b id="f41">41</b> M. Blagosklonny, From rapalogs to anti-aging formula, https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5482593/ (2017).


Without permission, anyone may use, reproduce or distribute any material in this white paper for non-commercial and educational use (i.e., other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notice are cited.

DISCLAIMER: This White Paper is for information purposes only. The authors and or its affiliates does not guarantee the accuracy of or the conclusions reached in this white paper, and this white paper is provided “as is”. The authors and or its affiliates not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from error; and (iii) that such contents will not infringe third-party rights. The authors and or its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will the authors and or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses.

