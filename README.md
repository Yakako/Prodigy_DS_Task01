# Task-01: Population Distribution Visualization
---

# 📄 Project Overview
This task focuses on visualizing the distribution of a population variable using a dataset from the World Bank. The goal is to create clear and informative graphs that show how populations vary across countries.

# 🗂 Dataset
- Source: World Bank Population Dataset
- Structure:
     - Column	Description
     - Country Name	Name of the country
     - Country Code	3-letter ISO country code
     - 1960–2024	Population for each year

For this task, we focused on the 2024 population column for visualization.

# 🧹 Data Cleaning

- mRemoved irrelevant columns ( Unnamed: 69)
- Handled missing values using forward fill and backward fill, keeping all countries
- Selected key columns: Country Name, Country Code, Population_2024
- Removed regional/aggregate entries ("World", "High income")
- Final dataset contains only valid countries with clean population data

---

# ✅ Key Learnings
- Handling missing data in time-series datasets without losing rows
- Selecting meaningful columns for visualization
- Using modern visualization techniques ( histogram, horizontal bar chart)
- Effectively communicating skewed data patterns
---

# 👤 Author
- Name: Pruonh Kimliya
- Email: kimliyapruonh@gmail.com
