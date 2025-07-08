# 🧪 Data Analysis Project: Optimizing Land Use in Agroforestry Farms  
## Supporting Food Security in Burundi

> This repository contains the complete data analysis workflow conducted as part of a study on optimizing land use and crop productivity in agroforestry systems in Burundi.  
>  
> 🔍 **Role**: Data Analyst | 📊 Tools: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)  
>  
> 👥 Supervised by: University of Burundi – Faculty of Agronomy and Bioengineering  

---

## 🎯 Project Objectives

This project supports agricultural development in Burundi by analyzing socio-economic data collected from smallholder farmers in two communes: **Giheta** and **Rutegama**.

The main goals of the analysis were:
- To assess profitability and land allocation patterns across different crops
- To model optimal crop combinations using mathematical programming
- To inform strategies for improving food security through diversified farming practices
- To support policy recommendations for sustainable land use and youth engagement in agriculture

---

## 🧩 Problem Statement

Smallholder farmers in Burundi face multiple challenges:
- Limited arable land due to population pressure and soil erosion
- Low profitability from traditional monocultures
- Inadequate access to markets and modern agricultural inputs
- Climate change impacts and environmental degradation

The goal was to identify high-yield, high-profit crop combinations that can be integrated into **agroforestry systems**, helping farmers improve income while ensuring long-term sustainability.

---

## 🧑‍💻 My Role as Data Analyst

I was responsible for the full end-to-end data analysis process, including:

### 1. **Data Preparation**
- Cleaned and structured raw survey data collected via **KoBoCollect** software
- Handled missing values, outliers, and inconsistencies in household responses
- Transformed categorical variables and encoded features for modeling

### 2. **Exploratory Data Analysis (EDA)**
- Visualized demographic characteristics (age, education, family size)
- Analyzed crop distribution and area allocation
- Calculated profit margins per crop
- Identified key drivers of profitability and risk

### 3. **Modeling Support**
- Preprocessed data for input into a **mathematical programming model** aimed at maximizing farm profits under resource constraints
- Provided statistical insights to guide model assumptions (e.g., yield estimates, cost structures)

### 4. **Result Interpretation**
- Created visualizations comparing current farming practices vs optimized scenarios
- Helped validate findings with stakeholders and field experts
- Delivered insights for academic publication and policy briefs

---

## 🛠️ Technical Workflow

### 📁 Data Collection
- Survey data collected from **164 households** grouped in coffee cooperatives
- Variables included:
  - Demographic info (age, gender, education level)
  - Farm characteristics (total area, crops grown)
  - Production costs and revenues
  - Household food security indicators

### 🧹 Data Cleaning
- Used **Pandas** to handle missing values and inconsistent entries
- Normalized data for cross-household comparisons
- Encoded categorical variables (e.g., education levels)

### 📊 Exploratory Data Analysis (EDA)
- Libraries used:
  - `Matplotlib`, `Seaborn`: For plotting distributions, bar charts, and scatter plots
  - `Pandas`, `NumPy`: For descriptive statistics and grouping operations
- Key outputs:
  - Distribution of age, education, and household size
  - Crop-wise land allocation and profitability
  - Profit margin comparisons across crops

### 📈 Modeling Inputs
- Prepared datasets for optimization modeling:
  - Cost per hectare
  - Yield per hectare
  - Market prices
  - Budget and land constraints
- Supported the following objective function:
  ```
  Maximize Z = ∑(Revenue_j × Area_j − Cost_j × Area_j)
  ```

### 📋 Constraints Included
- Total available land per plot
- Total production budget
- Minimum yield requirements
- Strategic crop limits (minimum/maximum area)

### 📊 Visualization Highlights
- Figure 1: Age distribution of household heads
- Figure 2: Education levels among farmers
- Figure 3: Crop-wise cultivated area
- Figure 4: Profit margins per crop
- Figure 5: Comparison of current vs optimized profit scenarios

---


## 🧰 Tools & Technologies

| Tool           | Purpose |
|----------------|---------|
| **Python 3.12** | Main language for data processing and analysis |
| **Pandas**      | Data manipulation and transformation |
| **NumPy**       | Numerical computations and array handling |
| **Matplotlib**  | Basic plotting and chart generation |
| **Seaborn**     | Advanced statistical visualizations |
| **Scikit-learn**| Optional ML techniques for classification/regression |
| **Statsmodels** | Statistical modeling and hypothesis testing |

---

## 📌 How to Reproduce the Analysis

1. Clone this repository:
```bash
   git clone https://github.com/yourusername/agroforestry-burundi.git
   ```

2. Install required packages:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
   ```

3. Run the data cleaning script:
```bash
   python code/clean_data.py
   ```

4. Generate EDA visualizations:
```bash
   python code/eda.py
   ```

5. Prepare inputs for modeling:
```bash
   python code/prepare_model_inputs.py
   ```

6. View results in the `figures/` directory or run the notebook:
```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

---

## 📄 References

- [Original SCIRP Paper](https://www.scirp.org/journal/paperinformation?paperid=140018)  
- Niyonzima, A. et al. (2025). *Optimizing Model Land Use and Crop Productivity in Agroforestry Farms for Food Security of Small Farmers in Burundi*. Agricultural Sciences, 16, 123-145. https://doi.org/10.4236/as.2025.161008

---

## 🤝 Contributions

Contributions are welcome! If you'd like to add more visualizations, expand the analysis, or translate the summary into another language, feel free to open an issue or submit a pull request.

---

## 📮 Contact

If you have any questions about the data or methodology, or if you’re interested in collaboration, feel free to reach out:

📧 Email: [rajajodick@gmail.com]  
📍 Location: [Nairobi/Kenya]  
🔗 LinkedIn/GitHub: [https://github.com/Jodick-Ndayisenga]

---# Optimizing-Land-Use-in-Agroforestry-Farms
