# AIT736-Team3
This is the repo for final project in Applied Machine Learning course Spring 2026

* Problem statement: Combining multiple factors, build ML models and select the most optimal one to predict customer churn at Telco. 

* Business goal: Don't miss churners

* Data: Telco Customer Churn 
    - Format: csv
    - Data source: Kaggle

##### --- Machine Learning pipeline --- 

* Step 1:
    - Outlining project strucuture
```
    mkdir -p \
    data \
    notebooks \


* Step 2:
    - Create virtual environment
    - Install required Python libraries
```
    cat > requirements.txt << 'EOF'
    pandas
    numpy
    scikit-learn
    pydantic
    python-dotenv
    matplotlib
    seaborn
    statsmodels
    xgboost
    EOF
```
```python3.11 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
uv pip install -r requirements.txt
```
* 'uv' package automatically select the proper version of each Python library, ensuring no depency issue
    * ![alt text](image-1.png)

* Step 3:
    - Performing exploratory data analysis (EDA)
    - Performing data preparation
    - Performing data cleaning
    - Validate models for consideration

* Step 3:
    - Constructing different ML models
    - Compare model's performance and select the best one
