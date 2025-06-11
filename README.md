# 🚀 Prosperity 2025 – IMC Trading Competition

Welcome to our repository for the Prosperity 2025 trading competition hosted by IMC Trading. This competition challenged participants to design and implement high-frequency trading algorithms that can perform in a simulated market environment.

---

## 👥 Team Members

- **Shivam Sagar**
- **Sashank Singh**

We collaborated on all aspects of strategy development, implementation, and optimization throughout the competition.

---
## 📊 Prosperity Dashboard

[![Prosperity Dashboard](https://github.com/Shivam-26102003/IMC_Trading_Prosperity_2025/raw/main/Desktop/IMC%20Repo/Prosperity%20dashboard/Prosperity%20dashboard.jpg)](https://github.com/Shivam-26102003/IMC_Trading_Prosperity_2025/blob/main/Desktop/IMC%20Repo/Prosperity%20dashboard/Prosperity%20dashboard.jpg)

<sub>This is the dashboard of result after the submission of round 2. We will update this repository with all trading strategies, experiment results, and improvements developed throughout the IMC Prosperity 2025 competition soon.</sub>


---

## 📈 Project Overview

The goal of this competition was to create an automated trading strategy capable of competing in a real-time, high-speed, and highly dynamic trading environment. We leveraged both quantitative analysis and strategic decision-making under pressure to build robust, fast, and adaptive trading bots.

---
## 🌐 Problem Statement

The competition simulated a virtual exchange with multiple fictional assets, where participants had to design automated trading algorithms to maximize profit while respecting position limits and market rules.

In Round 1, the exchange introduced the following products:
- **Rainforest Resin**: a stable product with minimal price volatility.
- **Kelp**: a product showing oscillating price behavior.
- **Squid Ink**: a highly volatile product exhibiting mean-reversion tendencies.

The goal was to design algorithms capable of efficiently trading these products by analyzing market data, managing positions, and executing profitable orders.

---

## 🧠 Our Approach

We focused our initial efforts on designing a robust algorithm for **Rainforest Resin**, which provided a good opportunity to test and develop market-making strategies due to its price stability.

### Strategy Highlights

- **Enhanced Market-Making for Rainforest Resin**
  - Dynamic fair price estimation.
  - Market making within a configurable spread around the fair price.
  - Aggressive order taking when favorable opportunities arise (arbitrage entries).
  - Position management via soft limits to prevent over-exposure.
  - Clearing logic to offload excess inventory when positions exceeded thresholds.
  - Fully parameterized logic to control trading behavior:
    - `take_width`: aggressiveness for taking orders.
    - `clear_width`: aggressiveness for clearing inventory.
    - `default_edge`: spread used for quoting.
    - `soft_position_limit`: threshold for adjusting quoting behavior.

- **PnL Logging & Analytics**
  - Position tracking and proper PnL logging for monitoring performance.
 
More to be updated soon.... about further rounds
---

## 🧠 Strategy Highlights

Our strategy focused on:

- **Market Making:** Providing liquidity on both sides of the order book.
- **Arbitrage:** Detecting and exploiting price discrepancies between related instruments.
- **Signal Processing:** Using statistical methods to predict short-term market moves.
- **Risk Management:** Implementing strict limits on exposure and volatility.

We iteratively refined our strategies based on performance logs, market metrics, and order book behavior during the simulation rounds.

---

## 💻 Tech Stack

- **Python** for algorithm development
- **NumPy / Pandas** for data analysis
- **Git** for version control and collaboration

---

## 📊 Results & Learnings

We achieved:

- Efficient quote placement and inventory management
- Profitable execution in multiple market scenarios
- Insights into real-world trading infrastructure and systems

Through this competition, we deepened our understanding of:

- Algorithmic trading principles
- Real-time systems
- Strategic coding under constraints

---



---

## 🧾 Acknowledgements

We would like to thank IMC Trading for organizing this challenging and insightful event and providing a platform for aspiring traders and technologists to showcase their skills.

---

## 📬 Contact

Feel free to reach out for any questions or collaboration ideas!

- **Shivam Sagar** – [https://www.linkedin.com/in/shivam-sagar-40266225a/]
- **Sashank Singh** – [https://www.linkedin.com/in/sashank-singh-3a46a6247/]

---
