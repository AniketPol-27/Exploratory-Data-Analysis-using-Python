# Exploratory-Data-Analysis-using-Python🛒
A comprehensive **Exploratory Data Analysis (EDA)** project analyzing customer purchasing behavior, product popularity, and order trends. This project helps optimize inventory, personalize marketing strategies, and improve customer retention through better product recommendations and timing of promotions.

---

## Project Overview

The goal of this project is to understand:

- Customer purchasing behavior
- Product popularity across aisles and departments
- Temporal ordering patterns
- Reorder tendencies
- Basket size patterns
- Trends by hour, day of week, and days since last order

Insights can be used to optimize **inventory management**, improve **marketing campaigns**, and enhance **customer experience**.

---

## Dataset Description

The analysis uses the following datasets:

| Dataset | Description |
|---------|-------------|
| `order_metadata.csv` | Metadata of customer orders including order time and prior order gaps |
| `order_items_train.csv` | Items in each order including reorder information |
| `product_catalog.csv` | Product information including IDs, names, aisle, and department |
| `department_info.csv` | Department names corresponding to department IDs |
| `aisle_info.csv` | Aisle names corresponding to aisle IDs |

---

## Libraries Used

- `pandas` – Data manipulation and analysis  
- `matplotlib` – Static visualizations  
- `seaborn` – Enhanced statistical visualization  

---

## Exploratory Data Analysis (EDA)

### 1. Total Number of Orders and Unique Customers

- Provides a high-level view of the dataset size and customer base.
- Metrics calculated:
  - Total Orders
  - Unique Customers

---

### 2. Number of Unique Products, Aisles, and Departments

- Understands diversity of products.
- Metrics calculated:
  - Unique Products
  - Unique Aisles
  - Unique Departments

---

### 3. Top 20 Most Frequently Ordered Products

- Lists the most popular products among customers.
- Highlights products that drive most orders.

---

### 4. Top Departments and Aisles by Order Volume

- **Departments:** Bar chart shows the top 10 departments by order count.
  - Helps identify which departments contribute most to sales.
- **Aisles:** Bar chart shows the top 10 aisles by order count.
  - Useful for aisle-level inventory management and targeted promotions.

---

### 5. Most Reordered Products (Highest Reorder Rate)

- Identifies products with the highest likelihood of being reordered.
- Valuable for predictive inventory and subscription services.

---

### 6. Average Basket Size

- Basket size = Number of items per order.
- Helps understand customer buying patterns and optimize packaging or bundle offers.

---

### 7. Order Trends

- **Orders by Hour of the Day:** Identifies peak ordering hours for customers.  
- **Orders by Day of the Week:** Highlights weekly patterns in shopping behavior.  
- **Days Since Prior Order:** Histogram of repeat purchase frequency.  
- Useful for targeting marketing campaigns and optimizing inventory.

---

## Visualizations

1. **Top Departments by Order Volume**  
   Shows departments contributing the most orders.

2. **Top Aisles by Order Volume**  
   Highlights aisles with highest order counts.

3. **Orders by Hour of Day**  
   Displays peak hours of ordering.

4. **Orders by Day of Week**  
   Shows weekly ordering trends.

5. **Distribution of Days Since Prior Order**  
   Shows repeat purchase patterns among customers.

> Note: Replace placeholder images with actual generated plots in your repository.

---

## Key Insights

- Certain products and departments dominate customer orders.
- Reorder behavior highlights staple products for repeat customers.
- Average basket size helps define typical order structure.
- Ordering patterns vary by hour and day, providing opportunities for targeted promotions.


