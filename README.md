
# Week 1 - Project: Data Analysis for Business Insights

<b> Scenario </b>:
You are a Data Analyst working for ShopEase, an online retail company. The company wants to improve sales performance and customer satisfaction by analysing its sales data. Your task is to:
1) Collect & Clean Data - A dataset with sales transactions is provided. Your first task is to inspect the data, remove duplicates, handle missing values, and standardize formats.
2) Explore Data - Identify key trends, seasonal sales patterns, and correlations (e.g., sales vs. advertising spend).
3) Visualize Findings - Create at least three visualizations (e.g., bar charts, line graphs, heatmaps) to present key insights.
4) Analyse Customer Behaviour - Identify the most popular product categories, best-selling months, and any customer purchase trends.
5) Ethical Considerations - Check if any customer data (emails, phone numbers) should be anonymised. Ensure compliance with data privacy laws (e.g., GDPR).
6) Tell a Data Story - Summarise your findings in a brief Data Insights Report with key takeaways and recommendations for ShopEase to improve sales and customer experience.


## Set up your Environment

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the notebook.


### **`macOS`** type the following commands : 


- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python3 -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

    ```Bash
    python.exe -m pip install --upgrade pip
    ```


## Data

The dataset for the notebook is stored in the `data` folder. 
