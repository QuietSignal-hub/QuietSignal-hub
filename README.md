<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:020617,45:0E2E5C,80:1C3F75,100:00E5FF&height=240&section=header&text=JAYESH%20PATIL&fontSize=64&fontColor=E6FBFF&fontAlignY=40&desc=%2F%2F%20QuietSignal%20%C2%B7%20analyst%20node%20online&descSize=18&descAlignY=62&animation=twinkling" alt="Jayesh Patil" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1100&color=00E5FF&center=true&vCenter=true&width=720&lines=%3E+initializing+QuietSignal...;%3E+Data+%C2%B7+Business+%C2%B7+BI+Analyst;%3E+SQL+%C2%B7+Power+BI+%C2%B7+Tableau+%C2%B7+Python+%C2%B7+R;%3E+Supply+Chain+%26+Operations+Analytics;%3E+turning+messy+data+into+decisions_" alt="Typing intro"/>

<a href="https://jayesh-patil.com"><img src="https://img.shields.io/badge/PORTFOLIO-jayesh--patil.com-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=00E5FF&labelColor=020617" alt="Portfolio: jayesh-patil.com"/></a>
<img src="https://img.shields.io/badge/STATUS-OPEN__TO__WORK-22C55E?style=for-the-badge&labelColor=020617" alt="Status: open to work"/>
<img src="https://img.shields.io/badge/BASE-BOSTON%2C%20MA-1C3F75?style=for-the-badge&labelColor=020617" alt="Base: Boston, MA"/>

```text
░▒▓█  SIGNAL ACQUIRED · ANALYTICS × OPERATIONS × SUPPLY CHAIN  █▓▒░
```

</div>

## 🛰️ `> whoami`

I turn messy operational data into dashboards, forecasts, and decisions. I bring two lenses to every problem: an analyst's and an operator's, so I start with what the business needs to decide.

- 🌐 **Portfolio:** [jayesh-patil.com](https://jayesh-patil.com)
- 🏅 **Lean Six Sigma Green Belt**
- 💼 Previously **Analytics Software Engineering Intern @ Dottir Labs**: reporting requirements and an automated pipeline across 40+ datasets, plus a self-service KPI dashboard
- 🚢 **Logistics analytics**: forecast Suez Canal shipping traffic in Power BI and mapped alternate routes from port coordinates

---

## 🧭 `> trace --signal-path`

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'fontFamily':'monospace','primaryTextColor':'#E6FBFF','lineColor':'#00E5FF','textColor':'#9FB3C8','cScale0':'#0B1B33','cScale1':'#0E2E5C','cScale2':'#12407A','cScale3':'#0E5C7A','cScale4':'#0B7285','cScale5':'#0891B2','cScale6':'#00B8D9','cScaleLabel0':'#E6FBFF','cScaleLabel1':'#E6FBFF','cScaleLabel2':'#E6FBFF','cScaleLabel3':'#E6FBFF','cScaleLabel4':'#E6FBFF','cScaleLabel5':'#E6FBFF','cScaleLabel6':'#03111F'}}}%%
timeline
    title SIGNAL PATH // India → Boston
    2018–2021 : BBA, Marketing : MIT World Peace University, Pune
    2019 : Marketing Intern : Sahyadri Hospitals, Pune
    2021–2023 : MBA, Operations & Supply Chain : Indira Institute of Management
    2022 : Logistics Analytics Intern : Suez Canal route forecasting in Power BI
    2024 : Moved to Boston : MPS in Analytics, Northeastern University
    2026 : Analytics Software Engineering Intern : Dottir Labs, Somerville, MA
    Now : Open to analyst roles : Boston and beyond
