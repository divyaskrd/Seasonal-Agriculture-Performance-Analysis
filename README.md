# 🌾 Seasonal Agriculture Performance Analysis

A data-driven analysis of agricultural performance across different seasons, crops, and regions using statistical analysis, data visualization, and exploratory data analysis.

## 📌 Project Overview

Agricultural performance can vary significantly across seasons due to differences in environmental conditions, farming practices, resource usage, and economic factors.

This project analyzes a seasonal agriculture performance dataset to identify:

* Seasonal performance differences
* Crop and regional variations
* Resource and water usage patterns
* Environmental relationships with crop yield
* Economic performance across seasons
* Disease and pest risk patterns
* Significant statistical differences
* Unusual and low-performing patterns

The project uses Python-based data analysis and visualization techniques to generate evidence-based insights and recommendations for seasonal agricultural planning.

---

## 🎯 Objectives

1. Understand and explore the agricultural dataset.
2. Clean and prepare the data for analysis.
3. Analyze agricultural performance across seasons.
4. Identify seasonal patterns and trends.
5. Compare crop and regional performance.
6. Analyze resource and water usage.
7. Study environmental conditions and their relationship with yield.
8. Analyze revenue, cost, and profit.
9. Perform statistical analysis to identify significant differences.
10. Identify unusual patterns and risk conditions.
11. Develop evidence-based recommendations.
12. Document the complete analysis in a Jupyter Notebook.

---

## 📊 Dataset

The dataset contains **4,000 records and 28 attributes** representing agricultural activities across different seasons, geographical areas, farming conditions, resource usage, production, and economic performance.

### Dataset Categories

* 🌱 Farm & Crop Information
* 🌦️ Environmental Conditions
* 💧 Resource & Water Usage
* 🚜 Farming Practices
* 📈 Crop Production
* 💰 Economic Performance
* ⚠️ Disease & Pest Risk

### Key Variables

| Category    | Variables                                                |
| ----------- | -------------------------------------------------------- |
| Location    | State, District                                          |
| Crop        | Crop, Season                                             |
| Environment | Rainfall, Temperature, Humidity, Soil Moisture, Sunlight |
| Soil        | Soil pH, Nitrogen, Phosphorus, Potassium                 |
| Resources   | Fertilizer, Pesticide, Water Used                        |
| Production  | Yield, Production                                        |
| Economy     | Market Price, Cost, Revenue, Profit                      |
| Risk        | Disease/Pest Risk                                        |
| Efficiency  | Water Efficiency                                         |

---

## 🛠️ Technologies Used

### Programming

* Python

### Development Environment

* Google Colab
* Jupyter Notebook

### Data Analysis

* Pandas
* NumPy
* SciPy

### Data Visualization

* Matplotlib
* Seaborn

### Data Format

* CSV

---

## 🔬 Analysis Performed

### 1. Data Cleaning

* Checked dataset dimensions and data types
* Identified missing values
* Checked duplicate records
* Prepared data for analysis
* Preserved missing yield values for appropriate handling during yield-based analysis

### 2. Exploratory Data Analysis

Analyzed the distribution and characteristics of:

* Crops
* Seasons
* Regions
* Environmental conditions
* Resources
* Production
* Economic variables

### 3. Seasonal Performance Analysis

Compared:

* Average Yield
* Average Profit
* Water Efficiency
* Environmental conditions
* Resource usage

### 4. Crop & Regional Analysis

Performed:

* Crop × Season comparison
* State × Season comparison
* Crop performance ranking
* Regional performance comparison
* Heatmap-based analysis

### 5. Resource & Water Analysis

Investigated:

* Water usage
* Water efficiency
* Fertilizer usage
* Nutrient usage
* Irrigation methods
* Relationship between water usage and yield

### 6. Economic Analysis

Analyzed:

* Revenue
* Total cost
* Profit
* Crop profitability
* Seasonal profitability
* Crop × Season economic performance

### 7. Environmental & Risk Analysis

Studied:

