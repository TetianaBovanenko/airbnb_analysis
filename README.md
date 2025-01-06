# Airbnb Data Analysis for Paris

![Airbnb Logo](https://github.com/TetianaBovanenko/airbnb_analysis/blob/main/airbnb_logo_4things.png?raw=true)

## 📋 Overview
This project analyzes Airbnb listings data in **Paris** to uncover insights about pricing, neighborhood trends, and market dynamics. By leveraging Python's data analysis libraries, this project aims to assist Airbnb hosts and potential investors in making data-driven decisions.

---

## 🎯 Objectives
1. Analyze price variations across neighborhoods in Paris.
2. Understand the relationship between accommodation capacity and pricing.
3. Explore trends in new Airbnb hosts and pricing over time.
4. Provide actionable insights for hosts to optimize their listings.

---

## 🛠️ Methodology
1. **Data Preparation:**
   - Loaded the Airbnb listings dataset.
   - Filtered data to include only Paris listings.
   - Selected relevant columns such as `host_since`, `neighbourhood`, `price`, and `accommodates`.

2. **Data Analysis:**
   - Grouped listings by neighborhood to calculate average prices.
   - Analyzed pricing trends based on accommodation capacity in premium neighborhoods.
   - Resampled data to observe trends in new hosts and average prices over time.

3. **Visualization:**
   - Created bar charts to highlight price variations by neighborhood and accommodation capacity.
   - Plotted time series trends for new hosts and average prices.
   - Used dual-axis charts for visualizing correlations between metrics.

---

## 📊 Results

### Price Variation Across Neighborhoods:
- Significant differences were observed in average prices across Paris neighborhoods.
- **Elysee** and similar premium areas commanded the highest prices, while others offered more budget-friendly options.

### Impact of Accommodation Capacity:
- Larger properties accommodating more guests had higher average prices, particularly in neighborhoods like **Elysee**.

### Trends Over Time:
- A steady increase in new Airbnb hosts was observed, indicating a growing market.
- Average prices showed fluctuations, suggesting seasonal or market-driven variations.

### Correlation Between New Hosts and Prices:
- Increased competition among hosts led to slight declines in average prices during certain periods.

---

## 📈 Visualizations
The following visualizations were created to support the analysis:
1. **Average Price by Neighborhood**:
   - Horizontal bar chart showing average prices across Paris neighborhoods.
2. **Price by Accommodation Capacity**:
   - Horizontal bar chart highlighting average prices based on the number of guests.
3. **Trends Over Time**:
   - Line charts showing trends in new hosts and average prices over the years.
4. **Dual-Axis Trends**:
   - Combined line chart showcasing the relationship between new hosts and average prices.

---

## 🚀 How to Run the Project
### Prerequisites:
- Python 3.8 or above
- Required Python libraries:
  - `pandas`
  - `matplotlib`
  - `numpy`
  - `seaborn`

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/airbnb-paris-analysis.git

2. Navigate to the project directory:
   ```bash
   cd airbnb-paris-analysis

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook airbnb_analysis.ipynb
