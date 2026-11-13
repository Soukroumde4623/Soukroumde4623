# Marcellin Soukroumde Quantitative Finance & Systems Engineering

I am a quantitative finance engineering student currently pursuing a double degree in **Financial Engineering and Applied Mathematics at ENSIMAG** (Grenoble INP - UGA) in France, after graduating **first in my class** in Digital Engineering for Finance at **ENSIAS** in Morocco.

My work sits at the intersection of stochastic calculus, low-latency systems engineering, and market microstructure. I specialize in translating mathematical pricing and statistical models into resilient, production-grade infrastructure capable of operating under live market constraints.

---

## Philosophy & Track Record

A quantitative model only creates value when its execution is reliable, reproducible, and fast. Throughout my academic training and industry internships, I have focused on bridging the gap between theoretical modeling and live deployment—building end-to-end pipelines where numerical precision meets clean software architecture.

Beyond academic research, I regularly test systematic strategies under competitive market conditions, recently placing **7th out of 1,500 teams** in the **2026 Global Trading Challenge** by managing a multi-asset portfolio across global equities and fixed income.

---

## Core Competencies

- **Derivatives Pricing & Structuring**  
  Implementation of option pricing frameworks and interest rate term-structure models—from Cox-Ross-Rubinstein (CRR) binomial trees and variance-reduced Monte Carlo engines to Vasicek and Cox-Ingersoll-Ross (CIR) short-rate models. Strong focus on calibration stability, numerical convergence, and Greeks sensitivity analysis.

- **Systematic Trading & Quantitative Risk**  
  Architecture of event-driven backtesting engines and portfolio optimization frameworks (Markowitz, Black-Litterman, Risk Parity) incorporating realistic market frictions such as bid-ask spreads, slippage, and turnover constraints. On the risk side, I model tail exposure using parametric/historical VaR, CVaR, stress testing, Gaussian Mixture Models (GMM) for regime detection, and credit risk metrics (PD/LGD/EAD).

- **Quantitative Infrastructure & Low-Latency Engineering**  
  Design of modular software backbones that take research from prototype to production: asynchronous event loops, REST APIs for real-time model serving, containerized microservices (Docker), and automated CI/CD pipelines. I pair **Python** for rapid statistical prototyping with **C++** for performance-critical pricing and simulation kernels.

---

## Technical Stack

| Domain | Technologies & Libraries |
|---|---|
| **Languages** | C++ (STL, Eigen, Boost, QuantLib), Python, SQL, R, Go, Solidity, Shell |
| **Quantitative & Scientific** | NumPy, pandas, SciPy, statsmodels, arch, scikit-learn, Matplotlib, Plotly |
| **Machine Learning & NLP** | PyTorch, Hugging Face Transformers, FinBERT, Gaussian Mixture Models |
| **Infrastructure & Backend** | Linux, Docker, Nginx, GitHub Actions, Django, Flask, React |
| **Data & Tooling** | PostgreSQL, SQLite, Git, LaTeX |

---

## Selected Projects & Research

### 1. Event-Driven Multi-Asset Systematic Backtesting Engine
Architected a modular, event-driven simulation and risk engine designed to eliminate look-ahead bias and mirror live execution environments:
- Built an asynchronous event queue orchestrating market data ticks, alpha signal generation, portfolio allocation, and order routing.
- Integrated realistic execution modeling accounting for transaction costs, bid-ask spreads, slippage, and dynamic position sizing.
- Automated post-trade risk and performance attribution (Sharpe, Sortino, Maximum Drawdown, VaR/CVaR, and factor exposures).

### 2. Derivatives Pricing & Short-Rate Modeling Library (C++ / Python)
Engineered a quantitative pricing library for vanilla/exotic options and interest rate dynamics:
- Implemented CRR binomial lattices and Monte Carlo engines with variance reduction techniques (antithetic variates, control variates).
- Modeled short-rate dynamics using **Vasicek** and **CIR** stochastic differential equations, including yield curve calibration and finite-difference Greeks computation.

### 3. Production-Grade Credit Risk Scoring Infrastructure
Designed and deployed a full-stack credit risk decision pipeline simulating institutional underwriting workflows:
- Benchmarked seven classification architectures (Logistic Regression, Random Forests, XGBoost) using custom SMOTE resampling to address severe class imbalance.
- Exposed real-time Probability of Default (PD) inference via a containerized REST API (Docker, Nginx) paired with an interactive monitoring interface.

### 4. FinSent Financial NLP & Sentiment Alpha Pipeline
Developed an alternative-data pipeline extracting directional market signals from financial news streams:
- Fine-tuned **FinBERT** on domain-specific financial corpora to score institutional news flow in real time.
- Deployed an API-driven inference service feeding time-series sentiment indicators for systematic strategy integration.

### 5. Empirical Asset Pricing Research
Co-authoring an empirical finance paper titled *"Do Traditional Asset Pricing Models Explain Bank Valuation in Emerging Green Finance Markets?"* (currently under peer review), investigating multi-factor pricing anomalies and valuation dynamics across emerging-market banking equities.

---

## Education & Experience

**ENSIMAG Grenoble INP - UGA (France)** | *2026 – Present*  
Engineering Degree in Financial Engineering and Applied Mathematics *(Double Degree)*  
Relevant Coursework: Stochastic Calculus, Derivatives Pricing, Numerical Methods in Finance, Convex Optimization, Time Series Analysis.  
*Active member of Finance ENSIMAG.*

**ENSIAS — Mohammed V University (Morocco)** | *2024 - 2026*  
Engineering Degree in Digital Engineering for Finance -**Graduated 1st in Class**  
*Head of Training, ENSIAS FinTech Club: Led quantitative workshops on financial modeling, algorithmic trading, and risk management.*

**Industry Experience**
- **Data Scientist Intern** Smart Automation Technologies *(Jul 2025 – Sep 2025)*
- **Data Science Intern** 3D Smart Factory *(Jul 2024 – Sep 2024)*: Automated quantitative financial scoring pipelines in Python and evaluated 50+ early-stage ventures for an investment committee.

---

## Career Objective

I am currently seeking a **3-month internship or gap-year placement starting in 2027** within a front-office, market-making, or systematic investment team as a:
- **Quantitative Developer**
- **Quantitative Trader**
- **Structurer / Quantitative Analyst**

I am particularly interested in roles where mathematical modeling, execution optimization, and high-performance software engineering converge to solve complex pricing and trading problems.

---

## Contact

- **Email:** [soukroumdem777@gmail.com](mailto:soukroumdem777@gmail.com)
- **GitHub:** [github.com/Soukroumde4623](https://github.com/Soukroumde4623)
- **LinkedIn:** [linkedin.com/in/marcellin-soukroumde-889134238](https://linkedin.com/in/marcellin-soukroumde-889134238)
