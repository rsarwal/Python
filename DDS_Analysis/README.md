# Python DDS Analysis - Vocational Rehabilitation Consumers' Insights Analysis

This repository contains Python-based analysis and a PowerBI dashboard focused on the **Vocational Rehabilitation Consumers' Insights**. The analysis involves handling and processing consumer data, identifying trends, and generating insights using Python, with the final output visualized using a PowerBI dashboard.

## Project Overview

This project aims to analyze the consumer data from Vocational Rehabilitation programs. It uses Python for data cleaning, exploration, and processing, and integrates the analysis with a PowerBI dashboard for visualization and actionable insights. 

## Python DDS Analysis

The **Python DDS Analysis** part of the project focuses on:
1. **Data Cleaning**: Handling missing values, replacing placeholder data, and correcting any inconsistencies.
2. **Data Aggregation**: Grouping data by various features such as County and Race/Ethnicity, calculating consumer totals, and analyzing trends over time.
3. **Exploratory Data Analysis (EDA)**: Exploring the dataset with visualizations to highlight key trends and distributions.
4. **Visualizing with Python**: Utilizing libraries like `matplotlib` and `seaborn` to plot graphs for trends, distributions, and correlations.

### Key Analysis Features:
- Data loading and cleaning from a CSV file (`dds_test.csv`).
- Handling missing or incorrect values.
- Aggregating consumer data by County and Race/Ethnicity.
- Visualizations showing consumer trends over time.
- Saving the cleaned data into a new CSV (`cleaned_dds_test.csv`).

#### Notable Python Libraries:
- `pandas`
- `matplotlib`
- `seaborn`
  
#### Key Code Files:
- `DDS.ipynb`: Jupyter Notebook containing the full analysis and visualizations.

## PowerBI Dashboard: **Vocational Rehabilitation Consumers' Insights**

This project also includes a **PowerBI dashboard** which visualizes the insights gained from the Python analysis. The dashboard is designed to present actionable insights for decision-makers involved in Vocational Rehabilitation programs.

### Features of the PowerBI Dashboard:
- **Consumers' Breakdown**: Visualizations showing the number of consumers across various counties and race/ethnicity groups.
- **Time-based Trends**: Analysis of consumer trends over different years.
- **Correlation Analysis**: Identifying key relationships between variables to help understand factors influencing consumer participation.

#### Dashboard Link:
[View Vocational Rehabilitation Consumers' Insights Dashboard PDF](https://github.com/rsarwal/PowerBI/blob/99607f634d462f899a1cea438c55b3624ec19533/Vocational%20Rehabilitation%20Consumers'%20Insight/DDS.pdf)

---

## Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- Required Python libraries listed in the `requirements.txt` file.
- PowerBI Desktop (for the dashboard file)

### Installing Dependencies

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/rsarwal/Python.git
   cd Python/Vocational_Rehabilitation
   ```

2. Install the necessary Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Python Analysis

1. Open the `DDS.ipynb` file in Jupyter Notebook or any compatible environment.
2. Run the code cells sequentially to load the data, perform cleaning, and generate insights.
3. Visualizations will be displayed directly in the notebook.

---

## Folder Structure

```
/Vocational_Rehabilitation
    /DDS_Analysis
        DDS.ipynb            # Jupyter notebook with analysis
        .gitignore            # Git ignore file
        requirements.txt      # Python dependencies
    /PowerBI
        DDS.pdf               # PowerBI dashboard insights (PDF)
    README.md                # Project overview and documentation
```

---

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to fork the repository and create a pull request.
