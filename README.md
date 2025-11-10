# Airbnb Data Analysis

## Overview
This project explores and analyzes Airbnb listings to uncover trends, patterns, and actionable insights in the rental market. The analysis includes pricing, room types, neighborhood distribution, and reviews over time.

**Tech Stack:** Python (Pandas, NumPy, Matplotlib, Seaborn), SQL, Power BI, Excel, Jupyter Notebook

---

## Dataset
The dataset contains Airbnb listings information including:  
- Listing ID, Name, Host Name  
- Neighborhood, Room Type  
- Price, Service Fee  
- Number of Reviews, Last Review  

> **Note:** For privacy and size reasons, a sample of the dataset is included. Full dataset can be linked or loaded separately.

---

## Project Steps

### 1. Data Cleaning & Preparation
- Checked for missing values and handled them (`fillna`, `dropna`)  
- Removed duplicates  
- Converted `price` and `service fee` to numeric type  
- Converted `last review` to datetime type  

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics for numeric columns (`df.describe()`)  
- Distribution of listing prices (histogram)  
- Room type distribution (countplot)  
- Listings per neighborhood (horizontal countplot)  

### 3. Relationship Analysis
- Boxplot for **Price vs Room Type** to visualize spread and outliers  
- Analysis of **reviews over time** to detect seasonal trends  

### 4. Insights & Visualization
- Created clear visualizations in **Python (Matplotlib & Seaborn)**  
- Built interactive dashboards using **Power BI** to present actionable insights  

---

## Key Insights
- Entire apartments are generally more expensive than private or shared rooms  
- Manhattan has the highest number of listings; Bronx has the fewest  
- Reviews peak during certain months, indicating seasonal demand  

---

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/Airbnb-Data-Analysis.git

2. Open the Jupyter Notebook:
cd Airbnb-Data-Analysis
jupyter notebook

3. Install required libraries if not already installed:
pip install pandas numpy matplotlib seaborn
Run all cells sequentially.

4. Screenshots

![Price Distribution](images/price_histogram.png)
![Room Type vs Price](images/roomtype_boxplot.png)
![Reviews Over Time](images/reviews_over_time.png)



Author
Diksha Bhul
