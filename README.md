# Used Cars Price Prediction with Machine Learning for an Automotive Platform
Predicting Used Cars Price to Support Company's Pricing Strategy and Decisions
---

## **Business Context**

The used-car market in Saudi Arabia is rapidly growing, valued at USD 9.6B in 2024 and projected to reach USD 16.8B by 2033. Over 40% of used-car transactions now occur through digital platforms. Buyers seek transparent, efficient, and good pricing, while sellers need broader market reach and faster sales.

Syarah is one of the largest digital used-car platforms in KSA, operating as a marketplace connecting buyers and sellers, with additional services such as inspection, trade-in, and direct car purchasing.

## **Problem Statement**

On Syarah’s platform, listing prices are fully determined by sellers, often leading to mismatches between listed prices and true market values. This causes slower sales, lengthy negotiations, lower conversion rates, and potential revenue loss. Overpricing discourages buyers, while underpricing reduces seller margin and company profitability.

To stay competitive, the business needs a data-driven pricing model that provides accurate price recommendations based on vehicle specifications.

## **Goals**

* Build a machine learning model to predict used-car prices and support optimal, transparent pricing.
* Identify key factors affecting car prices to support strategic decision-making.

## **Analytical Approach**

1. **Data Understanding**
   Explore data, detect outliers, and perform EDA.

2. **Data Preprocessing & Feature Engineering**
   Clean data, handle missing values, encode categorical features, scale numerical features, analyze correlations, engineer features, and split data.

3. **Machine Learning Modeling**
   Train multiple models, benchmark performance, tune hyperparameters, and select the best-performing model.

4. **Analysis**
   Interpret feature importance, compare actual vs predicted prices, and assess business impact through cost-benefit analysis.

5. **Conclusion & Recommendation**
   Summarize insights and propose pricing optimization strategies.

## **Evaluation Metrics**

This project uses **MAPE** and **MAE**, with MAPE as the primary metric:

* **MAPE:** Average percentage error relative to actual values.
* **MAE:** Average absolute difference between predicted and actual prices.

---

## **Conclusion**

This project successfully developed an XGBoost-based regression model to predict used-car prices in Saudi Arabia. The tuned model achieved a **MAPE of ~19%** and **~MAE 11832 SAR**, indicating reliable accuracy for practical pricing support. Feature importance analysis highlights **Brand Tier** as the strongest driver of price variation.

Cost-benefit evaluation shows that using the model can reduce potential losses by **10.5 M SAR**, demonstrating clear financial value. Overall, the model provides an effective data-driven tool to support more accurate pricing, improve market transparency, and enhance business performance for used-car transactions in Saudi Arabia.

---
