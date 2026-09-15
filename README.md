# 🧱 LEGO Sales Analysis Dashboard

An interactive **LEGO Sales Analysis** project built using **Microsoft Power BI** to analyze LEGO sets, pricing, number of pieces, themes, categories, and product-level information.

The project focuses on transforming LEGO sales data into an interactive dashboard that makes it easy to explore product performance and identify patterns across different LEGO categories and themes.

---

## 📌 Project Workflow

**Dataset → Data Cleaning & Preparation → Power BI → DAX → Interactive Dashboard → Insights**

### 1️⃣ Get Dataset

The project starts with a LEGO sales dataset containing information such as:

- Set Name
- Set ID
- Theme Group
- Theme
- Category
- Number of Pieces
- Price
- Year
- Product details

---

## 🧹 2️⃣ Data Cleaning & Preparation

The raw LEGO dataset was prepared before building the Power BI dashboard.

The data preparation process included:

- Checking the dataset structure
- Identifying missing values
- Removing duplicate records
- Cleaning column names
- Correcting data types
- Cleaning numerical fields such as price and pieces
- Standardizing category and theme values
- Preparing the final dataset for analysis

---

## 📊 3️⃣ Power BI Dashboard

Microsoft Power BI was used to create an interactive LEGO analysis dashboard.

### 📌 Key KPIs

- 🧱 **Total Sets:** 18K
- 🔢 **Average Pieces:** 227.86
- 💰 **Average Price:** $172

The dashboard also supports dynamic filtering, allowing users to explore LEGO products based on different categories and themes.

---

## 🎛️ Interactive Filters

The dashboard includes filters for:

- Category
- Theme Group
- Theme
- Set Name
- Price Range

These filters allow users to dynamically explore different LEGO products.

---

## 📈 Dashboard Analysis

### 🧱 Product Analysis

The dashboard provides detailed information about:

- LEGO Set Name
- Set ID
- Theme
- Average Price
- Average Pieces
- Release Year

### 🎨 Theme Analysis

The dashboard analyzes LEGO sets across different:

- Theme Groups
- Themes
- Categories

### 📊 Category Analysis

The dashboard provides insights into different LEGO product categories and their contribution to the total number of sets.

### 🔍 Product Details

When a LEGO set is selected, the dashboard displays detailed information including:

- Set Name
- Product Image
- Price
- Year
- Number of Pieces

---

## 🌳 Hierarchical Analysis

A hierarchy-based analysis was created to explore LEGO products from a broader category to individual sets.

```text
Total Sets
     ↓
Category
     ↓
Theme Group
     ↓
Theme
     ↓
Set Name
