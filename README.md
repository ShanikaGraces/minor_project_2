# minor_project_2
SpendDNA: Bank Transfer Analysis

SpendDNA is a Python-based transaction analysis project that cleans raw bank transaction data and generates meaningful insights into spending behavior.

Project Objectives

* Clean and standardize transaction data
* Extract vendors from transaction descriptions
* Categorize transactions
* Analyze spending and savings
* Identify monthly and time-based spending patterns
* Detect unusual transactions
* Identify spending archetypes

Technologies Used

* Python
* Pandas
* NumPy
* Google Colab / Jupyter Notebook

 Project Workflow

Raw Transactions
      ↓
Data Cleaning
      ↓
Vendor Extraction
      ↓
Category Mapping
      ↓
Spending Analysis
      ↓
Monthly & Time Analysis
      ↓
Anomaly Detection
      ↓
Spending Archetype Detection

Key Features

Data Cleaning

* Standardizes dates and transaction types
* Cleans currency values
* Removes duplicate transactions
* Checks for unparseable values

Vendor & Category Extraction

Identifies vendors such as **Swiggy, Zomato, Amazon, Zepto, Uber, Netflix, etc.** and maps them into categories such as Food Delivery, Ecommerce, Transport, Subscriptions, Investments, and more.

Spending Analysis

Calculates:

* Total credits and debits
* Net savings
* Savings rate
* Top spending categories
* Top vendors
* Monthly spending trends

Pattern & Anomaly Detection

Analyzes:

* Late-night food spending
* Morning cafe spending
* Category-wise spending trends
* Unusually large transactions using Z-score

Spending Archetypes

The project identifies spending behaviors such as:

Foodie
Quick Commerce Junkie
Shopaholic
Investor
Cab Commuter
Subscription Lover
YOLO Spender
Disciplined Saver

Project Structure
SpendDNA/
│
├── Shanika_MinorProject_2.ipynb
├── README.md
└── sample_data/
    └── rahul_transactions.csv

 How to Run

1. Open `Shanika_MinorProject_2.ipynb` in Google Colab or Jupyter Notebook.
2. Upload the transaction CSV file.
3. Run the notebook cells sequentially.
4. View the generated spending insights and archetypes.

Author
Shanika Graces
Python-Based Data Analysis Project

License
his project is created for educational and portfolio purposes.
