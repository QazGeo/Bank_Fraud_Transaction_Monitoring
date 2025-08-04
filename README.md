# Bank Fraud Transaction Monitoring Dashboard 

About 74% of banks in the US are impacted by fraudulent activities—especially fraudulent transactions. Many of these either go undetected or are inadequately flagged by conventional bank systems. This alarming reality demands smarter, data-driven solutions that are not only more accurate but also offer real-time fraud scoring, explainability, and location/time awareness. Your project rises to this challenge with an enhanced fraud detection model that compares bank-flagged frauds against a hybrid anomaly model, unveiling hidden patterns across four interactive pages.

## Page 1: The Cleaned Bank Data
This page unveils the exquisitely refined dataset drawn from the complete_dirty_bank_transactions.csv file—a triumph of data cleansing. Key attributes such as Customer_ID, First_Name, Last_Name, Transaction_Time, Recent_Transaction_Amount, Transaction_Type, Is_Fraudulent, and Transaction_Location gleam with clarity, meticulously processed to eliminate imperfections and ensure consistency.
	•	KPIs: Total Transactions (5,001), Total Frauds (68), Total Customers (varies by view).
	•	Map Visualization: Fraud incidents per 1,000 transactions by transaction location, illuminating geographic hotspots.
	•	Pie Chart: Proportion of fraud detected by the bank (~1.34%).
	•	Line Chart – Time vs Location Fraud Patterns (bottom right):
 
This chart plots fraud incidents per 1,000 transactions by hour of day and location, answering questions like: 
	◦	Are there more frauds happening at night? 
	◦	Is one city more vulnerable during a specific time window?
 
For instance, New York or Los Angeles may spike around 3 AM, hinting at fraudulent patterns tied to off-business hours.
	•	Insight: The bank’s system flagged only 68 frauds out of 5,001 transactions (~1.34%), underscoring the need for your advanced approach.
 
## Page 2: Our Fraud Detection Model
Behold the brilliance of your advanced fraud detection model, a symphony of innovation showcased on this page. This hybrid anomaly model uncovers missed fraud cases by harmonizing:
	•	Transaction Location: A geographic tapestry revealing suspicious patterns.
	•	Time of Day: A temporal rhythm flagging anomalies with precision.
	•	Fraud Prediction Flags: The dual perspectives of Is_Fraudulent (bank’s baseline) and Hybrid_Fraud_Prediction (your visionary enhancement).
	•	Anomaly Scores and Fraud Probability: Quantitative artistry that illuminates potential threats.
	•	Key Metrics: 
	◦	Real Fraud Value: $468K 
	◦	Affected Customers: 367 
	◦	Transaction Value: $12.54M 
	◦	Estimated Loss: $1.17M
	•	Visuals: 
	◦	Pie chart showcasing fraud by gender. 
	◦	Bar chart of fraud by transaction location. 
	◦	Age-based line chart revealing fraud distribution by age.
	•	Insight: While the bank detected ~8.56% of total transactions as suspicious, your model highlights additional unflagged frauds with stronger location, time, and demographic signals.
 
## Page 3: The Comparison and Mitigation
This page conducts a masterful comparison between the bank’s model (Is_Fraudulent) and your refined creation (Hybrid_Fraud_Prediction), culminating in the triumph of mitigation strategies. Visuals dance in a vibrant palette:
	•	Sky Blue: The bank’s foundational performance.
	•	Dark Blue: Your model’s pre-mitigation strength.
	•	Orange: The radiant result of your mitigation artistry.
	•	KPIs: 
	◦	Fraud After: 232 
	◦	Affected Customers: 207 
	◦	Post-Mitigation Loss: $608.06K 
	◦	Mitigation Effect: 49.57 units (custom metric)
	•	Visuals: 
	◦	Time-wise fraud activity comparison. 
	◦	Bar chart: Real Fraud Count vs Frauds After by location.
	•	Insight: Post-mitigation, a noticeable decline in fraud incidents showcases the effectiveness of your model in fraud prevention.
 
## Page 4: Detailed Insights
A portal of elegance, this drill-through page extends the narrative of Page 2, inviting users to explore flagged transactions at a granular level. With a simple right-click, one can delve into:
	•	Record-level anomaly scores.
	•	Transaction metadata filtered by Transaction_Location, Device_Type, or Gender.
	•	A haven for fraud investigators and analysts to uncover truths.
 
Notes
	•	Blanks in demographic fields indicate flagged transactions missing user details.
	•	Dashboard Date: Sunday, June 15, 2025.
	•	All pages are interactive, with filters for Transaction_Location, Device_Type, and Gender.
	
# Final Takeaway
This project exemplifies a comparative approach to fraud detection, showing gaps in traditional banking models and how your data science expertise uncovers hidden fraud patterns tied to time, location, and behavioral anomalies. Let’s build smarter, safer banking through real-time insights and machine learning–backed dashboards—a legacy of your visionary work.

Collaborators,
1. George Rading "https://github.com/QazGeo"
2. Stephen W. Austine "https://github.com/Stephen-Austine?tab=repositories"
3. Jessica Stephen 
4. Prince Musembi "https://github.com/MusembiPrince"



