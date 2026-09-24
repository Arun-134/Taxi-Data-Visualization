# 🚖 Taxi Data Visualization
# 📌 Project Overview
This project analyzes taxi trip data to uncover patterns in fares, distances, tips, and customer behavior. Using Python (Pandas, Matplotlib, Seaborn), the dataset was cleaned, missing values were handled, and multiple visualizations were created to highlight operational and customer insights.

# ⚙️ Steps Performed
## Data Loading

  1.Loaded the taxis dataset from Seaborn.

## Data Cleaning

  1.Imputed missing values:

  2.Numerical columns → median

  3.Categorical columns → mode

  4.Dropped rows with missing critical values (pickup, dropoff, fare).

## Visualizations

  1.Line Chart: Fare trends over time (hourly aggregation).

  2.Bar Chart: Total fare by pickup borough.

  3.Pie Chart: Distribution of trips by payment method.

  4.Histogram: Distribution of trip distances.

  5.Box Plot: Tip distribution by pickup borough.

  6.Count Plot: Number of trips per borough.

  7.Scatter Plot: Relationship between distance and fare, colored by borough.
  
  8.Heatmap: Correlation between numerical variables (distance, fare, tip, tolls, total).

  9.Pair Plot: Pairwise relationships between distance, fare, tip, and total, segmented by pickup zone.

  10.Violin Plot: Fare distribution by payment method.

  # 📊 Key Insights
  --Fare vs Time: Peak hours show higher fares, reflecting demand-driven pricing.

  --Borough Analysis: Manhattan consistently generates higher total fares.

  --Payment Methods: Majority of trips are paid via credit card (~72%), with cash still significant.

  --Distance Distribution: Most trips are short-distance; long-haul trips are rare.

  --Tips: Tip amounts vary widely across boroughs, showing differences in customer behavior.

  --Correlation: Strong positive correlation between distance and fare; weaker correlation with tips.

  --Zone Impact: Pickup zones influence fare and tip variability.

# ✅ Skills Demonstrated
  1.Data Cleaning & Preprocessing

  2.Exploratory Data Analysis (EDA)

  3.Basic & Advanced Data Visualization

  4.Insight Extraction for Business Decision-Making

# 🚀 Conclusion
This project demonstrates how raw taxi trip data can be transformed into actionable insights through systematic cleaning and visualization. The findings can help taxi services optimize pricing, improve customer satisfaction, and allocate resources effectively.
