# Project- Google Advanced Data Analytics Capstone

📊 Google Advanced Data Analytics Certificate Capstone
Welcome to the repository for my Google Advanced Data Analytics Certificate Capstone Project! This project showcases the application of advanced data analytics techniques to address a real-world business problem, leveraging Python for exploratory data analysis, model building, and actionable insights.

💼 Project Scenario
Business Problem
Salifort Motors is facing a high rate of employee turnover, impacting corporate culture and financial performance. To mitigate this issue, I analyzed employee data to predict turnover trends, uncover driving factors, and provide strategic recommendations for retention.

⚙️ Project Features

1️⃣ Exploratory Data Analysis (EDA)
- Explored self-reported employee data for patterns like satisfaction levels, hours worked, and tenure.
- Used Python libraries (Pandas, NumPy, Matplotlib, Seaborn, Plotly) to visualize correlations and trends.

2️⃣ Model Building and Evaluation
- Built predictive models to analyze turnover, including:- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Evaluated performance using metrics like AUC, precision, recall, F1-score, and accuracy.

3️⃣ Business Insights
- Derived actionable insights from model results and feature importance, enabling data-driven recommendations for leadership.


📂 Dataset Summary
The dataset (HR_capstone_dataset.csv) comprises:
- 14,999 rows: Each representing an employee’s self-reported data.
- 10 columns: Key attributes like satisfaction level, job role, and salary.

| Column Name | Type | Description | 
| satisfaction_level | float | Employee’s self-reported satisfaction level (0–1). | 
| last_evaluation | float | Score of last performance review (0–1). | 
| number_project | int64 | Number of projects the employee contributes to. | 
| average_monthly_hours | int64 | Average monthly hours worked. | 
| time_spend_company | int64 | Employee tenure in years. | 
| work_accident | int64 | Whether the employee experienced a work accident. | 
| left | int64 | Whether the employee left the company (1 = Yes, 0 = No). | 
| promotion_last_5years | int64 | Whether the employee was promoted in the last 5 years. | 
| department | string | Employee department. | 
| salary | string | Employee salary (low, medium, high). | 



🌟 Model Results and Evaluation
Logistic Regression
- Precision: 80%, Recall: 83%, F1-score: 80%, Accuracy: 83%.

Tree-Based Machine Learning Models
- Decision Tree:- AUC: 93.8%, Precision: 87.0%, Recall: 90.4%, F1-score: 88.7%, Accuracy: 96.2%.
- Random Forest: Marginally outperformed the Decision Tree.
- XGBoost: Achieved optimal results for identifying key drivers of turnover.

🛠️ Insights and Recommendations
Key Findings
The models confirm that employees are overworked and dissatisfied, especially those with extended tenures or high workloads.
Recommendations
- Cap the number of projects employees can undertake simultaneously.
- Consider promoting employees with at least four years of tenure or investigate their dissatisfaction levels.
- Adjust workloads and reward employees for longer hours or effort proportionately.
- Clarify overtime policies and expectations for workload and time off.
- Conduct discussions on work culture to address pain points specific to departments.
- Reassess evaluation criteria to reward contributions fairly, regardless of hours worked.

💡 Next Steps
- Investigate data leakage concerns by reevaluating model performance with certain features removed (e.g., last_evaluation, satisfaction_level).
- Develop clustering models (e.g., K-means) for deeper segmentation of employee profiles and further insights.
- Use these findings to inform company-wide initiatives, addressing turnover holistically.

🏆 Certifications and Resources
This capstone reflects proficiency honed through certifications:
- 🎓 Google Advanced Data Analytics Certificate
- 🤖 IBM AI Developer Certification
- 🏅 SQL Certified by HackerRank




