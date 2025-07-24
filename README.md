# Prestige Auto Data Analysis

This project presents a complete data analysis pipeline for **Prestige Auto**, an automobile sales company. Using Python and Jupyter Notebook, the project explores, cleans, and visualizes dealership data to extract meaningful insights on sales trends, vehicle types, and key performance metrics.

---

## Project Objective

To conduct thorough **exploratory data analysis (EDA)** and **data cleaning** on the Prestige Auto dataset in order to:

* Understand the structure and content of the data.
* Clean and prepare it for analysis by selecting relevant columns and handling missing values.
* Discover business insights related to sales volume, vehicle types, fuel preferences, and customer purchase behavior.

---

##  Dataset Description

The dataset contains sales records with the following key columns:

* `description` – Vehicle description
* `amount` – Selling price
* `region` – Geographical location
* `make`, `model` – Vehicle brand and model
* `year_of_man` – Year of manufacture
* `condition`, `bought_cond`, `selling_cond` – Condition at different stages
* `mileage`, `engine_size`, `horse_power` – Technical specifications
* `fuel_type`, `transmission` – Fuel and transmission type

---

##  Analysis Steps

### 1. **Data Exploration**

* Loaded the dataset (`prestige_data.csv`) into pandas.
* Used `.head()`, `.tail()`, `.shape`, `.info()`, `.describe()` to understand the dataset structure.
* Plotted histograms to observe feature distributions.

### 2. **Data Cleaning**

* Selected a subset of relevant columns based on analysis objectives.
* Checked and handled missing values in key fields like `mileage`, `year_of_man`, and `transmission`.
* Used statistical imputations (e.g. mode, mean) where appropriate.

### 3. **Insights Extraction**

* Explored year-wise and model-wise sales frequency.
* Analyzed fuel type popularity.
* Examined car conditions across various categories.
* Evaluated engine sizes and mileage patterns.
* Compared manual vs automatic transmission distributions.
* Identified most frequent vehicle brands and regions.

---

## 📈 Key Visualizations

* **Histograms** – To explore frequency distributions across multiple variables.
* **Bar Charts** – For ranking car models, fuel types, and transmission categories.
* **Pie Charts** – Showing share of popular brands or car conditions.
* **Box Plots / Strip Plots** – (if added) could reveal price vs feature trends.

---

## 🛠️ Technologies Used

* **Python 3**
* **Jupyter Notebook**
* **pandas** – data manipulation
* **matplotlib & seaborn** – static visualizations
* **plotly.express** – interactive charts
* **numpy** – numerical operations

---

## 💡 Business Insights (Examples)

* **Toyota and Honda** models appeared frequently, suggesting high demand.
* **Petrol-powered** vehicles dominated sales.
* **Automatic transmission** had slightly higher sales volume than manual in certain regions.
* **Most vehicles** were sold in fairly good condition but not new.
* **Branch-level and regional data** (if extended) can drive localized strategies.

---

## 📁 Project Structure

```
Prestige-Auto-Analysis/
│
├── Day 14 Prestige auto data analysis.ipynb   # Main notebook
├── prestige_data.csv                          # Raw data file (external)
├── README.md                                  # Project documentation
└── requirements.txt                           # (Optional) Python packages list
```

---

## How to Run the Notebook

1. Clone the repository or download the files.

2. Ensure you have the required packages:

```bash
pip install pandas matplotlib seaborn plotly
```

3. Launch Jupyter Notebook and open:

```bash
jupyter notebook "Day 14 Prestige auto data analysis.ipynb"
```

---



---

## Author

**Peter Akpobiebode Ogoba**
📧 Email: \[[peterogoba@gmail.com](mailto:peterogoba@gmail.com)]
🔗 GitHub: [https://github.com/Spacecloudsky](https://github.com/Spacecloudsky)
