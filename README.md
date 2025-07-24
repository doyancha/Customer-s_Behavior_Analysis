# 🛒 Customer Behavior Analysis Project

This project aims to explore customer behavior patterns and purchasing trends using a structured e-commerce dataset. Through data cleaning, visualization, and statistical analysis, the goal is to extract actionable insights that can guide business decisions around customer satisfaction, sales strategy, and operational improvements.

---

## 📊 Dataset Overview

The dataset contains customer-level transaction and behavior data with the following key features:

- **Demographics**: Age, Gender, Location
- **Purchase Behavior**: Product Category, Purchase Amount, Number of Items, Discount Usage
- **Website Interaction**: Time Spent on Website, Device Type
- **Order Fulfillment**: Delivery Time, Payment Method
- **Customer Attributes**: Return Customer Status, Subscription Status
- **Feedback Metrics**: Review Score (1–5), Customer Satisfaction (Target Variable)

---

## 🧠 Objectives

- Identify key drivers of **customer satisfaction**
- Analyze the effect of **delivery time, payment methods, and product categories**
- Segment customers by **location, return status, and subscription**
- Recommend actionable strategies to **boost retention, loyalty, and revenue**

---

## 📌 Major Insights

1. **Fast delivery improves customer satisfaction** significantly.
2. **Returning customers** are more loyal and spend more.
3. **Toys, Books, and Home Essentials** generate the highest revenue.
4. **Cash on Delivery** users report higher satisfaction despite lower usage.
5. Purchase behavior varies greatly across **locations**, especially in urban areas.
6. **Subscribed customers** show higher spending and satisfaction.
7. **Device type and gender** influence browsing and purchase behavior.
8. **Discount usage** increases purchase volume and satisfaction.

---

## 📁 Project Structure
📦 Customer-Behavior-Analysis
│
├── 📊 data/
│ └── customer_data.csv
│
├── 📓 notebooks/
│ └── EDA_and_Insights.ipynb
│
├── 📈 visuals/
│ └── plots, bar charts, pie charts, etc.
│
├── 📄 README.md
└── requirements.txt

---

## ⚙️ Technologies Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook
- Scikit-learn (for further modeling, if needed)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Customer-Behavior-Analysis.git
   cd Customer-Behavior-Analysis
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Launch the notebook:
   ```bash
   jupyter notebook notebooks/EDA_and_Insights.ipynb

## 📌 Future Work

- Predict customer satisfaction using machine learning.

- Add clustering for customer segmentation.

- Deploy dashboards using Streamlit or Dash.
