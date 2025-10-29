# Power-BI-Mobile-sales-Dashboard

Interactive Power BI dashboard for analyzing mobile sales data and business performance.

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#project-learning">project-learning</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>

- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#conclusion">conclusion</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

The Power BI Mobile Sales Dashboard provides a detailed analysis of mobile sales performance across different regions, brands, and time periods. The project aims to help business teams track key performance indicators (KPIs) such as total sales, profit margins, quantity sold, and regional growth trends.

This dashboard offers an interactive and visually appealing interface that enables users to:

- Monitor overall sales performance and revenue trends

- Compare brand-wise and category-wise sales data

- Identify top-performing regions and products

- Support data-driven decision-making through real-time insights

By leveraging Power BI’s visualization capabilities, this project transforms raw sales data into actionable insights for better business strategy and performance tracking.

---
<h2><a class="anchor" id="project-learning"></a>project-learning</h2>

During the development of this project, I gained practical experience in the complete Power BI workflow — from data collection to dashboard creation. Key learnings include:

- **Data Cleaning & Transformation:**
  Used Power Query to clean, format, and prepare raw sales data for analysis.

- **Data Modeling:**
  Created relationships between multiple tables and built an optimized data model to ensure accurate visualizations.

- **DAX Calculations:**
  Learned to write DAX measures and calculated columns to derive KPIs such as Total Sales, Profit, and Quantity Sold.

- **Dashboard Design:**
  Developed an interactive and visually appealing dashboard using Power BI visuals like cards, charts, and slicers.

- **Insights Generation:**
  Interpreted business insights from data trends, such as identifying top-performing brands and high-sales regions.

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- **Date:** Transaction date of each sale

- **Product:** Name or model of the mobile phone

- **Brand:** Brand associated with the product

- **Region:** Geographic region where the sale occurred

- **Quantity Sold:** Number of units sold

- **Unit Price:** Selling price per unit

- **Total Sales:** Total revenue generated (calculated)

- **Profit:** Profit earned from each transaction or product

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- **Microsoft Power BI:** For data visualization, dashboard creation, and KPI analysis

- **Power Query:** For data cleaning, transformation, and preparation

- **DAX (Data Analysis Expressions):** For creating custom measures and calculated columns

- **Microsoft Excel:** For storing and managing raw sales data before importing into Power BI

- **GitHub:** For project version control and portfolio presentation

- ---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
Power-BI-Mobile-Sales-Dashboard/
│
├── 📄 Mobile_Sales_Dashboard.pbix        # Main Power BI dashboard file
├── 📊 Mobile_Sales_Data.xlsx              # Raw dataset used for analysis
├── 📸 Dashboard_Screenshots/              # Folder containing dashboard visuals
├── 📜 README.md                           # Project documentation file
└── 📁 Additional_Files/                   # (Optional) Supporting or reference files
```

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

**1. Data Import:**

- Loaded the raw sales dataset from Excel into Power BI.

**2. Removed Duplicates & Missing Values:**

- Checked for duplicate entries and blank rows, and removed unnecessary records.

**3. Standardized Column Names:**

- Renamed columns (e.g., “Prod” → “Product”, “Qty” → “Quantity Sold”) for better readability.

**4. Data Type Correction:**

- Ensured correct data types for each column (e.g., Date, Text, Numeric).

**5. Calculated Columns Creation:**

- Added new calculated fields such as:

- Total Sales = Quantity × Unit Price

- Profit Margin = (Profit / Total Sales) × 100

**6. Data Filtering:**

- Filtered out irrelevant or incomplete data to maintain consistency.

**7. Data Model Setup:**

- Established relationships (if multiple tables) and created a clean, structured data model ready for analysis.

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone or Download the Repository
```bash
git clone https://github.com/yashkdm987/Power-BI-Mobile-sales-Dashboard.git
```

2. Open Power BI Desktop
  - `If you don’t have it, download Power BI Desktop`

3. Connect or Refresh the Dataset
  - `Ensure the dataset (.csv files) in the Dataset folder are correctly linked.`
  - `Click “Refresh” in Power BI to load the latest data.`

4. Explore the Dashboard
  - `Interact with filters, slicers, and charts.`
  - `View sales performance by product, region, and time period.`

---
<h2><a class="anchor" id="conclusion"></a>conclusion</h2>

The Power BI Mobile Sales Dashboard successfully transforms raw sales data into meaningful and interactive business insights. By visualizing key metrics such as total sales, profit, and regional performance, this dashboard helps stakeholders make data-driven decisions with ease.

Through this project, I enhanced my skills in data cleaning, DAX calculations, and dashboard design while learning how to present complex sales data in a simple and visually appealing way.

This dashboard can be further expanded by integrating live data sources or automating data refresh to support real-time analytics and business forecasting.

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Yash Kadam**  
Data Analyst  
📧 Email: yashkadam3000@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yash-kadam-ba2688211/)
