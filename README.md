# SIM-Project-2

### ****Aim****

- Predict the probability of a customer to churn in Train and Test samples.
- Interpret your final binary outcome model in such a way that illustrates which variables affect customer decision.

### Methodological approach

- Data Preparation
- Exploratory Data Analysis and Model Fitting should deal with train dataset.
- Profiling and Feature Selection
- Modeling using numeric variables using transformations if needed.
- Residual analysis: unusual and influent data filtering.
- Adding factor main effects to the best model containing numeric variables
- Residual analysis: unusual and influent data filtering.
- Adding factor main effects and interactions (limit your statement to order 2) to the best
model containing numeric variables.
- Final Residual analysis: unusual and influent data filtering. Iterative process could be needed.
- Goodness of fit and Model Interpretation. Train and Test datasets.

### **Data Preparation outline**

**Univariate Descriptive Analysis** (to be included for each variable):

- Original numeric variables corresponding to qualitative concepts have to be converted to
factors.
- Original numeric variables corresponding to real quantitative concepts are kept as numeric
but additional factors should also be created as a discretization of each numeric variable.
- Exploratory Data Analysis for each variables (numeric summary and graphic support).

**Data Quality Report:**

Per variable, count:

- Number of missing values
- Number of errors (including inconsistencies)
- Number of outliers
- Rank variables according the sum of missing values (and errors).

Per individuals, count:

- number of missing values
- number of errors,
- number of outliers
- Identify individuals considered as multivariant outliers.

Create variable adding the total number missing values, outliers and errors. Describe these
variables, to which other variables exist higher associations.

- Compute the correlation with all other variables. Rank these variables according the
correlation
- Compute for every group of individuals (group of age, size of town, singles, married, …) the
mean of missing/outliers/errors values. Rank the groups according the computed mean.

**Imputation**:

- Numeric Variables
- Factors

**Profiling**:

- Binary Target
