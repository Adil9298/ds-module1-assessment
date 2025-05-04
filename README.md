# ds-module1-assessment
Entri Elevate Module 1 Assessment


📊 Employee Dataset Analysis — ABC Company
This project performs data preprocessing and exploratory data analysis (EDA) on an employee dataset from ABC Company. The analysis leverages NumPy, Pandas, Matplotlib, and Seaborn to uncover trends, correlations, and insights from the data.

📁 Dataset Description
The dataset contains information about employees with the following fields:
Name: Employee's full name
Team: Department or team name
Number: Employee jersey or ID number
Position: Job role or designation
Age: Age in years
Height: Originally a mix of formats (cleaned in preprocessing)
Weight: In pounds
College: Educational background
Salary: Annual salary in USD

🔧 Preprocessing Steps :
Data Loading
The dataset was loaded using pandas.read_csv() and basic exploration was performed using .head(), .info(), and .describe().
Missing Values
Handled NaN values in College and Salary by either dropping or filling based on context.
Ensured salary entries are numerical for analysis.

Data Cleaning :
Standardized Height values: replaced mixed string formats (like "6-3", "07-Mar") with random heights between 150 cm and 180 cm using np.random.randint() to maintain data consistency.
Converted any inappropriate or malformed fields to valid values (e.g., cleaned dates posing as heights).
Data Type Fixes
Ensured all columns had appropriate data types (float, int, str) for accurate analysis and plotting.

📈 Analysis Tasks and Visualizations
1. Team Distribution :
Counted employees per team.
Calculated percentage distribution.
Visualization: Pie chart and bar chart of employee share across teams.

2. Position Segregation :
Analyzed how employees are distributed across job positions.
Visualization: Count plot using Seaborn with a custom color palette.

3. Age Group Analysis :
Binned ages into groups (e.g., 20–25, 26–30, etc.).
Identified the most common age bracket among employees.
Visualization: Bar chart and boxplot.

4. Salary Expenditure by Team and Position :
Calculated total salary spent per team and per position.
Identified highest salary spending team and highest-paid position.
Visualization: Bar charts.

5. Age vs. Salary Correlation
Checked statistical correlation between Age and Salary using .corr().

Visualizations:
Scatter plot with regression line
Hexbin plot for dense data visualization
KDE and joint plots for distribution comparison

📊 Key Insights (Data Story) :
The most represented age group was 26–30 years, indicating a relatively young workforce.
Point Guards (PG) and the Utah Jazz team had the highest total salary expenditure.
A moderate positive correlation was found between Age and Salary.
Several younger employees had high salaries, suggesting standout performers or premium roles.

🛠️ Technologies Used :
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook (for code development and visualization)

Author :
Mohammed Adil. K
GitHub : @Adil9298
