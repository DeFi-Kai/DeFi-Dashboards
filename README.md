# DeFi-Dashboards

## Correlation Coefficient Dashboard
![alt text](https://github.com/DeFi-Kai/DeFi-Dashboards/blob/main/Correlation_Coefficient_Dashboard.png)

The correlation coefficient measures how two assets move together, ranging from +1 (moving in the same direction) to -1 (moving in opposite directions). A correlation of 0 indicates no relationship between their movements.

This dashboard compares the correlation coefficients of popular liquidity pool (LP) pairs on Meteora, a liquidity hub on Solana. It helps LP depositors make informed decisions by identifying LPs with the highest correlation to minimize impermanent loss.

[Link to Dashboard](https://flipsidecrypto.xyz/defi_kai/correlation-coefficient-for-popular-meteora-pairs-V3WBVc)

### Roadmap
- [ ] **Write Parameterized Query:** Allow users to input a token pair to view its correlation coefficient.
- [ ] **Use Meteora Liquidity Data:** Display the highest-liquidity token pairs, by TVL, from Meteora (Table).
- [ ] **Add prices of each asset to correlation line charts:** Overlay asset prices on correlation charts to analyze price movements and correlation trends (Line Chart).


## Thala Labs Dashboard
![alt text](https://github.com/DeFi-Kai/DeFi-Dashboards/blob/main/Thala_Labs_Dashboard.png)

Thala Labs is the largest project on Aptos by TVL, providing key infrastructure for the Aptos DeFi ecosystem. The Thala suite includes:

- ThalaSwap – Decentralized Exchange (DEX)
- Thala CDP Stablecoin – Collateralized Debt Position stablecoin
- thAPT (Liquid Staked Aptos) – Liquid staking derivative for APT

This dashboard tracks Thala Labs' performance and compares its products to competitors on Aptos.

[Link to Dashboard](https://flipsidecrypto.xyz/defi_kai/thala-labs-dashboard-iUi98t)

### Roadmap
- [ ] **Thala Swap TVL Breakdown:** Visualize TVL distribution by asset (Pie Chart). 
- [ ] **Gas comparison:** Compare Thala’s gas usage to other Aptos dApps to identify the top apps driving network activity (Area Chart).  
- [ ] **30d user comparison:** Compare Thala’s user activity over the last 30 days to other Aptos dApps (Pie Chart).
- [ ] **Thala LSD data:** Track thAPT and sthAPT staking and compare them to other APT liquid staking tokens.
- [ ] **Top 100 Users by TXNs:** List the top Thala users by transaction volume (Table).
- [ ] **Top 100 Users by TVL:** List the top Thala users by TVL (Table).

