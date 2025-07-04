# Maryland Traffic Violation Analysis

## 🚦 Summer 2024 Data Science Final Project

**Authors**: Abebaw Tereda, Oscar Javier Soto, and Geremew Belew  
**Course**: CMCS320 - Data Science  
**Semester**: Summer 2024  

---

## 📌 Project Overview

This project focuses on analyzing traffic violation data from Maryland to uncover meaningful patterns, trends, and potential causes behind traffic violations. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/rounak041993/traffic-violations-in-maryland-county), and includes various attributes such as the date and time of the stop, violation type, location, and driver demographics (race, gender, etc.).

Through careful data wrangling, visualization, and analysis, this project aims to:

- Identify the most common traffic violations.
- Discover temporal patterns (e.g., peak hours, days, or seasons).
- Examine geographic hotspots for traffic violations.
- Explore demographic patterns related to violation trends.
- Predict trends using machine learning models.

---

## 📁 Dataset Details

- **File**: `Traffic_Violations.csv`
- **Source**: Kaggle  
- **Attributes Include**:
  - Date & Time of Stop
  - Violation Description
  - Location Information
  - Driver Gender & Race
  - Vehicle Details

---

## 🔧 Technologies & Tools

- **Languages**: Python 3
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation
  - `matplotlib`: Data visualization
  - `scipy.stats`: Statistical testing
- **Environment**: Jupyter Notebook

---

## 📊 Methods & Analysis

### 1. Data Preprocessing
- Loaded CSV data with `pandas`
- Removed or handled null values
- Converted data types as needed
- Extracted meaningful features (e.g., date parts, zip codes)

### 2. Exploratory Data Analysis (EDA)
- Top violations by frequency
- Violation trends by hour, day, and season
- Demographic analysis (gender, race)
- Location-based heatmaps and trends

### 3. Statistical Testing
- Used Z-scores and Chi-Square tests to evaluate correlations
- Highlighted significant deviations in demographic distributions

### 4. Visualization
- Bar plots, pie charts, and histograms for frequency distributions
- Line plots for trends
- Geospatial or categorical plots for regional insights

---

## 📈 Key Findings

- Speeding and failure to obey stop signs are among the most common violations.
- Most violations occur during peak commuting hours.
- Certain racial or gender groups may experience disproportionate stops (statistical significance tested).
- Urban areas see denser violation rates.

---



