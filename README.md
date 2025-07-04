# Northern Ireland Museum Visitor Retention Analysis

## Project Overview

This project presents a **machine learning approach to predicting and improving visitor retention** for museums. The analysis was done to identify key behavioural and demographic factors influencing visitor loyalty and to provide data-driven recommendations for boosting engagement.


## Author

**Bhagyaprasad (Postgrad Data Analytics)**

---

## Dataset Summary

- **Content:** Visitor frequency, dwell time, demographics, membership awareness, satisfaction metrics.
- **Preprocessing Steps:**
  - Missing data imputation (median).
  - Feature selection and categorical transformation.
  - Data normalisation for model consistency.

---

## Key Findings

- **Dwell Time:** Longer stays correlated with higher retention.
- **Membership:** 91.2% of members revisited, highlighting strong membership impact.
- **Events:** Attendance significantly increased dwell time.
- **Demographics:** Older visitors showed higher satisfaction and likelihood of return.

---

## Statistical Insights

- **T-Test:** Event attendees stayed significantly longer (p < 0.0001).
- **ANOVA:** Significant satisfaction variation across age groups (p < 0.0006).

---

## Insights 
![Age by museum](https://github.com/user-attachments/assets/c1b3d42e-87ea-4a49-9ac5-47c02ba8919a)
![mdm vs museum](https://github.com/user-attachments/assets/52765081-7d3d-4689-a40a-11881d002b33)
![retention by home loction](https://github.com/user-attachments/assets/acd5a322-e8bb-4d82-80dc-809910f6a97e)
![retention by membership](https://github.com/user-attachments/assets/8db179a8-101b-4f4a-b13d-0f1d39d37b52)
![Visitor Parties by museum](https://github.com/user-attachments/assets/e3216a08-8012-4d12-ae56-f40c072dd660)


## Predictive Modelling

| Metric        | Decision Tree | Random Forest |
|---------------|---------------|---------------|
| Accuracy      | 74.5%         | 77.17%        |
| ROC Score     | 0.78          | 0.84          |
| Sensitivity   | 80.56%        | 83.87%        |
| Specificity   | 68.34%        | 67.39%        |

**Random Forest outperformed Decision Tree**, reducing overfitting and improving prediction accuracy.

---

## Business Recommendations

1. **Personalized Engagement:** Offer tailored visitor recommendations.
2. **Membership Expansion:** Strengthen campaigns to increase memberships.
3. **Targeted Marketing:** Focus on high-probability returning visitors.
4. **Event-Driven Strategies:** Leverage events to drive repeat visits.
5. **Real-Time Analytics:** Implement dynamic data-driven decision-making.

---

## Conclusion

Data-driven approaches like the Random Forest model can effectively predict visitor retention, enabling museums to enhance their outreach strategies and improve long-term attendance growth.

---

## Repository Contents

- `Report_Analytathon1.pdf`: Full analysis report.
- `README.md`: Project overview and summary.

---

## Future Work

- Deploy models into a dashboard for real-time visitor retention prediction.
- Expand feature set with social media engagement and seasonal trends.

---

### Connect with me on [LinkedIn](https://www.linkedin.com/in/bhagyaprasad-vastrad-a652b6201/) for insights, collaboration, and project discussions.
- Expand feature set with social media engagement and seasonal trends.

---

