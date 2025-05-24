#  Retail Sales Data Analysis Project

This project focuses on analyzing retail sales data using Python-based tools. The goal is to uncover sales trends, seasonal patterns, top-performing products, and other business insights through data analysis — without involving machine learning or SQL.

## 🛠 Tools & Libraries Used

- **Python** - Core programming language
- **Pandas** - For data cleaning, manipulation, and aggregation
- **NumPy** - For numerical operations
- **Matplotlib** - For creating static data visualizations

##  Project Objectives

- Analyze monthly and yearly sales trends
- Identify seasonality in customer purchasing behavior
- Determine top-selling products over time
- Provide insights on sales growth and performance patterns

##  Project Structure

```
sales-data-analysis/
├── data/                 # Raw and cleaned datasets (CSV)
├── notebooks/            # Jupyter/Colab notebooks with code and visualizations
├── images/               # Exported charts/graphs
├── report/               # Final report (PDF)
├── README.md             # Project documentation
└── requirements.txt      # List of required packages
```

##  Key Findings

- **Sales Trends**: Clear monthly and yearly growth patterns were observed
- **Seasonality**: Sales peaked during specific months, indicating strong seasonal behavior
- **Top Products**: A small subset of products accounted for a large portion of total sales


##  Limitations

- This analysis does not include SQL or database queries (yet)
- Assumes clean, structured sales data in CSV format
- Does not incorporate customer demographics or external factors like promotions

##  How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DuncanMainya/Sales-data-analysis-.git
   cd sales-data-analysis
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the analysis:**
   - Open Jupyter/Colab notebook in the `notebooks/` directory
   - Or check the exported report in `/report`

### Example Usage Scenario
A retail chain manager could use this analysis to:
- Identify their best-selling products during Q4 holiday season
- Determine optimal inventory levels for different months
- Plan promotional campaigns based on historical sales patterns

##  Future Work

- Add SQL queries for deeper analysis
- Integrate dashboards using tools like **Plotly**, **Dash**, or **Streamlit**
- Expand analysis to include **customer segmentation** and **regional sales breakdown**

##  Author

**Duncan Mainya**

