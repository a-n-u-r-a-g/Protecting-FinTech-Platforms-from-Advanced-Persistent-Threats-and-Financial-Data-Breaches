# Protecting-FinTech-Platforms-from-Advanced-Persistent-Threats-and-Financial-Data-Breaches
Protecting FinTech Platforms from Advanced Persistent Threats and Financial Data Breaches

The growing dependence on FinTech platforms 
has intensified the prerequisite for robust cybersecurity 
measures against threats like Advanced Persistent Threats 
(APTs) and financial data breaches. This research offers a 
hybrid machine learning-based detection system that fit in both 
network-level anomaly detection and transaction-level fraud 
classification to secure modern FinTech infrastructures. The 
technique makes use of the CICIDS2017 dataset to detect 
network intrusions that indicate APT activity, as well as the 
IEEE-CIS Fraud Detection dataset to identify fraudulent 
financial transactions. To provide broad threat coverage, the 
models used include Random Forest, LightGBM, XGBoost, and 
CatBoost, which were trained on both datasets. A hybrid 
prediction function fuses both models to generate real-time 
alerts when suspicious activity is detected in either domain. The 
system incorporates data normalization, feature selection, and 
ensemble logic to improve detection accuracy and reduce false 
positives. The network intrusion model trained on CICIDS2017 
has an accuracy of 99.98% and a ROC-AUC score of 1.00, 
suggesting nearly flawless detection of aberrant network 
behaviour. The financial fraud detection model trained on 
IEEE-CIS data attained an accuracy of 98% and a ROC-AUC 
score of 0.94, indicating excellent performance in discriminating 
between genuine and fraudulent transactions. This dual-layered 
framework demonstrates strong potential in proactively 
identifying complex cyber threats, thereby enhancing the 
flexibility of financial platforms against evolving attack vectors 
and minimizing the risk of data and monetary loss. 
