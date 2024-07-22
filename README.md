### **Economic Model of Crime with Panel Data**

**Project Overview**

In this project, I conducted an econometric analysis to estimate the economic model of crime using panel data. The focus of this study was to investigate how the number of police officers per capita affects the crime rate across different counties over various years. The methodology and insights are inspired by the research of Cornwell and Trumbull (1994).

**Data and Methodology**

The dataset used includes panel data on crime rates, police numbers, and other socioeconomic factors across multiple counties and years. The primary aim was to build a robust regression model to determine the relationship between police presence and crime rates.

**Key Steps and Analysis**

**Data Preparation:**

Loaded and cleaned the dataset using Python libraries such as pandas.
Handled missing values and performed data transformation to ensure consistency.

**Model Specification:**

Initially specified a regression model to include relevant variables.
Tested for multicollinearity using Variance Inflation Factor (VIF) and correlation analysis.

**Regression Analysis:**

Conducted Ordinary Least Squares (OLS) regression.

**Refined the model by:**

Omitting irrelevant variables that were not statistically significant.
Adding new explanatory variables to improve the model's explanatory power.
Avoided the dummy variable trap by ensuring proper handling of categorical variables.

**Diagnostic Tests:**

Performed full and partial multicollinearity tests.
Conducted joint significance tests for variables that were not significant individually but might be jointly significant.

**Instrumental Variables (IV):**

Explored the possibility of using IV to address potential endogeneity issues. Specifically, considered the two-sided effect where higher police numbers are placed in areas with increased crime.

**Key Findings:**

The final model indicated that an increase in the number of police officers per capita actually increased the crime rate per capita.
This counterintuitive result was consistent across different model specifications and robustness checks.

**Caveats:**

Potential omission of relevant variables that were not included in the dataset could affect the results.
The two-sided effect where higher police presence is in response to rising crime rates could bias the findings. This effect was partially mitigated by adding more explanatory variables, but not entirely eliminated.
Future research could benefit from identifying a strong instrumental variable to better isolate the causal impact of police presence on crime rates.

**Conclusion**

The analysis underscores the complexity of the relationship between police presence and crime rates. While the initial results suggest a positive correlation between the number of police officers and crime rates, further investigation is warranted to account for potential biases and omitted variable effects. The project highlights the importance of robust econometric techniques and thorough diagnostic testing in drawing meaningful conclusions from data.

**Code and Outputs**

The complete Python code and detailed outputs of the analysis are available in the provided HTML file. This includes data cleaning steps, regression models, diagnostic tests, and visualization of results using libraries like seaborn and matplotlib.
