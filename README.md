# 📊 Marketing Funnel & A/B Testing Analysis

## 📌 Business Context
A performance marketing team tested a new campaign (**Test**) against an existing campaign (**Control**) to evaluate whether it improves conversion rate and marketing efficiency.  
The goal is to make a **data-driven decision** on whether the Test campaign should be scaled.

---

## 🎯 Objectives
- Compare **funnel performance** between Control and Test campaigns  
- Measure **conversion efficiency** and **cost effectiveness**
- Perform **statistical A/B testing** on conversion rates
- Provide a **clear business recommendation**

---

## 🧾 Dataset Overview
The dataset contains daily marketing metrics including:
- Impressions
- Website Clicks
- View Content
- Add to Cart
- Purchases
- Spend (USD)

Each row represents **daily campaign performance**, and campaigns are labeled as **Control** or **Test**.

---

## 🔄 Funnel Stages Analyzed
1. Impressions  
2. Clicks  
3. Views  
4. Add to Cart  
5. Purchases  

We analyze both **absolute counts** and **conversion rates** between stages.

---

## 📈 Key Metrics Defined
- **CTR (Click Through Rate)** = Clicks / Impressions  
- **View Rate** = Views / Clicks  
- **Add to Cart Rate** = Add to Cart / Views  
- **Conversion Rate** = Purchases / Clicks  
- **CPC (Cost per Click)** = Spend / Clicks  
- **CPA (Cost per Purchase)** = Spend / Purchases  

---

## 🧪 A/B Testing Methodology
- Statistical Test Used: **Two-tailed Z-test**
- Metric Tested: **Conversion Rate**
- Significance Level (α): **0.05**

### Hypotheses
- **H₀ (Null Hypothesis):** Control Conversion Rate = Test Conversion Rate  
- **H₁ (Alternative Hypothesis):** Control Conversion Rate ≠ Test Conversion Rate  

---

## 📊 Visual Analysis
The following visualizations are used to support the statistical findings:
- Funnel comparison (Control vs Test)
- Conversion rate comparison
- CPC vs CPA comparison
- Funnel drop-off rate analysis

These visuals help identify **where performance diverges** across the funnel.

---

## 🏁 Key Findings (Summary)
- Test campaign generates **higher CTR**
- Test campaign shows **significant drop-off in lower funnel stages**
- Conversion rate of Test is **statistically significantly lower**
- Test campaign has **higher CPA**, making it inefficient

---

## ✅ Final Business Decision
❌ **Do NOT scale the Test Campaign**

**Reason:**
- Lower conversion rate
- Higher cost per purchase
- Statistically significant difference (p < 0.05)

This decision is supported by **both statistical testing and visual analysis**.
