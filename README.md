# AtliQ Grand – Hospitality Data Analysis

## 📌 Project Overview
Analyzing hotel bookings, room categories, and revenue data to uncover the reasons behind **declining market share** and identify growth opportunities.

This Python project utilizes **Pandas ** & ** Matplotlib** for data cleaning, exploratory data analysis, and visualization, delivering actionable insights to improve **occupancy rates and revenue performance** across multiple cities and hotel types.

## 📂 Datasets Used
- `fact_bookings.csv` – Detailed customer booking data
- `fact_aggregated_bookings.csv` – Aggregated booking summaries
- `dim_date.csv` – Calendar dimension
- `dim_hotels.csv` – Hotel details (city, category)
- `dim_rooms.csv` – Room categories and pricing
- `room_category.csv` – Room classification

## 🔍 Analysis Performed
- Data cleaning & preprocessing (removing invalid guest data, handling missing values, detecting outliers).
- Revenue analysis (generated vs realized).
- Booking platform analysis (contribution to overall revenue).
- Room category performance & occupancy patterns.
- Insights on underperforming hotels/cities.

## 🛠 Tools & Libraries
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📊 Key Insights
- Booking platform contribution analysis highlighted which channels bring most revenue.
- Outlier removal improved accuracy of revenue and occupancy analysis.
- Identified underperforming room categories that need pricing/marketing optimization.
- Revealed focus areas to regain **revenue and market share**.

## 🚀 How to Run This Project
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/AtliQ-Grand-Analysis.git
   cd AtliQ-Grand-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook notebooks/AtliQ_Analysis.ipynb
