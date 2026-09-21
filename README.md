# Python-Fundamentals_Capstone-Project

# 🎫 Customer Support Ticket Analyser

## 📌 Project Overview

The **Customer Support Ticket Analyser** is a Python-based project designed to
store, clean, analyse, and extract useful insights from customer support tickets.

Customer support teams handle numerous service tickets daily. Analysing these
tickets can help identify common customer issues, customer sentiment, support
quality, ticket priorities, and areas for improvement.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Store and manage customer support ticket data using Python dictionaries and lists.
- Allow users to add new customer support tickets.
- Automatically generate ticket numbers for new tickets.
- Validate ticket priority as High, Medium, or Low.
- Clean and standardise customer issue descriptions.
- Identify frequently occurring keywords.
- Analyse tickets based on priority.
- Find the ticket containing the longest issue description.
- Extract unique words from customer issue descriptions.

---

## 🗂️ Dataset

The project starts with 10 preloaded customer support tickets.

Each ticket contains:

- **Ticket Number**
- **Customer Name**
- **Issue Description**
- **Priority**

Priority is classified into:

- High
- Medium
- Low

The program also allows additional tickets to be entered by the user.

---

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Python Dictionaries
- Lists
- Sets
- Loops
- Conditional Statements
- User-Defined Functions
- String Methods

---

## 📁 Project Structure

```text
Customer Support Ticket Analyser/
│
├── README.md
│
├── Python Fundamentals - Capstone Project.ipynb
│
├── Python Fundamentals - Capstone Project.pdf
```

---

## 🔍 Project Workflow

### 1. Data Loading and Organization

The initial customer support ticket data is stored using a
**dictionary of lists** and displayed in a readable format.

### 2. Adding New Tickets

The program allows users to add additional tickets by entering:

- Customer Name
- Issue Description
- Priority

Ticket numbers are automatically generated starting from **11**.

The program also validates the priority and accepts only:

`High`, `Medium`, or `Low`

### 3. Text Cleaning

Customer issue descriptions are cleaned and standardised by:

- Converting text to lowercase
- Removing punctuation
- Removing leading and trailing spaces
- Converting multiple spaces into a single space
- Replacing shorthand such as `ok` with `okay`

### 4. Keyword-Based Issue Analysis

A user-defined function is created to count the number of tickets
containing specific keywords.

The following keywords are analysed:

- `poor`
- `good`
- `slow`
- `excellent`

### 5. Priority Analysis

The program calculates the total number of:

- High-priority tickets
- Medium-priority tickets
- Low-priority tickets

### 6. Longest Issue Description

The program identifies the ticket with the longest issue description
based on **word count** and displays:

- Ticket Number
- Customer Name
- Cleaned Issue Description
- Word Count

### 7. Unique Word Analysis

A Python `set` is used to extract all unique words appearing across
the customer issue descriptions.

The program displays:

- Total number of unique words
- Sorted list of unique words

---

## 📊 Key Insights

The analysis helps identify:

- Frequently occurring words in customer support issues.
- Distribution of tickets across different priority levels.
- Common positive and negative service-related keywords.
- Tickets containing more detailed issue descriptions.
- Vocabulary patterns appearing across customer feedback.

The final results can change when new tickets are added by the user.

---

## 🧠 Python Concepts Practiced

This project provided hands-on practice with:

- Variables
- Lists
- Dictionaries
- Sets
- `for` loops
- `while` loops
- `if`, `elif`, and `else`
- User input
- Functions
- String manipulation
- Data cleaning
- Word counting
- Sorting
- Basic text analysis

---

## ▶️ How to Run the Project

1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Run the cells in sequence.
3. Enter the number of additional tickets you want to add.
4. Enter the customer name, issue description, and priority.
5. The program cleans the ticket descriptions automatically.
6. Run the analysis sections to view keyword, priority, longest-description,
   and unique-word insights.

---

## 📚 Skills Demonstrated

- Python Basics
- Data Loading and Management
- Data Cleaning and Transformation
- String Processing
- Functions and Loops
- Conditional Logic
- Data Analysis
- Data Structuring
- Sorting
- Basic Text Analytics
- Insight Generation

---

## 🚀 Conclusion

The **Customer Support Ticket Analyser** demonstrates how Python can be used to organise and analyse text-based customer service data.

Through this project, raw customer issue descriptions are cleaned and standardised before being analysed for keywords, priority distribution,
description length, and unique words.

This project strengthened my understanding of Python fundamentals while providing practical experience in data cleaning, text processing, functions,
loops, and basic data analysis.



Aspiring Data Analyst

**Skills:** Python | SQL | Excel | Power BI | MySQL
