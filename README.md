# hackathon-food-delivery-project
# Hackathon Food Delivery Data Analysis 🚀🍔

This project analyzes a food delivery dataset to uncover business insights using Python, Pandas, and data visualization techniques. The goal is to answer real-world business questions related to revenue, customer behavior, memberships, cities, cuisines, and restaurant performance.

---

##  Files in This Repository

| File Name | Description |
|----------|-------------|
| `hackathon_food_delivery.ipynb` | Main Jupyter Notebook with full analysis |
| `final_food_delivery_dataset.csv` | Cleaned and merged dataset used for analysis |
| `README.md` | Project explanation |

---

##  Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

##  Project Workflow

### 1️ Data Loading
Loaded three datasets:
- `orders.csv`
- `users.json`
- `restaurants.sql`

---

### 2️ Data Cleaning
- Removed duplicates
- Handled missing values using appropriate methods
- Converted data types
- Standardized column names

---

### 3️ Data Merging
Merged datasets using:
- `user_id` → Orders + Users
- `restaurant_id` → Orders + Restaurants

Final merged dataset saved as:
📁 `final_food_delivery_dataset.csv`

---

### 4️ Business Questions Answered

✔ Which city has the highest revenue from Gold members  
✔ Which cuisine has the highest average order value  
✔ Which restaurant rating range generates maximum revenue  
✔ What percentage of users are Gold members  
✔ How many users placed orders above ₹1000  
✔ Which restaurant has the highest AOV with fewer than 20 orders  
✔ Which combination of membership and cuisine generates highest revenue  
✔ Quarterly revenue trends  
✔ Orders by rating range and city  
✔ Gold vs Regular customer analysis  

---

##  Visualizations

The notebook includes:
- Revenue by city
- Revenue by cuisine
- Rating vs revenue
- Membership comparison charts
- Quarterly revenue trend graphs

All visualizations are created using **Matplotlib**.

---

##  Key Insights

- Gold members contribute significantly higher revenue.
- Restaurants with ratings **4.6 – 5.0** generate maximum revenue.
- Italian and Mexican cuisines show strong performance.
- Chennai and Hyderabad are top-performing cities.
- Customers with fewer but high-value orders contribute more to revenue.

---