* Rainfall
* Temperature
* Humidity
* Soil moisture
* Sunlight
* Soil pH
* Disease/Pest Risk

### 8. Statistical Analysis

Statistical techniques included:

* Pearson correlation
* One-way ANOVA
* Descriptive statistics

---

## 📈 Key Findings

### 🌧️ Seasonal Performance

**Kharif** showed the strongest overall descriptive performance in the analyzed dataset.

| Metric               |  Kharif |   Rabi |    Zaid |
| -------------------- | ------: | -----: | ------: |
| Average Yield (t/ha) |    5.64 |   5.08 |    4.67 |
| Average Profit (₹)   | 179,367 | 88,197 | -26,592 |
| Water Efficiency     |    5.89 |   5.19 |    4.41 |

Kharif recorded the highest average yield, profit, and water efficiency.

### 📊 Statistical Findings

* Seasonal yield differences were **not statistically significant**.
* Seasonal profit differences were **statistically significant**.
* Seasonal water-efficiency differences were **statistically significant**.
* Water usage showed the strongest resource-level association with yield (**r ≈ 0.389**).
* Environmental variables showed weak linear relationships with yield.
* Disease/Pest Risk did not show a statistically significant linear relationship with yield.

> **Note:** Correlation indicates association and does not establish causation.

---

## 🏆 Overall Crop-Season Ranking

A descriptive overall score was created using normalized:

* Yield
* Profit
* Water Efficiency

with weights of:

* Yield: 33%
* Profit: 33%
* Water Efficiency: 34%

### Best Performing Combination

**Sugarcane – Kharif**

Overall Score: **1.000**

### Lowest Performing Combination

**Rice – Zaid**

Overall Score: **0.008**

> The overall score is a project-defined descriptive ranking and is not a statistical significance measure.

---

## 💡 Recommendations

Based on the analysis:

* Consider seasonal differences when planning crop activities.
* Improve water-use efficiency, particularly in lower-performing seasons.
* Optimize agricultural resource utilization.
* Monitor crop profitability across seasons.
* Use regional performance differences to support localized planning.
* Monitor high-risk crop-season combinations.
* Use historical agricultural data to support evidence-based decisions.

---

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── 📓 Seasonal_Agriculture_Performance_Analysis.ipynb
├── 📊 seasonal_agriculture_performance_dataset.csv
├── 📑 Seasonal_Agriculture_Performance_Analysis.pptx
├── 📄 README.md
│
└── 📁 results/
    ├── final_season_kpi.csv
    └── final_crop_season_ranking.csv
```

---

## 🚀 Future Scope

The project can be extended with:

* Machine Learning-based yield prediction
* Seasonal crop recommendation
* Real-time weather data integration
* Satellite and remote sensing data
* Regional-level agricultural prediction
* Smart water and resource optimization
* Interactive dashboards using Power BI or Streamlit
* Intelligent agricultural decision-support systems

---

## 📓 Notebook

The complete analysis is available in the Jupyter Notebook:

**`Seasonal_Agriculture_Performance_Analysis.ipynb`**

The notebook contains the complete workflow from data loading and cleaning to statistical analysis, visualization, findings, recommendations, and conclusion.

---

## 📑 Presentation

The project presentation is available in:

**`Seasonal_Agriculture_Performance_Analysis.pptx`**

---

## 👩‍💻 Author

**Divya Kishor Sapkale**

B.Tech Computer Engineering
Sandip Institute of Technology and Research Centre, Nashik

---

## ⭐ Project Highlights

* 4,000 agricultural records
* 28 attributes
* Seasonal performance analysis
* Crop and regional comparison
* Resource and water analysis
* Economic analysis
* Statistical testing
* Risk pattern analysis
* Evidence-based recommendations
* Complete Jupyter Notebook documentation

---

## 📌 Disclaimer

The findings in this project are based on the analyzed dataset. Observed correlations and seasonal differences should not be interpreted as causal relationships without further experimental or modeling-based validation.
