# Supermarket POS
This project implements a Supermarket Point of Sale (POS) system using Python and the Tkinter library for creating a graphical user interface (GUI). The system allows users to select desired products and specify the quantity, and it provides functionalities for generating transaction records and keeping copies of transactions using Microsoft Excel.

Features:

Interactive GUI for selecting products and specifying quantities.
Integration with Microsoft Excel for bookkeeping and transaction record management.
Efficient handling of transactions through Python's openpyxl library for reading and writing Excel sheets.

Components:

Graphical User Interface (GUI):
Developed using the Tkinter library.
Allows users to interactively select products from a list and specify quantities for purchase.
Provides buttons for common actions such as resetting sales, calculating totals, printing receipts, and exiting the program.

Transaction Handling:
Upon selecting products and quantities, the system calculates the total amount for the transaction.
It provides options for printing receipts and generating transaction records.

Integration with Excel:
Utilizes the openpyxl library to interact with Microsoft Excel.
Enables the creation of transaction records and the storage of transaction data in Excel sheets.

Dependencies:

Python 3.x

Tkinter

openpyxl
