# Lending module

Solace lending module is the first lending market for derivatives assets and the key part of the protocol.

### **Purpose and Features**

Solace Lending module allows DeFi users to execute creative and unique strategies.

On one side, a user can efficiently hedge the risk of their DeFi positions and avoid unwanted losses. On the other side, liquidity providers get access to yield arbitrage, short yield leveraging and other strategies. These strategies improve the asset utilization rates and potentially yield higher for liquidity providers.

However, it's important to remember that derivative tokens use comes with more risk. If the underlying protocol is hacked, the token value can fall sharply. This could prevent liquidity providers from fully withdrawing their liquidity.

### **How does the Lending Module work?**

The lending module's technical implementation is based on Compound V2. Combining the attributes of Compound and ve-tokenomics, the Solace Lending Module initially lists five tokens. VeSGT holders control SGT emission distribution to various markets through weekly voting, influencing both the borrowing and supplying sides.

The Coverage module uses the Lending module to deposit PT tokens and borrow ETH.

#### **Backstop**

The backstop activates when the PT to ETH rate drops. In case of an exploit, borrowed Principal Tokens cannot be used to repay and withdraw ETH, leading to 'bad debt'. This results in a payout for ETH borrowers on the market, including the Coverage Module as one of the borrowers. If the value of the Principal Token is restored, the veSGT governance can reactivate it.

#### **Liquidation**

Liquidation occurs when a user's borrowed position exceeds the Borrow Limit, i.e., when the borrow utilization exceeds 100%.

The Borrow Limit represents the maximum amount a user can borrow based on the value of the deposited collateral and available liquidity. It equates to a 100% borrow utilization.

Borrow Utilization rate indicates the risk of liquidation. A lower utilization percentage means a safer position for the user's collateral.

#### **Listed tokens:**

* ETH
* PT-stETH
* PT-ankrETH-WETH
* PT-rETH-WETH
* PT-StaFirETH-WETH

### **Summary**

* The Solace Lending Module is a fork of Compound V2, optimized for Pendle's derivative tokens.
* The Solace Lending Module introduces innovative applications for PT tokens and enables new yield strategies.
* It features a backstop mechanism that safeguards users when the PT to ETH rate declines substantially.
* Liquidation occurs when a user's borrowed position exceeds the Borrow Limit
* Users earn yields by providing liquidity and depositing the received cTokens into a gauge.
* Users must be aware of the increased risks associated, especially related to derivative tokens and the vulnerabilities of their underlying protocols.
* Initial tokens listed on the Lending Module are ETH, PT-stETH, PT-ankrETH-WETH, PT-rETH-WETH, and PT-StaFirETH-WETH.
