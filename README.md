# 🌍 **GDP Per Capita Analysis - Python & Pandas** 🐍  

## 🎯 **Project Overview**  
This project explores the **GDP per Capita dataset**, utilizing **Python & Pandas** for **data manipulation, analysis, and visualization**. Through various querying and transformation techniques, we gain insights into global economic trends across different countries and regions.  

## 🛠 **Tools & Technologies**  
- **Python** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) – Core programming for data analysis  
- **Pandas** 🐼 – Handling and manipulating structured data  
- **Matplotlib & Seaborn** 📊 – Creating intuitive visualizations  
- **Jupyter Notebook** 📒 – Running structured interactive analysis  

## 📊 **Dataset Overview**  
📌 **GDP Per Capita Dataset Columns:**  
- 🌎 **Country/Territory** – Nation name and economic region classification  
- 📈 **IMF, World Bank, UN Estimates** – GDP per capita values from different sources  
- 📅 **Year** – Temporal data tracking global economic shifts  
- 🎯 **Region Categorization** – Mapping GDP figures across continents  

## 🔍 **Python Data Operations Used**  
✨ **Key Pandas functions leveraged:**  
- 📂 **Loading Dataset:** `df = pd.read_csv('GDP (nominal) per Capita.csv')`  
- 🏆 **Top 10 Countries by GDP Per Capita:** `df.nlargest(10, 'IMF_Estimate')`  
- ⚡ **Filtering by Year:** `df[df['WorldBank_Year'] == 2021]`  
- 🔄 **Data Cleaning & Handling Missing Values:** `df.fillna(0, inplace=True)`  
- 📊 **Visualization:** `sns.barplot(x='Country', y='IMF_Estimate', data=df)`  


## 🎨 **Why This Project Stands Out?**  
✅ **Efficient Data Handling with Pandas** – Structured data querying & filtering  
✅ **Engaging Visualizations** – Creating clear comparisons between global economies  
✅ **Insightful Analytics** – Extracting economic trends with simple transformations  

## 🚀 **How to Use This Repository**  
1️⃣ **Clone the repository** – `git clone https://github.com/your-repo-link`  
2️⃣ **Install dependencies** – `pip install pandas matplotlib seaborn`  
3️⃣ **Run Python scripts** – Perform GDP analysis and comparisons  

## 🌟 **Skills Demonstrated**  
- 🐍 **Python for Data Processing** – Loading, filtering, and transforming datasets  
- 📊 **Data Visualization** – Using **Matplotlib & Seaborn** for intuitive insights  
- 📈 **Global Economic Analysis** – Comparing GDP trends across different regions  

 

---

This README **adds structure, color, and clarity**, effectively showcasing your **Python & Pandas skills**! 🚀🔥 Let me know if you need refinements! 🎯✨  
