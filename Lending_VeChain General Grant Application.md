**VeChain General Grant Application**

**1. Project Overview** 

- Project: VeBank

- Team Name: ESOL Labs

- Payment Address:

-   VeChain: 0xa2b13B6Be3fb3F9f98A43371687255D5943754Eb

-   Ethereum: 0xF4B57a2749Fa8FBFA9644a186e0730c2C64DcB90

-   Binance Smart Chain (preferred): 0xF4B57a2749Fa8FBFA9644a186e0730c2C64DcB90

**1.1 Overview**

**VeBank** is a one-stop decentralized trading platform on the
VeThorChain (VeChain) blockchain. VeBank provides the major core finance
functions, but not limited to:

-   Trade: VeBank facilitates fast and cheap exchange of tokens with our automated market-maker (AMM)

-   Lend/Borrow: the non-custodial liquidity protocol on our platform
    allows users to participate instantly upon connecting to a wallet.
    As depositors, users can earn passive income by providing
    liquidity to the market. As borrowers, users can start borrowing
    in an over-collateralized (perpetually) or under-collateralized
    (one-block liquidity) fashion.

-   Farm: farming protocol allows users to deposit LP tokens and earn bonus rewards (not presented in this grant application)

-   Stake: users can stake $VB tokens to VeBank and earn platform rewards

VeBank protocol is implemented by a set of smart contracts on top of the
VeChain and is completely decentralized. No middlemen is involved so
users and applications can interact directly with the smart contracts,
the blockchain data, or via their favorite web3 providers.

**1.2 Project Details**

a.  How it works.

*VeBank is an automated liquidity protocol powered by a constant product
formula and a system of non-upgradeable smart contracts on the VeChain
blockchain. It obviates the need for trusted intermediaries and
prioritizes decentralization, censorship resistance, and security.
VeBank is an open-source software licensed under the General Public
License.*

Each VeBank smart contract or pair manages a liquidity pool which is
made up of reserves of two VIP-180 tokens.

To enable trading on the decentralized exchange (DEX), there must be
liquidity. The liquidity provided to the exchange comes from Liquidity
Providers ("LP") who stake/deposit their tokens in the "Pools".
Anyone can become a LP by depositing an equivalent value of each
underlying token asset in return for the pool tokens. The tokens are
tracked pro-rata to the LP shares in the total reserves and can be
redeemed for the underlying assets at any time.


<img alt="Vebank" src="https://images.rinz.io/rinz/nft/2022/07/05/1656989163.786813_2af6184d-79c4-4106-9010-5c594d7c0ac6.png" width="700" height="350">


Pairs act as automated market makers, standing ready to accept one token
for the other as long as the "constant product" formula is preserved.
This formula, most simply expressed as x * y = k, states that trades
must not change the product (k) of a pair's reserve balances (x and y).
Because k remains unchanged from the reference frame of a trade, it is
often referred to as the invariant. This formula has the desirable
property that larger trades (relative to reserves) execute at
exponentially worse rates than smaller ones.


<img alt="Vebank" src="https://images.rinz.io/rinz/nft/2022/07/05/1656988845.353522_7cd96ee4-744b-46d0-97e7-11f1a579267f.png" width="700" height="350">


Because the relative price of the two-pair assets can only be changed
through trading, divergences between the VeBank price and external
prices create arbitrage opportunities. This mechanism ensures that
VeBank prices always trend toward the market-clearing price.


<img alt="Vebank" src="https://images.rinz.io/rinz/nft/2022/07/05/1656989834.584935_f0fbdd75-6403-4a71-ac48-cae4e2458bd9.png" width="700" height="350">


b.  How users interact with the protocol

The VeBank permissionless ecosystem is primarily composed of four types
of users: liquidity providers, borrowers, traders, and developers.

-   Liquidity providers (LP) are incentivized to contribute VIP-180
    tokens to common liquidity pools. The interest rates correspond to
    the earn rates, with the algorithm guaranteeing withdrawals at any
    time. In exchange, the LPs earn trading fees (LP tokens), which
    can also be staked to earn $VB tokens in the "farm". When a
    user makes a token swap (trade) on the exchange, he or she will
    have to pay a 0.3% trading fee, which is broken down as follows:


