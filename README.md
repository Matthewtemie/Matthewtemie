# Hi ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif) My name is Matthew Temitayo Ilori, but you can call me Temie

## Data Analyst, Data Engineer & ML/AI Engineer

Welcome back to the Data Adventures of Temie, the Wizard of Numbers — now with a few new spells in the book! Step into a world where data doesn't just tell stories, it *predicts* them. I'm Temie, your guide on this thrilling journey through the realms of **data analysis, data engineering, and applied AI**. With my trusty companions — Python, SQL, Power BI, scikit-learn, and the Anthropic Claude API — I uncover hidden treasures buried deep within datasets, engineer pipelines that summon order from chaos, and train models that see patterns no spreadsheet ever could. Marvel at the dashboards I've crafted to surface insights for finance teams, the procurement pipelines I've stitched together for oil & gas analysts, and the AI workflows that read mountains of unstructured documents in seconds. Witness the predictive models I've shipped publicly — Premier League injury risk classifiers, stock-return forecasters, reinforcement-learning agents — every one deployed end-to-end as part of an ongoing **#BuildInPublic** challenge. As a data alchemist, I don't just observe numbers; I turn them into gold — into decisions, forecasts, and intelligent systems that drive real outcomes. So whether the quest is optimising a procurement workflow, predicting financial returns, or unravelling the enigma of football injury risk, let's embark on this thrilling adventure together. The possibilities are limitless, and the insights are boundless!

- 🌍  I'm based in Lagos, Nigeria
- ✉️  You can contact me at [ilorimatthew493@gmail.com](mailto:ilorimatthew493@gmail.com)
- 🚀  Currently shipping daily through September as part of #BuildInPublic

<a href="https://www.github.com/Matthewtemie" target="_blank" rel="noreferrer"><img src="https://img.shields.io/github/followers/Matthewtemie?logo=github&style=for-the-badge&color=0891b2&labelColor=1c1917" /></a>
<a href="https://www.twitter.com/DataTemi" target="_blank" rel="noreferrer"><img src="https://img.shields.io/twitter/follow/DataTemi?logo=twitter&style=for-the-badge&color=0891b2&labelColor=1c1917" /></a>

---

### 💼 Professional Work
*Production data and AI systems built for real organisations. Project names and client identifiers are abstracted under NDA — happy to walk through any of these in more depth in a conversation.*

🛢️ **AI-Powered Cost Benchmarking Platform** · *AI Engineer · Live in production · upstream oil & gas client*
A document-AI and analytics platform that ingests commercial evaluation PDFs, extracts line-item rates with the Claude API, normalises them across currencies and inflation indices, and benchmarks them against a historical price dictionary. Engineered the **two-pass chunked extraction system** for long PDFs, the **Price Dictionary** with P25 / P50 / P75 percentile statistics and confidence scoring, and a **human-in-the-loop review** workflow with full provenance tracking on every record.
**Stack:** Python · Anthropic Claude API · MySQL · prompt engineering · statistical benchmarking

🔗 **SAP Ariba → Power BI Procurement Data Pipeline** · *Data Engineer · Production-ready (Supplier Data) / WIP (Sourcing Reporting)*
End-to-end data engineering pipeline from SAP Ariba's REST APIs into Power BI for procurement analytics. Built **OAuth 2.0** authentication, paginated extraction (**289 suppliers** from the test realm), JSON flattening into clean tabular DataFrames, and architected the **SAP Ariba → SharePoint → Power BI** scheduled-refresh pipeline via GitHub Actions and an Azure AD service principal — no on-prem gateway required.
**Stack:** Python · pandas · OAuth 2.0 · REST + SOAP APIs · Microsoft Graph API · SharePoint · Power BI · GitHub Actions

🏢 **Enterprise Financial Data & Reporting Platform** · *Data Analyst · Live in production · Nigerian energy-sector client*
A financial workflow and reporting platform replacing spreadsheet-and-email processes for budget clearing, contracts, claims, and invoicing. Designed the **17-table financial data model**, dual-currency (NGN/USD) reporting, **Chart.js dashboards** for cycle times and departmental spend, **30/60/90-day expiry alerts** on the contract registry, and a complete **audit log and data governance layer** under a 9-tier RBAC model.
**Stack:** PHP 8 · MySQL · Chart.js · Azure AD SSO · Microsoft Graph API · SharePoint

🚀 **Multi-Tenant Financial Data SaaS** · *AI Engineer (Contributing) · In active development*
A multi-tenant budget and expense management SaaS for African enterprises. Contributing on **AI-agent task orchestration** for sprint deliverables, multi-tenant data architecture validation, and the design system.
**Stack:** Next.js 15 · NestJS · TypeScript · Prisma · PostgreSQL · Redis · Claude Code agents

---

