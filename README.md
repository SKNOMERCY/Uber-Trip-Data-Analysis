# 🚖 Uber Trip Data Analysis (2016)

## 📌 Project Overview

This project analyzes the **Uber Drives 2016 Dataset** using Python. The objective is to clean the raw dataset, perform feature engineering, conduct Exploratory Data Analysis (EDA), and generate meaningful business insights through data visualization.

The project demonstrates a complete data analytics workflow, from preprocessing raw data to presenting actionable insights.

---

## 🎯 Objectives

- Clean and preprocess the dataset
- Handle missing and duplicate values
- Perform feature engineering
- Explore travel patterns using EDA
- Visualize important trends
- Generate business insights from the data

---

## 📂 Dataset

**Dataset:** Uber Drives Dataset (2016)

### Original Features

- START_DATE
- END_DATE
- CATEGORY
- START
- STOP
- MILES
- PURPOSE

### Engineered Features

- MINUTES    (Trip Duration)
- RoundTrips (Yes / No)
- MONTH      (As numerical)
- MONTHS     (As name)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Converted START_DATE and END_DATE to datetime format
- Standardized column names
- Checked for missing values
- Handled missing values in the PURPOSE column
- Verified and corrected data types

---

## ⚙️ Feature Engineering

Additional features were created to improve the analysis:

- Calculated trip duration (MINUTES)
- Created RoundTrips feature
- Extracted numeric month (MONTH)
- Created month names (MONTHS)

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Monthly Trip Distribution
- Business vs Personal Trips
- Purpose-wise Trip Distribution
- Round Trip Analysis
- Trip Duration Analysis
- Distance (Miles) Distribution
- Correlation Heatmap
- Top Starting Locations
- Top Destination Locations
- Relationship between Trip Duration and Miles

---

## 📈 Key Visualizations

The project includes visualizations such as:

- Trips by Month
- Business vs Personal Categories
- Purpose Distribution
- Round Trip Distribution
- Correlation Heatmap
- Top Start Locations
- Top Stop Locations
- Miles Distribution
- Trip Duration vs Distance

*(Screenshots of these plots can be found in the `images/` folder.)*

---

# 📌 Key Insights

- Business trips account for the majority of rides.
- Cary is the most frequent starting and ending location.
- Meal/Entertainment, Meetings, and Temporary Site Visits are the most common trip purposes.
- Trip duration generally increases as travel distance increases.
- Round trips are observed where the starting and ending locations are the same.
- Monthly ride demand varies throughout the year, with a noticeable peak in December.

---

# ✅ Final Conclusion

Based on the exploratory data analysis of the Uber Trips 2016 dataset, the following insights were obtained:

1. Trip demand peaked in **December**, indicating a noticeable seasonal effect that may be influenced by holidays and year-end travel.

2. Business trips account for the majority of rides, showing that Uber was primarily used for professional purposes in this dataset.

3. Commute, Moving, and Charity trips occur exclusively under the Personal category, indicating a clear distinction between personal and business travel purposes.

4. Office Visits and Airport/Travel rides are recorded only under the Business category, highlighting their professional nature.

5. Monthly trip distribution suggests seasonal variations, implying that holidays, festivals, and business cycles may influence ride demand.

6. A considerable number of trips are round trips where the starting and ending locations are the same.

7. Meal/Entertainment, Meetings, and Temporary Site Visits are the most common trip purposes, reflecting frequent business-related travel.

8. Trip duration generally increases as travel distance increases, indicating a positive relationship between time and distance.

9. Cary is the most frequent starting and ending location, making it the primary travel hub in this dataset.

Overall, this project demonstrates how **data cleaning**, **feature engineering**, and **exploratory data analysis** can be used to extract meaningful insights and identify travel patterns from real-world transportation data.

---

## 📁 Project Structure

```
Uber-Trip-Analytics/
│
├── data/
│   ├── My Uber Drives - 2016.csv
│   └── uber_cleaned.csv
│
├── notebook/
│   └── Uber_Trip_Analytics.ipynb
│
├── images/
│   ├── monthly_trips.png
│   ├── purpose_and_category_distribution.png
│   ├── heatmap_miles_minutes.png
│   ├── heatmap_miles_minutes_month.png
│   ├── round_trips.png
│   └── duration_vs_miles.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/yourusername/Uber-Trip-Analytics.git
```

### Navigate to the project folder

```bash
cd Uber-Trip-Analytics
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 🚀 Future Improvements

- Perform time-series forecasting on ride demand.
- Build an interactive dashboard using Power BI or Tableau.
- Create a Streamlit web application for interactive analysis.
- Apply machine learning models to predict trip duration.
- Analyze geographical travel patterns using maps.

---

## 👨‍💻 Author

**Kavin**

Computer Science Engineering Student  
VIT Vellore

---

## ⭐ If you found this project useful, consider giving the repository a star!