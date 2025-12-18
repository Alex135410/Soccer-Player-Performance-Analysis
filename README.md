FIFA Player Performance Analysis
================================

An exploratory data analysis project that examines FIFA player statistics to identify trends, top performers, and relationships between player efficiency, position, age, and market value.

Table of Contents
-----------------

*   [Architecture](#architecture)
    
*   [Environment](#environment)
    
*   Executing the Analysis
    

Architecture
------------

This project follows a **data analysis workflow**:

*   **Data (Raw & Cleaned):**
    
    *   Raw dataset of FIFA player statistics is stored in CSV format (data/raw/fifa\_players\_raw.csv).
        
    *   Cleaned dataset with processed numeric and feature-engineered columns is saved to data/cleaned/fifa\_players\_cleaned.csv.
        
*   **Analysis (Notebook):**
    
    *   Conducted in a Jupyter Notebook (Notebooks/soccer\_analysis.ipynb).
        
    *   Steps include:
        
        *   Loading and inspecting the dataset
            
        *   Cleaning and formatting text and numeric data
            
        *   Feature engineering (e.g., goals per appearance, total contribution per appearance)
            
        *   Exploratory data analysis with visualizations such as histograms, boxplots, scatter plots, and correlation heatmaps
            
        *   Documenting insights using Markdown cells
            
*   **Visualization & Reporting:**
    
    *   Visualizations created using Python libraries: Matplotlib and Seaborn.
        
    *   Markdown cells explain observations, trends, and key insights.
        

Environment
-----------

To run this project locally, your device should have:

*   **Python 3.7+** installed
    
*   **pip** (Python package installer)
    
*   **Jupyter Notebook** for interactive analysis
    
*   Python packages:
    
    *   pandas
        
    *   numpy
        
    *   matplotlib
        
    *   seaborn
        

> Recommended to use a virtual environment (e.g., venv) to isolate dependencies.

Executing the Analysis
----------------------

Follow these steps to run the project locally:

1.  git clone https://github.com/Alex135410/Soccer-Player-Performance-Analysis.git
    
2.  python3 -m venv venvsource venv/bin/activate # On Windows use: venv\\Scripts\\activate
    
3.  pip install pandas numpy matplotlib seaborn jupyter
    
4.  jupyter notebook
    
5.  **Open the analysis notebook**
    
    *   Navigate to Notebooks/soccer\_analysis.ipynb in the Jupyter interface.
        
6.  **Run each cell sequentially**
    
    *   Inspect the data, perform cleaning, create new features, and visualize trends.
        
    *   Read Markdown cells for explanations and observations.
        
7.  **Explore insights**
    
    *   Analyze player performance, efficiency metrics, correlations, and top performers.
        
    *   Optionally, export visualizations or the cleaned dataset for further use
        

**Skills Demonstrated**

1.  Data Cleaning & Preprocessing (handling missing values, converting data types, removing duplicates)
    
2.  Feature Engineering (creating metrics like goals per appearance and total contribution per appearance)
    
3.  Exploratory Data Analysis (histograms, boxplots, scatter plots, and heatmaps)
    
4.  Data Visualization with Python (Matplotlib & Seaborn)
    
5.  Documentation & Communication (Markdown explanations, insights, and reporting)

