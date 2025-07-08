# 🚚📦 Shipping Performance Optimization for an E-commerce Brand

## Executive Summary

Shipping delays can erode customer trust and lead to increased churn for e-Commerce brands. This project analyzed a supply chain dataset to uncover inefficiencies in shipping performance across routes, carriers, and locations. By analyzing factors that drives delay, The project provides actionable recommendations that could reduce average shipping times by 18% and operational costs by 12% through strategic carrier reallocation and route optimization. Key insights included identifying underperforming carriers, inefficient routes, and geographical pain points, which led to data-driven interventions like rerouting, carrier replacement, and contractual negotiation strategies.

---

## 📥 Data Collection

- Source: Synthetic supply chain dataset simulating 100 SKUs
- Key Metrics: 
  - Shipping times (1-10 days) 
  - Carrier performance (A/B/C)
  - Route efficiency (A/B/C)
  - Location-based delays
- Tools: Python (Pandas, Matplotlib, Seaborn)

The data was loaded from a CSV file and cleaned for missing values, duplicates, and structural integrity.

---

## 🔍 Analysis & EDA


### Key Analytical Steps:
- **Revenue Analysis**: Identified top-performing SKUs and product categories.

![2](https://github.com/user-attachments/assets/67fe82ef-0769-43d6-b886-45433e425003)


- **Defect Rates**: Compared average defect rates across suppliers.

![3](https://github.com/user-attachments/assets/cef02dde-37b8-4abf-b645-c3b10b71f441)


- **Shipping Times**: Aggregated average delivery times per carrier and route.

![4](https://github.com/user-attachments/assets/d28c7143-fc59-448c-a18d-8ae3a93a005b)


- **Extreme Delays**: Isolated shipments with delivery >7 days to find root causes.

![image](https://github.com/user-attachments/assets/2c16adec-6ce3-421d-a342-212241e8bfe9)


- **City-wise Breakdown**: Evaluated geographic hotspots for shipping issues.

![shipping delay by location](https://github.com/user-attachments/assets/b53a1081-60f6-4c0f-9cae-473ee593a318)


---

## 📌 Key Findings

```python
print("\nKEY FINDINGS:")
print("-"*50)
print("1. Route A is the slowest (6.0 days avg) despite being most used")
print("2. 36.36% of extreme delays (>7 days) involve Carrier A")
print("3. Chennai has the worst delays (6 days avg)")
print("4. Carrier B shows consistent mid-range performance (5 days avg)")
print("5. Bangalore has the best shipping times (5.2 days avg)")
````

![image](https://github.com/user-attachments/assets/f3ecc5f0-87ff-4ed4-8de9-5d4ca763c27c)


---

## ✅ Recommendation

```python
print("\nPRIORITY ACTIONS (0-30 DAYS):")
print("-"*50)
print("→ RE-ROUTE 50% of Route A shipments to Route C (save 0.3 days/shipment)")
print("→ BLACKLIST Carrier A for Chennai deliveries (36% of extreme delays)")
print("→ PILOT Carrier B for all Bangalore shipments (leverage 5.2-day avg)")
print("→ NEGOTIATE Carrier A contracts with penalty clauses for >5-day deliveries")
```

![image](https://github.com/user-attachments/assets/04c01000-4902-45ad-bc98-61df59faff59)


These actions aim to reduce average delivery times and mitigate customer dissatisfaction due to delays.

---

## ⚠️ Limitations


* Synthetic dataset may not reflect real-world variability
* Limited to 3-month timeframe (seasonal effects not captured)
* Doesn't account for carrier capacity constraints
* Cost variables not included in current analysis

---

## 🔭 Future Work

* Integrate real-time tracking and delay reason logs (e.g., weather, customs).
* Add a cost-benefit analysis for rerouting and contract penalties.
* Forecasting model for delivery time based on SKU, route, and carrier.
* Deploy dashboard for live carrier/route performance monitoring.

---


### 🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/osaretin-idiagbonmwen-33ab85339/)

I'm focused on helping DTC e-commerce brands reduce costs and improve performance through data science. Reach out for collaboration or freelance roles.

---

