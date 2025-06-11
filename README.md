# 🎮 Video Game Sales Analysis

## 📊 Overview
This project analyzes global video game sales trends, identifying top genres, platforms, publishers, and regional differences. The insights aim to uncover what drives sales performance across different dimensions of the video game industry.

## ❓ Business Problem
The global video game market is highly competitive, with thousands of new releases every year. This project seeks to:
1. 🔍 Identify the most successful genres and platforms  
2. 📈 Uncover trends in game releases and sales over time  
3. 🌍 Analyze regional sales patterns to inform market strategy  
4. 📊 Provide visual insights for publishers and stakeholders  

## 🗂️ Data
The dataset was obtained from Kaggle: [EDA Video Games Sales by siddharth0935](https://www.kaggle.com/code/siddharth0935/eda-video-games-sales)

It contains data on over **19,000 video games**, including:
- 🎮 Title, Genre, Publisher, Platform  
- 📅 Release Date, Developer  
- ⭐ Critic Score, User Score  
- 🌎 Sales by region: NA, JP, PAL, Other  
- 💰 Global Sales (in millions of units)  

## 🧪 Methodology

### 1. 🧹 Data Cleaning:
- Removed rows with missing `total_sales`
- Dropped irrelevant columns (`img`, `last_update`)
- Converted date fields and extracted release year
- Filled missing developer names with `'Unknown'`

### 2. 📊 Exploratory Data Analysis (EDA):
- Visualized top-performing genres, platforms, and publishers
- Analyzed correlation between critic scores and sales
- Investigated regional sales distribution
- Tracked game release trends over time

### 3. 📉 Visualization:
- Created 8 data visualizations using `matplotlib` and `seaborn`
<img width="985" alt="viz1" src="https://github.com/user-attachments/assets/e9a9f4fc-da7c-43d5-a48b-4ebf097f1a1c" />
<img width="985" alt="viz2" src="https://github.com/user-attachments/assets/c3cb62d3-0728-4347-ace7-4b3f6d8477c6" />



## 🌟 Key Findings
- **Action**, **Sports**, and **Role-Playing** are the best-selling genres  
- **PS2**, **X360**, and **PS3** are the top-selling platforms  
- Higher **critic scores** are generally associated with better sales  
- **North America** leads with ~49% of global video game sales  
- Game releases peaked between **2008–2012**, followed by a gradual decline  

## 🖼️ Visual Highlights
- 🔝 Top 10 genres and platforms by number of games and sales  
- 📉 Correlation between critic scores and total sales  
- 📅 Annual release trends  
- 🧩 Global sales distribution by region (pie chart)  

## 🛠️ Tools Used
- 🐍 **Python**: pandas, numpy, matplotlib, seaborn  
- 📓 **Jupyter Notebook** (.ipynb)  
- 📂 **Dataset Source**: Kaggle  
- 🔧 **Version Control**: Git & GitHub  

---

👨‍💻 Created by: **David Sebastian Aritonang**  
📧 Email: [davidsebastianartt@gmail.com](mailto:davidsebastianartt@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/david-sartt](https://www.linkedin.com/in/david-sartt/)  
📁 GitHub Repo: [Video Game Sales Analysis](https://github.com/davidsebastianart/VideoGame-Sales-Analysis)
