# Task1-EDA-Titanic-Dataset-Developer-Hub-Corporation-Intrenship-
🚢 Titanic Dataset – Exploratory Data Analysis (EDA)
**Task Overview**

This repository contains Task 1 of my internship at Developers Hub.
The goal of this task was to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand its structure, clean missing values, visualize important features, and summarize key insights.

**📂 Dataset**

File Used: Titanic dataset.csv (Kaggle Titanic Dataset – Train file).

Size: 891 rows × 12 columns.

Description: The dataset contains demographic and travel information of Titanic passengers, along with survival status (Survived column).

**⚙️ Steps Performed**
**1. Load and Check Data**

Loaded dataset with Pandas.

Displayed first rows, shape, and column details.

**2. Variable Description**

Identified categorical and numerical features.

**3. Univariate Variable Analysis**

Categorical Variables: Survived, Sex, Pclass, Embarked, Cabin, Name, Ticket, SibSp, Parch.

Numerical Variables: Age, Fare, PassengerId.

**4. Basic Data Analysis**

Summary statistics for numerical variables.

Count plots for categorical variables.

Histograms and boxplots for numerical variables.

**5. Outlier Detection**

Boxplots used to detect outliers in Age and Fare.

**6. Missing Value Handling**

Checked missing values across columns.

Imputed missing Age values with median.

Imputed missing Embarked with mode.

Dropped duplicates (if any).

**7. Visualizations**

Bar charts (e.g., Survival by Gender, Pclass).
<img width="540" height="395" alt="image" src="https://github.com/user-attachments/assets/3fdd4e74-3709-4c0d-bc15-a45413a719ba" />
Histograms (Age, Fare).

Correlation Heatmap.
<img width="637" height="528" alt="image" src="https://github.com/user-attachments/assets/ab22e8f0-0f80-49f1-8e99-3fb06bff95c4" />

Feature vs. Survival plots (Sex, Pclass, Age, SibSp, Parch).
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/5b50259e-eaf1-4ae9-89ca-bce1179f1dc6" />



**8. Insights**

Females had a significantly higher survival rate compared to males.

Passengers in 1st Class had higher survival rates compared to 2nd and 3rd class.

Younger passengers had better survival chances than older ones.

Family size (SibSp & Parch) influenced survival — passengers with small families survived more.

**Tools & Libraries**

Python 3

Pandas

Matplotlib

Seaborn
