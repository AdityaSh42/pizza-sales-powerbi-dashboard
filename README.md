# 🍕 Pizza Sales Analysis Dashboard — Power BI

## 📊 Project Overview

This project is an interactive **Pizza Sales Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of this project is to analyze one year of pizza sales data and transform the raw data into meaningful business insights. The dashboard provides an overview of sales performance, customer ordering patterns, pizza preferences, and time-based sales trends.

The project uses multiple related CSV datasets and demonstrates practical skills in **data modeling, DAX, calculated columns, and interactive data visualization**.

---

## 📁 Dataset

The dataset consists of four CSV files:

| File                | Description                                                            |
| ------------------- | ---------------------------------------------------------------------- |
| `orders.csv`        | Contains order date and time information                               |
| `order_details.csv` | Contains details of pizzas included in each order and their quantities |
| `pizzas.csv`        | Contains pizza information such as price, size, and pizza type         |
| `pizza_types.csv`   | Contains pizza names, categories, and ingredients                      |

The raw datasets are available in the [`dataset`](./dataset) folder.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **DAX**
* **Power Query** for data import and preparation
* **CSV** datasets
* **Data Modeling**
* **Data Visualization**

---

## 📈 Dashboard Analysis

The dashboard was designed to analyze several aspects of pizza sales, including:

* Total revenue
* Total orders
* Total pizzas sold
* Average order value
* Average pizzas per order
* Sales trends over time
* Busiest days and time slots
* Pizza category preferences
* Best-selling pizzas
* Sales by pizza size
* Category-wise sales performance

---

## 🔍 Key Insights

### 🍕 Preferred Pizza Categories

The dashboard shows that customer preferences are relatively evenly distributed across the four pizza categories.

* **Classic pizzas** have the highest share at **29.02%**, making them the most preferred category.
* **Veggie pizzas** account for **24.28%** of the distribution.
* **Supreme pizzas** account for **23.89%**.
* **Chicken pizzas** have the lowest share at **22.81%**.

The difference between the most and least preferred categories is only **6.21 percentage points**, indicating that customer demand is fairly balanced across the four categories rather than being dominated by a single category.

### 📊 Overall Category Distribution

| Category |  Share |
| -------- | -----: |
| Classic  | 29.02% |
| Veggie   | 24.28% |
| Supreme  | 23.89% |
| Chicken  | 22.81% |

Classic pizzas therefore represent the largest portion of the category distribution, while Chicken pizzas represent the smallest.

---

## 💡 Business Questions Explored

The dashboard was developed to answer questions such as:

1. How much revenue was generated from pizza sales?
2. How many orders were placed?
3. How many pizzas were sold?
4. What is the average order value?
5. What is the average number of pizzas per order?
6. Which pizza category is preferred by customers?
7. Which pizza sizes are most popular?
8. Which pizzas are the best sellers?
9. What are the busiest days and time slots?
10. How do pizza sales change over time?

---

## 📂 Repository Structure

```text
pizza-sales-powerbi-dashboard/
│
├── dataset/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── screenshots/
│   └── dashboard screenshots
│
├── Pizza_Sales_Dashboard.pbix
│
└── README.md
```

---

## 📊 Power BI Dashboard

The Power BI dashboard is provided as:

`Pizza_Sales_Dashboard.pbix`

To explore the dashboard interactively, download the `.pbix` file and open it using **Microsoft Power BI Desktop**.

---

## 🧠 Skills Demonstrated

This project demonstrates practical experience with:

* Importing and working with multiple CSV datasets
* Data cleaning and preparation
* Relational data modeling
* Establishing relationships between tables
* Creating DAX measures
* Creating calculated columns
* Time-based analysis
* Categorizing data into time slots
* Building interactive Power BI dashboards
* Creating business-focused visualizations
* Extracting insights from sales data

---

## 👤 Author

**Aditya Sharma**

B.Tech — Computer Science Engineering
MANIT Bhopal
