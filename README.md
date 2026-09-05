<div align="center">

# Hi there! I'm Ding Hao 👋

<a href="https://dhcchh.github.io">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=22&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=680&height=45&lines=Data+Engineer;Deeper%2C+not+wider;Java+%C2%B7+Parquet+%C2%B7+Iceberg+%C2%B7+Flink" alt="Data Engineer" />
</a>

<a href="https://dhcchh.github.io"><img src="https://img.shields.io/badge/Portfolio-0B1120?style=for-the-badge&logo=astro&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/dhchan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://medium.com/@chdinghao"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
<a href="mailto:chdinghao@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

I graduated with a BSc Economics from Singapore Management University. I'm currently starting out in data engineering. 
Previously, I came from analytics and spent enough time downstream of messy, unreliable data to want to work on the layer that fixed it

Though my previous roles were "Data Analyst" officially, I have had wide exposure to various data pipelines (Snowflake/Redshift/GCP OLAPs, Airflow, dbt etc) that powered the visualization tools that my dashboards used, i.e. data engineering for human consumption. 

I've come to realise that I enjoy more technically complex work involving streaming pipelines, and data pipelines not just for human consumption, but for various ML/AI algorithms and other machine use cases. 

## What I'm working on

There's quite a fair bit that I don't know but here's some things I am currently learning. 

- **Java and Spring Boot**: the backend stack I use at work, and my way into the JVM that most of the data ecosystem runs on.
- **File formats**: how columnar formats like Parquet and ORC encode, compress, and order data on disk, and what each choice costs at read time.
- **Lakehouse storage**: object storage as the base layer, table formats like Iceberg on top for schema evolution, snapshots, and time travel.
- **Streaming pipelines**: event time, windowing, and state, and the point where streaming earns its complexity over a batch job.
- **Use cases**: matching the system to the workload, down to batch training on a fixed snapshot versus models updating live from a stream.

Writing up what I learn on [Medium](https://medium.com/@chdinghao) as I go.

## Currently reading

- *Fundamentals of Data Engineering* by Joe Reis and Matt Housley
- *Designing Data-Intensive Applications* by Martin Kleppmann

## Tech stack

<div align="center">

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Pipelines**<br>
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)

**Cloud**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)

**Analytics & BI**<br>
![Apache Superset](https://img.shields.io/badge/Apache_Superset-20A6C9?style=for-the-badge&logo=apachesuperset&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=for-the-badge&logo=looker&logoColor=white)
![Lightdash](https://img.shields.io/badge/Lightdash-7262FF?style=for-the-badge)

</div>

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

## Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=dhcchh&theme=transparent&hide_border=true&date_format=j%20M%5B%20Y%5D&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="Contribution streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhcchh/dhcchh/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhcchh/dhcchh/output/snake-light.svg" />
  <img src="https://raw.githubusercontent.com/dhcchh/dhcchh/output/snake-light.svg" alt="Snake eating my contribution graph" width="100%" />
</picture>

</div>

## Get in touch

- 🌐 [Personal Website](https://dhcchh.github.io)
- 💼 [LinkedIn](https://www.linkedin.com/in/dhchan/)
- ✍️ [Medium](https://medium.com/@chdinghao)
- 📫 [chandinghao@yahoo.com](mailto:chandinghao@yahoo.com)
