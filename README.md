# COVID-19 Variant Data Analysis & Visualization

This repository contains two data analysis projects focused on exploring COVID-19 variant data through different visualization techniques. Using Python's powerful data science libraries, these notebooks transform raw case data into meaningful graphical insights.

## 📊 Projects Overview

### 1. COVID-19 Cases by Variant (Bar Graph Analysis)

Located in `bar graph .ipynb`, this project focuses on filtering and analyzing the impact of different COVID-19 variants within a specific target country.

* **Target Country**: Specifically configured for data analysis of India.
* **Key Features**:
* Data filtering using `pandas`.
* Aggregating total case counts by variant.
* Static visualization using `matplotlib` with customized labels and rotation for readability.



### 2. Global Variant Distribution (Interactive Sunburst Map)

Located in `map.ipynb`, this notebook provides a hierarchical view of how variants are distributed across various countries.

* **Key Features**:
* Multi-level hierarchical analysis (Variant > Country).
* Interactive sunburst chart created with `plotly.express`.
* Visual encoding where the size represents **Total Cases** and color intensity represents **Recovered** patients using an 'icefire' color scale.



## 🛠️ Requirements

To run these notebooks, you will need the following Python libraries installed:

```bash
pip install pandas matplotlib plotly

```

## 📂 Dataset

The analysis is based on a dataset titled `covid_variants_dataset.csv`. This file includes columns for:

* **Variant**: The specific strain of COVID-19.
* **Country**: The geographic location.
* **Cases**: Total number of confirmed cases.
* **Recovered/Deaths**: Outcomes for the reported cases.

## 🚀 Getting Started

1. Clone this repository to your local machine.
2. Ensure `covid_variants_dataset.csv` is in the same directory as the notebooks.
3. Open the Jupyter Notebooks using your preferred environment (JupyterLab, VS Code, etc.).
4. Run all cells to generate the visualizations.
