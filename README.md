# Loan Approval Prediction  
This repository contains a Jupyter Notebook that analyzes and builds a predictive model for loan approval. The data was provided by Dream Housing Finance, a home loan provider serving customers across urban, semi-urban, and rural areas. The goal is to predict if a loan application will be approved based on various applicant features, which are discussed in detail.

### Dataset  
The dataset used for this project includes information about applicants and their financial details, such as:

- **Applicant Income**: Applicant's monthly income
- **Coapplicant Income**: Coapplicant's monthly income
- **Loan Amount**: Loan amount requested (in thousands)
- **Loan Amount Term**: Duration of loan repayment (in months)
- **Credit History**: Applicant's credit repayment history
- **Property Area**: Location of the property, categorized as Urban, Semiurban, or Rural
- **Loan Status**: Target variable indicating loan approval status (Yes/No)

### Project Structure  
The notebook is well-organized, divided into the following sections:

1. **Data Import and Libraries**: Importing the necessary Python libraries for data analysis and model building.
2. **Exploratory Data Analysis**: Overview and summary statistics of the data, with visualizations to understand data distributions and correlations.
3. **Data Cleaning and Preprocessing**: Handling missing values, encoding categorical variables, and normalizing numerical features.
4. **Feature Engineering**: Creating new features or modifying existing ones to improve model performance.
5. **Modeling**: Training multiple machine learning models, including logistic regression, decision trees, and ensemble methods, to predict loan approval.
6. **Evaluation**: Measuring model performance using metrics like accuracy, precision, recall, and F1-score.
7. **Conclusion and Insights**: Overview of the results and key insights gained from the analysis.

### Requirements  
To run this notebook on your machine, you will need the following Python packages:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install the requirements with:
```
pip install -r requirements.txt
```

### Usage  
Clone the repository:
```
git clone https://github.com/Tameralinada/loan-approval-prediction.git
```

Change to the project directory:
```
cd loan-approval-prediction
```

Run the Jupyter Notebook:
```
jupyter notebook pr-loanapproval-train.ipynb
```

Follow the notebook to replicate the analysis and model training.

### Results  
The model performs well on the test dataset, effectively predicting loan approval status with satisfactory accuracy. Detailed evaluation metrics and visualizations are available in the notebook.

### License  
This project is under the MIT License.
