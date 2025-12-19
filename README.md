# Predictive-Model-for-Corporate-Controversy-Financial-Volatility
**Corporate Controversy & Volatility Predictor (NLP)**

Quantifying the "Reputation Risk Premium" in Public Equities
Project Type: MBA Dissertation / Quantitative Research
Domain: Sustainable Investing (ESG), Financial Risk Modeling, NLP
Tech Stack: Python, NLTK/SpaCy, Pandas, Statsmodels (Regression)

**Executive Summary**

Standard financial risk models (like GARCH or standard deviation) rely heavily on historical price action. They often fail to capture "Tail Risk" events caused by non-financial triggers—specifically, corporate scandals and controversies.
This project investigates the link between Firm-Specific Controversy (news sentiment) and Future Stock Volatility. By applying Natural Language Processing (NLP) to alternative data sources, I engineered a predictive model to determine if "Bad News" is a leading indicator of "Market Turbulence."

**The Business Problem**

**The Blind Spot:** Investors often treat ESG (Environmental, Social, Governance) as a moral metric rather than a risk metric.

**The Hypothesis:** Companies with high "Controversy Scores" (negative sentiment spikes) will exhibit higher future volatility than their peers, even if their financials appear stable.

**The Goal:** Build a "Forward-Looking" risk assessment tool that identifies hidden volatility signals before they hit the price.


**Methodology**

**Data Engineering & NLPData Sources:** Ingested alternative data covering corporate news, press releases, and controversy reports.

**Sentiment Analysis:** Utilized NLP techniques to quantify "Controversy Intensity."Tokenization & Filtering: Isolated keywords related to fraud, litigation, environmental spills, and governance failures.

**Scoring:** Assigned a quantitative "Controversy Score" to each firm for specific time windows.

**Statistical Modeling**
**Target Variable:** Realized Volatility (Standard Deviation of Daily Returns).

**Predictors:** Historical Volatility (Control) + Controversy Score (Test Variable).

**Regression Analysis:** Performed OLS Regression to test statistical significance.

**Equation:** $Volatility_{t+1} = \alpha + \beta_1(Volatility_t) + \beta_2(ControversyScore_t) + \epsilon$

**Key Findings**

The Signal exists: The inclusion of Controversy Metrics improved the predictive accuracy of volatility forecasts compared to using financial data alone.
Asymmetric Impact: "Governance" controversies (fraud/executive misconduct) had a stronger correlation with immediate price volatility than "Environmental" controversies.
Investment Implication: Portfolios that filter out high-controversy firms do not just improve "Ethics"—they actively reduce Downside Risk Exposure.

**Author**

Oluwagbenga Gabriel Adediran MBA, Financial Technology & Data Analytics (2025)