-   0.25% - Paid to liquidity pools in the form of a trading fee for liquidity providers (LP)

-   0.05% - Sent to $VB token farm


<img alt="Vebank" src="https://images.rinz.io/rinz/nft/2022/07/05/1656989124.847522_d6b8ca68-18bf-46a6-ab17-998841486275.png" width="700" height="350">


-   Borrowers are subject to risk evaluation of the asset loan,
    calculated Loan-To-Value, amount of funds available in the pool at
    time of borrow (the less funds incur the higher interest rates),
    and collateral policies. Liquidation modules would automatically
    trigger when predetermined liquidation thresholds are met. The
    table below shows a summary of the latest values:


<img alt="Vebank" src="https://images.rinz.io/rinz/nft/2022/07/05/1656989070.863715_460c75f6-de8b-4d1b-86bb-8b321dca2698.png" width="700" height="350">


-   The protocol also incentivizes users to acquire liquidated assets at discount and with token incentives.

-   Traders can swap one token for one another at a fixed 0.30% fee which goes to liquidity providers at 0.25% and 0.05% to token farms.

-   Developers can interact with the open-source, accessible nature of VeBank. There are also many VeBank-specific tools built by the community.

Overall, interactions between these classes create a positive feedback
loop, fueling digital economies by defining a common language through
which tokens can be pooled, traded and used. VeBank's core lending and
borrowing will initially support VET, VeTHO, VeUSD and $VB and expand
to other big-cap assets in the future.


<img alt="Vebank" src="https://images.rinz.io/rinz/nft/2022/07/05/1656988808.54421_76535002-9414-4bc2-a1a0-51d439d56d63.png" width="700" height="350">


For reference:

- Beta site with full UI: https://beta.vebank.io

- Documentation: https://docs.vebank.io

**1.3 Ecosystem Fit**

**VeThorChain (VeChain)** is a robust layer-1 blockchain with
Proof-of-Authority consensus mechanism and is elected to the top 40 most
popular global blockchain. The market capitalization of VeChain is
recorded at over \$2 billion dollars (at the time this application was
first written), notably known for its duo-token system, VET and VTHO.
With a mission to solve real-world problems on the blockchain, VeChain
recently became the *UFC's first-ever Official Layer 1 Blockchain
Partner*, actively promoting the development of DeFi infrastructure and
adoption of its recent initiatives VeChain stablecoins (VeUSD) and
Alchemy Pay. As total value locked (TVL) up to 10 million dollars is
deemed to be an early stage of an ecosystem, VeChain became a fertile
ground for developers to build large-scale DeFi projects.

VeBank aims to provide essential DeFi protocols on VeChain which improve
trading experience and increase total on-chain transaction numbers as
well as the total value locked. While it is obviously easy to clone EVM
lending dApps (like Aave, Compound) from Ethereum to VeChain, there is
not yet an Oracle available to support the core DeFi functions.
Therefore, we developed our own version of a centralized oracle (SEER),
and used it to provide multi-asset price feeds to VeBank.

VeBank Protocol is developed with security as our priority. An audit
third party will be involved to perform smart contract audits. Upon
completion, VeBank team will circulate the report to the VeChain
Foundation.

In the future, our goal is to enrich the ecosystem with additional DeFi
products, becoming the primary access point to the VeChain ecosystem.
The initiatives include cross-chain bridges to bring BTC, ETH and other
assets to VeChain, concentrated liquidity (similar to Uniswap v3),
stableswaps, NFT airdrops and NFT staking to boost lending/farming APY%.



**2. Team** 

2.1 Team members

