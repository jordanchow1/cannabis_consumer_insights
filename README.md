# Cannabis Consumer Insights  

This project reconstructs and analyzes Canadian cannabis consumer behaviour using synthetic microdata generated from published market research metrics. It replicates core variables such as spending levels, purchase frequency, and product category preferences based on aggregated statistics, then applies data preprocessing, exploratory analysis, and clustering algorithms (e.g., K-Means) to identify distinct consumer segments. The workflow demonstrates how to translate high-level market data into granular behavioral insights, providing a quantitative foundation for market segmentation, pricing optimization, and targeted marketing strategy development.

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

Through simulated consumer-level data and clustering analysis, three distinct cannabis consumer segments were identified, each characterized by unique spending and usage patterns:

### 1. Occasional / Budget Users
- **Profile:** Low spending frequency (1–2 purchases per month) and below-average monthly expenditure.  
- **Behavioral Traits:** Price-sensitive, opportunistic shoppers who purchase smaller quantities or lower-THC products, often driven by promotions or convenience.  
- **Strategic Implications:**  
  - Attract with **value bundles**, **discount programs**, and **introductory product lines**.  
  - Use targeted **digital ads** and **loyalty incentives** to build habitual purchasing behavior.  
  - Potential conversion opportunity through education and trial campaigns.  

### 2. Balanced / Core Consumers
- **Profile:** Moderate frequency and consistent monthly spend; represent the **largest share** of the simulated population.  
- **Behavioral Traits:** Exhibit predictable purchasing cycles, balanced interest across THC and CBD categories, and mid-tier brand loyalty.  
- **Strategic Implications:**  
  - Maintain retention with **membership programs** and **cross-category bundles** (e.g., combining edibles and flower products).  
  - Strengthen brand attachment through **personalized recommendations** and **email marketing**.  
  - Serve as a stabilizing segment for long-term revenue growth.  

### 3. Premium / Heavy Users
- **Profile:** High-frequency purchasers with the **highest monthly spend** and a preference for premium, high-THC products.  
- **Behavioral Traits:** Brand-loyal, experience-driven consumers who prioritize quality and potency over price.  
- **Strategic Implications:**  
  - Focus on **premium product launches**, **limited editions**, and **subscription-style purchasing**.  
  - Promote **exclusive experiences** (e.g., early access, loyalty tiers) to reinforce engagement.  
  - Potential ambassadors for **brand advocacy** and **social marketing efforts**.  

---

## Overall Insights

- **Spending intensity** and **usage frequency** are the most discriminating variables in consumer segmentation.  
- The market displays a **bimodal spending distribution**, suggesting clear differentiation between casual and habitual users.  
- Across all groups, **product format diversification** (e.g., pre-rolls, edibles, oils) influences purchasing frequency more than spend.  
- The simulation framework can be extended to test **pricing elasticity** or **promotion scenarios** across segments.

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
