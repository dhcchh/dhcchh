# Hi, I'm Ding Hao 👋

**Data Engineer** · Python · SQL · dbt

Economics graduate from Singapore Management University, now starting out in data engineering. I came to it from the analytics side, having spent enough time downstream of messy, unreliable data to want to work on the layer that fixes it.

What I'm drawn to is the data infrastructure that machines consume rather than people: feature pipelines behind models, training and evaluation data that's actually reproducible, and the plumbing under experimentation. Dashboards have a human who notices when a number looks wrong. A model retraining on bad features doesn't, which is what makes that side of the problem the harder and more interesting one.

🌐 [Portfolio](https://dhcchh.github.io) · ✍️ [Medium](https://medium.com/@chdinghao) · 💼 [LinkedIn](https://www.linkedin.com/in/dhchan/)

## What I'm working on

Moving from single-node Python into distributed systems, and from batch reporting into infrastructure that serves models and experiments.

- **Distributed processing**: Spark for batch, Flink for streaming, and learning where the boundary between them actually sits.
- **Lakehouse storage**: Iceberg table formats on Hadoop, with schema evolution and time travel that survive contact with production.
- **Real-time OLAP**: Doris and Kudu for the serving layer, where query latency stops being an afterthought.
- **Feature pipelines**: serving the same transformations to training and inference without skew.
- **Experimentation infrastructure**: assignment, exposure logging, and metric pipelines that make an A/B readout trustworthy.
- **Data quality**: contracts, tests, and lineage, since a silent schema change is a model failure nobody sees.

Writing up what I learn on [Medium](https://medium.com/@chdinghao) as I go.

## Tech stack

| | |
| --- | --- |
| **Languages** | Python, SQL |
| **Pipelines** | dbt |
| **Picking up next** | Spark, Flink, Hadoop, Iceberg, Doris, Kudu, Airflow |
| **ML** | scikit-learn, XGBoost, pandas, LangChain / LangGraph |
| **Cloud** | AWS, GCP |
| **Analytics & BI** | Apache Superset, Tableau, Looker, Lightdash |
| **Apps** | Streamlit, Flask |

## Projects

Ordered by how much of the work was engineering rather than analysis.

**[YouTube Customer Insights](https://github.com/dhcchh/youtube-customer-insights)** · `Python` `NLP`\
Ingestion-to-insight pipeline: pulls comments from the YouTube API, cleans and normalises free text, then clusters it into product feedback themes. The interesting part was making the extraction step survive real comment data. [Write-up →](https://medium.com/@chdinghao/nlp-to-decode-customer-frustration-with-coffee-machines-b0317c907fb8)

**[Vessel-Cargo Optimisation](https://github.com/dhcchh/Team-xgboostedv2---SMU_BIA_2026_Datathon)** · `Python` `LangGraph` `Streamlit`\
SMU BIA Datathon 2026. A TCE costing engine with Dijkstra port-distance lookups feeding a Hungarian-algorithm matcher, wrapped in a LangGraph agent that re-runs the optimisation for "what-if" questions.

**[ScoutBot](https://github.com/dhcchh/vct-hackathon-esports-manager)** · `Python` `AWS Bedrock` `Streamlit`\
VCT Esports Manager Hackathon. Player-stat processing pipeline behind a Bedrock-backed scouting assistant, deployed with a Streamlit front-end. [Write-up →](https://medium.com/@chdinghao/vct-esports-manager-hackthon-our-attempt-fbb7a2e37b4c)

**[Inflation Hedging with ETFs](https://github.com/dhcchh/IS428-G2T3-Project-)** · `Python` `Flask`\
IS428. Flask microservices handling data fetching and processing for an ETF portfolio matcher, served to an interactive front-end.

**[SMU BIA Datathon 2025](https://github.com/dhcchh/Team-xgboosted---SMU-BIA-Datathon-2025)** · `Python` `LLMs`\
Structuring unstructured security-threat text for the Internal Security Department (MHA), then surfacing it through dashboards.

**[Credit Card Fraud Detection](https://github.com/dhcchh/Machine-Learning-for-Credit-Card-Fraud-Detection)** · `scikit-learn` `XGBoost`\
End-to-end ML on a heavily imbalanced dataset: resampling, model comparison, and threshold selection.

**[Card Payments Analytics](https://github.com/dhcchh/card-payments-analytics)** · `SQL` `pandas`\
Wise case study on cross-border card economics, weighing interchange and FX revenue against transaction cost.

**[SPY Analytics & Forecasting](https://github.com/dhcchh/SPY-Analytics-Forecasting-Project)** · `Prophet` `LSTM` `XGBoost`\
Long-horizon analysis of index investing: returns, inflation hedging, and forecasting. Written up in three parts: [1](https://medium.com/@chdinghao/spy-analytics-forecasting-part-1-consistent-returns-3cfe49e7b9b5) · [2](https://medium.com/@chdinghao/spy-analytics-forecasting-part-2-hedging-against-inflation-a52a48b9469b) · [3](https://medium.com/@chdinghao/spy-analytics-forecasting-part-3-forecasting-future-returns-3c3cb650beef)

## Get in touch

- 🌐 [dhcchh.github.io](https://dhcchh.github.io)
- 💼 [LinkedIn](https://www.linkedin.com/in/dhchan/)
- ✍️ [Medium](https://medium.com/@chdinghao)
- 📫 [chdinghao@gmail.com](mailto:chdinghao@gmail.com)
