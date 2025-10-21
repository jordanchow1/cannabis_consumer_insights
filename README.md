# Cannabis Consumer Insights  

This project explores Canadian cannabis consumer behaviour by reconstructing and analyzing synthetic microdata inspired by published market research. Using metrics from Numerator’s Modern Cannabis Consumer Behavior report, I simulated around 2,000 individual “consumer” records to model spending levels, usage frequency, and product preferences.

The goal was to turn high-level industry data into consumer-level insights that could inform market segmentation, product positioning, and marketing strategy.

---

## Project Objectives

- Translate summary metrics from a published market research report into simulated microdata for deeper analysis  
- Explore distributional characteristics (spend, frequency) of consumer segments  
- Apply clustering techniques (K-means) to uncover distinct consumer personas  
- Generate insights and recommendations for product strategy, marketing, and segmentation  

---

## Methodology & Approach

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

## Key Findings & Personas

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
