# Casino Profitability & Player Behavior Simulation

A comprehensive Monte Carlo simulation built in R to model casino operations, calculate house advantage, and analyze player behavior across six classic games. This project was completed as a statistical modeling capstone.

## 📄 Project Report

The full project report, including all R code, detailed methodology, results, and visualizations, is contained in the PDF.

## 🎯 Project Overview

This capstone project simulates a casino environment with 8,000 virtual players to answer key business questions:
- **What is the house advantage for each game?** (Roulette, Baccarat, Slots, Keno, Craps)
- **Which games are the most profitable for the casino?**
- **How can a player rewards program be designed to maximize retention and profit?**

## 🔧 Key Techniques & Technologies

*   **Language:** R
*   **Methods:** Monte Carlo Simulation, Statistical Modeling
*   **Probability Distributions:** `rgamma`, `rmultinom`
*   **Data Visualization:** `ggplot2`, `hist`
*   **Reporting:** `knitr::kable`

## 📈 Summary of Key Results

The simulation of over $2.6 billion in total bets yielded the following house advantages:

| Game          | House Advantage |
|---------------|-----------------|
| Roulette      | 5.07%           |
| Baccarat      | 12.11%          |
| Keno          | 27.39%          |
| 4-Reel Slots  | 25.79%          |
| **5-Reel Slots** | **17.10%**      |
| Craps         | 0.74%           |
| **Overall**   | **17.08%**      |

*Analysis revealed that 5-Reel Slots, due to high volume and a progressive jackpot mechanism, was the primary driver of total casino profit.*
