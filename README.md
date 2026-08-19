## Hi there 👋

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=2E86C1&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Ridwanllah+%F0%9F%91%8B;Data+Analyst+%7C+Analytics+Engineer+%F0%9F%93%8A;Turning+Messy+Data+Into+Decisions+%F0%9F%92%A1;SQL+%7C+Python+%7C+Power+BI+%7C+Warehousing" alt="Typing SVG" />

</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=husainridwan&label=Profile%20Views&color=2e86c1&style=flat" alt="profile views" />
  <a href="https://www.linkedin.com/in/ridwanllah-husain/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:h.ridwan707@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20Out-D14836?style=flat&logo=gmail&logoColor=white" /></a>
</div>

<br/>

## 🧭 About Me

I'm a **Data Analyst / Analytics Engineer** working on risk and lending data at a fast-growing Nigerian fintech, where I turn loan and transaction data into decisions that move real numbers, like helping lift early repayment rates from **54% → 66%** through segmentation and root-cause analysis.

I studied **Electrical & Electronics Engineering** (Second Class Upper Honours), which is probably why I can't look at a messy dataset without wanting to model it, break it down, and rebuild it into something that makes sense.

- 🔭 Just shipped **[NEGA](https://github.com/husainridwan/NigeriaElectricityGridAnalytics)** — a warehouse and Power BI model tracing where Nigeria's grid loses **45% of its energy** between generation and cash.
- 📊 Daily tools: **SQL (PostgreSQL), Python, Power BI, Excel, Metabase**.
- 🌱 Leveling up in **data engineering** (Airflow, dbt, cloud) and **ML explainability**.
- 🎯 Looking to grow into: **Data Analyst → Analytics Engineer / Data Engineer**.
- ⚡ Fun fact: I'd rather find *why* a metric moved than just report *that* it moved.

---

## 🛠️ Tech Stack

<div align="left">

**Languages & Querying**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />

**Data & ML**
<br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge" />
<img src="https://img.shields.io/badge/SHAP-6A5ACD?style=for-the-badge" />

**BI & Visualization**
<br/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
<img src="https://img.shields.io/badge/Metabase-509EE3?style=for-the-badge&logo=metabase&logoColor=white" />

**Engineering & Cloud**
<br/>
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />

</div>

---

## 🚀 Featured Projects

Here's a closer look at the work behind the repos below — what each one does and the skill it's meant to prove. The first two are where I've been spending my time lately: moving data end to end and modelling it properly before anyone builds a chart on top of it.

<table>
<tr>
<td width="50%" valign="top">

### ⚡ [Nigeria Electricity Grid Analytics](https://github.com/husainridwan/NigeriaElectricityGridAnalytics)
Traces where Nigeria's power sector loses value between generation and cash. 24 API endpoints extracted and OCR'd, cleaned through a staging layer into a **Postgres star schema on Supabase**, then modelled in a 3-page **Power BI** report ending in a what-if simulation. Only 55% of generated energy survives to revenue, and the simulation shows why building more plants alone won't fix that.

**[▶ Open the live dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTgzNDBjZjAtMzhkOC00N2Y4LTg3OGQtMmIyODRjYjY4NTM2IiwidCI6ImFjYjY3YTYyLTRiOWQtNDhjZS04MmM0LTYyYjlmMjE2YjM5NyJ9)**

`Python` `PostgreSQL` `Supabase` `Power BI` `ETL` `Data Modelling`

</td>
<td width="50%" valign="top">

### ⚙️ [Automated ETL Pipeline (Airflow)](https://github.com/husainridwan/Data-Pipeline-Using-Airflow)
Orchestrated pipeline that pulls, transforms, and loads real-estate data into a warehouse on a schedule which was built to be reliable and reproducible, not just a one-off script.

`Python` `Apache Airflow` `AWS Redshift` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏦 [Probability of Default Model](https://github.com/husainridwan/ProbabilityOfDefault)
End-to-end credit risk model for a lending business using two segmented models (first-time vs. returning borrowers), built with **LightGBM + Optuna** for tuning, **SHAP** for explainability, and served via **FastAPI** with a **Streamlit** demo.

**[▶ Open the live website](https://defaultpredictorapp.streamlit.app/)**

`Python` `SQL` `Machine Learning` `FastAPI`

</td>
<td width="50%" valign="top">

### ⚽ [EPL Exploratory Analysis](https://github.com/husainridwan/EPL-Exploratory-Analysis)
Exploratory analysis and performance reporting using English Premier League data digging into what actually drives player value.

`Python` `SQL` `Power BI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏠 [Lagos Rent Predictor](https://github.com/husainridwan/lagos-rent-predictor)
Predicts rent prices for houses/apartments across Lagos, an end-to-end project from raw listings to a working price model, tackling the kind of messy, real-world local data that off-the-shelf datasets don't have.

`Python` `Machine Learning` `Data Analytics`

</td>
<td width="50%" valign="top">

### 🎬 [Movie Recommendation System](https://github.com/husainridwan/movie-recommendation-system)
A recommendation engine exploring collaborative filtering to suggest movies based on user behavior patterns.

`Python` `Recommender Systems`

</td>
</tr>
</table>

🌐 And the front door to all of it: **[my portfolio site](https://github.com/husainridwan/portfolio)**, built to give a quick visual walkthrough of the work above.

> 💬 **Why these projects?** Each one was picked to prove a different muscle: end-to-end analytics engineering from raw API to semantic layer (NEGA), production-grade pipelines (Airflow ETL), risk modeling with explainability (PD Model), working with messy local data (Rent Predictor), and pure exploratory storytelling (EPL Analysis).

---

## 📈 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=husainridwan&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=husainridwan&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=husainridwan&theme=tokyonight&hide_border=true" />
</div>

---

## 🤝 Let's Connect

<div align="center">

I'm actively exploring **Data Analyst, Analytics Engineer, and Data Engineer** roles — remote or Lagos-based.  
Always happy to talk data, automating pipelines, or Power BI dashboards.

<a href="https://www.linkedin.com/in/ridwanllah-husain/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:h.ridwan707@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=2E86C1&height=100&section=footer" />
</div>
