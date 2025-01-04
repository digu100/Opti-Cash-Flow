Cash Flow Minimizer System:

Welcome to the Cash Flow Minimizer System, a project designed to optimize and minimize the number of financial transactions among multiple banks. This system intelligently identifies the least number of transactions required to settle debts while considering different payment modes available across banks.

Features:

Net Amount Calculation:
Calculates the net credit or debit for each bank based on incoming and outgoing transactions.

Payment Mode Matching:
Identifies common payment modes between banks to facilitate direct transactions.

World Bank Intermediary:
Acts as a central entity to resolve transactions between banks with no common payment modes.

Efficient Cash Flow Settlement:
Uses a systematic approach to reduce the number of transactions and the complexity of the process.

Transaction Visualization:
Displays the minimized transactions required to settle all debts.

How It Works

Input Data:

Number of banks and their supported payment modes.

Transaction details (debtor bank, creditor bank, amount).

Processing:

Computes the net amount for each bank.

Matches creditors and debtors based on net amounts and common payment modes.

Routes transactions through the World Bank if no direct payment mode exists.

Output:

A detailed list of transactions to minimize cash flow.

Technology Stack

Programming Language: C++

Libraries Used: Standard Template Library (STL)
