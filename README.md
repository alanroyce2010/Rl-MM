# Rl-MM
This is the repo for course project of HS4007.
# Team Members
- Alan Royce Gabriel - BS22B001  
- Shivan Ajay Iyer - BE22B048  
- Nazia Tabassum - HS24H061  
- Akansha Dnyaneshwar Surwade - HS24H049  

---

# Description
We aim to model and study **Market Making at high frequency using Reinforcement Learning**, where the market maker adapts quoting strategies in the presence of:

1. Adverse selection from *"toxic"* informed traders (whose trades predict short-term price movements).  
2. Exogenous policy constraints such as transaction taxes, speed bumps, or minimum resting times.  

The RL market maker will interact with a simulated **limit order book (LOB)** populated with noise traders and informed traders. By training an RL agent, we intend to evaluate:

- How well the RL market maker learns to balance profitability, inventory risk, and adverse selection.  
- How policy interventions affect market quality (liquidity, spreads, depth) and the agent's strategy.  
- The broader implications for public policy in algorithmic and HFT market design.  

---

# Tentative Work Plan

| **Work Item** | **Target Date** |
|---------------|-----------------|
| **Literature Review** (RL in market making, AS model, policy impacts on HFT) | 10/09/2025 |
| **Environment Setup:** Design a basic LOB simulator with Poisson/Hawkes arrivals for market orders and cancellations | 17/09/2025 |
| **RL Agent (Baseline):** Implement simple RL agent and Report for intermediate submission | 27/09/2025 |
| **Adverse Selection Module:** Add informed trader that moves mid-price after trades | 07/10/2025 |
| **Policy Layer:** Implement toggles for transaction tax, speed bump, minimum resting time | 14/10/2025 |
| **Experiments & Metrics:** Measure PnL, inventory risk, spreads, adverse selection, market depth under different policies | 21/10/2025 |
| **Final Report & Visualization:** Consolidate results, policy implications, plots/animations of order book dynamics | 05/11/2025 |
