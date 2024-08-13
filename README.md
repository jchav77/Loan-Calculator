# 🏦 Loan Calculator

## 📝 Description
This Loan Calculator is a Python-based application designed to help users manage and analyze loans. It provides functionality for creating loans, tracking payments, generating amortization schedules, and producing loan summaries. This tool is particularly useful for those involved in owner financing or anyone needing to manage long-term loans.

## ✨ Features
- 💰 Create new loans with customizable terms
- 📅 Record and track loan payments
- 📊 Generate amortization schedules
- 📑 Produce detailed loan summaries
- 📈 Visualize loan data with graphs
- 🗑️ Delete and modify payment records
- 🧮 Calculate remaining balances and interest paid

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Required Libraries
Install the required libraries using pip:pip install pandas matplotlib python-dateutil tabulate sqlite3

### Setup
1. Clone the repository: git clone https://github.com/jchav77/loan-calculator.git
2. Navigate to the project directory: cd loan-calculator

## 🖥️ Usage

Run the main script: python loan_calculator.py

Follow the on-screen prompts to:
1. Create a new loan
2. Make payments
3. View loan summaries
4. Generate amortization schedules
5. Delete payments
6. Exit the program

## 🏗️ Code Structure

- `LoanApplication` class: Main class containing all loan-related methods
- SQLite database: Stores loan and payment information
- Matplotlib: Used for generating visual representations of loan data

## 🔑 Key Functions

- `create_loan()`: Initialize a new loan
- `make_payment()`: Record a payment on a loan
- `generate_amortization_schedule()`: Create a full amortization schedule
- `generate_loan_summary()`: Produce a summary of the loan's current state
- `delete_payment()`: Remove a payment record and recalculate the loan

## 💾 Data Storage

Loan and payment data is stored in an SQLite database, allowing for persistent data storage between program runs.

## 🛠️ Customization

Users can modify loan parameters such as interest rates, loan terms, and payment frequencies by adjusting the relevant variables in the code.

## 🤝 Contributing

Contributions to improve the Loan Calculator are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## 📞 Contact

Julio Chavez - Jchav77@gmail.com

Project Link: [https://github.com/Jchav77/loan-calculator](https://github.com/Jchav77/loan-calculator)
