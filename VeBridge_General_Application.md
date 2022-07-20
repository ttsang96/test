# VeChain General Grant Application

## 1. Project Overview

- Project: VeBridge v1.0

- Team Name: Esol Labs

- Payment Address:

    - VeChain: 0xa2b13B6Be3fb3F9f98A43371687255D5943754Eb

    - Ethereum: 0xF4B57a2749Fa8FBFA9644a186e0730c2C64DcB90
    
    - Binance Smart Chain (preferred): 0xF4B57a2749Fa8FBFA9644a186e0730c2C64DcB90

### 1.1 Overview

**[VeBridge v1.0](https://vebridge-stag.vebank.io/home)** is our first implementation of generic message passing protocol that connects to multiple chains between VeChain and Ethereum, Solana, Terra, Binance Smart Chain, Polygon, Avalanche, Oasis, Fantom, Karura, Celo and Aurora.

<img alt="Vebridge" align="center" src="https://github.com/ttsang96/test/blob/main/media/VBr.png?raw=true" >

Our key emphasis is bring assets from BSC and Ethereum to VeChain, secured by multi-nodes system and "Watch dogs" as 2nd layer of security - run transparency with community

### 1.2 Project Details

#### _1.2.1 Introduction_

-   VeBridge at its core is a centralized notary. Works by monitoring a set of chains for messages emitted by smart contracts on those chains. The resulting messages are then routed to target chains, allowing a form of cross chain message passing.

-   Currently, VeBridge is secured by a guardian set of 7 nodes consisting of professional validators in the space.
#### 1.2.2 Overview

1. Contract with functions for bring assets from top chains to VeChain

2. Guardian is the role to observe messages and sign the corresponding payloads. Each guardian performs this step in isolation, later combining the resulting signatures with other guardians as a final step. The resulting collection of independent observations form a multisig which represents a proof that a state has been observed and agreed upon by a majority of the wormhole network. These multisigs are referred to as VPA's in VeBridge.

3. VPA (Verified Proof Approval) is Messages emitted by contracts need to be verified by the guardians before they can be sent to the target chain. Once a majority of guardians reach consensus that an observation has been made, the message is wrapped up in a structure called a VPA which combines the message with the guardian signatures to form a proof.
These VPA's are ultimately what a smart contract on a receiving chain must process in order to receive a wormhole message.

### 1.3 Ecosystem Fit

**VeThorChain (VeChain)** is a robust layer-1 blockchain with Proof-of-Authority consensus mechanism and is elected to the top 40 most popular global blockchain. The market capitalization of VeChain is recorded at over $2 billion dollars (at the time this application was first written), notably known for its duo-token system, VET and VTHO. With a mission to solve real-world problems on the blockchain, VeChain recently became the _UFC&#39;s first-ever Official Layer 1 Blockchain Partner_, actively promoting the development of DeFi infrastructure and adoption of its recent initiatives VeChain stablecoins (VeUSD) and Alchemy Pay. As total value locked (TVL) up to 10 million dollars is deemed to be an early stage of an ecosystem, VeChain became a fertile ground for developers to build large-scale DeFi projects. However, our study shows that DeFi protocols on VeChain are missing constant, seamless real-time external data feeds, which will eventually limit the ability to add more complex financial layers to the platforms, especially during the time crypto market faces high level of volatility.

In the future, our goal is to further enrich the ecosystem with more essential DeFi products, becoming the primary access point for data into the VeChain ecosystem. Further developments will involve:

(i) Cross chain exchange.
(ii) Cross chain governance app.
(iii) Cross chain game.

## 2. Team

### 2.1 Team members
|||
| --- | --- |
| Team leaders: | Mr. Thong Nguyen (CEO) |
|| Mr. Tram Vo (CTO) |
| Team members: | Mr. Phat Nguyen (DevOps Team Lead) |
|| Mr. Hanh Nguyen (Frontend Team Lead)|
|| Mr. Truong Phan (Head Of BlockChain)|
||+ 1 system engineer<br>+ 1 blockchain engineer<br>+ 1 backend engineer<br> + 1 designer<br>|

### 2.2 Team Website

#### 2.2.1 Team&#39;s experience

| Name | <p align="center">Experience<p> | <p align="center">Previous project/skill<p> |
| --- | --- | --- |
| Thong Nguyen | <ul><li>16 years of experience as a financial analyst.<li>Over 3 years of blockchain market research.<li>6 years of experience as a banking manager. |
| Tram Vo | <ul><li> Over 8-year experience in Software development<li> Deep experience in software development for large-scale systems, with over 25 million users and 2 million CCU at the 2018 AFC U-23 Championship.<li> Profound understanding of many subjects in software development such as requirement analysis, implementation, code review, testing, deployment process, alert and monitoring system.<li>Technical leader for 2 blockchain projects | <ul><li> Language: Python, Java, Solidity, Javascript, C/C++.<li> Database: MongoDB, MySQL, Redis, Firebase.<li> Tech: Docker, Redis, Micro-services architecture.<li> Cloud: GCP, AWS.<li> OS: Linux, Windows.<li> Blockchain: EVM, Truffle, Remix, Ganache.<li> Management: Agile, Jira. |
| Phat Nguyen | <ul><li> 7+ years of experience as a Senior DevOps Engineer with different server systems, especially streaming systems.<li> Experience in handling a large number of users (over 25 millions) | <ul><li> Media Streaming: Wowza, Nimble, Evostream, Nginx-rtmp.<li> Continuous Integration and Continuous Delivery: Jenkins, Ansible, Gitlab ci/cd.<li> Build Microservices architecture: Docker Swarm, Kubernetes.<li> Has experience with Cloud base systems (AWS / Azure / GCP).<li> Monitor system: Prometheus, netdata, zabbix, Grafana.<li> Log central: ELK, GrayLog.<li> Scripting languages: bash shell, python, Lua.<li> CDN: Nginx, Cloudflare.<li> Storage: Cephfs, Lizardfs, minio.<li> Mail server: Zimbra, ses aws. |
| Hanh Nguyen | <ul><li>Over 7 years in software development. | <ul><li> Database: MySQL, PostgreSQL, MongoDB.<li> Backend: PHP Node JS, Redis, rabbit MQTT , web service (RESTful APIs/SOAP).<li> Front end: Javascript/Typescript React , Web3, SASS/SCSS. |
| Truong Phan | <ul><li>Senior Project Manager at Stably, Seattle-based stablecoin company.<li>6 years of experience leading product development for traditional finance and blockchain technology. | <ul><li>Stably various stablecoin projects: VeUSD on VeChain, USDS on Harmony, Chia, ICON,...<li> Gohub.vn - tech startup in e-SIM and telecom services |

#### 2.2.3 Team Code Repos

| **Platform** | **<p align="center">ID** |
| --- | --- |
| Github | https://github.com/VeBridge |

#### 2.2.4 Team LinkedIn Profiles

| **Name** | **Linked in Profile** |
| --- | --- |
| Mr. Thong Nguyen | https://www.linkedin.com/in/buckphan/ |
| Mr. Tram Vo | https://www.linkedin.com/in/tram-vo-a72309199/ |
| Mr. Phat Nguyen | https://www.linkedin.com/in/phat-nguyen-kim-715481233/ |
| Mr. Hanh Nguyen | https://www.linkedin.com/in/hanh-nguyen-21839923a/ |
| Mr. Truong Phan | https://www.linkedin.com/in/buckphan/ |


##


## 3 Development Roadmap

### 3.1 Example Roadmap for a dApp Application

- August 2022

    - Deploy VeBridge v1.0 contracts on VeChain, Ethereum, BSC testnet.
    - Supports bridge ETH, BNB from Ethereum, BSC to VeChain.
- September 2022

    - Launch VeBridge v1.0 on mainnet.

### 3.2. Overview

|| Milestone 1 | Milestone 2 | Total |
| --- | --- | --- | --- |
| Estimated Duration | 2 month | 1 month | 3 months |
| Full-time equivalent (FTE) | 3 full-time engineers| 3 full-time engineers||
| Cost (up to $ 30,000) | Development cost: $10,000<br>(Backend: $3,000<br>Frontend: $1,000<br>Smart contracts: $3,000)| Development cost: $10,000<br>(Backend: $2,000<br>Frontend: $1,000<br>Smart contracts: $2,000<br>Server: $6,000 for 12 months)<br>Gas fee to keep the guardian running:$10,000 | $30,000 |

#### 3.2.1 Milestone 1 — Deploy VeBridge v1.0 on testnet
 
- Smart contracts for VeChan, Ethereum, BSC on testnet.
- Website testnet on https://vebridge-stag.vebank.io/home.

#### 3.2.2 Milestone 2 — Deploy VeBridge v1.0 on mainnet

- Deploy smart contracts to VeChan, Ethereum, BSC on mainnet.
- Deploy official VeBridge website.

##


## 4. Future Plans

In the future, our goal is to further enrich the ecosystem with more essential DeFi products, becoming the primary access point for bring assets into the VeChain ecosystem.

## 5. Additional Information

What we have already accomplished:

- Smart contracts VeChan, Ethereum, BSC on testnet.
- Deploy beta website for VeBridge: [https://vebridge-stag.vebank.io/home](https://vebridge-stag.vebank.io/home).
- Run stress-test to test bridge stability with 100% accuracy and up-time.
- Ready for mainnet.

About other grants

- We haven&#39;t applied for any other grants.

Financial contributions

- Our team has self-financed this project from the beginning.
- Total budget that we have spent till date is about $20,000.