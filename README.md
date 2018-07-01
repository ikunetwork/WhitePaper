# IKU - Biotech Redefined

Working Draft

## Abstract

IKU is the first public utility to scale biotechnology research and clinical trials by establishing digital rights to research and clinical trial data sets as assets to be issued and traded in an open, global market. Currently, the marginal increase in lifespan is severely disproportionate to research duration as drug development and clinical trials traditionally focus on new molecular entities ("NME"). NME's typically take over 15 years per market entry and cost over $1 billion - a faulty, non-scalable process. Why? Patent friction.  Recent developments in globalization of clinical trials allow for an arbitrage in which clinical trials and approvals cost 200x less than the traditional patent-based pharma model.  IKU provides for research assets in the copyright of the actual research data itself, abstract from patents, providing a digital infrastructure on which bio R&D can scale.

IKU employs the blockchain and smart contracts to construct an incentive framework conducive to the advancement of bio R&D and clinical trials. Smart contracts collapse capital, data and execution into one, providing a new digital incentive mechanism. Through global smart contract enabled bio R&D markets, we can significantly increase the marginal return on lifespan per unit of research advancement. A digital, liquid R&D and clinical trial economy is a new paradigm, serving to improve capital formation and realization of pent up demand for biotechnology. This paper explains (i) the deficiencies of the current legacy R&D model, (ii) the mission of creating a digitally, liquid global market to scale bio R&D/trials and (iii) how IKU ultimately compounds value through global arbitrage to push science and medicine to boundaries yet unseen.  This architecture will be supported by a two-token incentive model providing fee derivation from IKU supported R&D.

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
2. [The Network Economy](#the-network-economy)
   1. [Research Target](#research-targets)
   2. [Dev Tools](#dev-tools)
   3. [IKU Network Participants](#iku-network-participants)
   4. [Request for Proposals](./#request-for-proposals)
   5. [IKU Network Utility for R&D](./#iku-network-utility)
   6. [The Library Exchange](./#the-library-exchange)
3. [Tokenization](./#tokenization)
   1. [`IKU`](./#iku)
   2. [`RST`](./#rst)
   3. [`IKU` Value](./#iku-value)
   4. [`RST[x]` Value](./#%60RST[x]%60-value)
   5. [Burning](./#burning)
   6. [`The RST[x]` `permissionlessLicense`](./#the-rst[x]-permissionlessLicense)
   7. [Decentralized Key Management System](./#decentralized-key-management-system)
   8. [The `IKU` Reserve](./#the-elixr-reserve)
   9. [Future Development](#future-development)
4. [Conclusion](./#conclusion)

## Introduction

### Problem Statement

Bio R&D operates in analog fashion. And rightfully so as patents and capital formation conform under the same hood. Unfortunately, the patent system makes it close to impossible for the public to realize new biotech at scale.<sup>[2](#f2)</sup> Why? Because of its analog infrastructure and associated cost in trust and liquidity. There is no enforceable global record of R&D data rights without fault (litigation), resulting in significant inefficiencies in clinical development. <sup>[3](#f3)</sup> Only large, well-capitalized corporations can sustain such inefficiencies, whom then seek rent from patients, insurance and the general public through high retail cost - rare disease drugs often come with high price tags, limited human exposure, and can cost as much $1 million per regimen.<sup>[4](#f4)</sup> Researchers are then incentivized to conceal their data in hopes of a large corporation pursuing a license to research, as opposed to peer collaboration within the scientific community. The result is (i) very limited R&D investment per capita and (ii) significant illiquidity as the necessary resources are firmly controlled by centralized institutions.

In addition, capital is almost exclusively allocated to new molecular entities NME - molecules never conceived nor had human exposure, as NME's are a more enforceable record of data.<sup>[5](#f5)</sup> Unfortunately, NME's are logistically difficult to achieve, requiring:

* $2.6 billion in R&D spend
* 15 years to complete clinical trials for market access
* 0.02% chance of obtaining FDA approval upon being discovered in the lab.<sup>[6](#f6)</sup>

This model has proven to be very inefficient as pharma’s internal rate of return IRR on capital over the last ~30 years has been decreasing in linear fashion, with IRR already below the cost of capital in 2017<sup>[7](#f7)</sup> See Figure A:

**Figure A: Return on Investment in Pharma R&D**

 ![Return on Investment in Pharma RD](https://github.com/ikunetwork/WhitePaper/raw/master/Return-on-Investment-in-Pharma-R%26D.png)

Compounded with pharma R&D spend never outpacing non-R&D spend i.e. marketing, etc. in any given year since ~1990.<sup>[8](#f8)</sup> We've also seen a decrease in medical research funding from the U.S. National Institute of Health.<sup>[9](#f9)</sup>) See Figure B:

**Figure B: NIH Funding 2003-2015**

![NIH Funding 2003-2015](https://github.com/ikunetwork/WhitePaper/raw/master/NIH-Funding.png)

The outcome is a ~20 year backlog of potential drugs waiting for funds to enter clinical trials.<sup>[10](#f10)</sup> In fact, there are over 10,000 diseases/conditions afflicting humans of which less than 600 have known treatments.<sup>[11](#f11)</sup>) While it costs over $2 billion to develop a NME in the U.S., there are multiple R&D efficiencies in which it can cost under $15 million to get a treatment approved.  This is due to clinical trial arbitrage between China and the rest of the world.  It costs under $15 million to get a drug approved in China, of which then such data can be submitted to the U.S., Europe, etc. for approval.  Notably, 80% of approved marketing applications for drugs and biologics cuse data from clinical trials conducted outside the U.S.  China has recently become a major player in biotech as potential treatments can be tested effectively, faster and at a lower cost compared to the U.S. or western Europe. <citations>.  
   
   Show China Chart
   
   
   The U.S. is starting to answer China, as can be seen with passage of the 21st Century Cures Act (passed in the U.S. in Q4 2016) calls for using "real world evidence" to determine the true efficacy of a biotechnology.  In 2016, 5 treatments were approved by the U.S. FDA on one efficacy clinical trial alone and in 2017, 19 treatments were approved on one clinical trial!  For rare disease populations, often determined to not be "blockbuster" enough for big pharma shareholders, development and Phase II clinical trials can be completed for under $10 million, of which then this can potentially lead to an approval on just this one trial.
   
   Rare Disease + Approvals quick
   
   In addition, generic drugs have proven to be safe and inexpensive, and can be rediscovered to treat many more conditions, for which no quality treatment exist.<sup>[12](#f12)</sup>) where rediscovery can be fully realized \(e.g. FDA approved\) in just one clinical trial for as little as $5 million, while significantly lowering any potential reason for future litigation.<sup>[13](#f13)</sup> . 50% of existing drugs can be redeveloped to reach the market at a fraction of the cost and time.<sup>[1](#f1)</sup>
   
   Metforming Mexico Trial

The industry R&D model as it currently stands is clearly a failure and does not account for this arbitrage.<sup>[14](#f14)</sup> The holdup is not the science, but the incentive to efficiently mobilize resources to realize the science. Blockchains can now  digitally program incentive models to coordinate resources where it was not previously possible. Generic medicines are built on the same active ingredients (as the patented drugs) once their patents or marketing exclusivities expire.<sup>[20](#f20)</sup> More specifically, the same dosage, effectiveness and - safety - profile as the original drug.<sup>[21](#f21)</sup> By the time the generic form can be sold, the ingredients would have already been on the market for many years and as such, the generic themselves are considered safe for patients.<sup>[22](#f22)</sup> Because their patents expired, there is significantly less risk of infringement and more freedom to operate. IKU's focus will be on the redevelopment of generics, 

_The most fruitful basis for the discovery of a new drug is to start with an old drug_ - Sir James W. Black, Nobel Prize in Medicine 1988.  As per U.S. NIH researchers, approx. 50% of existing drugs can be rediscovered for a disease or a condition lacking viable options.<sup>[23](#f23)</sup> Because existing drugs have already proven to be safe, the majority of clinical trial rediscovery initiatives can skip Phase I _safety_, and move directly into Phase II _efficacy_.<sup>[24](#f24)</sup> Phase II costs are estimated to be as low as $5 million and take as little as a few years for approval, as opposed to ~15 years for NME.<sup>[25](#f25)</sup> In fact, there were only 20+ U.S. FDA medicine approvals in 2016 - 2017 on just one _efficacy_ clinical trial, compared to ~30% FDA approval rate for drug rediscovery vs. 5% FDA approval rate for NME \(approximately .1% in lab, 10% upon entering clinical trial\).<sup>[26](#f26)</sup> It is clear the probability of success is higher for rediscovery, eliminating years of uncertainty with dramatically lower costs. Such strategy compresses the R&D pipeline, allowing for value inflection to be reached more efficiently - accelerating market entry of inexpensive, safe medicines. Figure D illustrates how IKU streamlines research as compared to the traditional R&D pipeline:

**Figure D: IKU vs. Traditional R&D Pipeline** 

![IKU vs. Traditional R&D Pipeline](https://github.com/ikunetwork/WhitePaper/raw/master/IKU-vs-Traditional-R%26D-Pipeline.png)

### IKU Approach

IKU provides the infrastructure for a liquid, bio R&D network to advance R&D productivity by orders of magnitude. The IKU Network **IN** will serve to provide value exchange entry and exit opportunities through a fungible digital licensing mechanism enforced on the Ethereum blockchain. Consider IKU as the Manhattan Project for R&D efficiency, with Figure C contextualizing its benefits:

**Figure C: Existing R&D Models**

![Existing R&D Models](https://github.com/ikunetwork/WhitePaper/raw/master/Existing-R%26D-Models.png)

### How?

IKU provides a global liquid architecture for R&D and clinical trials through tokenized copyright licenses, leveraging a liquid licensing protocol \(see The `RST[x] permissionlessLicense` section below\) in which all transactions are settled programmatically as data points on-chain, as rights are proved through existence of smart contract provenance.   

IKU reinvents bio R&D and clinical trial markets through tokenization, providing transparent and open markets for the generation, tracking and exclusive usage of R&D data sets to accelerate access to the future of medicine. This will serve to provide interested parties with rapid market entry and exit abilities, reducing transaction costs, ultimately providing coordination and liquidity advantages for R&D between parties who otherwise would not know or trust each other. The IKU token provides bandwidth to power the protocol's enforcement on the ethereum virtual machine.

### What are Smart Contracts?

Smart contracts are agreements with super powers, as they provide a deterministic environment guaranteeing information fidelity and trusted exchange of value. Specifically, a smart contract is: \(i\) code that moves information and/or money based on a condition between as many parties as needed, regardless of jurisdiction \(IKU will strive to obey by all applicable laws and regulations\); \(ii\) an automatism that is guaranteed to execute as it uses algorithms \(blockchain\) for enforcement, not a legal system; and \(iii\) binding.<sup>[15](#f15)</sup>

Once a smart contract is set in motion, the blockchain is utilized to serve as an independent third party to verify agreement execution.<sup>[16](#f16)</sup> Ultimately, overhead is reduced ,trust improves, and efficiency increases with no third party necessary for escrow.<sup>[17](#f17)</sup> Money is guaranteed to flow on contract resolution without the need to sue - smart contracts provide justice without judges.

IKU is built on Ethereum, leveraging smart contracts to transact in digital R&D assets without the necessity of a middle man \(VC, investment banks, Big Pharma, etc.\). Barrier to entry dramatically decrease, and allows \(i\) researchers and other learned persons to maximize scientific objectives by directly engaging p2p capital, \(ii\) anyone to participate in the market and \(iii\) the realization of global supply and demand of medical science as opposed to a few centralized entities with their own private interests. All transactions will be public on the Ethereum blockchain, allowing all stakeholders to collectively provide liquid R&D, incentivizing one record of scientific truth.

### Why IKU?

IKU allows for multilateral transparency and programmatic settlement for value exchange, currently not possible within the legacy bio R&D system. By shifting traditional business processes from a few controlling entities to a global decentralized network, it is possible to provide a commercially valuable infrastructure for science and medicine that is both dynamic and open for all. Network participants will be able to capitalize, support and trade in R&D assets through decentralized resource allocation and increased market transparency. Access to R&D data and licenses are unlocked to the community at large which may result in new discoveries and drug applications. The successful creation of this system will create a positive economic and scientific feedback loop.

The IN will serve to attract R&D ideation through crowdsourced input from thought leaders and patients. Realistically, researchers and patients do not have the time, expertise or resources to commence clinical trials. The IN aims to correct this slump and inform the market of the most scientifically viable R&D initiatives.

### What about Patents?

By the time an NME enters clinical trials, its patent life has 10 years, often times 5-6 years remaining.<sup>[18](#f18)</sup> Jurisdictions including U.S., EU and Asia provide market/data exclusivity periods \(independent of patents\) for clinical trial data for up to ~10 years, regardless if it is an NME.<sup>[19](#f19)</sup> IKU is designed to leverage biotech regardless of patent policy, as rights are based in the copyright of the data generated, which ethically applies upon conception of the data, as opposed to patents which have to be registered limited by jurisdiction.  

Specifically, a license is required by regulatory bodies globally \(i.e. FDA, EMA, CFDA\) proving copyright title provenance to R&D data.<sup>[27](#f27)</sup> Without such a license, a party may not utilize such data for submission to a regulatory body and must start the research process anew \(raising capital and performing an independent clinical trial, etc.\). Licenses have proven to be worth billions of dollars to economic and medical systems worldwide.<sup>[28](#f28)</sup> 

In the case of IKU, data will be hashed and stored on Inter Planetary File System IPFS. The hash is proof of data existence - therefore proving genesis of the data and copyright title provenance.  The data itself is openly available for anyone to see, but is protected from a third party's commercial explotiation through the copyright.<sup>[29](#f29)</sup> This hash is tokenized and traded on the blockchain, enabling cryptographic, timestamped validation of each transaction, providing the current state of IKU. A license will be granted upon acquisition of a certain threshold of tokens, a proof-of-license mechanism, of which the licensee can put the redeveloped drug through already established manufacturing and distribution channels, which are abundantly available for contract. This allows for clinical trial data licenses to be liquid and accessible while also providing for efficient market access. Parties, and in IKU's case the `RST[x]DC`, may capitalize on data/market exclusivity periods for competitive advantage in many jurisdictions, including but not limited to:

* Europe: up to ~10 years
* Asia: up to ~10 years
* U.S.: up to ~7 years<sup>[30](#f30)</sup>

A `RST[x]DC` may pursue a patent together as a DC, with sole ownership of rights by the DC. While `RST[x]` holders may pursue patent protection for inventions developed based on IN funded research, patents may not be used in the IN. 

Figure E further illustrates the benefits of the IKU data approach as opposed to the current, patent system:

**Figure E: IKU Data Approach**

![IKU Data Approach](https://github.com/ikunetwork/WhitePaper/raw/master/IKU-Data-Approach.png)

**Liquidity**: Bio R&D markets remain non-liquid, silo'd and permissioned in which on average $2.6 billion is required per drug, resulting in exorbitant pricing per unit.<sup>[31](#f31)</sup> Sadly, pharma companies carry significant non-R&D “baggage," where non-R&D spend has outpaced R&D for the last 20 years.<sup>[32](#f32)</sup> IKU's output yields preclinical and clinical research data sets, open to any interested party globally, building the the basis for two related asset classes - \(i\) the IKU Network Token `IKU` and \(ii), Research Specific Token `RST[x]`. The `RST[x]` enables the licensing of a specific data set as described below. Both asset classes collapse money value and information into one, facilitating the liquid exchange of R&D. Given that IKU's focus, R&D expenditures are expected to be minor by comparison, no such demands on amortizing exorbitant R&D costs on patients have to be met.

### IKU Scales

The current industry model is costly as we explained above. IKU on the other hand can scale in capital, time and approval probability. Figure F compares this for better context:

**Figure F: IKU Scales at Low Cost**

![IKU Scales at Low Cost](https://github.com/ikunetwork/WhitePaper/raw/master/IKU-Scales-at-Low-Cost.png)

At any given time, the scientific probability of a NME reaching approval is 5%, at a cost of $2.6 billion over 15 years.

* **NME:** $2.6 billion/15 years =  $173 million per year spend.  

The scientific probability of a rediscovered drug achieving approval is 30%, at a cost of 10 - 100 million \(avg. $55 million\) over 5 years,

China: $15 million 5 years.

* **IKU US:** ~55 million/5 years = ~ $11 million per year spend. 

* **IKU China:** 15 million/5 yaers = 3 million per year spend

By design, the IKU model is much less expensive in capital and time, with significantly greater probability of scientific success. We anticipate these global clinica trial efficiencies to surpasspass the longevity escape velocity — the point at which, for every year you're alive, science is able to extend your life for more than a year.

### The IKU Network

The mission is to establish the IN as a public utility for bio R&D, driving efficiency through global capital formation and decentralized liquidity pools. The community will own the IN in a trustless fashion, connecting individuals, science, verified researchers/research organizations – collectively participants - and capital. The IN will operate with a core objective to establish and facilitate the IN, create IKU, maintain the IN reserve and evangelize R&D efficiencies. In addition, the IN will maintain a grants program in which bounties will be issued for (i) eliminating issues in the IN code and (ii) accomplishing specific innovations i.e. developing effective cancer treatments, aging treatments, etc. Circulating IKU will vote on the priority of bounties, capital allocation, and have the right to perform work for IN.

## The Network Economy

The IN combines the wisdom of crowds with the wisdom of science thru participant capital information exchange. The following tools will give life to the IN: `researchTarget`, `devTools`, Request for Proposals `RFP`, and the `permissionlessLicense`.

### Research Target

Any person with internet access may submit a `researchTarget` which may be a concrete, verifiable objective or broad target. For example:

* Verifiable Object: Rediscovery of Metformin in a slow release formulation to treat lung cancer.
* Broad Target: Advancing research of aging and age-related diseases.

Among other aspects, the `researchTarget` may specify medical conditions, technology type i.e. therapy, device, mechanism of action, or any other known R&D metric. The `researchTarget` will be visible and sortable to the public, allowing for thorough analysis and determination of demand. The public will be able to upvote a `researchTarget` - spam protected thru captcha.

### Dev Tools

Participants will access the IN through a `devTools` integrated interface. The `devTools` consist of the following:

* `RFP` submission forms
* Wallet registration
* Topic forums
* Friends
* Direct messaging
* Reputation
* Upvote
* Share
* Comment
* Peer Review
* Upgrade to clinical trial subject 

Friends, messaging, and upvote access will require an IN profile, but will not require holding IKU in the Network Digital Wallet NDW - allowing anyone to use the IN. This type of access is classified as `devTools A`. RFP submissions, comments, peer review, reputation scoring and upgrading to clinical trial subject will require an IN profile AND holding at least 1 IKU in the NDW - `devTools B`.

### IKU Network Participants

Below are the players in the IKU Network. They are not mutually exclusive:

* `IKU`** Holder**: IKU token holder; can be an individual, institution, private company, etc. \(described further below\)
* `RST[x]`** Holder**: Research Specific Token holder; can be an individual, institution, private company, etc. \(described further below\)  
* **VR**: Verified Researcher i.e. MD, PhD, etc. whose expertise is credentialed through the IN. The VR can propose and respond to  a `researchTarget`, vote on their viability and review proposals. He/she is fundamental to the IKU peer review process.  
* **ADV** Anonymous data viewer - the public, who can freely contribute a `researchTarget`, views projects on the IN and has the option to create an IN profile to access `devTools A`. The IN will make information ethically and publicly available as current clinical trial results are typically not open to the public - even though they are required to be.  In addition, all `RST[x]DC` initiatives will post a gantt chart for how advanced their research initiative is as well as the research data they have generated on a quarterly basis.

Participants will be subject to a `reputationScore`:

* `reputationScore` is part of `devTools`. All participants will be subject to a profile linked `reputationScore` which accounts for utilization of IN resources and behavior, allowing for meritocratic decision-making based in scientific liquidity. All IN participants start with the same `reputationScore`, but will be separated by VR and non-VR. `reputationScore` may increase to `power`, `super_power` and `grand_maester`.  This enables the best ideas to flow freely, producing efficient and rapid evolution based on merits.[32](./#f32) Participants will be obligated to provide `reputationScore` to other participants they have digitally engaged.  The `reputationScore` will be publicly available.

### Request for Proposals

The IN will serve to produce requests for peer reviewed proposals `RFP` in response to `researchTargets`. A VR will be able to submit proposals at any time as paid for by the IN reserve, whereas non-VR will be required to post a bond to submit a proposal.

A proposal is required to consist of 

\(i\) a principal investigator PI and/or Project Lead that leads the R&D team along with the `RST[x]` Holders that the PI and his/her team will have to answer to \(see below `RST[x]` value\), 
\(ii\) how much capital is being raised and for what percentage of `RST[x]`, with proposers encouraged to not issue 100% of `RST[x]` to account for future capital requirements and 
\(iii\) the scientific justification of proposed R&D. 

A standard `RST[x]` proposal template will be provided by the IN for `RFP`. Further `RFP` value may be determined by the IKU user submitting the proposal, allowing for a flat environment in which value proposition may be programmed into an `RST[x]`.<open zeppelin citation upgrade> This leaves significant room for `RST[x]` value creativity.

Participants will use the `devTools` to peer review. The IN peer review process to score an `RFP` can be defined as a function:

```text
`s` = `f(a,b,c)` = `RFP` score - PUBLIC
`a` =  pariticipant`reputationScore` (a VR's `a` is weighted 2x)
`b`: Sum of `RFP` upvotes  
`c`: IKU balance weight 
`r`: A specified threshold value
```

   ### The\_Library\_Exchange <citation Zero to One/Stanford Course>
   
The RFP model is just the beginning.   Network-based computational bio analysis has become a strategy for determining R&D pipelines due to the ever-increasing pace of bio and chemical information available.<sup>[33](#f33)</sup> Various different computational approaches, including deep learning, matrix factorization methods and various algorithms have proved beneficial in navigating the wealth of information to uncover potential leads.<sup>[34](#f34)</sup> . This data is often fragmented and to date, has lacked economic incentive for the proper capital formation to enable clinical trials. IKU will serve to provide an open source machine learned R&D/clinical trial proposer, Jonas, based in computational bio analysis of the bio R&D available to date (pubmed, bioRXiv, PLOS ONE, etc.) for use by anyone with internet access.  Jonas will help extract insight to allow for researchers and the general population to compare patterns and essentially peer review the most efficient proposals from Jonas - a human-computer hybrid approach. <peter thiel> . The IKU data mining architecture is designed “stand on the shoulders” of the computational analysis that has been completed to date to provide highly predictive, robust R&D pipelines. Participants are incentivized to peer review these proposals to earn fees \(more on fees below\) from the IN in the form of BTC, ETH, IKU and `RST` - encouraging and incentivizing the most promising R&D initiatives to be capitalized.
   
 `s` is expected to be optimized overtime with IN demand. As this process generates data and continues to grow, Jonas's recommendations should get better to help us determine the most efficient forms of bio R&D.

Upon `s` > `r`, 2 smart contracts will be deployed to the Ethereum Blockchain: \(i\) `RST[x]` - An ERC20 token representing the specific research and \(ii\) `RSTCrowdsale[x]` \(based on [https://github.com/OpenZeppelin/zeppelin-solidity](https://github.com/OpenZeppelin/zeppelin-solidity)\), which responsible for minting `RST[x]` and in exchange send tokens to contributors

Upon `RSTCrowdsale[x]` achieving its softcap - minimum BTC/ETH required to achieve milestone:

1. \[y%\] of the funds will be released to the R&D team,
2. All `RST[x]` Holders will be able to participate in their respective `RST[x]` sub-network, and
3. IKU Token Holders earn `RST[x]` as described below under ** `RST[x]` Bandwidth and the Network Digital Wallet**.

Funds released to the R&D team in BTC and ETH can be converted to fiat, through a trusted third party crypto to fiat provider. In addition, prior to initiating a clinical trial, an `RST[x]DC` will be responsible for ensuring ethical compliance through an institutional review board.

**Smart contract code for **`RSTCrowdsale`

```text
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

### IKU Network Utility

The following sequence of events illustrate the IKU Network utility to facilitate global capital formation and trade for R&D:

**Figure G : IKU Network Utility**

![IKU Network Utility](https://github.com/ikunetwork/WhitePaper/raw/master/IKU-Network-Utility.png)

redo this so that RT, Library Exchange and RFP are in a triangle that then feeds into Peer Review, etc.

The IN will serve to be a library-hub for the generation, tracking and exchange of such data allowing for an incentivized, open workflow for the most promising research and clinical trials.  Through this utility, IKU serves to achieve open markets for digital rights to research - created and traded in a fungible, liquid fashion.


## Tokenization

The IN creates two classes of native tokens:

* `IKU`: Serves as software license to access the Network, bandwidth for the Network to run and to mediate participation in the Network.  The supply of IKU is finite.
* `RST`: The Research Specific Token `RST` is representative of a fungible copyright license to the R&D `[x]` it was specifically created to capitalize - digital rights to R&D. In addition, `RST[x]` serves as a license to access the `RST[x]` sub-network, bandwidth for the `RST[x]` sub-network to run and to mediate participation in the sub-network supply. `RST[x]` bundles, `RST[i]` may be developed as per a future bounty, allowing for scientific and economic risk diversification where `i` represents the number of `RST[x]` bundled.

The two token incentive model is designed to provide scientists and the general public with agency in determining the future of biotech, regardless of patent policy and large corporations - a radically different model that enables global liquidity for research assets. This will serve to provide equitable foundations in science and liquidity.  The `RST[x]` holder carries pro-rata rights in the R&D data if they hold the respective `RST[x]`.  
`RST[x]` are 

### `IKU` Value

Wallet verification of a minimum of balance of 1 IKU enables access to the `devTools B` and fees as explained under **Fees and the Network Digital Wallet**. Value in the IKU token can be ascribed to access the following:

* `devTools B`
* 2nd priority to upgrade to clinical trial subject
* `RST[x]`

Establishing a profile on the IN provides access to the Network Digital Wallet NDW.  The NDW will serve to hold BTC, ETH, IKU and all `RST[x]`, and is expected to also eventually hold digitalized fiat, providing for efficient capital formation and value exchange. In addition, the NDW enables IKU holders to earn `RST[x]` as \[z%\] of all of the `RSTCrowdsale`, pro-rata, will flow to IKU holders in exchange for performing a certain threshold of work on the Network, e.g. participating in the peer review process, etc. Such model gives an IKU holder the opportunity to have rights to all the research on Network. 

### `RST[x]` Value

An `RST[x]` carries pro-rata digital rights to its specific research initiative \(clinical trials, etc.\) and such rights are cryptographically maintained with the ability to \(i\) access the `RST[x]DC` and \(ii\) be transacted in an `permissionlessLicense` smart contract. Value in the `RST[x]` token can be ascribed to the following:

* `permissionlessLicense` threshold
* 1st priority to upgrade to clinical trial subject
* Early access to realized biotechnology upon regulatory approval \[at a discounted \(or free\) rate\]
* Access to the `RST[x]` sub-network to work on R&D development

R&D data will be made available to `RST[x]` holders and updated by the `RST[x]` sub-network through the IN infrastructure on an ongoing basis. `RST[x]` R&D data will be de-identified and stored on IPFS. Access to the data and specific `RST[x]` sub-network will be made available with possession of a minimum, predetermined `RST[x]` threshold and private key, unless otherwise made public thru IKU. A transaction involving `RST[x]` is the cryptographic validation of rights transfer to `RST[x]` hashed data, timestamped by the blockchain. This is transparently irrefutable evidence of both proof of the data's existence and rights provenance on IPFS at a given point in time, protecting against reasons for litigation.

`RST[x]`** Smart Contract**

```text
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

* \(i\) Determine whether R&D team should have access to remainder of funds for continuing research \(upon reaching or not reaching R&D a milestone\), based on reputation.
* \(ii\) Upgrade to clinical trial subject.
* \(iii\) Provide reputation scores to fellow `RST[x]` holders and the R&D team.

The `RST[x]DC` is incentivized to provide timely and relevant information to both its own DC and the public as the `RST[x]` and `IKU` will be at the mercy of market sentiment. `IKU` and `RST[x]` tokens are expected to trade in real time, globally in the cryptourrency market place. If an `RST[x]DC` does not operate in efficient scientific fashion, it is expected to be reflected accordingly.

### Token and License

`IKU` and `RST[x]` token holders will retain custody , with no asset exchange third-party intervention, distributing the liquidity pool on a global basis to encourage and reward successful R&D. `IKU` serves as bandwidth to run and mediate participation in the Network.  When `IKU` [is staked] in the Network digital wallet, it signals to the scientific community that the Network is active and potentially ripe for research.

 The IKU architecture facilitates a market around R&D data to use copyright licenses to such data for clinical trial packages, e.g. Rapamycin Animal/Phase I clinical trial safety study \(study\) for Rapamycin for longevity, modified release \(clinical trial drug rediscovery package\). 

[Based on the IKU R&D rediscovery strategy, There are challenges in sourcing and obtaining all relevant existing historical data for a bio product data package \(dosing, effect, etc.\) as is required for clinical trial initiation. The lack of access to data means that there is the potential need to replicate expensive tests and even clinical studies, adding cost and time.<sup>[34](#f34a)</sup>]



[License Example]

In the Rapamycin example, the Animal/Phase I data can be hashed and its digital rights tokenized as `RAP-I`. The data can be licensed by acquiring a certain threshold of `RAP-I` token, and utilized in a data package for a Phase II clinical trial \(efficacy\), eliminating significant time and cost spent replicating studies. The most scientifically valuable data would be expected to command greater market demand, incentivizing the uncovering and advancement of discovery, making R&D as a whole more efficient - more transparent, frictionless access to rich pools of data. Mining data pool trends of various variables \(e.g. mechanism of action, general aging, at risk populations, etc.\) will serve to efficiently align proposals to be capitalized, through both in-silico and ‘bruteForce’ peer review. 


Licensees will either be in the form of a third party that acquires a certain threshold of tokens, engaging the `permissionlessLicense` protocol as described below, or the `RST[x]DC`. An `RST[x]DC` represents an ad-hoc, virtual collective capitalized through smart contracts, power a R&D specific sub-network (e.g. Longevity rejuvenation through telomeres). An `RST[x]DC` will consist of a project lead, lead researcher and its token holder network to progress research/clinical trials by interacting through their R&D specific sub-network.

### Burning

IKU aligns its burning strategy with the creation of `RST[x]`, where a % of IKU tokens contributed to a specific `RST[x]` are burned from the IKU Reserve. The same % of the specific `RST[x]` pool are also offered to IKU Token holders as a fee. Burning may occur as follows:

* A `researchTarget` is submitted for Levodopa Trials - Cure Parkinson’s. The Alice Foundation submits an `RFP` for the `researchTarget` of which the IN accepts and an associated `RSTCrowdsale` commences. The `RSTCrowdsale` is successful and the associated `RST[x]DC` Levodopa Trials - Cure Parkinson’s is created. \[y%\] of the total contributed IKU tokens are burned from the IKU Network Reserve pool and `RST[x]` are distributed to `IKU` Token holders pro-rata based on IKU holdings.
* Let’s say Bob contributed 500 IKU tokens to `RST[x]DC` Levodopa Trials - Cure Parkinson’s. The Alice Foundation receives all 500 IKU tokens of which they can exchange for fiat. The Alice Foundation’s IKU Tokens received from BOB are not burned, but rather [y%] of the total contributed IKU tokens are burned from the IKU Reserve pool. The same [y%] of the `RST[x]DC` pool is transferred back to all funders who held IKU tokens at the time of funding, pro-rata based on IKU holdings. Thus Bob receives a piece of that [y%] in addition to 500 IKU for `RST[X]` ratio.

### The `RST[x]` `permissionlessLicense`

The `permissionlessLicense` facilitates digital scarcity as an additional efficienct economic incentive vehicle. The `permissionlessLicense` protocol allows for global trade of any data or IP, that has scarcity properties, as cryptographic assets. Acquisition of a certain threshold of cryptographic assets - a token supply number which is predetermined at the time of the `RFP` creation - triggers an automatic license to the data or IP generated by the `RST[x]DC`. This allows for a license to be highly available, fungible and auditable as it is a datapoint on a blockchain. In IKU's case, a `permissionlessLicense` would be granted upon a certain Ethereum address holding z% of outstanding `RST[x]`. The party who holds the private key to such Ethereum address now has a license to utilize and exploit the clinical trial data, e.g. completed Phase II clinical trial data, to potentially submit to the U.S. FDA for approval. The more scientifically advanced the R&D initiative, the greater the expected demand as the data and its corresponding license and therefore `RST[x]` becomes more scientifically valuable i.e. completing Phase II clinical trials - therefore more value will be required by one who desires a `permissionlessLicense` to achieve the `RST[x]` threshold.

The IN will provide a standard `permissionlessLicense` with drop down variables such as territory, `RST[x]` license threshold, required efforts for good faith development \(e.g. Phase II clincal trial commence in 6 months\), amongst others. This will enable proposers to click through, filling in variables at their discretion, likely dramatically reducing the need for negotiation, lawyers and other middlemen, enabling an open streamlined licensing process. In addition, parties will have the opportunity to provide their own customized license, subject to market demand.

Specifically, the `permissionlessLicense` enables exit opportunities for `RST[x]` Holders to license `RST[x]`-backed data which can be obtained by any interested party \(e.g. health insurance distributor, venture, foundation, etc.\). If the `permissionlessLicense` threshold is not achieved after a succcessful Phase II clinical trial, the `RST[x]DC` may become a collective ad hoc venture team around its cryptoasset, e.g. an approved ALS treatment with 7 years of market exclusivity in the U.S. for market distribution. This creates a self perpetuating ecosystem of innovation and multiple opportunities for IKU and `RST[x]` holders, as well as other parties interested in licensing.

Upon the public release of the IN, IKU token holders will be able to decide what happens to `RST[x]` that are not part of the `permissionlicense`. This may include creating a software bounty thats allows for royalties to flow to the remaining outstanding `RST[x]` in exchange for work or in the alternative, as a securitized asset. Because `RST[x]` is traded on the Ethereum blockchain, provenance of `RST[x]` data rights are known, facilitating potential trustless royalty distribution to `RST[x]` holders from the licensee. Note that this will be up to IKU token holders to decide.

### Decentralized Key Management System

As the `RST[x]DC` is incentivized to upload relevant and appropriate research data to IPFS, the associated private key to trigger the `permissionlessLicense` must be encrypted and only available to `RST[x]` Holders at a specified balance threshold. In no way will the IKU Trust/Foundation own or control any private key to `RST[x]` associated data in IPFS of which the `permissionlessLicense` unlocks. Instead, IKU will employ a proxy re-encryption mechanism where the `RST[x]DC` will delegate re-encryption of the private key to a proxy upon the respective `RST[x]` Holder request of the `RST[x]` in the `devtools`.<sup>[35](#f35)</sup> As per the NuCypher White Paper:

* When the data is stored in a cloud or decentralized storage, it is encrypted with the data owner’s \(_sender_\) key _pks_ \(**Figure H\)**. The data itself is encrypted with a random symmetric key _dek_, with one key per file. The _dek_, encrypted with _pks_ is attached to the encrypted data. This combination \(_edek, c_\) can be stored anywhere - in IPFS, Swarm, S3, or any kind of decentralized or centralized storage.

* When storing the data, the user to whom we delegate access is not necessarily known in advance. First, the receiver should show the sender his public key \(**Figure I**\). It often makes sense for the public key to correspond to an address in the Ethereum network \(to prove a payment has been made from that address for a digital content subscription, for example\). The sender generates a re-encryption key _res→r_ \(including an encrypted random ephemeral key when needed\) and sends it to a random re-encryption node, selected according to proof-of-stake out of the active nodes in a decentralized network. The nodes which have shared data of user _sender_ with a user _receiver_ register this information in the network.

* When the receiver wants to decrypt data shared with him, he first downloads that data from storage or an encrypted stream \(**Figure J**\). He separates out _edek_ from the message and sends _edek_ to the network of re-encryption nodes and finds active re-encryption nodes which can share the data of the sender with the receiver \(those which have reencryption key\(s\) _res→r_\). The receiver asks the node\(s\) that has the re-encryption key to transform _edek_ to _edek1_ and uses his own secret key _skr_ to decrypt it and obtain DEK. Now, he can use DEK to decrypt the bulk of the data.

**Figure H,I,J: Decentralized Key Management System**

![Proxy Re-encyrption](https://github.com/ikunetwork/WhitePaper/raw/master/Proxy-Re-encryption.png)

### The IKU Reserve

The IN will maintain its assets as necessary for incentivizing VR peer review, liquidity and community bounties in both software and bio R&D. The funds will be stored in an Ethereum MultiSigWallet: \([https://github.com/Gnosis/MultiSigWallet](https://github.com/Gnosis/MultiSigWallet)\) which is built on top of ConsenSys Ethereum MultiSigWallet \([https://github.com/ConsenSys/MultiSigWallet](https://github.com/ConsenSys/MultiSigWallet)\).\] All foundation transactions and bounties will be public, enabling anyone to see its balance sheet in real time.

### Future Development

Additional IN features are expected to be developed and/or integrated based on IKU decision making to further enable bio R&D efficiency, which may include but are not limited to advanced analytic and platform navigation tools, as well as links to language agnostic relevant public and private content through APIs \(e.g., PubMed, IP Databases\). This will improve workflow efficiency and thus lead to enhanced platform performance.

As to specific anticipated service components, dependent on IKU token holder decision making, a software bounty may be deployed for `RST[i]` bundling, `i` representing the number of `RST[x]` bundled, as stated below:

Bundling may serve to enable various bio R&D assets to mitigate economic and scientific risk exposure as well as provide horizontal, or vertical licensed research collaboration. As opposed to a traditional centralized corporation, the `RST[i]` bundle lowers the cost of both trust and risk.

How to bundle:

* Declare `RST[x]` eligible to bundle with `i-1` in the `RFP`, during token sale, or later point in time
* Declare `RST[x]` seeking bundle

All IN R&D initiatives would have the option to actively bundle `RST[x]` into `RST[i]`, or allow for `RST[i]` to choose to bundle with an `RST[x]`, with atomic swap capability, allowing for high performant assets to be transacted globally across, or in the same R&D verticals. Atomic exchange serves as a mechanism to reduce risk and stabilize IKU/`RST[i]` in a frictionless fashion, as atomic assets do not need to be traded on a centralized exchange, but can be swapped for one another through direct p2p algorithmic execution.

This would be especially important for clinical trials in the same research vertical i.e. condition, disease, mechanism of action, molecule, etc. as it mitigates scientific and economic risk. Capital resources would be allocated purely towards R&D with the ability to algorithmically bond with each other thru smart contract.

## Conclusion

IKU will serve to enable unprecedented global creation and deployment of resources for safe and impactful clinical trial research. Decentralizing resource allocation and asset transactions allows for increased transparency of market activity which is expected to lead to significant bio innovation in the near future. The foregoing working draft has sketched a paradigmatically novel vision of the structural and organizational means by which this can dramatically increase the reward for efficient R&D, reduce the risk of failure, all the while enabling global, decentralized liquidity. We expect the IN to be a critical infrastructure piece to spark and launch the entire system of digital R&D rights. This is the fundamental intention and the essence of the IN.

## Footnotes

<b id="f1">1</b> Bernard Munos, Faster Cures, [https://www.nature.com/news/can-you-teach-old-drugs-new-tricks-1.20091](https://www.nature.com/news/can-you-teach-old-drugs-new-tricks-1.20091) \(2016\).

<b id="f2">2</b> James Bessen, The Evidence is in: Patent trolls do hurt innovation, Harvard Business Review \(2014\). Gene Quinn, et. al., Are More than 90% of Patents Challenged at the PTAB Defective?, IPWatchdog \(2017\). J. Hudson et. al., Into the valley of death: from research to innovation, [https://www.ncbi.nlm.nih.gov/pubmed/23402848](https://www.ncbi.nlm.nih.gov/pubmed/23402848) \(2013\).Tufts Center for the Study of Drug Development, How the Tufts Center for the Study of Drug Development Pegged the Cost of a New Drug at $2.6 Billion \(2014\).

<b id="f3">3</b> James Bessen, The Evidence is in: Patent trolls do hurt innovation, Harvard Business Review \(2014\). Gene Quinn, et. al., Are More than 90% of Patents Challenged at the PTAB Defective?, IPWatchdog \(2017\). Robert Sachs, Fenwick & West LLP, Patent Invalidity Rates: The Summertime Blues Continue, Law 360 \(2015\). Such inefficiencies have caused significant IP law has attempted to enforce, but enforceability is difficult, time consuming and expensive as:

* patent litigation costs ~ $30 billion per year
* ~80% of the litigation comes from patent trolls 
* 50%+ of U.S. patents are being invalidated in post-grant proceedings.

All of which lead to significant issues in transaction finality, exacerbating an already illiquid market. Id.

<b id="f4">4</b> FiercePharma, The world's most pricey drugs, from a $1.2M gene therapy to a $450K lymphoma med, [https://www.fiercepharma.com/marketing/world-s-most-pricey-drugs-from-a-1-2m-gene-therapy-to-a-450k-lymphoma-med](https://www.fiercepharma.com/marketing/world-s-most-pricey-drugs-from-a-1-2m-gene-therapy-to-a-450k-lymphoma-med) \(2017\).

<b id="f5">5</b>See FN 2.

<b id="f6">6</b> Tufts Center for the Study of Drug Development, How the Tufts Center for the Study of Drug Development Pegged the Cost of a New Drug at $2.6 Billion \(2014\).

<b id="f7">7</b> K. Stott, Pharma’s broken business model: An industry on the brink of terminal decline, [https://endpts.com/pharmas-broken-business-model-an-industry-on-the-brink-of-terminal-decline/](https://endpts.com/pharmas-broken-business-model-an-industry-on-the-brink-of-terminal-decline/) \(2017\).

<b id="f8">8</b> Id.

<b id="f9">9</b> Congressional Research Service, NIH Funding: FY1994-FY2016, [https://fas.org/sgp/crs/misc/R43341.pdf](https://fas.org/sgp/crs/misc/R43341.pdf) .

<b id="f10">10</b> Roger Stein, MIT Research Associate, A Bold New Way to Fund Drug Research, TED Talk \(2013\).

<b id="f11">11</b> 21st Century Cures Whitepaper, A Path to Discovery, Development, [https://energycommerce.house.gov/cures/](https://energycommerce.house.gov/cures/) \(2016\).

<b id="f12">12</b> Bruce Bloom, Cures Within Reach, [http://www.the-scientist.com/?articles.view/articleNo/47744/title/Repurposing-Existing-Drugs-for-New-Indications/](http://www.the-scientist.com/?articles.view/articleNo/47744/title/Repurposing-Existing-Drugs-for-New-Indications/) \(2017\).

<b id="f13">13</b> Id.

<b id="f14">14</b> Id.

<b id="f15">15</b> Nick Szabo, Formalizing and Securing Relationships on Public Networks, [http://firstmonday.org/ojs/index.php/fm/article/view/548/469-publisher=First\#introduction](http://firstmonday.org/ojs/index.php/fm/article/view/548/469-publisher=First#introduction) \(1997\).

<b id="f16">16</b> Vitalik Buterin, A NEXT GENERATION SMART CONTRACT & DECENTRALIZED APPLICATION PLATFORM, ethereum/Wiki.

<b id="f17">17</b> H. Diedrich, IBM Liason to Ethereum, Ethereum: Blockchains, Digital Assets, Smart Contracts, Decentralized Autonomous Organizations \(2016\).

<b id="f18">18</b> The Economist, Patents that kill, [https://www.economist.com/blogs/freeexchange/2014/08/innovation](https://www.economist.com/blogs/freeexchange/2014/08/innovation) \(2014\).

<b id="f19">19</b> Lisa Diependaele, et. al., Raising the Barriers to Access to Medicines in the Developing World – The Relentless Push for Data Exclusivity, [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5347964/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5347964/) \(2017\). CFDA, Provisions for Drug Registration, [http://eng.sfda.gov.cn/WS03/CL0768/61645.html](http://eng.sfda.gov.cn/WS03/CL0768/61645.html). International Federation of Pharmaceutical and Manufacturers Association, [https://www.ifpma.org/wp-content/uploads/2016/01/IFPMA\_2011\_Data\_Exclusivity\_\_En\_Web.pdf](https://www.ifpma.org/wp-content/uploads/2016/01/IFPMA_2011_Data_Exclusivity__En_Web.pdf).

<b id="f20">20</b> FDA, What are generic drugs?, [https://www.fda.gov/Drugs/ResourcesForYou/Consumers/QuestionsAnswers/ucm100100.htm](https://www.fda.gov/Drugs/ResourcesForYou/Consumers/QuestionsAnswers/ucm100100.htm).

<b id="f21">21</b> Id.

<b id="f22">22</b> Id.

*<b id="f23">23</b> See FN 1.

<b id="f24">24</b> See FN 12.

<b id="f25">25</b> Id.

<b id="f26">26</b> FDA Approvals 2016 - 2017, [https://www.fda.gov/Drugs/DevelopmentApprovalProcess/DrugInnovation/ucm483775.htm](https://www.fda.gov/Drugs/DevelopmentApprovalProcess/DrugInnovation/ucm483775.htm) , [https://www.fda.gov/Drugs/DevelopmentApprovalProcess/DrugInnovation/ucm537040.htm](https://www.fda.gov/Drugs/DevelopmentApprovalProcess/DrugInnovation/ucm537040.htm). JJ Hernandez, et. al., Giving Drugs a Second Chance: Overcoming Regulatory and Financial Hurdles in Repurposing Approved Drugs As Cancer Therapeutics, [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5694537/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5694537/) \(2017\). Tufts Center for the Study of Drug Development, How the Tufts Center for the Study of Drug Development Pegged the Cost of a New Drug at $2.6 Billion \(2014\).

<b id="f27">27</b> See FN 19.

<b id="f28">28</b> Id.

<b id="f29">29</b> J. Benet, IPFS - Content Addressed, Versioned, P2P File System \(DRAFT 3\). M. Egorov, M. Wilkinson, D. Nunez, NuCypher KMS: Decentralized key management system.

<b id="f30">30</b> See FN 19.

<b id="f31">31</b> C. Burniske, Cryptoassets \(2017\).

<b id="f32">32</b> R. Dalio, Principles \(2017\).

<b id="f33">33</b> E. March-Villa, et. al., On the Integration of In Silico Drug Design Methods for Drug Repurposing, [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5440551/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5440551/) \(2017\).

<b id="f34">34</b> Id. R. Hodos, In silico methods for drug repurposing and pharmacology, [https://pdfs.semanticscholar.org/39a3/04dabca77d203c5639545c4f8480d9018797.pdf](https://pdfs.semanticscholar.org/39a3/04dabca77d203c5639545c4f8480d9018797.pdf) \(2016\).

<b id="f34a">34a</b> EU Commission, Public Health, 8th Commission Expert Group on Safe and Timely Access to Medicines for Patients \("STAMP"\) Meeting \(2018\).

<b id="f35">35</b> SF Cryptocurrency Devs, A Deep Dive into Proxy-Reencryption w/ NuCypher \(2017\).
