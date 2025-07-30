# 📈 Time Series Visualizer

This project is part of the **freeCodeCamp Data Analysis with Python Certification**.

## 📌 Project Objective

The goal of this project is to visualize time series data using:

* Line chart
* Bar chart
* Box plots

You will use `Pandas`, `Matplotlib`, and `Seaborn` to analyze forum page view statistics from freeCodeCamp.org between **2016-05-09** and **2019-12-03**.

---

## 🗂️ Dataset

**File:** `fcc-forum-pageviews.csv`
**Columns:**

* `date`: Date of the observation (format: YYYY-MM-DD)
* `value`: Number of page views

---

## 📊 Visualizations

### 1. Line Plot

Shows daily page views over time.

* **Title:** `Daily freeCodeCamp Forum Page Views 5/2016-12/2019`
* **X-axis:** Date
* **Y-axis:** Page Views
* **File saved as:** `line_plot.png`

### 2. Bar Plot

Displays average daily page views for each month grouped by year.

* **X-axis:** Years
* **Y-axis:** Average Page Views
* **Legend:** Months (January to December)
* **File saved as:** `bar_plot.png`

### 3. Box Plots

Two box plots:

* **Year-wise:** Trend in page views across years.
* **Month-wise:** Seasonal variation in page views across months.
* **File saved as:** `box_plot.png`

---

## 🧹 Data Cleaning

To remove extreme outliers, the dataset is trimmed:

* Top 2.5% of page views
* Bottom 2.5% of page views

---

## 🛠️ Setup Instructions

1. Clone the repository or download the files.
2. Ensure the following libraries are installed:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the script:

   ```bash
   python main.py
   ```

---

## 📁 Folder Structure

```
.
├── fcc-forum-pageviews.csv
├── main.py
├── time_series_visualizer.py
├── line_plot.png
├── bar_plot.png
├── box_plot.png
└── README.md
```

---

## ✅ Project Requirements from freeCodeCamp

* [x] Import and clean data
* [x] Create a line plot
* [x] Create a bar plot
* [x] Create box plots
* [x] Pass all test cases from `test_module.py`
