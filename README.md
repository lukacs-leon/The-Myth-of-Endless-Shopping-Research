# The Myth of Endless Shopping - Research
## Aim and methodology of the research
### Purpose of the research
The aim of this research is to investigate whether it is possible, in a predetermined system - mainly a financial system - to continuously increase or maintain the standard of living of all indefinitely.
## Methodology
The research is conducted using a Python-based simulation framework. Various "worlds" are modeled as isolated environments, into which pre-defined "casts"—representing agents or players—are placed. These agents are stored as separate files or objects, enabling them to behave identically when placed in identical scenarios.

The setup for each simulation is defined in a central `config.json` file. This file specifies which `map.json` to use (see below), the initial agents involved, and other simulation parameters.

Each map encodes the static layout of a world: the spatial or logical configuration of relevant elements. A modular "world manager" system handles the simulation logic. This manager is implemented as a directory of interchangeable modules—each capable of modeling a specific dynamic, such as DAO governance or infinite money printing.

Rules and behavioral logic are written directly into the relevant world manager modules, allowing for flexible experimentation with different systemic conditions.

As part of the research, Python scripts will be developed and executed for the different models, and their outcomes will be systematically evaluated.
#### Raw materials
##### Money
##### Food
##### Iron
##### Wood
##### Water
#### Casts
##### Farm
- Produces 1 food.
- Every size increse produce +1 food.
- Buying 1 plot of land if no one has owned it before costs 25 money. Otherwise the farmer have to negotiate with the owner.
- Each level increase reduces costs by 10%.
- 1 level development costs 10% more than the previous one. Costs for the first 50 technologies
##### Farmer
- Every farmer produces +0.1 food. 1 farmer don't produces plus food.
- Every Graduate farmer produces +1 food. 1 farmer is too.
##### Office
##### Officer
##### Factory
##### Factory worker
##### Blockchain
##### Computer
##### Reactor
##### Reactor worker
##### Leader
##### Cracker
##### Programer
##### School
##### Train
##### Car
##### Ship
##### Airplane
##### Infrastructure Engineer
##### University

#### Modells
This research focuses on two types of financial systems: Crypto-like and fiat-like. The former incorporates some crypto ideas and plans, such as DAO and trustless banking mechanisms. The fiat-like system incorporates structures used in the fiat world. For example, there is endless money printing.
##### Crypto-like
1. DAO Governance Voting: Simulate proposal creation and voting to test efficiency and fairness of decentralized decision-making.
2. Smart Contract Automation: Test simple and complex financial transactions executed via smart contracts for automation and reliability.
3. Token Supply Models: Experiment with fixed, inflationary, and deflationary token supplies to see effects on wealth distribution.
4. Decentralized Exchange Liquidity: Test liquidity provision/removal and its impact on price volatility and user experience.
5. Trustless Lending/Borrowing: Model peer-to-peer loans using smart contracts, examining default and collateral handling.
6. Sybil Attack Resistance: Simulate attacks with fake identities to test system robustness against manipulation.
7. Gas Fee Impact: Analyze how fluctuating transaction fees affect user participation and system scalability.
8. Blockchain Network Congestion: Simulate network overload and observe transaction delays and user frustration.
9. Randomized Block Rewards: Test how various reward mechanisms (lottery, pro-rata) affect miner/validator behavior.
10. On-chain vs. Off-chain Governance: Compare the effectiveness and transparency of on-chain vs. off-chain decision processes.
##### Fiat-like
1. Central Bank Money Printing: Model various rates of money creation to observe inflation and wealth dilution.
2. Fractional Reserve Banking: Test money supply growth and risk of bank runs under fractional reserve rules.
3. Interest Rate Policy: Simulate raising/lowering rates to see effects on loans, savings, and economic growth.
4. Government Bailouts: Test effects of corporate and bank bailouts on public trust and market stability.
5. Taxation Schemes: Model progressive, flat, and regressive tax systems and their effects on inequality.
6. Debt Accumulation & Defaults: Simulate household, corporate, or government debt cycles and the triggers for crisis.
7. Inflation Shocks: Introduce sudden inflation events and analyze impact on wages, prices, and living standards.
8. Unemployment Benefits: Test different welfare models for supporting citizens during recessions.
9. Currency Devaluation: Simulate effects of rapid currency depreciation on imports, exports, and living costs.
10. Banking System Trust Crisis: Model scenarios where public trust collapses and observe systemic reactions.