```

---

## 💼 `> cat mission.log`

> **`[ 2026 ]` Analytics Software Engineering Intern** · Dottir Labs  
> 📍 Somerville, MA &nbsp;|&nbsp; 🗓️ *Jan 2026 – Apr 2026*  
> <sub>`automated pipeline` · `KPI dashboard` · `40+ datasets` · `detection-threshold reporting`</sub>

> **`[ 2022 ]` Logistics Analytics Intern** · Indira Institute of Management  
> 📍 Pune, India &nbsp;|&nbsp; 🗓️ *May 2022 – Jul 2022*  
> <sub>`Suez Canal forecasting` · `Power BI` · `route mapping` · `trade-impact analysis`</sub>

> **`[ 2019 ]` Marketing Intern** · Sahyadri Hospitals  
> 📍 Pune, India &nbsp;|&nbsp; 🗓️ *Aug 2019 – Dec 2019*  
> <sub>`campaign reporting` · `voice-of-customer analysis`</sub>

---

## 🗂️ `> ls ./projects`
<sub>▸ Click a file to decrypt it.</sub>

<details>
<summary><b>📁 FILE_01 · Pharmacy Claims Data Warehouse</b> &nbsp;·&nbsp; <code>SQL · Data Modeling</code></summary>
<br>

**Problem:** Raw pharmacy claims data wasn't usable for reporting.  
**Approach:** Normalized the data to 3NF and designed a MySQL star-schema warehouse (1 fact table + 4 dimension tables) with primary/foreign keys, then built SQL reporting on drug utilization, cost by age segment, and latest fill per member using CTEs and window functions.  
**Result:** A reporting-ready dimensional model with referential integrity. Found and fixed empty fill records that were inflating utilization counts.  

[View repository →](https://github.com/QuietSignal-hub/pharmacy-claims-data-warehouse)
</details>

<details>
<summary><b>📁 FILE_02 · CRM Profiling & RFM Segmentation (YSSL Inc.)</b> &nbsp;·&nbsp; <code>Segmentation · Data Quality</code></summary>
<br>

**Problem:** 65,000+ grant records (2017–2024) with duplicates and no audience structure.  
**Approach:** Team capstone. My part: profiled and cleaned the source data, applied CPI inflation adjustment, built the RFM profiles and segments, wrote the data-quality and governance package, and built the source-validation layer in the app.  
**Result:** **24,350** unique profiles classified into **4** named audience segments; the top segment (19% of recipients) received 74% of funding.  

[View repository →](https://github.com/QuietSignal-hub/crm-rfm-segmentation)
</details>

<details>
<summary><b>📁 FILE_03 · Traffic Crash Injury Prediction & Archetypes</b> &nbsp;·&nbsp; <code>Python · ML</code></summary>
<br>

**Problem:** Predict crash injury severity and find recurring high-risk crash patterns.  
**Approach:** Team project. My part: IQR outlier cleaning (195,092 → 182,237 rows), EDA, an SVM classifier, and K-means crash archetypes. Caught a capitalization bug that had split 5 severity levels into 10 classes.  
**Result:** Crash archetypes by time, location, and conditions, plus targeted road safety recommendations.  

[View repository →](https://github.com/QuietSignal-hub/Traffic-Crash-Analysis-ML)
</details>

<details>
<summary><b>📁 FILE_04 · Energy Consumption Forecasting</b> &nbsp;·&nbsp; <code>R · Time Series</code></summary>
<br>

**Problem:** Understand what drives building energy use and how it shifts by season.  
**Approach:** GLM regression and ARIMA time-series forecasting, with correlation and seasonal trend analysis.  
**Result:** Key consumption drivers and seasonal impacts identified.  

[View repository →](https://github.com/QuietSignal-hub/Energy-Consumption-Analysis)
</details>

<details>
<summary><b>📁 FILE_05 · Global Energy Trends & Nuclear Analysis</b> &nbsp;·&nbsp; <code>Tableau · Visualization</code></summary>
<br>

**Problem:** Track how global energy production and fuel dependency are shifting.  
**Approach:** Tableau dashboards on production trends, with a focus on nuclear energy's role in sustainability and safety.  
**Result:** A visual view of energy diversification and shifts in fuel dependency.  

[View repository →](https://github.com/QuietSignal-hub/Global-Energy-Trends-and-Nuclear-Analysis)
</details>

<details>
<summary><b>🧪 FILE_06 · LLM Content-Moderation Agent</b> &nbsp;·&nbsp; <code>LLM · Toxicity Detection</code> &nbsp;<code>⏳ IN DEVELOPMENT</code></summary>
<br>

An LLM-based agent for content moderation and toxicity detection. Currently in development; the repository link will appear here once it's published.
</details>

---

## 🛠️ `> lsmod --stack`

**Analytics & BI** &nbsp; <img src="https://img.shields.io/badge/SQL-0A1628?style=flat-square" alt="SQL"/> <img src="https://img.shields.io/badge/Power%20BI-0A1628?style=flat-square" alt="Power BI"/> <img src="https://img.shields.io/badge/Tableau-0A1628?style=flat-square&logo=tableau&logoColor=00E5FF" alt="Tableau"/> <img src="https://img.shields.io/badge/Advanced%20Excel-0A1628?style=flat-square" alt="Advanced Excel"/> <img src="https://img.shields.io/badge/Power%20Query-0A1628?style=flat-square" alt="Power Query"/> <img src="https://img.shields.io/badge/PivotTables-0A1628?style=flat-square" alt="PivotTables"/> <img src="https://img.shields.io/badge/KPI%20Dashboards-0A1628?style=flat-square" alt="KPI Dashboards"/>

**Programming & Visualization** &nbsp; <img src="https://img.shields.io/badge/Python-0A1628?style=flat-square&logo=python&logoColor=00E5FF" alt="Python"/> <img src="https://img.shields.io/badge/R-0A1628?style=flat-square&logo=r&logoColor=00E5FF" alt="R"/> <img src="https://img.shields.io/badge/pandas-0A1628?style=flat-square&logo=pandas&logoColor=00E5FF" alt="pandas"/> <img src="https://img.shields.io/badge/NumPy-0A1628?style=flat-square&logo=numpy&logoColor=00E5FF" alt="NumPy"/> <img src="https://img.shields.io/badge/Matplotlib-0A1628?style=flat-square" alt="Matplotlib"/> <img src="https://img.shields.io/badge/Seaborn-0A1628?style=flat-square" alt="Seaborn"/>

**Machine Learning & Statistics** &nbsp; <img src="https://img.shields.io/badge/scikit--learn-0E2E5C?style=flat-square&logo=scikitlearn&logoColor=00E5FF" alt="scikit-learn"/> <img src="https://img.shields.io/badge/XGBoost-0E2E5C?style=flat-square" alt="XGBoost"/> <img src="https://img.shields.io/badge/Random%20Forest-0E2E5C?style=flat-square" alt="Random Forest"/> <img src="https://img.shields.io/badge/Logistic%20Regression-0E2E5C?style=flat-square" alt="Logistic Regression"/> <img src="https://img.shields.io/badge/SVM-0E2E5C?style=flat-square" alt="SVM"/> <img src="https://img.shields.io/badge/K--means%20%C2%B7%20PCA-0E2E5C?style=flat-square" alt="K-means · PCA"/> <img src="https://img.shields.io/badge/SMOTE-0E2E5C?style=flat-square" alt="SMOTE"/> <img src="https://img.shields.io/badge/ARIMA%20%C2%B7%20GLM-0E2E5C?style=flat-square" alt="ARIMA · GLM"/> <img src="https://img.shields.io/badge/Time%20Series%20Forecasting-0E2E5C?style=flat-square" alt="Time Series Forecasting"/> <img src="https://img.shields.io/badge/RFM%20Segmentation-0E2E5C?style=flat-square" alt="RFM Segmentation"/>

**Data Engineering** &nbsp; <img src="https://img.shields.io/badge/MySQL-12407A?style=flat-square&logo=mysql&logoColor=00E5FF" alt="MySQL"/> <img src="https://img.shields.io/badge/SQLite-12407A?style=flat-square&logo=sqlite&logoColor=00E5FF" alt="SQLite"/> <img src="https://img.shields.io/badge/Star%20Schema-12407A?style=flat-square" alt="Star Schema"/> <img src="https://img.shields.io/badge/Data%20Warehousing-12407A?style=flat-square" alt="Data Warehousing"/> <img src="https://img.shields.io/badge/ETL%20Pipelines-12407A?style=flat-square" alt="ETL Pipelines"/> <img src="https://img.shields.io/badge/Data%20Validation-12407A?style=flat-square" alt="Data Validation"/>

**Business Analysis** &nbsp; <img src="https://img.shields.io/badge/Requirements%20Gathering-0E5C7A?style=flat-square" alt="Requirements Gathering"/> <img src="https://img.shields.io/badge/Process%20Mapping-0E5C7A?style=flat-square" alt="Process Mapping"/> <img src="https://img.shields.io/badge/Gap%20Analysis-0E5C7A?style=flat-square" alt="Gap Analysis"/> <img src="https://img.shields.io/badge/KPI%20Definition-0E5C7A?style=flat-square" alt="KPI Definition"/> <img src="https://img.shields.io/badge/UAT-0E5C7A?style=flat-square" alt="UAT"/> <img src="https://img.shields.io/badge/Agile%20%2F%20Scrum-0E5C7A?style=flat-square" alt="Agile / Scrum"/>

**Operations & Supply Chain** &nbsp; <img src="https://img.shields.io/badge/Demand%20Planning-0B7285?style=flat-square" alt="Demand Planning"/> <img src="https://img.shields.io/badge/Forecasting-0B7285?style=flat-square" alt="Forecasting"/> <img src="https://img.shields.io/badge/Process%20Optimization-0B7285?style=flat-square" alt="Process Optimization"/> <img src="https://img.shields.io/badge/Cost%20%26%20Variance%20Analysis-0B7285?style=flat-square" alt="Cost & Variance Analysis"/> <img src="https://img.shields.io/badge/Lean%20Six%20Sigma%20Green%20Belt-0B7285?style=flat-square" alt="Lean Six Sigma Green Belt"/>

**Tools** &nbsp; <img src="https://img.shields.io/badge/Julia-0891B2?style=flat-square&logo=julia&logoColor=white" alt="Julia"/> <img src="https://img.shields.io/badge/Git-0891B2?style=flat-square&logo=git&logoColor=white" alt="Git"/> <img src="https://img.shields.io/badge/Jupyter-0891B2?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/> <img src="https://img.shields.io/badge/Google%20Colab-0891B2?style=flat-square&logo=googlecolab&logoColor=white" alt="Google Colab"/>

---

## 🎓 `> cat credentials.db`

<table width="100%">
<tr>
<td align="center" width="25%" valign="top">
🎓<br>
<b>MPS in Analytics</b><br>
Northeastern University<br>
<sub>Boston, MA · 2024 – 2026</sub><br>
<sub><i>Statistical Modeling</i></sub>
</td>
<td align="center" width="25%" valign="top">
🎓<br>
<b>MBA, Operations & Supply Chain</b><br>
Indira Institute of Management<br>
<sub>Pune, India · 2021 – 2023</sub><br>
<sub><i>Business Analytics</i></sub>
</td>
<td align="center" width="25%" valign="top">
🎓<br>
<b>BBA, Marketing</b><br>
MIT World Peace University<br>
<sub>Pune, India · 2018 – 2021</sub><br>
<sub><i>Marketing · CSR</i></sub>
</td>
<td align="center" width="25%" valign="top">
🏅<br>
<b>Lean Six Sigma Green Belt</b><br>
Anexas<br>
<sub>Certified</sub><br>
<sub><i>Process improvement</i></sub>
</td>
</tr>
</table>

---

## 📡 `> netstat --community`

- 🏥 **MIT Hacking Medicine GrandHack 2026**: Participant, Portable Health track · *Mar 2026*
- ☁️ **GDG Cloud Boston**: Community member · DevFest Boston attendee (2024–2026) · *2024 – Present*
- 🤖 **AI Agent Workshops**: Agentverse (Google Cloud Labs) · Build with AI Boston · *2024 – 2026*

---

## 🧠 `> query --operator`

```sql
SELECT * FROM analysts WHERE name = 'Jayesh Patil'\G
```
```yaml
        name: Jayesh Patil
      status: OPEN_TO_WORK
