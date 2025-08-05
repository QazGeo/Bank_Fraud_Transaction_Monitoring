# Power BI Capstone Project – Power BI Bank Fraud Transaction Monitoring Dashboard
## **Executive Summary**

Fraudulent transactions cost financial institutions millions in daily losses. In this project, we identified that the bank’s existing model was flagging fraud inaccurately, resulting in an **estimated daily loss of \$1.7 million**.

Through **performance tuning and model optimization**, we designed and deployed a **hybrid anomaly detection model** that integrates location, time, and behavioral features to improve fraud prediction accuracy. As a result, the revised model **reduced the average daily fraud loss to \$608,000**, saving over **\$1 million per day** and demonstrating the immense value of data-driven fraud mitigation.

---

## **Business Problem**

Traditional fraud detection systems operate with rigid rule-based thresholds and static criteria. This often leads to:

* Low fraud detection coverage
* High false negatives (undetected fraud)
* Poor adaptation to changing fraud patterns

In our case, the original bank system detected only **68 fraud cases out of 5,001 transactions** (\~1.34%), failing to flag hundreds of high-risk transactions and incurring daily fraud losses nearing **\$1.7 million**.

---

## **Proposed Solution**

We applied **iterative model refinement and performance tuning** using enhanced anomaly detection logic. The revised model was validated using a combination of:

* **Hybrid anomaly scores**
* **Demographic segmentation (age/gender)**
* **Transaction metadata (location, time of day)**
* **Probability scoring**

This tuned model significantly improved fraud detection precision and recall, outperforming the baseline by a wide margin.

---

## **Objectives**

* Tune fraud detection model for higher precision and recall
* Detect missed fraudulent activities using non-linear signals
* Reduce false negatives to protect revenue and improve trust
* Lower business losses
* Empower fraud teams with interactive dashboards for faster triage

---

## **Model Performance Tuning Highlights**

| Metric               | Bank Model | Tuned Hybrid Model     |
| -------------------- | ---------- | ---------------------- |
| Fraud Detection Rate | \~1.34%    | \~4.63%                |
| Daily Fraud Loss     | \~\$1.7M   | \~\$608K               |
| Missed Fraud Value   | High       | Significantly Lower    |
| Detection Accuracy   | Low        | Significantly Improved |
| Mitigation Effect    | Minimal    | 49.57 custom units     |

**Techniques Implemented:**

* Multi-variable anomaly scoring
* Filtering by location + time + demographic patterns
* Advanced DAX logic for real-time computation
* Custom performance metric tracking (pre- vs post-mitigation)

---

## **Key Insights**

1. **Model Optimization Pays Off:** After tuning, the model caught a significantly higher number of previously undetected frauds, directly correlating to a \$1.1M/day reduction in financial loss.

2. **Behavioral Fraud Patterns Matter:** Fraudulent activities spiked during off-hours and were concentrated in specific cities—trends missed by the original system.

3. **Demographic Blind Spots Reduced:** Our model flagged transactions previously ignored due to missing or incomplete user attributes, tightening fraud detection coverage.


## **Conclusion**

This project proves that **performance tuning of fraud detection models is not just a technical improvement—but a high-value business strategy**. By using better model logic and deeper data features, we:

* Reduced loss exposure
* Improved fraud visibility
* Enabled better resource allocation for fraud response

Institutions that adopt this tuned detection framework can expect measurable ROI in both fraud prevention and operational efficiency.
