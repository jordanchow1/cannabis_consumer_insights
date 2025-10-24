# Canadian Cannabis Consumer Insights  

This project analyzes Canadian cannabis consumer behaviour by reconstructing data published in Numerator’s Cannabis Consumer Behaviour report.
Using published metrics, I built a dataset of roughly 2,000 individual consumer records to model spending levels, usage frequency, and product preferences.

The goal was to transform high-level industry research into consumer-level insights that inform market segmentation, product positioning, and marketing strategy.

---

## Objectives

- Model consumer-level data from published industry statistics
- Identify distinct behavioural segments in the cannabis market
- Explore relationships between spending, frequency, and product choices
- Demonstrate how data science can translate research metrics into actionable insight

---

## Methodology

1. Data Reconstruction
- I extracted key figures from Numerator’s report—such as average monthly spend and purchase frequency by THC vs. CBD users—and used these as parameters to generate distributions. The dataset simulates ~2,000 consumer profiles balanced between THC and CBD users.

2. Exploratory Data Analysis
- Using Python (Pandas, Matplotlib, Seaborn), I visualized spending and frequency distributions, compared means between groups, and ran statistical tests to understand variability within and across user types.

3. Clustering & Segmentation
- After scaling numeric features, I applied K-Means clustering (k=3) to group consumers into meaningful clusters. Each cluster was then profiled and interpreted from a marketing perspective, with supporting visualizations and descriptive statistics.

4. Insights & Recommendations
- The clustering results were interpreted to build consumer personas and recommend targeted marketing approaches. These insights illustrate how behavioral segmentation can guide brand strategy, pricing models, and campaign planning.

---

## Key Findings & Personas

- Identified **three distinct consumer segments**:
  1. **High-Spend Enthusiasts** — frequent users spending $180+ monthly, primarily purchasing THC flower products  
  2. **Moderate Experimenters** — weekly users with moderate spend ($80–120), often choosing edibles  
  3. **Casual Buyers** — low-spend, infrequent users preferring vapes and oils  

- **Spending and usage frequency** are strongly correlated *(r ≈ 0.78)*, suggesting high-value opportunities in habitual user segments.  
- Product preferences shift toward **edibles and oils** as consumers move from experimental to regular use.  

---

## 💼 Business Implications  
- **Segmentation Targeting:** Enables tailored marketing strategies for high-value consumers based on spend and frequency profiles.  
- **Product Development:** Suggests opportunity for mid-tier product bundles or subscription models for moderate users.  
- **Strategic Insight:** Demonstrates how reconstructed microdata can fill data gaps and support decision-making in emerging markets.

---

## Visual Highlights  

![Scatterplot](https://github.com/jordanchow1/cannabis_consumer_insights/blob/main/monthly-spend-vs-usage-frequency.png)
![Projected](https://github.com/jordanchow1/cannabis_consumer_insights/blob/main/projected_spend.png)
![distribution](https://github.com/jordanchow1/cannabis_consumer_insights/blob/main/spend_distribution.png)
![user_type](https://github.com/jordanchow1/cannabis_consumer_insights/blob/main/user_type.png)

---

## Methodology  

### 1. Data Generation  
- Used published metrics (spending brackets, usage rates, product category shares) from Numerator’s *Modern Cannabis Consumer Behavior* report.  
- Reconstructed consumer-level data distributions (~2,000 rows) to reflect realistic market patterns.  

### 2. Exploratory Analysis  
- Visualized spend, frequency, and product distribution using `matplotlib` and `plotly`.  
- Examined relationships between variables using correlation and clustering.  

### 3. Segmentation  
- Applied **K-Means clustering** to identify consumer groups based on spend and frequency.  
- Profiled each segment and analyzed product preference tendencies.  

### 4. Insights & Validation  
- Compared simulated results to public benchmarks.  
- Extracted business-relevant insights and strategic opportunities.

## Tools
- **Language:** Python 3.10  
- **Libraries:**  
  - `pandas`, `numpy` — data manipulation and random sampling  
  - `matplotlib`, `seaborn`, `plotly` — data visualization and exploratory analysis  
  - `scikit-learn` — clustering (K-Means) and scaling  
  - `scipy.stats` — probability distributions for generating realistic numeric patterns  

---

## 🪜 Next Steps  
- Integrate regional and demographic dimensions using open datasets (e.g., StatCan).  
- Deploy an interactive dashboard using **Tableau** or **Power BI**.  
- Expand clustering features to include psychographics and brand loyalty indicators. 
