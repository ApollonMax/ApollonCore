Apollon Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/Apollon-Project/Apollon.svg?branch=master)](https://travis-ci.org/Apollon-Project/Apollon) [![GitHub version](https://badge.fury.io/gh/Apollon-Project%2FApollon.svg)](https://badge.fury.io/gh/Apollon-Project%2FApollon)

Apollon is an open source crypto-currency focused on fast private transactions with low transaction fees & environmental footprint.  It utilizes a custom Proof of Stake protocol for securing its network and uses an innovative variable seesaw reward mechanism that dynamically balances 90% of its block reward size between masternodes and staking nodes and 10% dedicated for budget proposals. The goal of Apollon is to achieve a decentralized sustainable crypto currency with near instant full-time private transactions, fair governance and community intelligence.
- Anonymized transactions using the [_Zerocoin Protocol_](http://www.apollon.one/zxap).
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftX_.
- Decentralized blockchain voting utilizing Masternode technology to form a DAO. The blockchain will distribute monthly treasury funds based on successful proposals submitted by the community and voted on by the DAO.

More information at [apollon.one](http://www.apollon.one) Visit our ANN thread at [BitcoinTalk](https://bitcointalk.org/index.php?topic=3058895.0)

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>43,199,500 XAP</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>Infinite</td></tr>
<tr><td>Premine</td><td>60,000 XAP*</td></tr>
</table>

*60,000 XAP Premine was burned in block [279917](http://www.presstab.pw/phpexplorer/Apollon/block.php?blockhash=206d9cfe859798a0b0898ab00d7300be94de0f5469bb446cecb41c3e173a57e0)

### Reward Distribution

<table>
<th colspan=4>Genesis Block</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th></tr>
<tr><td>1</td><td>60,000 XAP</td><td>Initial Pre-mine, burnt in block <a href="http://www.presstab.pw/phpexplorer/Apollon/block.php?blockhash=206d9cfe859798a0b0898ab00d7300be94de0f5469bb446cecb41c3e173a57e0">279917</a></td></tr>
</table>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th><th>Budget</th>
<tr><td>2-43200</td><td>20% (50 XAP)</td><td>80% (200 XAP)</td><td>N/A</td></tr>
<tr><td>43201-151200</td><td>20% (50 XAP)</td><td>70% (200 XAP)</td><td>10% (25 XAP)</td></tr>
<tr><td>151201-259200</td><td>45% (22.5 XAP)</td><td>45% (22.5 XAP)</td><td>10% (5 XAP)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternodes & Stakers</th><th>Budget</th>
<tr><td>Phase 1</td><td>259201-302399</td><td>50 XAP</td><td>90% (45 XAP)</td><td>10% (5 XAP)</td></tr>
<tr><td>Phase 2</td><td>302400-345599</td><td>45 XAP</td><td>90% (40.5 XAP)</td><td>10% (4.5 XAP)</td></tr>
<tr><td>Phase 3</td><td>345600-388799</td><td>40 XAP</td><td>90% (36 XAP)</td><td>10% (4 XAP)</td></tr>
<tr><td>Phase 4</td><td>388800-431999</td><td>35 XAP</td><td>90% (31.5 XAP)</td><td>10% (3.5 XAP)</td></tr>
<tr><td>Phase 5</td><td>432000-475199</td><td>30 XAP</td><td>90% (27 XAP)</td><td>10% (3 XAP)</td></tr>
<tr><td>Phase 6</td><td>475200-518399</td><td>25 XAP</td><td>90% (22.5 XAP)</td><td>10% (2.5 XAP)</td></tr>
<tr><td>Phase 7</td><td>518400-561599</td><td>20 XAP</td><td>90% (18 XAP)</td><td>10% (2 XAP)</td></tr>
<tr><td>Phase 8</td><td>561600-604799</td><td>15 XAP</td><td>90% (13.5 XAP)</td><td>10% (1.5 XAP)</td></tr>
<tr><td>Phase 9</td><td>604800-647999</td><td>10 XAP</td><td>90% (9 XAP)</td><td>10% (1 XAP)</td></tr>
<tr><td>Phase X</td><td>648000-Infinite</td><td>5 XAP</td><td>90% (4.5 XAP)</td><td>10% (0.5 XAP)</td></tr>
</table>
