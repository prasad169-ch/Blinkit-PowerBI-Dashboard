📊 Blinkit Sales Analytics Dashboard – Power BI

This project is an interactive Power BI dashboard that provides a comprehensive analysis of Blinkit’s sales, outlet performance, item categories, customer ratings, and business insights.
It helps visualize key metrics to support data-driven decision-making.

🖼 Dashboard Preview

![Blinkit Dashboard](images/Screenshot%202025-11-28%20120613.png)


🚀 Project Overview

The dashboard highlights major business KPIs, including:

✔️ Total & Average Sales

✔️ Number of Items

✔️ Average Customer Rating

✔️ Sales by Item Type

✔️ Outlet Size & Location Performance

✔️ Fat Content Sales Comparison

✔️ Year-wise Outlet Establishment Trend

📌 Key Insights

Total Sales: $1.20M

Average Sales per Outlet: $141

Number of Items: 8,523

Average Rating: ⭐ 3.9

Top Performing Outlet Location: Tier 3

Highest Sales by Outlet Size: Medium (37.01%)

Top Selling Categories: Snack Foods, Fruits & Vegetables

Regular Fat items generate more sales than Low Fat

🛠 Tools & Technologies Used
Tool / Technology	Purpose
Power BI	Data visualization & dashboard creation
Power Query	Data cleaning, transformation
DAX	Measures & business logic
Excel / CSV	Dataset
GitHub	Version control & project hosting
📂 Project Structure
📁 Blinkit-Sales-Analysis
 ┣ 📄 Blinkit_Dashboard.pbix
 ┣ 📄 Dataset.xlsx / data.csv
 ┣ 📁 images
 ┃   ┗ 📄 Screenshot 2025-11-28 120613.png
 ┗ 📄 README.md

🧮 DAX Measures Used (Samples)
Total Sales = SUM(Data[Sales])

Average Sales = AVERAGE(Data[Sales])

No_of_Items = DISTINCTCOUNT(Data[Item_Identifier])

Average Rating = AVERAGE(Data[Rating])

📈 Dashboard Features

📍 Slicers for Outlet Size, Location, Item Type

🟢 Donut charts for outlet size distribution

📊 Horizontal bar charts for item-wise sales

🧁 Fat Content vs Sales visual

📅 Line graph for outlet establishment trend

🔍 Fully interactive and filter-based insights

🎯 Clean, modern UI with KPI cards

🧠 What I Learned

Building professional dashboards in Power BI

Using DAX for calculated metrics

Data modeling techniques

Designing clean and effective visual layouts

Publishing and documenting analytics projects

📬 Contact

If you'd like to connect or provide feedback:

📧 Email: chsurya2004@gmail.com

🔗 LinkedIn: https://linkedin.com/in/suryachitturi/

⭐ Show Your Support

If you found this project useful, please consider giving this repository a ⭐ star!
