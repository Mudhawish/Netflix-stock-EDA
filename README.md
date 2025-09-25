# Netflix Stock Data Analysis 🎬📈

This project explores **Netflix historical stock data** using Python (Pandas, NumPy, Matplotlib, Seaborn).  
It’s a practical exercise in **data cleaning, slicing, filtering, aggregation, and visualization** to uncover insights from stock movements.

---
## 🗂 Dataset

The dataset contains Netflix historical stock data with the following key columns:

| Column | Description |
|--------|-------------|
| Date   | Trading date |
| Open   | Opening stock price for the day |
| High   | Highest stock price during the day |
| Low    | Lowest stock price during the day |
| Close  | Closing stock price for the day |
| Volume | Number of shares traded |
| ticker | Stock ticker symbol (e.g., NFLX) |
| name   | Company name (Netflix) |

## 📊 What I Did in the Notebook
Here’s the full breakdown of the steps I worked on:

- 🔧 Imported core libraries → **Pandas, NumPy, Matplotlib, Seaborn**  
- 🗓️ Converted the `Date` column to **datetime format** and sorted by date  
- 📍 Practiced slicing and indexing with **`.loc` and `.iloc`**  
- ⚡ Applied **conditional filtering** (e.g., rows where Close > 500, or Close > 500 & Open < 500)  
- 🔎 Filtered rows using the **`.query()` method** for clean expressions  
- ↕️ Performed **sorting** (both normally and using lambda functions)  
- 📊 Used **groupby and aggregation** to summarize stock data  
- 🔁 Experimented with **transform and apply** functions  
- 🎨 Built **visualizations** using Matplotlib and Seaborn to show stock trends  

---

## 📈 Example Insights
- Netflix stock reached **over 500** on multiple occasions, showing volatility.  
- Conditional filtering revealed unique patterns in Open vs Close price behaviors.  
- Aggregations helped identify trading volume trends and growth phases.  
- Visualizations made long-term vs short-term fluctuations clearer.  

---

## 💡 Reflections
This wasn’t just about code — it was about learning the workflow of **EDA (Exploratory Data Analysis)**:  
- Starting with raw data  
- Cleaning and reshaping it  
- Exploring through slicing, filtering, and grouping  
- Telling a story with visualizations  

Working with Netflix stock data helped me practice **data manipulation, aggregation, and storytelling** in a realistic scenario.

---


