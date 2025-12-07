**Airbnb Trends & Pricing Analysis – NYC 2024
 Project Overview**

This project performs an extensive Exploratory Data Analysis (EDA) on the 2024 New York City Airbnb dataset to uncover patterns in pricing, availability, demand, location dynamics, and host behavior.
Using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn, the project demonstrates strong data-cleaning, visualization, and analytical capabilities.

**Objective**

The main goals of this project are to:

Analyze room types, prices, and availability across NYC neighborhoods.

Understand host behaviour, listing patterns, and review trends.

Detect outliers and anomalies in pricing.

Provide actionable insights for both hosts and guests.

Suggest data-driven optimization strategies for pricing and occupancy.

 **Dataset Information**

The dataset consists of 20,765 listings and 22 features, including:

id – Unique listing ID

name – Listing title

host_name – Host’s name

neighborhood_group – NYC borough

latitude / longitude – Location coordinates

price – Nightly cost

room_type – Type of property

reviews_per_month – Review frequency

availability_365 – Free days per year

**Workflow & Steps**
**1. Data Cleaning**

Handled missing values (e.g., price, beds, neighborhood).

Converted date columns like last_review to datetime format.

Removed extreme price outliers (>$1000) to keep visualizations meaningful.

**2. Exploratory Data Analysis (EDA)**
**Room Type Distribution**

Majority listings = Entire home/apt

Private rooms offer budget-friendly options.

**Neighborhood Group Analysis**

Manhattan shows highest prices and strongest demand.

Brooklyn follows as a popular mid-range option.

 **Price Distribution**

Most listings fall between $50 – $300.

**Availability & Reviews**

Listings with high availability tend to charge less.

More reviews generally indicate better guest experiences.

**Host Behavior**

Identified hosts with multiple listings → commercial hosting trend.

Visualizations included:
✔ Histograms
✔ Boxplots
✔ Bar plots
✔ Heatmaps
✔ Pair plots

**Key Insights & Business Outcomes**
**1. Price Optimization**

Insight: Strong correlation between price, beds, and room type.
Solution: Entire homes can charge premium rates; pricing can be optimized by number of beds.

**2. Availability Management**

Insight: Price and availability are negatively correlated.
Solution: Lower prices for high-vacancy listings or improve amenities to justify higher pricing.

**3. Neighborhood-Based Revenue**

Insight: Clear clustering patterns across NYC boroughs.
Solution: Premium pricing for Manhattan/Brooklyn; competitive pricing for Queens/Bronx.

**4. Guest Reviews Influence**

Insight: Well-reviewed listings can charge higher prices.
Solution: Improve guest experience → higher reviews → premium pricing.

**5. Room Type Profitability**

Insight: Entire homes generate most revenue; private rooms offer affordability.
Solution: Hosts should invest based on demand patterns for each room type.

**6. Outlier Detection**

Insight: Found price outliers > $15,000.
Solution: Remove unrealistic values for analysis; treat luxury listings separately.

**7. Minimum Stay Optimization**

Insight: Minimum nights correlate with demand.
Solution: Adjust minimum stay rules based on neighborhood demand.

**8. Data Quality Improvements**

Insight: Missing values and duplicates impacted accuracy.
Solution: Cleaned dataset for reliable analytics.

**How to Run This Project**
Clone the Repository
git clone https://github.com/shivaraj2705/Airbnb-Trends-Pricing-Analysis-NYC-2024

Install Dependencies
pip install pandas numpy matplotlib seaborn

Run the Notebook
jupyter notebook Airbnb_EDA_Project.ipynb


**Future Enhancements**

Build a machine learning price prediction model.

Perform sentiment analysis on guest reviews.

Create a Plotly/Talend/Tableau interactive dashboard for real-time Airbnb analytics.



**Author & Contact**

Author: Shivaraj Neelannavar
GitHub: https://github.com/shivaraj2705
LinkedIn: https://www.linkedin.com/in/shivaraj-neelannavar-83069129a/
Repository: https://github.com/shivaraj2705/Airbnb-Trends-Pricing-Analysis-NYC-2024

