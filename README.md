<!-- ![abstract](./abstract_graph.jpg) -->

# Table of Contents
- [Curriculum Vitae](#curriculum-vitae)
- [Tech Stack](#tech-stack)
- [Repositories](#repositories)
- [Bootcamps](#bootcamps)
- [Publications](#publications)

# Curriculum Vitae

[**Curriculum Vitae in English**](./cv_pavel_valov_data_analyst_english.pdf)

[**Curriculum Vitae in Russian**](./cv_pavel_valov_data_analyst_russian.pdf)

Data Analyst / Data Scientist with experience in development, research, and analytics both in industry and academy.
Strong knowledge of SQL, Python, and data analysis.
Honest, responsible, driven, fluent Russian and English proficiency, honed by years of teaching and research.

# Repositories

## Professional development

### Advanced AB-testing
- 

### Data Analyst
- Analyzed novel newsfeed recommendation algorithm, designed to improve the key metric (CTR)
- Performed A/B testing to demonstrate CTR deterioration with a new recommendation algorithm using: transformations of the initial data (Laplace smoothing, Poisson bootstrap, bucket transformation), normality criterias (Shapiro-Wilk, D'Agostino), distribution difference criterias (Student's T-test, Mann-Whitney U-test), SQL, ClickHouse, Python, pandas, matplotlib ([Jupyter Notebook](https://github.com/valovpm/newsfeed_ab_testing/blob/main/newsfeed_ab_test.ipynb))
- Demonstration of increasing of a key metric sensitivity using the linearization method ([Jupyter Notebook](https://github.com/valovpm/newsfeed_ab_testing/blob/main/newsfeed_linearization.ipynb))
- A/A testing to check CTR consistency across different datasets ([Jupyter Notebook](https://github.com/valovpm/newsfeed_ab_testing/blob/main/newsfeed_aa_test.ipynb))
- ETL-pipelines for sending reports to ClickHouse and Telegram using Apache Airflow, Python, SQL ([Airflow Graphs](https://github.com/valovpm/newsfeed_airflow))
    - Pipeline for monitoring and sending a report in case of an anomaly in the metrics ([Graph in Python](https://github.com/valovpm/newsfeed_airflow/blob/main/airflow_anomaly_telegram.py))
    - Pipeline of a report to Telegram on key metrics of two products in different time slices ([Graph in Python](https://github.com/valovpm/newsfeed_airflow/blob/main/airflow_application_telegram.py))
    - Pipeline of a report to Telegram on basic product metrics (DAU, views, likes, CTR) ([Graph in Python](https://github.com/valovpm/newsfeed_airflow/blob/main/airflow_newsfeed_telegram.py))
    - Pipeline for sending a report to ClickHouse about the basic product metrics in different slices ([Graph in Python](https://github.com/valovpm/newsfeed_airflow/blob/main/airflow_clickhouse.py))
- Dashboards for visualization and analysis of key metrics using Apache Superset, ClickHouse, SQL ([Dashboards](https://github.com/valovpm/newsfeed_dashboards))
    - Dashboard for analyzing the abnormal drop in the active audience of the newsfeed ([Dashboard](https://github.com/valovpm/newsfeed_dashboards#dashboard_01))
    - Dashboard for analyzing differences in the behavior of `organic' and `advertising' users ([Dashboard](https://github.com/valovpm/newsfeed_dashboards#dashboard_02))
    - Dashboard for analyzing basic product metrics of the newsfeed (likes, view, CTR, etc.) ([Dashboard](https://github.com/valovpm/newsfeed_dashboards#dashboard_03))
    - Dashboard for analyzing audience metrics of several products (DAU, MAU, WAU, etc.) ([Dashboard](https://github.com/valovpm/newsfeed_dashboards#dashboard_04))

## Publications
- Transferring Pareto Frontiers across Heterogeneous Hardware Environments
    - Designed and published a machine learning approach for approximating and transferring Pareto frontiers of systems' properties across different cloud environments, using Python ecosystem (pandas, scikit-learn, matplotlib)
    - [Repository](https://github.com/valovpm/icpe2020?tab=readme-ov-file#transferring-pareto-frontiers-across-heterogeneous-hardware-environments)
    - [Paper](https://research.spec.org/icpe_proceedings/2020/proceedings/p12.pdf)
    - [Video](https://www.youtube.com/watch?v=fB3WO3q4uLQ)
    - [Slides](https://icpe2020.spec.org/slides/Valov_Transferring.pdf)
- Transferring Performance Prediction Models Across Different Hardware Platforms
    - Designed and published a machine learning approach for generalizing performance prediction models of configurable systems across different hardware platforms, extensively using R (tidyr, dplyr, reshape2, ggplot2, etc)
    - [Repository](https://github.com/valovpm/icpe2017?tab=readme-ov-file#transferring-performance-prediction-models-across-different-hardware-platforms)
    - [Paper](https://research.spec.org/icpe_proceedings/2017/proceedings/p39.pdf)
- Empirical Comparison of Regression Methods for Variability-Aware Performance Prediction
    - Designed and published a machine learning study on comparison of various performance prediction methods, while extensively using R ecosystem (tidyr, dplyr, reshape2, ggplot2, etc)
    - [Repository](https://github.com/valovpm/splc2015?tab=readme-ov-file#empirical-comparison-of-regression-methods-for-variability-aware-performance-prediction)
    - [Paper](https://dl.acm.org/doi/abs/10.1145/2791060.2791069)


<!-- ## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/pavel-valov) -->

<!-- # Обо мне:
Аналитик данных / Ученый по данным с опытом разработки, исследований и аналитики в индустрии и академии.
Уверенное владение SQL, Python, анализом данных.
Честный, ответственный, целеустремленный, свободное владение английским, отточенное годами преподавания и исследований. -->

# Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)

![SQL](https://img.shields.io/badge/-SQL-blue?style=for-the-badge) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white) ![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=azure-devops&logoColor=white)

![LINUX](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)

# 📊 GitHub Stats:
<!-- ![](https://github-readme-stats.vercel.app/api?username=valovpm&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=valovpm&theme=dark&hide_border=false)<br/> -->
![](https://github-readme-stats.vercel.app/api/top-langs/?username=valovpm&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=valovpm&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