target_roles: Data Analyst, Business Analyst, BI Analyst, Supply Chain Analyst
  core_stack: SQL, Power BI, Tableau, Python, R, Excel
   strengths: Requirements gathering, KPI reporting, Forecasting, Process improvement
     domains: Logistics, Healthcare, Operations, Public safety data
  heading_to: Cloud, Data & AI
   portfolio: https://jayesh-patil.com
```

---

## 🎯 `> cat interests.cfg`

<table>
<tr>
<th align="left">🤖 &nbsp;At Work</th>
<th align="left">🎧 &nbsp;Off the Clock</th>
</tr>
<tr>
<td valign="top">AI agents & automation<br>Healthcare analytics</td>
<td valign="top">Music · Movies · Reading<br>Sports</td>
</tr>
</table>

### ⚙️ `> upgrade --queue`

- [ ] ☁️ Google Cloud Data Analytics Certificate *(in progress)*
- [ ] 🛡️ LLM content-moderation agent *(in development)*
- [ ] 🧠 Build an AI agent for data analysis (text-to-SQL)
- [ ] 📊 Power BI DAX → PL-300 certification
- [ ] 🧪 A/B testing & experimentation
- [ ] 🏆 Kaggle competitions: first submission

---

<div align="center">

## 📬 `> open --channel`

<a href="https://jayesh-patil.com"><img src="https://img.shields.io/badge/Portfolio-020617?style=for-the-badge&logo=googlechrome&logoColor=00E5FF" alt="Portfolio"/></a> <a href="https://www.linkedin.com/in/jayeshp-242e/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="mailto:jayeshp7970@gmail.com"><img src="https://img.shields.io/badge/Email-0E2E5C?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a> <a href="https://github.com/QuietSignal-hub?tab=repositories"><img src="https://img.shields.io/badge/Projects-1C3F75?style=for-the-badge&logo=github&logoColor=white" alt="Projects"/></a> <img src="https://gitviews.com/user/QuietSignal-hub.svg?style=for-the-badge&label=Profile%20views&label-color=%230E2E5C&color=%231C3F75" alt="Profile views"/>

<sub>Open to Data Analyst · Business Analyst · BI Analyst · Supply Chain / Operations Analyst roles</sub>

```text
> transmission ended · signal remains open_
```

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:00E5FF,25:1C3F75,60:0E2E5C,100:020617&height=120&section=footer" alt="" width="100%"/>

</div>
