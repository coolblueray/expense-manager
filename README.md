# Expense Manager

## Overview

The Expense Manager is a simple, web-based application designed to help you track your daily, weekly, monthly, and annual spending effortlessly. It allows you to add, edit, and delete expenses, categorize them, and view reports to understand your spending habits.

## Features

-   **Add/Edit/Delete Expenses**: Easily add new expenses with details like name, category, amount, payment type, date, and time. You can also modify existing entries or remove them.
    
-   **Expense Categorization**: Organize your spending into predefined categories (Personal, Family, Eating Out, School, Stationary, SOHO, Household, Vehicle, Medical, Grocery).
    
-   **Payment Type Tracking**: Record how you pay for expenses (Cash, Electronic Transfer, Credit Card, Debit Card).
    
-   **Interactive Expense List**: View all your expenses in a sortable table, with the most recent entries displayed first.
    
-   **Comprehensive Reports**: Generate weekly, monthly, and annual reports that summarize your total spending and break it down by category and payment type.
    
-   **CSV Import/Export**:
    
    -   **Export**: Download all your recorded expenses as a CSV file for backup or further analysis in spreadsheet software.
        
    -   **Import**: Upload a CSV file to add multiple expenses at once. The app will attempt to parse the data and add valid entries.
        

## How to Use

1.  **Adding an Expense**:
    
    -   Fill out the "Add New Expense" form with the expense name, category, amount, payment type, date, and time.
        
    -   Click "Add Expense" to save it.
        
2.  **Editing an Expense**:
    
    -   In the "Your Expenses" table, click the "Edit" button next to the expense you wish to modify.
        
    -   The form will pre-populate with the expense's details. Make your changes and click "Update Expense".
        
    -   Click "Cancel Edit" to discard changes and revert the form.
        
3.  **Deleting an Expense**:
    
    -   In the "Your Expenses" table, click the "Delete" button next to the expense you want to remove.
        
    -   A confirmation modal will appear. Click "Delete" to confirm or "Cancel" to keep the expense.
        
4.  **Viewing Reports**:
    
    -   Navigate to the "Expense Reports" section.
        
    -   Click "This Week", "This Month", or "This Year" to generate a summary report for the selected period.
        
5.  **Exporting Data**:
    
    -   In the "Data Management" section, click the "Export as CSV" button.
        
    -   Your expenses will be downloaded as a `expenses.csv` file.
        
6.  **Importing Data**:
    
    -   In the "Data Management" section, click the "Import from CSV" button.
        
    -   Select a CSV file from your computer. The app will attempt to import expenses from the file. Ensure your CSV file has the following headers (case-insensitive): `ID`, `Name`, `Category`, `Amount`, `Payment Type`, `Date`, `Time`.