### 🤖 ML & AI Projects — #BuildInPublic
*End-to-end machine learning projects I build, deploy, and write about publicly.*

⚡ **[InjuryWatch](https://injurywatch.onrender.com/)** — Premier League Injury Risk Predictor
XGBoost classifier flagging players at risk of major injuries (90+ days missed) for the 2024-25 season. Trained on 660 player-seasons combining FBref + Transfermarkt data, with **SMOTE** for class imbalance. Compared Logistic Regression, KNN, Random Forest, and XGBoost head-to-head; XGBoost won across every metric.
**Results:** 82.6% accuracy · 88.6% AUC-ROC · 71.6% F1
**Stack:** XGBoost · scikit-learn · SMOTE · pandas · Flask

⚽ **MatchForecast** — Premier League Match Outcome Predictor
Multinomial classification model on real Premier League historical match data. Engineered features around team form, home/away splits, and head-to-head history; returns probabilistic Win / Draw / Loss outcomes.
**Stack:** scikit-learn · Logistic Regression · pandas · Flask

📈 **StockSage AI** — Stock Return Prediction Dashboard
Daily-running predictor that models **percentage returns** rather than raw prices, using **Huber loss** for robustness against financial outliers. Sends daily forecasts via email alerts.
**Stack:** scikit-learn · Alpaca Market API · time series feature engineering · APScheduler

🚕 **Taxi-v3 RL Agent** — Reinforcement Learning From Scratch
Tabular **Q-learning** agent solving OpenAI's Taxi-v3 environment with no prior knowledge. Converges in 2,000 episodes using ε-greedy exploration with decay; delivers passengers in 13 steps (under the 16-step target).
**Stack:** Gymnasium · NumPy · Q-learning · ε-greedy with decay

🐧 **Palmer Penguins** — Unsupervised Clustering Pipeline
End-to-end clustering pipeline: missing-value handling → StandardScaler → K-Means → cluster profiling and visualisation.
**Stack:** scikit-learn · pandas · Matplotlib

🍲 **[NaijaPrep](https://naijaprep-1.onrender.com/)** — AI-Powered Meal Prep Optimizer
LLM-powered meal-planning app for Nigerian professionals. Calculates BMR / TDEE / BMI from user body profile and goals, then generates personalised weekly plans through the Claude API. A practical study in **prompt engineering, token-budget management, and production LLM constraints**.
**Stack:** React + Vite · Flask · Anthropic Claude API

---

### Skills

<p align="left">
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a>
<a href="https://www.r-project.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/rlang-colored.svg" width="36" height="36" alt="R" /></a>
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="36" height="36" alt="TypeScript" /></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a>
<a href="https://www.php.net/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/php-colored.svg" width="36" height="36" alt="PHP" /></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" /></a>
<a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="36" height="36" alt="PostgreSQL" /></a>
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mongodb-colored.svg" width="36" height="36" alt="MongoDB" /></a>
<a href="https://redis.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/redis-colored.svg" width="36" height="36" alt="Redis" /></a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" /></a>
<a href="https://nextjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nextjs-colored.svg" width="36" height="36" alt="Next.js" /></a>
<a href="https://nestjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nestjs-colored.svg" width="36" height="36" alt="NestJS" /></a>
<a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/flask-colored.svg" width="36" height="36" alt="Flask" /></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" /></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="36" height="36" alt="Git" /></a>
<a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/figma-colored.svg" width="36" height="36" alt="Figma" /></a>
</p>

**Data & ML toolkit:** pandas · NumPy · scikit-learn · XGBoost · SMOTE · Matplotlib · Jupyter · Anthropic Claude API · Power BI
**ML techniques:** Logistic Regression · Random Forest · Gradient Boosting · KNN · K-Means · Q-learning · time series modeling · feature engineering · hyperparameter tuning · cross-validation
**AI engineering:** prompt engineering · document AI / extraction · chunked / multi-pass prompting · few-shot design · human-in-the-loop · LLM agent orchestration
**Data engineering & BI:** SQL · ETL pipelines · REST + SOAP APIs · OAuth 2.0 · scheduled refresh / GitHub Actions
**Cloud & enterprise:** Azure AD (SSO) · Microsoft Graph API · SharePoint Online · SAP Ariba · Render

---

### Socials

<p align="left">
<a href="https://www.github.com/Matthewtemie" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /></a>
<a href="https://www.linkedin.com/in/matthewilori" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" /></a>
<a href="http://www.medium.com/@ilorimatthew493" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/medium.svg" width="32" height="32" /></a>
<a href="https://www.twitter.com/DataTemi" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/twitter.svg" width="32" height="32" /></a>
</p>

---

### Badges

<a href="https://github.com/Matthewtemie" align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Matthewtemie&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20%Languages" alt="Top Languages" /></a>

**Top Repositories**

<div width="100%" align="center"></div>
