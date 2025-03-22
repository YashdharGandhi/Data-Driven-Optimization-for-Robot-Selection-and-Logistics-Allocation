# Data-Driven Optimization for Robot Selection and Logistics Allocation

## Project Overview
This project focuses on the selection and allocation of autonomous robot prototypes to optimize last-mile logistics. Using **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** for robot selection and **Linear Programming (LP)** for allocation, we ensure an effective and cost-efficient distribution strategy. 

## Data Description
The project involves two main datasets:
- **Management_Priority.xlsx**: Contains weight distributions for key selection criteria (carrying capacity, speed, battery size, cost, reliability).
- **Transactions_Customer.csv**: Records of customer spending behavior used in recommendation modeling.

## Tasks Performed
### **1. Robot Prototype Selection**
- Assessed four robot prototypes: **Deviant, Bowler, Archer, and Corner**.
- Applied **TOPSIS** methodology to evaluate performance based on predefined management weights.
- Identified **Deviant** as the optimal choice due to its superior performance across key criteria.

### **2. Robot Allocation Strategy**
- Developed an allocation model using **Linear Programming (LP)**.
- Considered constraints: budget, minimum robots per store, technician availability.
- Implemented using **Python Pulp library** and **Excel Solver**.
- Optimized allocation to maximize daily order fulfillment.

### **3. Customer Spending Analysis**
- Analyzed customer behavior for targeted marketing recommendations.
- Used regression modeling to determine the impact of **income, advertisement channels, and voucher visibility** on revenue.
- Found that **voucher visibility and income level significantly impact spending**.

## Key Findings
- **Deviant is the best robot prototype** based on **TOPSIS** scoring.
- **LP allocation model** ensures optimal robot distribution within budget constraints.
- **Voucher visibility increases customer spending**, making it a key promotional strategy.
- **Social Media and Influencer marketing** show the highest impact on revenue growth.

## Requirements to Run the Project
### **1. Dependencies**
Ensure you have the following installed:
- Python 3.x
- `pandas` (for data processing)
- `numpy` (for numerical computations)
- `pulp` (for linear programming)
- `openpyxl` (for handling Excel files)

To install dependencies:
pip install pandas numpy pulp openpyxl

## Author 
**Yashdhar Gandhi**

## License
This project is licensed under the MIT License.
