Hotel Revenue & Booking Analytics
A Data Analytics Portfolio Project by Uday Sharma MBA | Hospitality Domain Expert |
Data Analytics Practitioner
Project Overview
This end-to-end data analytics project analyses hotel booking patterns, revenue
performance, and guest behaviour across 3,000 reservations (2022–2023). Leveraging
Python and machine learning, it delivers actionable business insights relevant to hotel
revenue management.
Why this project? Combining 5+ years of hospitality domain knowledge with data analytics
skills, this project demonstrates the ability to translate industry metrics (ADR, RevPAR,
cancellation rate) into data-driven stories.
KPI Value
Total Revenue (2022–23) ₹4.97 Crore
Average Daily Rate (ADR) ₹7,754
Cancellation Rate 23.2%
Avg Guest Satisfaction 7.43 / 10
Repeat Guest Rate 27.1%
ML Model ROC-AUC 0.62
Key Findings
Top Insights:
August is the peak revenue month; December shows a strong festive spike
OTA (Online) channel has the highest cancellation rate (~30%)
Suite rooms achieve 8.5/10 satisfaction — highest of all room types
Lead time is the #1 predictor of cancellation risk (ML finding)
Direct bookings yield 0.3 points higher satisfaction vs OTA
Project Structure
hotel_analytics/
│
│
│
│
├── generate_data.py ├── analysis.py ├── ml_model.py ├── generate_report.py # Synthetic dataset generator (3,000 records)
# EDA, KPIs, and 9 visualization charts
# Cancellation prediction (Random Forest)
# Automated PDF report generator
├── hotel_bookings.csv # Generated dataset
├── metrics.json # Business KPIs (auto-generated)
├── ml_metrics.json # ML model metrics (auto-generated)
├── Hotel_Analytics_Report.pdf # Final 10-page PDF report
└── charts/ ├── 01_monthly_revenue.png
├── 02_room_type_revenue.png
├── 03_cancellation_by_channel.png
├── 04_seasonal_heatmap.png
├── 05_leadtime_vs_adr.png
├── 06_guest_satisfaction.png
├── 07_revpar_trend.png
├── 08_guest_channel_mix.png
├── 09_correlation_matrix.png
├── 10_feature_importance.png
├── 11_roc_curve.png
└── 12_confusion_matrix.png
# All 12 visualization charts
Tech Stack
Tool Purpose
Python 3.11 Core language
Pandas Data manipulation & aggregation
NumPy Numerical operations
Matplotlib Custom visualizations
Seaborn Statistical plots (heatmap, boxplot)
Scikit-learn Random Forest, cross-validation, metrics
ReportLab Automated PDF report generation
Analyses Performed
1. Exploratory Data Analysis (EDA)
Monthly revenue trends with seasonal pattern identification
Room type revenue and ADR comparison
Guest mix and booking channel distribution
2. Hospitality KPI Dashboard
ADR (Average Daily Rate) by room type and month
RevPAR (Revenue Per Available Room) monthly trend
Occupancy heatmap across room types and months
3. Cancellation Analysis
Cancellation rate by booking channel
Lead time impact on cancellation probability
Risk classification (Low / Medium / High) by channel
4. Guest Satisfaction Analysis
Rating distribution by booking channel
Satisfaction scores by room type
Repeat guest behaviour patterns
5. Machine Learning — Cancellation Prediction
Model: Random Forest Classifier
Features: 11 (lead time, ADR, room type, channel, stay duration, etc.)
Validation: 5-Fold Cross-Validation
Output: Feature importance, ROC curve, confusion matrix
How to Run
# 1. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn reportlab
# 2. Generate the dataset
python generate_data.py
# 3. Run analysis and create charts
python analysis.py
# 4. Train the ML model
python ml_model.py
# 5. Generate the PDF report
python generate_report.py
1. 2. 3. 4. 5. Strategic Recommendations
Reduce OTA Dependency — Shift 10–15% volume to Direct channel to cut
cancellations and commission costs
Dynamic Pricing — Deploy demand-based pricing in Jan–Feb off-peak months
Early Booking Retention — Automate outreach for bookings with >60-day lead time
Suite Upsell Programme — Front-desk upsell training can significantly lift RevPAR
Loyalty Initiative — Target 27% → 35%+ repeat guest rate with tiered programme
