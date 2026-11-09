## Enock Mulenga

**Data Scientist | Machine Learning | Data Engineering | MLOps | Generative AI | Python | R | SQL | AWS**

I build data systems and models for decisions that matter. I've spent 9 years in health and development data: health-information pipelines, record linkage, statistical analysis and dashboards for national HIV programmes in Zambia. Before that I worked in banking. I'm now studying for an MSc in Data Science and Advanced Computing at the University of Reading, UK.

[LinkedIn](https://www.linkedin.com/in/enock-mulenga-8472ba137) · [Portfolio](https://mulengasnr.github.io) · Reading, UK

---

### Selected achievements (professional work)
- Analysed **230M+ medical records** with Python, R and STATA to produce intervention reports for health programmes.
- Designed a **Python + Airflow pipeline** loading **1M+ clinical records nightly** into a data warehouse.
- Built a **fuzzy-matching engine** that improved patient-record deduplication accuracy to **99.8%** across **1,600+ facilities**.
- Consolidated three legacy databases into a **PostgreSQL warehouse**, cutting query times from 90 s to 5 s.
- Replaced an enterprise data-profiling tool with an **open-source Python solution**, saving **$100K+** in licensing costs.
- Wrote an enterprise data analysis plan that informed **$30M+** of PEPFAR funding decisions.

*That work used confidential health data, so it isn't public. The projects below use only public or synthetic data and rebuild those skills from scratch.*

---

### Portfolio
| Project | What it shows | Status |
|---|---|---|
| [Hospital readmission risk model](https://github.com/MulengaSnr/readmission-risk-model) | Healthcare ML with patient-grouped validation, calibration, SHAP and a fairness audit. Test set: the top 20% of discharges reaches 39% of readmissions | **Complete** |
| [Readmission model in production](https://github.com/MulengaSnr/readmission-risk-mlops) | The same model as a tested API with a [live demo](https://ca-readmission-api.purplemushroom-33c1d15b.francecentral.azurecontainerapps.io/docs). CI retrains and deploys to Azure on every merge, and monitoring was tested on simulated traffic. MLflow, FastAPI, Docker, GitHub Actions | **Complete** |
| [Patient record linkage pipeline](https://github.com/MulengaSnr/patient-record-linkage) | Finds the same patient across hospital, GP and lab records, with stable IDs, a data-quality gate and a daily Airflow pipeline. Synthetic held-out test, medium errors: finds 96.3% of true matches at 99.9% precision, against 85.8% for exact-match rules. Splink, PostgreSQL, PySpark, Shiny | **Complete** |
| UK public documents assistant (RAG) | LLMs, embeddings, retrieval evaluation | Planned |
| NHS demand forecasting | Time series, backtesting, Streamlit | Planned |
| Policy impact evaluation | Causal inference, difference-in-differences | Planned |
| Credit risk scorecard | Probability of default, calibration, fair lending | Planned |

---

### Tools
**Languages:** Python · R · SQL · STATA
**ML and statistics:** scikit-learn · XGBoost · SHAP · statsmodels · regression and predictive modelling
**Data engineering:** Apache Airflow · PostgreSQL · SQL Server · ETL/ELT · data quality · record linkage
**MLOps and cloud:** Docker · MLflow · Git / GitHub Actions · AWS · Azure (learning)
**BI and visualisation:** Power BI (DAX, Power Query) · Apache Superset · Matplotlib · Plotly

### Background
MSc Data Science and Advanced Computing, University of Reading *(in progress)* · MSc Economics and Finance, University of Lusaka · BA Development Studies and Economics, University of Zambia · Mandela Washington Fellow
