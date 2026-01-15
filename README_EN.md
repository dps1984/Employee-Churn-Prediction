# Employee Churn Prediction

**[Versión en Español](README.md)**  

This project addresses the **employee churn** problem using *Machine Learning* models.  
The goal is to predict which employees are most likely to leave the company, supporting HR teams to take proactive decisions.

---

## 🧠 Business Context

Employee churn has a direct impact on operational continuity, team performance, and recruitment costs.
This project explores how data-driven insights can help HR teams identify at-risk employees early and prioritize retention actions.

---

## 📂 Project Structure
- `notebooks/` → contains the main notebook with step-by-step analysis.  
- `data/` → datasets used (not included in public repo for privacy reasons).  

---

## ⚙️ Workflow
1. **Data exploration**: structure, variable types and class balance.  
2. **Preprocessing**: scaling numerical features and one-hot encoding categorical features.  
3. **Modeling**:  
   - Logistic Regression (baseline model).  
   - Random Forest (benchmark model).  
4. **Evaluation**: F1 score, ROC AUC, PR AUC, confusion matrix, and threshold analysis.  
5. **Business takeaways**.  

---

## 📊 Key Results
| Model               | Precision | Recall | F1   | ROC AUC | PR AUC |
|---------------------|-----------|--------|------|---------|--------|
| Logistic Regression | 0.51      | 0.81   | 0.62 | 0.83    | 0.48   |
| Random Forest       | 0.99      | 0.98   | 0.98 | 1.00    | 0.99   |

🚀 Takeaways
- Logistic Regression provides a solid and interpretable baseline suitable for stakeholder discussions.
- Random Forest significantly improves predictive performance but requires careful validation.

⚠️ Important considerations:
- Near-perfect RF scores may indicate overfitting.
- In a real-world setting, models should be validated on temporal or external hold-out data.
- Model selection should balance predictive power, stability, and explainability, depending on business needs.

  ---

## 📫 Contact
- [LinkedIn](https://www.linkedin.com/in/daniel-pacheco-santamaria/)  
- [GitHub](https://github.com/dps1984)
