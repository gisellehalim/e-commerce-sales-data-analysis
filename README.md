# Data Analysis with Python

## Setup  (Option 1)
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel
```

## Setup (Option 2 - Using Terminal/PowerShell without Conda)
```
mkdir main-ds
cd main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel
pipenv install
pipenv shell
```

## Run steamlit app
```
streamlit run dashboard_ecommerce.py
```
