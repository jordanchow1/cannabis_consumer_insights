# Cannabis Consumer Insights  

This project explores Canadian cannabis consumer behaviour by reconstructing and analyzing synthetic microdata inspired by published market research. Using metrics from Numerator’s Modern Cannabis Consumer Behavior report, I simulated around 2,000 individual “consumer” records to model spending levels, usage frequency, and product preferences.

The goal was to turn high-level industry data into consumer-level insights that could inform market segmentation, product positioning, and marketing strategy.

---

## Objectives

- Translate summary statistics from published reports into microdata for deeper analysis

- Explore spending and usage distributions across simulated consumer types

- Use clustering (K-Means) to identify distinct buyer personas

- Generate data-driven insights for product, pricing, and marketing strategies

---

## Methodology

1. Data Reconstruction
I extracted key figures from Numerator’s report—such as average monthly spend and purchase frequency by THC vs. CBD users—and used these as parameters to generate distributions. The dataset simulates ~2,000 consumer profiles balanced between THC and CBD users.

2. Exploratory Data Analysis
Using Python (Pandas, Matplotlib, Seaborn), I visualized spending and frequency distributions, compared means between groups, and ran statistical tests to understand variability within and across user types.

3. Clustering & Segmentation
After scaling numeric features, I applied K-Means clustering (k=3) to group consumers into meaningful clusters. Each cluster was then profiled and interpreted from a marketing perspective, with supporting visualizations and descriptive statistics.

4. Insights & Recommendations
The clustering results were interpreted to build consumer personas and recommend targeted marketing approaches. These insights illustrate how behavioral segmentation can guide brand strategy, pricing models, and campaign planning.

---

## Key Findings & Personas

Three distinct consumer segments emerged from the clustering analysis:

1. Occasional / Budget Users

- Traits: Low purchase frequency (1–2 per month), below-average monthly spend, price-sensitive, often driven by promotions.

- Marketing focus: Value bundles, loyalty incentives, and educational content to encourage repeat purchasing and brand trust.

2. Balanced / Core Consumers

- Traits: Moderate spend and frequency; the largest segment by population share. Predictable purchase cycles and balanced interest in THC and CBD products.

- Marketing focus: Membership programs, personalized recommendations, and cross-category bundles to deepen loyalty.

3. Premium / Heavy Users

- Traits: High-frequency buyers with the highest monthly spend; prefer premium and high-THC products.

- Marketing focus: Premium-tier experiences, early access to new products, and storytelling-driven campaigns to strengthen brand advocacy.

---

## Overall Insights

- **Spending intensity** and **usage frequency** are the most discriminating variables in consumer segmentation.  
- The market displays a **bimodal spending distribution**, suggesting clear differentiation between casual and habitual users.  
- Across all groups, **product format diversification** (e.g., pre-rolls, edibles, oils) influences purchasing frequency more than spend.  
- The simulation framework can be extended to test **pricing elasticity** or **promotion scenarios** across segments.

---

## Marketing Strategies

Based on the identified consumer segments, tailored marketing strategies can be developed to optimize engagement, retention, and conversion across the cannabis market. Each strategy aligns with the behavioral and spending patterns revealed through clustering analysis.

### Strategy Matrix

| **Segment**              | **Primary Objective**                                         | **Key Tactics**                                                                                      | **Success Metrics**                                       |
|---------------------------|---------------------------------------------------------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| **Occasional / Budget Users** | Drive trial and increase purchase frequency                     | Value bundles, discount campaigns, retargeting ads, educational content                              | Redemption rate, repeat purchase rate, average order value |
| **Balanced / Core Consumers** | Deepen loyalty and cross-category engagement                   | Personalized recommendations, memberships, gamified loyalty, THC–CBD cross-promotion                 | Retention rate, LTV, category diversity index             |
| **Premium / Heavy Users**     | Reinforce exclusivity and brand advocacy                       | VIP tiers, premium launches, storytelling campaigns, ambassador programs                             | Repeat purchase frequency, NPS, premium product share     |

### 1. Occasional / Budget Users
**Objective:** Increase purchase frequency and brand familiarity among price-sensitive consumers.

**Tactics:**
- Implement **discount-driven campaigns** (e.g., “buy two, get one free” or limited-time promos) to stimulate trial and repeat purchases.  
- Highlight **affordable entry-level products** through in-store displays and digital advertising.  
- Use **retargeting ads** and **email drip campaigns** to re-engage inactive customers.  
- Develop **educational content** (e.g., beginner guides, responsible use messaging) to foster product understanding and trust.  

**Key Metrics to Monitor:** redemption rates, conversion from trial to repeat, average order value (AOV).

---

### 2. Balanced / Core Consumers
**Objective:** Strengthen loyalty and encourage cross-category purchasing.

**Tactics:**
- Introduce **personalized recommendation systems** powered by purchase data or behavioral analytics to promote relevant add-ons.  
- Offer **membership or subscription programs** with incremental perks (e.g., free delivery, early access to seasonal products).  
- Cross-promote between **THC and CBD categories** to diversify purchase portfolios.  
- Use **loyalty-based gamification** (points, tiers, challenges) to maintain engagement over time.  

**Key Metrics to Monitor:** retention rate, lifetime value (LTV), category diversity index.

---

### 3. Premium / Heavy Users
**Objective:** Enhance exclusivity, brand advocacy, and long-term retention among high-value consumers.

**Tactics:**
- Design **premium-tier experiences** such as invitation-only product launches or private tasting events.  
- Leverage **storytelling and brand craftsmanship** in marketing to emphasize quality and authenticity.  
- Implement **VIP loyalty tiers** offering early access, personalized packaging, or dedicated support.  
- Encourage **user-generated content** and **community building** through ambassador or referral programs.  

**Key Metrics to Monitor:** repeat purchase frequency, customer advocacy (NPS), premium product share.

---

### Cross-Segment Strategies
- **Omnichannel integration:** Ensure consistency between online, mobile, and in-store touchpoints to build seamless experiences.  
- **Data-driven personalization:** Use CRM data and behavioral analytics to deliver relevant product recommendations and targeted offers.  
- **Market feedback loop:** Continuously update persona definitions and strategy effectiveness based on sales and engagement metrics.  

---

By aligning marketing execution with data-informed segmentation, brands can better allocate resources, improve customer experience, and maximize lifetime value across diverse consumer groups.
