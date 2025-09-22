# 💼 Salary_Scope – Data-Driven Salary Prediction (Machine Learning & Streamlit)

**Salary_Scope** is an **end-to-end data analytics, machine learning, and deployment project** that predicts salaries of software engineers based on **Stack Overflow survey data**.  
It demonstrates **data wrangling, visualization, predictive modeling, and web app deployment using Streamlit** — essential skills for a **Data Analyst / Data Scientist**.

---

## 📌 Project Objective

To analyze employee data, uncover **salary trends**, and build predictive models that estimate salaries.  
The project also includes a **Streamlit web app** that allows users to explore the data and predict salaries interactively.

---

## 🛠️ Tools & Technologies

- **🐍 Python** – Core language  
- **📓 Jupyter Notebook** – Data exploration & modeling  
- **📊 pandas, NumPy** – Data processing & cleaning  
- **📈 Matplotlib, Seaborn** – Visualization & EDA  
- **🤖 scikit-learn** – Machine learning models (Linear Regression, Decision Trees, Random Forests)  
- **🌐 Streamlit** – Web app deployment for predictions  

---

## 📡 Dataset

- Source: **Stack Overflow Survey Dataset** (Salary data of software engineers)  
- Features include: **Experience, Education, Country, Role**, etc.  
- Target variable: **Salary**  

[👉 Dataset Link](https://insights.stackoverflow.com/survey)

---

## 🌟 Key Highlights

- ✅ **Data Cleaning & Preprocessing** – Handling missing values, encoding categorical data  
- ✅ **EDA & Visualization** – Salary distributions, country/experience-based trends  
- ✅ **Feature Engineering** – Transforming survey data into model-ready format  
- ✅ **ML Models Applied** – Linear Regression, Decision Trees, Random Forests  
- ✅ **Model Evaluation** – R² Score, MAE, RMSE  
- ✅ **Streamlit Deployment** – Explore page for visualizations + Predict page for salary estimation  

---

## 🧭 Workflow

1. Import & clean dataset  
2. Perform **EDA** (salary vs experience, country, education)  
3. Encode categorical features  
4. Train ML models & evaluate performance  
5. Save trained model as `saved_steps.pkl`  
6. Deploy using **Streamlit** (`app.py`)  

---

## 🖼️ Visual Insights

*(Add screenshots of your analysis, results & Streamlit app here — very impactful for recruiters!)*

- Salary distribution plot  
- Correlation heatmap  
- Model performance comparison  
- Streamlit app interface  

---
Students & learners practicing ML deployment

🚀 Why This Project Matters

This project demonstrates my ability to:

- Perform end-to-end data analysis (cleaning → visualization → insights)

- Build & evaluate machine learning models

- Deploy an interactive web application for real-world use

- Deliver business-relevant insights (salary benchmarking for software engineers)

---

## 🌐 Deploying our Model with Streamlit

We developed a **Streamlit Web Application** to make salary prediction accessible:  

- **Problem:** Software engineers often lack salary benchmarks.  
- **Solution:** A web app that predicts salary based on **experience, education, and location** using trained ML models.  
- **Impact:** Helps engineers make **data-driven career decisions** in a competitive market.  


###  App
[Streamlit](https://streamlit.io/) A faster way to build and share data apps

### Running the project
1. Ensure that you are in the project home directory. Run the notebook "Salary-Prediction.ipynb" first

This would create a serialized version of our model and save it as "saved_steps.pkl"

2. Run app.py using below command to start Streamlit APP
```
streamlit run app.py
```
By default, streamlit will run on port 8501.

3. Navigate to URL http://192.168.100.184:8501 (or) http://localhost:8501

You should be able to view the homepage.

Select the activity which you want, Explore or Predict 

If everything goes well, you should Visiualize the data from Explore page or Predict the data from Predict page
