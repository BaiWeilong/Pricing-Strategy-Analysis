# Pricing Strategy Analysis for Mobile Phones

## Project Overview

This project focuses on analyzing the relationship between various features of mobile phones and their price ranges. Using exploratory data analysis and statistical techniques, the project identifies key features that significantly influence the pricing of mobile devices, enabling better pricing strategies for manufacturers.

---

## Tech Stack

- **Python**: For data analysis and visualization.
- **Pandas**: For data manipulation and aggregation.
- **Matplotlib & Seaborn**: For creating visualizations and identifying trends.
- **NumPy**: For numerical operations and statistical calculations.

---

## Logic and Solution Approach

### 1. Data Understanding

The dataset includes diverse features of mobile phones, such as:
- `battery_power`: Battery capacity.
- `blue`: Presence of Bluetooth.
- `clock_speed`: Processor clock speed.
- `dual_sim`: Dual SIM support.
- `int_memory`: Internal memory capacity.
- `ram`: RAM capacity.
- `px_height` and `px_width`: Screen resolution.
- `price_range`: Target variable indicating price category (0 to 3).

### 2. Exploratory Data Analysis (EDA)

- Checked for missing values (no missing data found).
- Analyzed distributions and descriptive statistics for key features.
- Identified correlations between features and the price range.

#### Key Observations:
- `ram` shows a strong positive correlation with `price_range`, indicating its significant impact on price.
- Features like `battery_power`, `int_memory`, and screen resolution (`px_height`, `px_width`) also correlate positively with price but to a lesser extent.
- Categorical features like `dual_sim` and `blue` have minimal correlation with price.

### 3. Visualizations

- Created histograms for features like `battery_power`, `ram`, and `px_width` to understand their distributions.
- Generated a heatmap to visualize correlations among features.
- Used boxplots to analyze the relationship between key features and `price_range`.

---

## Results

- **RAM**:
  - The most significant feature influencing price. Phones with higher RAM consistently fall into higher price categories.

- **Battery Power**:
  - Strongly associated with higher price ranges, as customers value longer battery life.

- **Internal Memory**:
  - Larger internal memory positively influences perceived value and pricing.

- **Screen Resolution**:
  - Higher resolution is moderately linked to higher prices, appealing to customers seeking premium visuals.

### Example Insights:
- Phones with 4GB RAM are predominantly in the highest price category.
- Devices with battery power > 1500mAh are more likely to be in higher price ranges.

---

## Recommendations

1. **Focus on High RAM and Battery Power**:
   - Invest in these features to position products in premium price segments.

2. **Segmented Product Offerings**:
   - Offer a variety of models with differing RAM, battery power, and internal memory to target diverse consumer budgets.

3. **Optimize Screen Resolution Costs**:
   - While resolution impacts price perception, its contribution is moderate. Balance quality with cost efficiency.

4. **Differentiation for Competitive Advantage**:
   - Leverage insights to develop feature-complete devices at competitive price points to capture larger market segments.

---

## Future Steps

- Apply machine learning models to predict `price_range` based on features.
- Investigate regional preferences to refine pricing strategies further.
- Explore additional features like camera quality and build materials for enhanced analysis.
