

---

# 🚴‍♂️ Bike Sales Dashboard Dataset

## 📋 Overview

The **Bike Sales Dashboard dataset** offers detailed insights into customer demographics and their decisions regarding bike purchases. It is valuable for:

* Analyzing consumer behavior
* Identifying trends in purchasing patterns
* Building predictive models for bike-buying likelihood

This dataset is ideal for **data analysts**, **marketers**, and **retail/cycling industry professionals**.

---

## 📑 Dataset Description

* **Records:** 1,000 customers
* **Structure:** Each record represents one customer
* **Focus:** Demographic, socio-economic factors, and purchase decision (bike bought or not)

---

## 📊 Columns

| Column             | Description                                                                 |
| ------------------ | --------------------------------------------------------------------------- |
| `ID`               | Unique identifier for each customer                                         |
| `Marital Status`   | Customer's marital status (`Married`, `Single`)                             |
| `Gender`           | Customer's gender (`Male`, `Female`)                                        |
| `Income`           | Annual income in USD                                                        |
| `Children`         | Number of children                                                          |
| `Education`        | Education level (e.g., `Bachelors`, `High School`, `Graduate Degree`, etc.) |
| `Occupation`       | Job type (e.g., `Professional`, `Clerical`, `Management`)                   |
| `Home Owner`       | Home ownership status (`Yes`, `No`)                                         |
| `Cars`             | Number of cars owned                                                        |
| `Commute Distance` | Commute range (e.g., `0-1 Miles`, `>10 Miles`)                              |
| `Region`           | Geographic location (`Europe`, `Pacific`, `North America`)                  |
| `Age`              | Numeric age                                                                 |
| `Purchased Bike`   | Bike purchase status (`Yes`, `No`)                                          |
| `Age Group`        | Age categorization (`Younger`, `Adult`, `Old`)                              |

---

## 📈 Summary Statistics

### 💰 Average Income

* **Female:** \$54,580.78
* **Male:** \$58,062.62
* **Overall:** \$56,360

### 🚗 Purchase Distribution by Commute Distance

| Commute Distance | Total | Purchased | Not Purchased |
| ---------------- | ----- | --------- | ------------- |
| 0-1 Miles        | 366   | 200       | 166           |
| 1-2 Miles        | 169   | 77        | 92            |
| 2-5 Miles        | 162   | 95        | 67            |
| 5-10 Miles       | 192   | 76        | 116           |
| >10 Miles        | 111   | 33        | 78            |

### 👥 Purchase Distribution by Age Group

| Age Group | Total | Purchased | Not Purchased |
| --------- | ----- | --------- | ------------- |
| Younger   | 110   | 39        | 71            |
| Adult     | 701   | 383       | 318           |
| Old       | 189   | 59        | 130           |

* **Total Customers:** 1,000
* **Purchased Bike:** 481
* **Did Not Purchase Bike:** 519

---

## 💡 Potential Use Cases

* **Customer Segmentation:** Identify target markets using age, income, and occupation.
* **Predictive Modeling:** Predict bike purchase likelihood.
* **Market Analysis:** Understand the influence of commute, region, income, etc.
* **Business Strategy:** Create tailored marketing campaigns.

---

## 🧪 How to Use

1. **Load the Data**: Import `Bike Sales Dashboard.xlsx` into tools like Python (pandas), R, or Excel.
2. **Explore**: Use descriptive statistics and visualization tools.
3. **Analyze**: Apply statistical or ML models.
4. **Visualize**: Build dashboards or charts for insights.

---

## ❓ Example Analysis Questions

* How does **income** affect bike purchases?
* Are **short-distance commuters** more likely to buy bikes?
* Which **demographics** (gender, age, occupation) buy more bikes?
* Does **home ownership** or **car ownership** impact purchases?

---

## 📌 Notes

* Dataset is **clean**, with **no missing values**.
* `Age Group` provides a simplified way to analyze age-based behavior.
* Suitable for both **beginner** and **advanced** data analysts.

---

## 📄 License

This dataset is provided for **educational and analytical purposes**.
Please **cite appropriately** if used in public projects.

---

## 📬 Contact

For questions or contributions, feel free to **open an issue or pull request** in this GitHub repository.

---

