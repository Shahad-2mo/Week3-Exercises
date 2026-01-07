# Shipping Crisis: E-Commerce Delay Prediction
Machine learning solution to predict and prevent shipping delays for a Saudi e-commerce platform using AutoGluon.
## Features
- Exploratory data analysis of logistics data
- Feature engineering with domain-driven transformations
- AutoGluon automated machine learning
- Business value optimization (threshold tuning)
- Achieved +SAR 67,500 business value with 0.10 optimal threshold
## Project Structure
```
.
├── data
│   └── raw
│       └── Saudi_Retail_Logistics_Data.csv
├── notebooks
│   └── Shipping_Crisis_Template.ipynb
├── pyproject.toml
├── README.md
└── uv.lock
```

## Setup
-  Create a virtual environment (at the project root):

    ```
    uv init
    ```
    ```
    uv sync
    ```

- Activate it:

    (Linux/Mac) 
    ```
    source .venv/bin/activate
    ``` 
    
    (Windows)
    ```
    .venv\Scripts\Activate.ps1
    ``` 

- Install dependencies:

    ```
    uv add pathlib pandas matplotlib seaborn scikit-learn autogluon numpy ipywidgets
    ```

## How to Run
Open and run the Jupyter notebook:
```bash
jupyter notebook notebooks/Shipping_Crisis_Template.ipynb
```