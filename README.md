<h1 align="center">Hi 👋, I'm Bakdaulet</h1>
<h3 align="center">ML & AI Engineer</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BakdauletBolatA&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

- 🔭 I build data, ML and AI systems and measure whether they actually work: LLM gateways, RAG evaluation, credit scoring, financial models
- 🌱 I'm currently deepening **LLM engineering**, **RAG evaluation** and **machine learning for risk**
- 📫 How to reach me: **bolatbakdaulet2000@gmail.com**

## 🤖 AI & LLM engineering

| Project | What it does | Stack |
|---|---|---|
| [LLM Gateway](https://github.com/BakdauletBolatA/llm-gateway) | One OpenAI-compatible API over Anthropic, OpenAI and Ollama with cost tracking and budget limits. Reliability measured on a mock provider driven by a chaos harness — 11 failure scenarios, not live traffic: success rate 46% → 91%, p95 in a failure storm 20 s → 250 ms | Python, PostgreSQL, Docker |
| [Contract risk screening (Kazakhstan)](https://github.com/BakdauletBolatA/kz-contract-risk) | First-pass review of lease, supply and works contracts for small businesses: finds clauses unfavourable to *your* side, explains the risk in money and days, shows the market norm and a safer wording. Rules + ML + Claude with structured output; on 135 synthetic test contracts the rules reach P 1.00 / R 0.98, and a stress slice shows where they stop working | Python, FastAPI, scikit-learn, Claude, pgvector |
| **RAG evaluation harness** 🔒 | Measurement apparatus for RAG: separates retrieval from generation failures, validates LLM judges, reports bootstrap confidence intervals and robustness to prompt injection. First results on MuSiQue: BM25 finds 42% of the gold paragraphs at k=5, but all hops of a question only 9.6% of the time | Python, BM25, dense retrieval, statistics |
| [Kazakhstan Labour Code RAG](https://github.com/BakdauletBolatA/kz-labor-rag) | Question answering over the Labour Code of Kazakhstan that cites the exact article and clause, or says the Code has no answer. Evaluation harness built before the pipeline; hybrid BM25 + dense search with a cross-encoder reranker raises clause-level recall@5 from 0.84 to 0.94–0.97 on held-out questions over a naive dense baseline | Python, pgvector, Ollama, FastAPI |

## 🧠 Machine learning

| Project | What it answers | Stack |
|---|---|---|
| **Credit risk scoring with text features** 🔒 | Does borrower free text improve default prediction on 278k LendingClub loans, and what is it worth in money? Text adds +0.0009 AUC — real but trivial; rejecting applications earns nothing on a risk-priced book; ranking on expected return beats it by +3.81 pp a year, annualised | LightGBM, SHAP, Streamlit |

## 📈 Data & finance

| Project | What it answers | Stack |
|---|---|---|
| [United Airlines equity research](https://github.com/BakdauletBolatA/ual-equity-research) | HOLD or buy? DCF in three scenarios, reverse DCF and peer multiples from SEC filings, with a live-formula Excel model, report and deck built by scripts | Python, Excel |
| [QuantDesk](https://github.com/BakdauletBolatA/quant-research-desk) | Equity research stack: DCF with Monte Carlo, factor attribution, portfolio allocation and walk-forward backtests | Python, statsmodels, scikit-learn |
| **Northwind SaaS unit economics** 🔒 | Should a SaaS company double its sales team? CAC payback and cash runway by scenario, on synthetic data for a fictional company | Python, pandas, SQLite, Excel |
| [Who does the tenge move with?](https://github.com/BakdauletBolatA/tenge-fx-analysis) | Ruble or oil? National Bank of Kazakhstan exchange rates 2005–2026 tested against popular narratives | Python, Jupyter |
| **SQL e-commerce analytics** 🔒 | Eight business questions on an 11-table online store database, answered in pure SQL | SQL, SQLite |

<sub>🔒 Private repository — code available on request.</sub>

## 🛠 Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=sqlite&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-2C7BB6?style=flat) ![LLM APIs](https://img.shields.io/badge/LLM_APIs-412991?style=flat) ![RAG](https://img.shields.io/badge/RAG-5A45A8?style=flat) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
