<img src = "https://miro.medium.com/max/1400/1*f7m92eei7PE8gFyaCQnXMw.jpeg"><br>

# 👨‍💻 | Loan Default Prediction 💰

--<br><br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![scikit_learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)<br>

--

# Important Note

This notebook is easier to read on Kaggle. Please, <a href ="https://www.kaggle.com/code/lusfernandotorres/loan-default-prediction/notebook">click here</a> to see it on Kaggle, where plotly charts are fully interactive!

# About
Loans are an essential part of our economy.People borrow money from financial institutions all the time, either for starting a business, emergency expenses, vehicle financing, vacation costs, or education costs.<br><br>

However, when lending money to someone, there is always the risk that that person may not be able to pay you back. When it comes to financial institutions, such as banks, that borrow large amounts of money to many different people for many different reasons, the risk of losses from defaults gets exponentially higher.<br><br>

For this reason, it is extremely important that financial institutions avoid loans to people that are highly likely to default, and they usually invest a lot of time and resources in background checks on people to avoid having losses. In this notebook, I'll develop a machine learning model that will be able to predict how likely a client is to default based on whether or not he's employed, his bank balance, and his annual salary.<br><br>

# The dataset

To develop this loan default predictor, I've used the <a href = "https://www.kaggle.com/datasets/kmldas/loan-default-prediction">Loan Default Prediction dataset</a> on Kaggle, which is a synthetic dataset created using actual data from a financial institution, containing data from 10,000 clients. It's important to notice that this data has been transformed in order to avoid identification of these clients and this institution.<br><br>
The attirbutes in this dataset are as follows: <br><br>

- **Employed**: 1 for employed and 0 for unemployed; <br><br>

- **Bank Balance**: The amount of money that client had available in their account at the moment the data was obtained; <br><br>

- **Annual Salary**: The annual salary of each client; <br><br>

- **Defaulted?**: This is our target variable and it's filled of 0 for each client who didn't default and 1 for each client who defaulted their loans. <br><br>

I've used some **EDA** techniques to evaluate how each attributed interacted with each other and how relevant they were to the target variable. <br><br>

# Libraries Used

> - pandas;
> - numoy;
> - plotly;
> - matplotlib;
> - seaborn;
> - sklearn;
> - pycaret

---

Author

*Luis Fernando Torres*
