# 🛍️ Vrinda Store - Excel Dashboard Project

This is an interactive Excel dashboard created to analyze sales, orders, and customer demographics for a fictional fashion retail store called **Vrinda Store**. The dashboard is designed for business users and provides valuable insights through a clean, slicer-based layout.

---

## 📌 Key Features

- 📊 **Orders vs Sales Trend** (Bar + Line chart)
- 🧍‍♂️🧍‍♀️ **Sales Split by Gender**
- 🧾 **Order Status Breakdown**
- 🌍 **Top 5 States by Sales**
- 👥 **Orders by Age & Gender**
- 📦 **Sales by Channel (Ajio, Amazon, Flipkart, etc.)**
- 🎛️ **Interactive Slicers** for Channel, Month, and Product Category

---
## 📐 Methodology
### Data Cleaning

- Removed duplicates, standardized column headers.

- Created month columns and ensured numeric formatting.

- Added calculated fields where necessary (e.g., total sales, order count).

### Data Processing

- Used IF() formulas to categorize customer ages into groups:

- Teenager, Adult, Senior — based on defined age ranges.

- Extracted Month names from the order date using the TEXT() function for better aggregation and trend analysis in charts.

- Ensured proper data formatting (e.g., numeric types, date consistency).

- Created additional calculated columns to support visualizations.

### Dashboard Design in Excel

- Built PivotTables as backend data sources.

- Used Slicers for interactivity (Channel, Month, Category).

### Developed visualizations:

- Combo chart for Sales vs Orders trend.

- Pie and Donut charts for gender and channel distributions.

- Bar charts for state-wise sales and demographic analysis.

### Styling & UX

- Used a consistent blue-gray color scheme for a professional look.

- Customized slicers for better user interaction.

- Arranged charts in a modular layout for quick understanding.

- Added 3D and shaded visuals to enhance impact without clutter.

---


## 📂 Files Included

| File | Description |
|------|-------------|
| `Vrinda_Store_Dashboard.xlsx` | Final dashboard file with interactive filters |
| `Dashboard_Screenshot.png`    | Snapshot of the dashboard |
| `raw_file.xlsx`               | Raw data used for analysis (optional) |
| `data/cleaned_data.csv`       | Cleaned data after preprocessing |

---

## 🎨 Design Choices

- **Color Palette**: Blue-gray theme for a professional, clean look
- **Slicer Styling**: Customized slicers for intuitive filtering
- **Chart Types**: Pie, donut, clustered bar, and combo charts
- **Layout**: Balanced and modular grid layout for easy understanding

---

## 📈 Tools Used

- Microsoft Excel (PivotTables, Charts, Slicers, Formatting)
- Data Cleaning (within Excel)
- Optional: Power Pivot or Power Query for backend modeling (if used)

---

## 💡 Insights Highlighted

- Majority of sales come from **Amazon, Flipkart, and Myntra**
- **Women** contribute to 64% of overall sales
- Most orders are from **Maharashtra** and **Karnataka**
- **Adults** are the highest purchasing age group
- 92% of orders are successfully **Delivered**

---

## 📌 Use Cases

- Great for showcasing Excel dashboard skills in portfolios
- Demonstrates understanding of data storytelling
- Useful for small businesses needing Excel-based reporting tools

---

## 📸 Dashboard Preview

![Image](https://github.com/ridumjeetsingh/Excel-Sale-Project/blob/main/Dashboard_Image.png)

---

## 🙋‍♂️ About Me

Hi! I'm a Data Analyst passionate about turning raw data into actionable insights using tools like Excel, Power BI, SQL, and Python. Feel free to connect or fork this repo if you like the work!

---

