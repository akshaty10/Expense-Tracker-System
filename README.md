# Expense-Tracker-System
Python Automobile Visualization and Analysis
Project Overview
This project involves loading automobile data, cleaning it, and performing various operations such as adding, updating, and deleting data, as well as visualizing key statistics. Additionally, this project offers a user module to track car-related expenses, including fuel, maintenance, and insurance costs, as well as depreciation. Visualization techniques are applied using matplotlib and seaborn libraries for enhanced data analysis and presentation.

Features
1. Data Management
Add, Update, Delete Entries: Functions to manage the automobile data stored in a CSV file, including adding new entries, updating existing ones, and deleting records.
2. Data Cleaning
Handles missing or invalid values by replacing them with appropriate statistics (e.g., mean, mode).
Columns such as Normalized-Losses, Price, Mileage, and more are cleaned to remove inconsistencies.
3. Expense Tracking
View Car Expenses by Make: Analyze the total expenses based on car make.
Track Fuel, Maintenance, Insurance Costs: Functions to visualize the costs of fuel consumption, maintenance, and insurance over time.
4. Data Visualization
Bar and Pie Charts: Visualize car expenses and other key statistics using bar and pie charts.
Bubble Charts: Plot the relationship between engine size, horsepower, and mileage, categorized by fuel type.
5. User Module
Car Expense Tracking: Offers the ability to track various expenses such as fuel, maintenance, insurance, and depreciation for each car.
Interactive Menu: Provides an interactive menu allowing users to view car details and select operations like adding, updating, or deleting records.
Installation
Clone the repository:


git clone https://github.com/yourusername/python-visualization.git
Install the required dependencies:


pip install -r requirements.txt
Load the dataset by placing your CAR.csv file in the project directory.

How to Use
Data Cleaning and Visualization:

The dataset is cleaned to handle missing values and inconsistencies.
Use the provided functions to visualize key insights like car expenses, fuel costs, maintenance, and depreciation using matplotlib and seaborn.
Admin Access for Data Manipulation:

Users can add, update, and delete entries in the automobile dataset interactively.
User Module:

Track and visualize car expenses, maintenance, and insurance costs over time.
Select individual cars to view detailed expense breakdowns.
Visualization Capabilities:

Analyze expenses based on different factors like car make, fuel type, and body style.
Visualize data using different types of charts such as bar plots, pie charts, and bubble charts.
Key Libraries Used
Pandas: For data manipulation and cleaning.
Matplotlib and Seaborn: For creating visualizations.
NumPy: For numerical operations and handling missing values.
Example Code

# Bar plot for car expenses by make
sns.barplot(x='Make', y='Expense', data=df, estimator=sum)
plt.title('Total Expenses by Make')
plt.show()

# Bubble Chart for Engine Size vs Horsepower
sns.scatterplot(x='engine-size', y='horsepower', size='Mileage', hue='Fuel-Type', data=df, sizes=(20, 200), alpha=0.7)
plt.title('Bubble Chart: Engine Size vs. Horsepower')
plt.show()
License
This project is licensed under the MIT License.

Contact
For any questions or contributions, feel free to contact me.
