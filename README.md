# Employee Churn Risk Prediction & Retention Insights  

## 📌 Project Overview  
- This project is a pilot HR analytics initiative designed to predict employee turnover risk and provide HR teams with actionable insights to reduce attrition.
- It leverages Google BigQuery, Google Colab, PyCaret (Random Forest), and Looker Studio to answer critical HR questions and deliver insights through an interactive dashboard.  

---

## Dashboard


<img width="733" height="547" alt="Screen Shot 2025-08-25 at 7 53 44 PM" src="https://github.com/user-attachments/assets/6038b416-de4b-451a-828f-c3ce249814eb" />

From Google Looker Studio


---
## ❓ Questions  

- Which employees are most at risk of quitting?  
- Which departments have the highest dissatisfaction and turnover risk?  
- What categories (e.g., salary, workload, lack of growth) contribute most to employee churn?  
- How can predictive analytics guide HR in building stronger retention strategies?  

---

## 📂 Dataset

Over 15,000+ Employee Records Analyzed from the Pilot Program

---

## ⚙️ Tools & Technologies  

- **Google BigQuery** – Data storage and querying of HR datasets  
- **Google Colab** – Model development and experimentation environment  
- **PyCaret (Random Forest)** – Automated ML pipeline for classification and prediction  
- **Looker Studio** – Interactive dashboards for reporting and insights  
- **Looker Studio REST API** – Integration between Python outputs and dashboards  

---

## 📂 Workflow  

### 1. Data Collection  
- Queried employee HR data from **Google BigQuery**, including demographic, departmental, and performance information.  

### 2. Data Preparation  
- Cleaned and preprocessed the data within **Google Colab**.  
- Encoded categorical variables like **department**, **salary range**, and **job role**.  
- Handled missing values and standardized numerical features.  

### 3. Model Training  
- Built and compared multiple models using **PyCaret’s classification module**.  
- Selected **Random Forest** as the best-performing model based on **accuracy, F1 score, and ROC-AUC**.  
- Extracted **feature importance** to identify key drivers of turnover.
- Created a structured table with predicted employee attrition labels and corresponding risk scores

### 4. Insights & Analysis  
- Identified employees at **high risk of leaving**.  
- Highlighted **departments with elevated turnover risk**.  
- Determined top attrition drivers such as **salary dissatisfaction, workload, and limited career growth**.  
- Provided **employee-level risk scores** for targeted retention strategies.  

### 5. Dashboard Development  
- Created an **interactive Looker Studio dashboard** showing:  
  - Employee turnover risk distribution  
  - Department-wise attrition insights  
  - Key attrition drivers ranked by importance  
- Automated data flow from Python to Looker Studio using the **REST API**, ensuring up-to-date insights.  

---




## 📈 Key Results  

- Achieved **92% accuracy** in predicting employee turnover.  
- Identified **top 3 drivers of attrition**: **Satisfaction Level, Time Spent in Company, Number of Projects**.
- Recognized **top 3 Departments Most at Risk for Employee Turnover**: **Technical, Support, Sales and Product**
- Provided HR actionable insights to **prioritize retention efforts**.  
- Enabled **data-driven workforce planning** and proactive employee engagement strategies.  

---

## 💡 Business Impact  

- Supports HR in **focusing retention efforts strategically**.  
- Reduces turnover by identifying **high-risk employees early**.  
- Improves **employee satisfaction and organizational stability**.  
- Helps leadership make **evidence-based policy decisions**.  

---

## 📌 Next Steps  

- Integrate additional HR datasets (e.g., engagement surveys, performance reviews).  
- Explore **time-series modeling** for predicting turnover trends over months or quarters.  
- Implement **scenario simulations** to evaluate the impact of retention initiatives.  
- Expand predictive capabilities to **internal promotions and talent mobility planning**.  
