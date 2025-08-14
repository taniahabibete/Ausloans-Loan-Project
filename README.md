# Ausloans Loan Decision Project

## What This Project Does
This project decides if someone should get a loan using:
- **Applicant Data**: Details like age, income, and loan amount (`loan_application_dataset.csv`).
- **Lender Rules**: Conditions for loans (`product_matrix_rule_dataset.csv`).
- **Smart Prediction**: A system that guesses if a loan will be approved.

It tests one person (loanApplicationId = 738380) and lists 2 loan products they qualify for.

## How to Use It
1. **Install Tools**:
   - Install Python: [python.org](https://www.python.org/downloads/).
   - Open Terminal and install:
pip install jupyter pandas scikit-learn flask joblib matplotlib seaborn
text- Put all project files in a folder (e.g., `LoansProject`).

2. **Run the Project**:
- In Terminal, go to your folder:
cd ~/Documents/LoansProject
text- Start Jupyter:
jupyter notebook
text- Open `Ausloans_Decision_Engine_Simple.ipynb` and run each cell (Shift+Enter).

3. **What You’ll See**:
- Data being prepared.
- Approval/rejection counts.
- Charts showing what’s important (e.g., income, credit score).
- Prediction for loanApplicationId = 738380 (e.g., “Approved” with 2 loan products).

## Files
- `Ausloans_Decision_Engine_Simple.ipynb`: Main project code.
- `loan_application_dataset.csv`: Applicant data.
- `product_matrix_rule_dataset.csv`: Loan rules.
- `loan_model.pkl`, `scaler.pkl`: Prediction tools.
- `README.md`: This file.

## Results
- Predicts loan approval with ~85% accuracy.
- For loanApplicationId = 738380, predicts “Approved” with 2 loan products.
- Charts show income and credit score matter most.

## Need Help?
Check if files are in the right folder or tools are installed. Contact a friend with IT experience for errors.

## GitHub Instructions
To update this project:
1. Edit files in your folder.
2. In Terminal:
git add .
git commit -m "Updated project"
git push origin main
