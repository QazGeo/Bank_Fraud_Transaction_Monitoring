# Power BI Capstone Project – Power BI Bank Fraud Transaction Monitoring Dashboard
## **Executive Summary**

Fraudulent banking transactions pose a growing threat to financial institutions, with over **74% of U.S. banks affected** by such activities. Many cases remain undetected or are flagged too late due to the limitations of conventional rule-based detection systems. This capstone project addresses that gap by introducing an advanced, anomaly-based fraud detection model built using Power BI and predictive techniques.

The project not only cleans and visualizes banking transaction data but compares traditional bank-flagged fraud detection with a custom hybrid model that uncovers undetected fraud through deeper behavioral patterns and anomaly scoring. The results demonstrate a substantial potential for fraud mitigation, reduced financial losses, and improved investigative insight.

## **Business Problem**

Banks often rely on static, rule-based fraud detection systems that are reactive rather than predictive. This leaves them vulnerable to evolving fraud tactics that operate outside of predefined thresholds—particularly those exploiting off-peak hours, regional vulnerabilities, or subtle behavioral anomalies.

The institution in question flagged only **68 out of 5,001 transactions** (\~1.34%) as fraudulent. Our model revealed the possibility of **hundreds more undetected anomalies**, pointing to a significant exposure in current operations.

## **Proposed Solution**

This project delivers a **Power BI–driven hybrid fraud detection model** capable of:

* Comparing real fraud cases with anomalies the bank missed
* Enhancing accuracy with **location and time-based risk signals**
* Providing **drill-through capabilities** for fraud analysts to investigate patterns at the transaction level
* Enabling mitigation and policy refinement based on data-backed insights

Through interactive dashboards and clear KPIs, the solution provides both operational and strategic decision-makers with a real-time window into high-risk behaviors.

---

## **Objectives**

* Build a comparative dashboard to evaluate current fraud detection methods
* Develop a more sensitive model that uncovers missed fraud
* Reduce financial losses through early fraud detection
* Provide explainable, location- and time-aware fraud scoring
* Empower fraud investigators with detailed insights and drill-through features

---

## **Key Results & Insights**

| Metric             | Bank Detection | Hybrid Model                      |
| ------------------ | -------------- | --------------------------------- |
| Fraud Transactions | 68 (1.34%)     | 232 (4.63%)                       |
| Real Fraud Value   | \$468,000      | Improved Accuracy                 |
| Affected Customers | 207+           | More Inclusive Coverage           |
| Estimated Loss     | \$1.17M        | Reduced to \$608K post-mitigation |
| Mitigation Effect  | —              | 49.57 custom units                |

### **Top Insights:**

1. **Undetected Fraud Patterns:** The bank flagged \~1.34% of transactions, while the hybrid model surfaced a much higher fraud likelihood through anomaly detection.
2. **Temporal and Spatial Trends:** Fraud incidents are significantly higher during off-business hours (e.g., 3 AM in major cities), suggesting a behavioral attack vector.
3. **Demographic Gaps:** Certain flagged transactions lacked full demographic details, revealing a blind spot in current customer profiling.

---

## **Return on Investment (ROI) Estimate**

While exact monetary returns depend on institutional scale, implementing the hybrid model has the potential to:

* **Reduce fraud losses by \~48%** based on the mitigation effect observed
* **Save an estimated \$560,000** in prevented fraud across the test data (\$1.17M → \$608K)
* **Decrease manual review time** by enabling visual investigation tools and anomaly scoring
* **Improve regulatory compliance and customer trust** through enhanced fraud detection transparency

---

## **Key Features and Capabilities**

* **Star Schema Data Model** with **Row-Level Security (RLS)**
* **30+ custom DAX measures** powering dynamic KPIs
* **Drill-through and parameterized filtering**
* **Fully responsive layout for desktop and mobile users**
* **Visual comparison between models and post-mitigation impact**

---

## **Implementation Value**

This solution is deployable in real-world bank environments using Power BI Service or embedded platforms. It requires no major infrastructure overhaul and can integrate with existing fraud detection logs or transaction databases. Moreover, the dashboard supports explainability and internal audit use through transparent scoring models and traceable metrics.

---

## **Conclusion**

This capstone project demonstrates how **data science and business intelligence** can dramatically improve fraud detection performance. By moving beyond static rules and embracing contextual, data-driven models, banks can proactively identify and mitigate fraud, improve customer security, and strengthen their operational resilience.

Our dashboard is not just a reporting tool—it is a **strategic instrument** for fraud prevention and risk management in the modern financial landscape.

---

