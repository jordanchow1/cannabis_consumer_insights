# Canadian Cannabis Consumer Insights  

This project analyzes Canadian cannabis consumer behaviour by reconstructing microdata inspired by Numerator’s Modern Cannabis Consumer Behavior report.
Using published metrics, I built a dataset of roughly 2,000 individual consumer records to model spending levels, usage frequency, and product preferences.

The goal was to transform high-level industry research into consumer-level insights that inform market segmentation, product positioning, and marketing strategy.

---

## Objectives

- Translate summary statistics from published reports into microdata for deeper analysis
- Explore spending and usage distributions across simulated consumer types
- Use clustering (K-Means) to identify distinct buyer personas
- Generate data-driven insights for product, pricing, and marketing strategies

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

![Scatterplot](https://github.com/jordanchow1/cannabis_consumer_insights/blob/main/monthly-spend-vs-usage-frequency.png)

Three distinct consumer segments emerged from the clustering analysis:

1. Occasional / Budget Users

- Traits: Low purchase frequency (1–2 per month), below-average monthly spend, price-sensitive, often driven by promotions.
- Marketing focus: Value bundles, loyalty incentives, and educational content

2. Balanced / Core Consumers

- Traits: Moderate spend and frequency; the largest segment by population share. Predictable purchase cycles and balanced interest in THC and CBD products.
- Marketing focus: Membership programs, personalized recommendations, and cross-category bundles

3. Premium / Heavy Users

- Traits: High-frequency buyers with the highest monthly spend; prefer premium and high-THC products.
- Marketing focus: Premium-tier experiences, early access to new products, and storytelling-driven campaigns to strengthen brand advocacy.

---

## Overall Insights

- **Spending intensity** and **usage frequency** are the most discriminating variables in consumer segmentation.  
- The market displays a **bimodal spending distribution**, suggesting clear differentiation between casual and habitual users.  
- Across all groups, **product format diversification** (e.g., pre-rolls, edibles, oils) influences purchasing frequency more than spend.  
- The simulation framework can be extended to test **pricing elasticity** or **promotion scenarios** across segments.
