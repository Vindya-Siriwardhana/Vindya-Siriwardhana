<h1 align="center">Hi 👋, I'm Vindya Siriwardhana</h1>
<h3 align="center">Data Analyst | Data Scientist | Turning Data into Actionable Insights</h3>

---
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Vindya%20Siriwardhana&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:83a6ff,100:b98cff&height=200&section=header&text=Data%20Analyst&fontSize=50&fontColor=fff&animation=fadeIn" />

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_GITHUB_USERNAME
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
            dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
---

## 🚀 About Me

I'm an analytical professional with dual master's degrees in **Applied Statistics** and **Data Science**, passionate about transforming complex data into strategic business insights. With proven expertise in statistical modeling, machine learning, and data-driven decision making, I've successfully optimized operations across research, manufacturing, and business environments.

- 🔭 I'm currently working at **CLINSTATS LTD** as a Data Analyst
- 🌱 I'm currently expanding my expertise in **Advanced Machine Learning, Deep Learning & Cloud Analytics**
- 🎓 Dual Master's degrees: **MSc Data Science (University of Essex)** & **MSc Applied Statistics (University of Colombo)**
- 💼 **4+ years** of professional experience in data analysis and analytics
- 📊 Successfully reduced data processing time from **2 days to 4 hours** through automation
- 🎯 Specialized in **Statistical Modeling, predictive modeling, Time Series Forecasting & Business Analytics**
- 📫 How to reach me: **asvindyaravi@gmail.com**
- 📍 Based in **Stevenage, UK**

---

🛠️ Technical Skills
Programming Languages
<p align="left">
<a href="https://www.python.org" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
</a>
<a href="https://www.r-project.org/" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/r/r-original.svg" alt="r" width="40" height="40"/> 
</a>
</p>
Data Analysis & Machine Learning
<p align="left">
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> 
</a>
<a href="https://numpy.org/" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" alt="numpy" width="40" height="40"/> 
</a>
<a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> 
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> 
</a>
<a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> 
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> 
</a>
</p>
Deep Learning Frameworks
<p align="left">
<a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> 
  <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> 
</a>
<a href="https://pytorch.org/" target="_blank" rel="noreferrer"> 
  <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> 
</a>
</p>
Database Systems
<p align="left">
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> 
</a>
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> 
</a>
</p>
Tools & Platforms
<p align="left">
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> 
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> 
</a>
<a href="https://jupyter.org/" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="40" height="40"/> 
</a>
</p>
Core Competencies

Statistical Modeling & Regression Analysis
Hypothesis Testing & A/B Testing
Time Series Forecasting (ARIMA, Prophet)
Exploratory Data Analysis (EDA)
Machine Learning & Predictive Modeling
Data Visualization (Tableau, Power BI, Matplotlib, Seaborn)
Database Management (MySQL, PostgreSQL)
---

## 💼 Professional Experience

### 🔹 Data Analyst | CLINSTATS LTD
**October 2022 – Present | Part-time**
### 🔹 Assistant Research Manager | State Timber Corporation, Sri Lanka
**February 2017 – April 2021**
### 🔹 Statistical Programmer | Gestetner of Ceylon Plc
**October 2016 – January 2017**

---

## 📊 Featured Projects

### 🔸 ARIMA and Machine Learning for Predicting Climate Metrics in England
- Developed time series forecasting models for climate prediction - Applied ARIMA methodology and machine learning algorithms - Achieved high accuracy in predicting climate metrics for England - **Tech Stack:** Python, ARIMA, Machine Learning, Statistical Modeling

### 🔸 Data-Driven Customer Segmentation Analysis
- Developed clustering algorithms identifying distinct customer segments - Applied advanced feature engineering improving model performance by **25%** - Created interactive visualization dashboard for business insights - **Tech Stack:** Python, Scikit-learn, Pandas, Tableau

### 🔸 Time Series Forecasting for Resource Optimization
- Built ARIMA and Prophet models forecasting resource demands with **87% accuracy** - Designed automated anomaly detection alerting system - Optimized resource allocation through predictive analytics - **Tech Stack:** Python, ARIMA, Prophet, Statistical Modeling

### 🔸 Classification of Timber Species in Sri Lanka
- Applied statistical classification methods to timber strength properties - Developed predictive models for timber species identification - Conducted comprehensive statistical analysis and validation - **Tech Stack:** R, Statistical Classification, Data Analysis

---

## 🏆 Key Achievements

- ✅ Improved data collection efficiency by **30%** through statistical methodology redesign
- ✅ Reduced data processing time by **92%** (from 2 days to 4 hours) via automation
- ✅ Achieved **15% cost savings** in resource allocation through data-driven initiatives
- ✅ Developed forecasting models with **87% accuracy** for resource optimization
- ✅ Enhanced model performance by **25%** through advanced feature engineering
- ✅ Successfully completed dual master's degrees in Data Science and Applied Statistics

---

## 🤝 Connect with Me

<p align="left">
<a href="https://www.linkedin.com/in/vindya-siriwardhana/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:asvindyaravi@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
</p>

---

## 💡 What I'm Currently Learning

- 🧠 Advanced Deep Learning Architectures
- ☁️ Cloud Computing for Data Science (AWS, Azure)
- 📊 Real-time Data Analytics and Streaming
- 🤖 MLOps and Model Deployment Best Practices
- 📈 Advanced Time Series Forecasting Techniques

---

## 🌟 Fun Facts

- 🎯 Successfully founded and managed **Liya Holding Pvt Ltd**, applying data-driven strategies to business operations
- 🌱 Active volunteer promoting statistics education in local schools in Sri Lanka
- 🌍 Experienced working across multiple industries: Biotechnology, Manufacturing, Apparel, and Research
- 💼 Authorized to work in the UK

---

<p align="center">
  <i>⭐️ "Data is the new oil, but analytics is the combustion engine." - Let's turn your data into fuel for success!</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</p>

---

⭐️ From [Vindya Siriwardhana](https://github.com/YOUR_GITHUB_USERNAME)
