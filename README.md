# Cannabis Consumer Insights  

This repository contains an interactive Jupyter Notebook (`cannabis_consumers.ipynb`) that explores consumer behaviour in the cannabis market, using simulated data built on the findings from the **Numerator “Budding behaviors — Cannabis Consumers”** report. The analysis demonstrates how to go from high-level market report metrics to actionable data insights via clustering, visualization, and segmentation.

---

## 🧭 Project Objectives

- Translate summary metrics from a published market research report into simulated microdata for deeper analysis  
- Explore distributional characteristics (spend, frequency) of consumer segments  
- Apply clustering techniques (K-means) to uncover distinct consumer personas  
- Generate insights and recommendations for product strategy, marketing, and segmentation  

---

## 🧠 Methodology & Approach

1. **Report Review & Data Extraction**  
   - Began with the Numerator report’s published metrics (e.g. average monthly spend by THC vs CBD users)  
   - Identified key variables (spend, usage frequency) as foundations for deeper modeling  

2. **Data Simulation / Synthetic Dataset Creation**  
   - Generated synthetic distributions for “Monthly Spend” and “Usage Frequency” based on report means and assumed variances  
   - Combined into a single DataFrame simulating ~2,000 “consumer records” (THC and CBD users)  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions via histograms / density plots  
   - Computed summary statistics (mean, median, standard deviation, etc.)  
   - Conducted hypothesis testing (e.g. t-tests) to assess significance between groups  

4. **Clustering / Segmentation**  
   - Applied **K-Means clustering** (k = 3) on scaled features (spend, frequency)  
   - Mapped cluster assignments back to original units for interpretability  
   - Visualized clusters via scatterplots  

5. **Interpretation & Insights**  
   - Characterized each cluster (e.g. “Occasional / budget”, “Balanced / core users”, “Premium / heavy users”)  
   - Derived marketing / product implications for each persona  
   - Framed a narrative suitable for a business or consumer insights audience  

---

## 📊 Key Findings & Personas

- **Cluster 0 – Occasional / Budget Users**  
  Low spend, low usage frequency; likely CBD-dominant. Ideal for entry-level products or value pricing.

- **Cluster 1 – Balanced / Core Users**  
  Mid spend, regular usage. Mixed THC/CBD usage. Represents the “mainstream consumer” base.

- **Cluster 2 – Premium / Heavy Users**  
  High spend and high frequency. Likely THC-dominant, high value per user. Prime target for premium offerings, subscriptions, or loyalty models.

These segments highlight how cannabis consumers fall into **Value (CBD)**, **Mainstream (Mixed)**, and **Premium (THC)** archetypes — useful for tailoring marketing and product strategies.

---

## 🎯 Marketing Strategies

Based on the identified segments, potential marketing approaches include:  

- **Cluster 0 – Occasional / Budget Users**  
  - Emphasize affordability and accessibility (discounts, entry-level pricing)  
  - Highlight health/wellness positioning for CBD-based products  
  - Use educational campaigns to lower barriers for first-time users  

- **Cluster 1 – Regular / Balanced Users**  
  - Offer loyalty rewards and bundled product deals to drive retention  
  - Showcase versatility (mix of CBD & THC product formats: edibles, flower, vapes)  
  - Focus messaging on everyday integration and balanced lifestyles  

- **Cluster 2 – Premium / Heavy Users**  
  - Launch premium product lines (craft flower, high-end vapes, exclusive strains)  
  - Promote memberships, subscription boxes, or VIP clubs  
  - Build brand identity around exclusivity, quality, and “connoisseur” experiences  

By tailoring strategies to these segments, brands can capture both **volume (budget users)** and **value (premium heavy users)** while maintaining strong engagement with the mainstream base.
