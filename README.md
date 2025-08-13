# -Exploratory-Data-Analysis-EDA-
# Basic info
df.info()

# Summary statistics for numeric
print(df.describe())

# Summary for categorical
print(df.describe(include='object'))

# Missing values
print(df.isnull().sum())
age 177and deck 688 missing values. and total column 15.

#**Value counts** : 
More passengers did not survive.
Class 3 has the most passengers.
More males than females.
Majority embarked from "S" (Southampton).

# Pairplot (relationships) : Observation:
Higher fares and lower pclass numbers (1st class) seem related to survival.
Younger passengers appear in all classes, but older passengers mostly in higher classes.

# Heatmap (correlation) : 
pclass negatively correlates with fare and survived.
fare has a small positive correlation with survival.
Age correlation with survival is weak.

# Boxplots : 
First-class passengers are generally older.
Survivors tended to have paid higher fares.

# Scatterplots : 
Survivors cluster in higher fare ranges.
Younger survivors appear in all fare ranges.

# Summary of Findings :
Survival rate is ~38% overall.
Females had much higher survival than males.
1st class passengers had the highest survival, followed by 2nd class, then 3rd class.
Higher fare is associated with greater survival.
Age has a weak effect, but children seem to have a slightly higher chance.
Most passengers embarked from Southampton (S).
