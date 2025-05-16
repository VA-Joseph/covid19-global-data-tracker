# 🌍 COVID-19 Data Analysis Project

This project is a guided data analysis of the global COVID-19 pandemic, completed as the **final project for Week 8 of the PLP Software Engineering Essentials (Python Module)**. The goal was to apply key Python skills to load, clean, analyze, and visualize real-world data.

## 📊 Dataset

The analysis uses the `owid-covid-data.csv` dataset from [Our World in Data (OWID)](https://ourworldindata.org/coronavirus-source-data), which provides up-to-date COVID-19 case counts, deaths, vaccinations, and more.

Key columns used:
- `date`
- `location`
- `total_cases`, `new_cases`
- `total_deaths`, `new_deaths`
- `total_vaccinations`, `people_fully_vaccinated`
- `iso_code`

## 🧰 Tools & Libraries

- **Python**
- **Jupyter Notebook**
- `pandas` for data handling
- `matplotlib` & `seaborn` for static visualizations
- `plotly.express` for interactive maps
- `numpy` for numerical computations

## 🔍 Project Segments

### 1. Data Collection & Loading
- Source: OWID CSV file
- Loaded using `pandas.read_csv()`

### 2. Data Cleaning
- Focused on three countries: **Kenya**, **India**, and the **United States**
- Removed missing critical values
- Converted date columns to proper datetime format

### 3. Exploratory Data Analysis (EDA)
- Line plots of total cases and deaths over time
- Daily new cases comparison
- Death rate calculations

### 4. Vaccination Analysis
- Trends of total vaccinations
- Percentage of population fully vaccinated

### 5. Choropleth Map (Global Snapshot)
- Visualizes total confirmed cases globally using Plotly
- Snapshot for the **latest date available in dataset**

## 📈 Key Visualizations

- 📉 Total Cases Over Time (Line Plot)
- 🦠 Daily New Cases by Country
- 💀 Total Deaths Over Time
- 💉 Vaccination Progress
- 🗺️ Global Choropleth Map of Total Cases

## 💡 Insights

1. The United States has historically reported the highest number of total COVID-19 cases.
2. India experienced sharp surges but also rapid recovery and high vaccination coverage.
3. Kenya's vaccination rate remains comparatively low, with fluctuations in case reports.
4. Global vaccination efforts increased rapidly post-2021, with notable regional differences.
5. The global death rate fluctuated over time, indicating shifts in variant severity, healthcare responses, and vaccination effectiveness.

## 📁 Project Structure

```
covid19-data-analysis/
│
├── covid19_analysis_project.ipynb       # Jupyter Notebook with full analysis
├── owid-covid-data.csv                  # Dataset used for the project
├── covid19_analysis_project.pdf         # PDF version of the notebook
├── README.md                            # This file
└── requirements.txt                     # Optional (list of Python dependencies)
```

## 📌 Requirements

You can install the required libraries with:

```bash
pip install pandas matplotlib seaborn plotly
```

Or use the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Open `covid19_analysis.ipynb` in **Jupyter Notebook**.
2. Run all cells from start to finish (recommended: Kernel → Restart & Run All).
3. Interact with visualizations and read embedded markdown insights.

## 📃 License

This project is for educational purposes under the PLP Scholarship Program.
