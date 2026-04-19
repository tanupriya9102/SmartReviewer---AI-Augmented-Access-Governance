# SmartReviewer: AI-Augmented Access Governance
### Mitigating Reviewer Fatigue with Predictive Identity Analytics

## 📌 Project Overview
**SmartReviewer** is an intelligent decision-support system designed for Identity & Access Management (IAM). It solves the critical industry challenge of **Reviewer Fatigue**—where managers are overwhelmed by thousands of access certification items, leading to high-risk "rubber-stamping."

By utilizing Machine Learning, SmartReviewer categorizes access requests into three tiers:
1. **✅ Safe (Bulk Approve):** High-confidence, peer-aligned requests.
2. **🔍 Standard Review:** Typical requests requiring standard human oversight.
3. **🚩 FLAG (Manual Audit):** High-risk anomalies that bypass bulk approval.

## 🚀 Impact & Results
* **Efficiency:** Automated the triaging of **95.45%** of access requests.
* **Accuracy:** Achieved an overall model accuracy of **95.45%**.
* **Reliability:** **96% Precision** for "Safe" recommendations, ensuring bulk actions are highly trustworthy.
* **Compliance:** Integrated **SHAP (Explainable AI)** to provide human-readable justifications for every automated decision.

## 🛠️ Technical Stack
* **Language:** Python
* **Models:** CatBoost (Gradient Boosting on Decision Trees)
* **Explainability:** SHAP
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter

## 🧠 Key Innovations
* **Peer-Similarity Feature:** Engineered a custom metric to measure entitlement prevalence within departments.
* **Categorical Optimization:** Leveraged CatBoost's native handling of high-cardinality IDs (Resource, Dept, Role).
* **Smart Triage:** Implemented probability-based thresholds to separate operational speed from security risk.

---
**Author:** IAM & AI/ML Professional
