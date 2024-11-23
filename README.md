# Bank Marketing Analysis
## Overview
This project focuses on analyzing the Bank Marketing Dataset, which contains data about direct marketing campaigns of a Portuguese banking institution. The purpose of the analysis is to explore the dataset, handle missing values, and derive insights to understand the factors influencing customer subscription to a term deposit. The project was implemented using Python in a Kaggle notebook.You can view the project notebook on Kaggle at [the following link](https://www.kaggle.com/code/lalehseyin/bank-marketing)

## Dataset
The dataset contains information related to direct marketing campaigns, including:
- **Bank client data**: Age, job type, marital status, education level, default status, housing loan status, etc.	
 - **Last contact details**: Communication type, last contact month, last contact duration, etc.
- **Other attributes**: Number of contacts, previous campaign outcome, employment variation rate, consumer price index, etc.
- **Target variable (y)**: Indicates whether the client subscribed to a term deposit (yes or no).

## Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical computations.
- **Matplotlib**: For creating visualizations.
- **Seaborn**: For advanced and aesthetically pleasing visualizations.

## Analysis Steps

 1.	Dataset loading and exploration:
	-	Loaded the dataset from kaggle
	-	Inspected its structure and key features
 2. Handling missing values:
	- Introduced missing values artificially
	- Imputed missing values using mean for numerical and mode for categorical features.
 3.	Exploratory Data Analysis (EDA):
	- Explored the dataset through histograms, bar plots, and heatmaps.
	-	Performed correlation analysis to identify relationship between numerical features.
 4. Feature selection and engineering:
	 - Encoded categorical features using one-hot and binary mapping.
	-	Identified more correlated features and removed to avoid multicollinearity.
 5. Conclusions and insights:
    - Derived insights into factors influencing customer subscription to term deposits.
    - Suggested actionable recomments based on the findings.

## Key insights
- Clients in certain age groups are more likely to subscribe to a term deposit.
- The outcome of previous campaigns influences client behavior.
- Call duration is a critical feature but must be handled to avoid data leakage.
- Employment variation rate, consumer confidence index, and euribor rates are correlated with subscription rates.