<pre > 
+---------------+------------------------------------------+ 
| Team leader:  | Mr. Truong Phan (CEO)                    | 
+===============+==========================================+ 
|               |                                          | 
+---------------+------------------------------------------+ 
| Team members: | Mr. Tram Vo (CTO)                        | 
+---------------+------------------------------------------+ 
|               | Mr. Phat Nguyen (Lead DevOps Engineer)   | 
+---------------+------------------------------------------+ 
|               | Mr. Hanh Nguyen (Lead Frontend Engineer) | 
|               |                                          | 
|               | -   1 system engineer                    | 
|               |                                          | 
|               | -   2 frontend engineers                 | 
|               |                                          | 
|               | -   3 blockchain engineers               | 
|               |                                          | 
|               | -   3 backend engineers                  | 
|               |                                          | 
|               | -   1 tester                             | 
|               |                                          | 
|               | -   1 designer                           | 
+---------------+------------------------------------------+ 
</pre> 

2.2 Team Website

<pre > 

  Website    https://vebank.io
  ---------- -----------------------------
  Twitter    
  Telegram   https://t.me/vebank_offical
  Email      hello@esollabs.com
</pre> 


2.3 Team's experience

<pre> 

+-------------+--------------------------+--------------------------+
| **Name**    | **Experience**           | **Previous               |
|             |                          | project/skill**          |
+=============+==========================+==========================+ 
| Truong Phan | - Senior Project         | - Stably various         | 
|             | Manager at Stably,       | stablecoin projects:     | 
|             | Seattle-based stablecoin | VeUSD on VeChain, USDS   | 
|             | company.                 | on Harmony, Chia,        | 
|             |                          | ICON,...                 | 
|             | - 6 years of experience  |                          | 
|             | leading product          | - Gohub.vn - tech        | 
|             | development for          | startup in e-SIM and     | 
|             | traditional finance and  | telecom services         | 
|             | blockchain technology.   |                          | 
+-------------+--------------------------+--------------------------+ 
| Tram Vo     | - Over 8 years           | - Language: Python,      |
|             | experience in software   | Java, Solidity,          |
|             | development              | Javascript, C/C++.       |
|             |                          | - Database: MongoDB,     |
|             | - Expert in the          | MySQL, Redis, Firebase.  |
|             | development of           | - Tech: Docker, Redis,   |
|             | large-scale systems with | Microservices            |
|             | over 25 million users    | architecture.            |
|             | and 2 million CCU        | - Cloud: GCP, AWS.       |
|             |                          | - OS: Linux, Windows.    |
|             | - Tech lead from        | - Blockchain: EVM,        |
|             | requirement analysis,    | Truffle, Remix,          |
|             | implementation, code     | Ganache.\                |
|             | review, testing,         | - Management: Agile,     |
|             | deployment process,      | Jira.                    |
|             | alert and monitoring     |                          |
|             | system.                  |                          |
|             |                          |                          |
|             | - Lead architect for    |                           |
|             | other two Web3 projects: |                          |
|             | RinZ video streaming and |                          |
|             | Luna Rush GameFi.        |                          |
+-------------+--------------------------+--------------------------+
| Phat Nguyen | - 7+ years of            | - Media Streaming:       |
|             | experience as senior     | Wowza, Nimble,           |
|             | DevOps Engineer with     | Evostream, Nginx-rtmp.   |
|             | various server systems,  | - Microservices          |
|             | especially in video      | architecture: Docker     |
|             | streaming with 25M+      | Swarm, Kubernetes.       |
|             | number of users.         | - Cloud systems: AWS,    |
|             |                          | Azure, GCP.              |
|             |                          | - Monitor system:        |
|             |                          | Prometheus, Netdata,     |
|             |                          | Zabbix, Grafana.         |
|             |                          | - Log central: ELK,      |
|             |                          | GrayLog.                 |
|             |                          | - Scripting languages:   |
|             |                          | bash shell, python,      |
|             |                          | Lua.                     |
|             |                          | - CDN: Nginx,            |
|             |                          | Cloudflare.              |
|             |                          | - Storage: Cephfs,       |
|             |                          | Lizardfs, Minio.         |
|             |                          | - Mail server: Zimbra,   |
|             |                          | SES Aws.                 |
+-------------+--------------------------+--------------------------+
| Hanh Nguyen | 7+ years in full-stack   | - DB: MySQL,             |
|             | software development.    | PostgresSQL, MongoDB     |
|             |                          | - Backend: PHP Node JS,  |
|             |                          | Redis, rabbit MQTT, web  |
|             |                          | service (RESTful         |
|             |                          | APIs/SOAP)               |
|             |                          | - Frontend:              |
|             |                          | Javascript/Typescript    |
|             |                          | React, Web3, SASS/SCSS   |
+-------------+--------------------------+--------------------------+
</pre> 


