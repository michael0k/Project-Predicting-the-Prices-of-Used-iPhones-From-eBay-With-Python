## Predicting the Prices of Used iPhones From eBay With Python

Regression modeling project to predict used iPhone prices using data scraped from eBay.

### Overview
- Goal: Clean, explore, and model eBay iPhone listing data to predict listing prices using a multi-linear regression model.
- Stack: Python (pandas, scikit-learn), data cleaning, EDA, and regression modeling.

### Dataset
- Source: `iphone_ebay.csv` dataset of eBay listings including iPhone name, listed price, and condition. 
- Included: Scraped and cleaned data used for analysis and modeling.

### Methods
- Cleaning: Extract and normalize price values from ranges, encode condition categories, and parse iPhone model variants. 
- EDA: Visualize distributions and relationships among price, condition, and model. 
- Modeling: Build a multi-linear regression model to estimate iPhone prices and evaluate using metrics such as MAE, MSE, and R². 

### Results 
- Identified distributions of listing prices and condition effects.
- Created engineered features for price prediction (e.g., model variants and condition encoding).
- Demonstrated regression performance with visual evaluation of actual vs. predicted prices. 

### How to Run
1) Place `iphone_ebay.csv` in the project `data/` directory.
2) Open and run the Jupyter notebook for data cleaning, EDA, and modeling.
3) Review generated plots and regression evaluation results.

### Structure
- `data/`: iPhone eBay listing dataset
- `notebooks/`: Python notebook with cleaning, EDA, and model code
- `visualization/`: plots and visual outputs


### Next
- Add comparison with additional models (e.g., Random Forest, Gradient Boosting).
- Deploy as a simple web app to estimate iPhone prices dynamically.

### License
GNU GPL v3
