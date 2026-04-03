# 🚗 US Car Auction Market Analysis (500k+ Records)

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on a massive dataset of over 500,000 car auction records. The primary objective is to understand the factors driving vehicle prices, evaluate the accuracy of the MMR (Manheim Market Report), and discover geographic opportunities for buying and selling. 

Due to the dataset's large size, comprehensive data cleaning was performed initially to ensure accurate and actionable business insights.

---

## 📊 Key Business Insights & Findings

### 1. Market Trends & Top Sellers
* **Peak Years:** Over the last decade, the highest sales volume was recorded for vehicles manufactured in **2012** , closely followed by **2013** and **2014**.
* **Market Dominance:** **Ford** is the most sold brand in the dataset , with specific models like the F-150 driving the volume.

### 2. Geographic Arbitrage (Where to Buy & Sell)
* **Highest Volume:** **Florida** leads the United States as the state with the highest number of car sales.
* **Investment Opportunities:** The data reveals geographic price gaps. **New Mexico** and **Massachusetts** are the best states to buy cars at the lowest prices. 
* **Flipping Strategy:** For car dealers or flippers, purchasing vehicles in the aforementioned cheaper states and reselling them in higher-priced markets like **Nevada** presents a highly profitable business model.

### 3. Valuation & MMR Reliability
* **Is MMR Accurate?** Yes. The analysis between Selling Price and MMR shows that the Manheim Market Report is highly reliable, with an accuracy rate of approximately **90%**.
* **Price Gaps:** Occasional significant price gaps are typically associated with specific auction dynamics where vehicle prices multiplied unexpectedly.

### 4. Depreciation & The Purchasing "Sweet Spot"
* **Usage Impact:** As expected, there is a strict inverse relationship between the Odometer reading and the car's value (MMR and Selling Price); as mileage increases, the car is consumed and the price drops.
* **The Sweet Spot:** The most optimal purchase for a buyer is a vehicle with **40,000 to 60,000 miles**. In this range, the car is still in good condition but comes at a significantly discounted price compared to buying new.

### 5. Top Condition Vehicles
* When filtering for the best overall condition based on user ratings, top-tier models emerge across different brands. Models like the **Audi Q3**, **Mercedes-Benz B-Class/GLA**, and **Lexus RC 350** show consistently high condition values, making them strong recommendations for buyers.

---

## 🛠️ Tools & Technologies Used
* **Python:** Pandas, NumPy (Data Wrangling & Cleaning)
* **Data Visualization:** Plotly
* **Environment:** Jupyter Notebook

## 📂 Dataset & Full Code
Due to GitHub's file size limits for large datasets (Big Data), the raw CSV files and the full execution notebook are hosted on Kaggle.

🔗 **[View the Full Dataset & Execution on Kaggle](https://www.kaggle.com/code/youssef13797/cars-motors-db)**