2.4 Team Code Repos

  **Platform**   **ID**
  -------------- ---------------------------
  Github         https://github.com/vebank

2.5 Team LinkedIn Profiles
<pre> 

  **Name**          **Linked in Profile**
  ----------------- --------------------------------------------------------
  Mr. Truong Phan   https://www.linkedin.com/in/buckphan/ 
  Mr. Tram Vo       https://www.linkedin.com/in/tram-vo-a72309199/ 
  Mr. Phat Nguyen   https://www.linkedin.com/in/phat-nguyen-kim-715481233/ 
  Mr. Hanh Nguyen   https://www.linkedin.com/in/hanh-nguyen-21839923a/
</pre> 

**3. Development Roadmap**

3.1 Roadmap


<img alt="Vebank" src="https://images.rinz.io/rinz/nft/2022/07/05/1656988721.170695_ecee74b6-db72-48fb-9a25-16c1137e2cdc.png" width="700" height="350">


3.2. Overview

<pre> 

+-------------+-------------+-------------+-------------+-------------+
|             | Milestone 1 | Milestone 2 | Milestone 3 | **Total**   |
+=============+=============+=============+=============+=============+
| Estimated   | 4 months    | 2 months    | 2 months    | **8 month** |
| Duration    |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Full-time   | 9           | 9           | 9           |             |
| equivalent  | developers  | developers  | developers  |             |
| (FTE)       |             |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| Cost        | $80,000     | $40,000     | $40,000     | **          |
|             | development | development | development | $190,000**  |
|             |             |             | cost        |             |
|             | cost        | cost        |             |             |
|             |             |             | $30,000    |              |
|             |             |             | audit fees  |             |
+-------------+-------------+-------------+-------------+-------------+
</pre> 


*3.2.1 Milestone 1 --- Launch on VeChain testnet for the core lending functionalities* 

-   Complete research and development to arrive at MVP.

-   Complete design + UI mockup for the MVP website (https://beta.vebank.io) (beta.vebank.io)

-   Complete system infrastructure and user acceptance requirements for VeBank.

-   Complete development of following features: supply liquidity to
    lending pools, withdraw/repay liquidity from lending pools,
    liquidate a borrowing, claim incentive reward ($VB), claim
    incentive rewards, trigger safety/backstop module that liquidates
    up to 30% staked $VB for Short Fall event.

-   Determine risk parameters and collateral policies as well as platform fees.

-   Monitor lending pools with health factor <1.

*3.2.2 Milestone 2 --- Development & launch on testnet for trade, pool, and staking*

-   Enable Add/Remove liquidity pools, Stake/unstake $VB, and farming function.

-   Enable distribution of trading fees and protocol fees for users.

*3.2.3 Milestone 3 --- Official launch mainnet*

-   Perform smart contract audits with participation of a third party audit company.

-   Officially live on Mainnet for full functionalities of: trade, pool, lend & borrow, stake.

**4. Future Plans**

-   Develop VeBank NFT -> used to boost APY% for lend/borrow

-   Build a bridge system to allow seamless movements of big-cap assets from other blockchains to VeChain - BTC, ETH, BNB, etc to name a few.

-   Enable Futures/Options contract features on VeBank

-   Develop ETF-pegged assets (for example: stock index funds like VN30, VN-INDEX) to lend or borrow.

**5. Additional Information** 

Accomplished:

-   Deployed beta on beta.vebank.io (on VeChain testnet)

-   Deployed Lend/Borrow functions

-   Developed liquidation + safety module model.

-   Research and technical planning for DeFi Bridge, Vietnam ETF-pegged assets.

-   Whitepaper at docs.vebank.io

About other grants

-   We have not applied for any other grants.

Financial contributions

-   ESOL Labs team has self-financed this project from the beginning

-   Total expenses spent on this project are $50,000 which mostly cover technical development costs.

