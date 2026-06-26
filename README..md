# Multi-Product Distribution Optimization under Demand Volatility

**Inventory Optimization | Supply Chain Analytics | Operations Research | Scenario Analysis**

---

## Overview

This project analyzes the distribution network of a global healthcare company through a comprehensive inventory optimization case study. The objective was to evaluate alternative distribution strategies under uncertain demand while minimizing total supply chain costs and maintaining a **99% service level**.

The study models multiple pharmaceutical products with distinct demand growth trajectories and compares inventory policies across different network configurations using classical Operations Research techniques.

---

## Business Problem

Healthcare supply chains must balance high service levels with inventory and transportation costs while managing products exhibiting different demand patterns.

This project evaluates how different inventory and distribution strategies perform under varying demand growth scenarios and recommends the most cost-effective approach.

---

## Objectives

- Analyze a centralized healthcare distribution network
- Compare multiple inventory control strategies
- Evaluate distribution decisions under stochastic demand
- Quantify cost-service trade-offs
- Recommend the optimal inventory policy for each product category

---

## Methodology

The study evaluates three pharmaceutical products exhibiting different market growth trajectories. For each product, multiple inventory policies were developed and compared using quantitative performance metrics.

### Distribution Strategies

| Strategy | Description |
|---|---|
| Centralized | Single distribution hub serving all demand points |
| Decentralized | Regional warehouses closer to demand |
| Hybrid | Mixed network combining both approaches |

### Inventory Models

- **EOQ** — Economic Order Quantity
- **Continuous Review (Q,R)** — Reorder point policy under continuous monitoring
- **Newsvendor Model** — Single-period stochastic demand optimization
- **Joint Replenishment** — Coordinated ordering across product lines
- **Risk Pooling** — Variance reduction through demand aggregation
- **Obsolescence Cost Analysis** — Expiry and write-off cost quantification

### Scenario Analysis

Three independent demand scenarios evaluated across all distribution strategies:

| Scenario | Demand Profile |
|---|---|
| Stable | Low variance, steady-state demand |
| Moderate Growth | Gradual upward trend |
| High Growth | Aggressive expansion trajectory |

Each scenario maintains a target **99% service level** as a hard constraint.

---

## Key Results

- **~$1.69M estimated annual savings** through improved inventory policies
- Recommended optimal distribution strategy per product category based on demand profile
- Demonstrated inventory pooling benefits under centralized distribution
- Quantified transportation vs. holding cost trade-offs across network configurations
- Evaluated stochastic inventory decisions while maintaining 99% service level across all scenarios

---

## Performance Metrics

| Metric | Description |
|---|---|
| Total Annual Cost | Aggregate supply chain cost |
| Ordering Cost | Fixed cost per replenishment cycle |
| Holding Cost | Capital and storage cost of inventory |
| Transportation Cost | Inbound and outbound logistics |
| Stockout Cost | Lost sales and penalty costs |
| Safety Stock | Buffer inventory for demand uncertainty |
| Service Level | Fill rate maintained across scenarios |
| Inventory Turns | Annual throughput efficiency |

---

## Repository Structure

```
├── Data/
├── Case Study Report.pdf
├── Financial Models.xlsx
├── Presentation.pdf
├── Analysis.ipynb
└── README.md
```

---

## Tools & Technologies

- Python (NumPy, Pandas, Jupyter Notebook)
- Microsoft Excel (Financial Models)

---

## Skills Demonstrated

`Supply Chain Analytics` `Inventory Optimization` `Operations Research` `Distribution Network Design` `Stochastic Inventory Models` `Scenario Analysis` `Cost Optimization` `Quantitative Decision Making`

---

## Learning Outcomes

This project demonstrates the application of inventory theory and Operations Research techniques to a real-world healthcare supply chain. By integrating stochastic demand modeling with inventory optimization, the study provides data-driven recommendations that balance cost efficiency, service levels, and operational risk.

---

*Srijan Ghosh — B.Tech (Hons.), Industrial Engineering, IIT Kharagpur*
