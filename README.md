# Python-Final-Project-California-Housing-Price-Analysis
This project uses data processing, visualization, and predictive modeling techniques using tools learned throughout the semester. The analysis focuses on California housing price trends using Zillow housing data, incorporating data cleaning, time series analysis, statistical modeling, and visualization to better understand housing growth patterns.  
# Project Structure  
python_final_project/  
├── data_raw/                       
│   └── zillow_housing_raw.csv        # Raw Zillow housing dataset  
├── data/                              
│   └── zillow_california_clean.csv  # Cleaned California-only dataset (generated)  
├── src/                               
│   ├── __init__.py                   
│   ├── data_processing.py          # Data loading & cleaning functions  
│   └── analysis.py                 # Analysis, visualization, modeling functions  
├── notebook.ipynb                  # Main analysis notebook  
└── README.md                       # This file  

# Requirements  

- Python 3.7+  
- pandas  
- matplotlib  
- numpy  
- scikit-learn  
- jupyter
# Installation and Setup  
# Local Execution  

1. Clone this repository:   
``` git clone https://github.com/YOUR-USERNAME/math120_final_project.git ```  
```cd python_final_project```  
2. Install required packages (if needed):  
```pip install pandas matplotlib numpy scikit-learn jupyter```  
3. Launch Jupyter Notebook:  
``` jupyter notebook notebook.ipynb ```
4. Download Zillow ZHVI, rename to zillow_housing_raw and add to drive, Fall 120 > raw_data
# Google Colab Execution  
1. Open Google Colab  
2. Upload the notebook.ipynb file or connect to your GitHub repository  
3. Run the first cell to automatically set up the environment  
# Data Description
* Zillow Housing Data: Monthly median home values by city and region
* Original source: Zillow Research Data
*  Key variables include:
  - RegionName (city/region)
  - State
  - County
  - Monthly median home prices (time-series columns)  
# Limitations:
- Some cities have missing monthly values
- Data availability varies by region
- Dataset size is large and must be filtered
# Analysis Features
- Data loading and cleaning
- Filtering to California-specific data
- Time-series trend analysis
- Regional price growth comparisons
- Linear regression modeling for price prediction
- Data visualization using matplotlib
- Modular code organization
- Visualize time-series housing price trends per city
- Create multi-city comparison plots
- Calculate growth rates for major California cities
- Apply rolling-average smoothing to reveal trends
- Fit linear regression and polynomial regression (degree 2) models
- Compare model predictions vs. actual prices
- Evaluate model performance using Mean Absolute Error (MAE)
# Key Learning Objectives Demonstrated
- File I/O operations with pandas
- Data cleaning and preprocessing
- Time-series visualization
- Statistical modeling
- Regression analysis
- Function creation and modular programming
- Environment compatibility (local vs. cloud)

# Usage
- Run all cells in ```notebook.ipynb``` sequentially. The notebook will:
- Load the raw Zillow dataset
- Clean and filter California housing data
- Perform exploratory data analysis
- Generate visualizations
- Train a regression model
- Evaluate predictions
- Save processed data to the ```data/``` folder

# Author  

Elliot Wiley  
MATH 120 – Final Project  
Fall 2025  
