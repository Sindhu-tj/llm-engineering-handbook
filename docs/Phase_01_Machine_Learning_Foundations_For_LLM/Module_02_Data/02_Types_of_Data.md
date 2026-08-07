# Types of Data

## Introduction

Data can exist in different forms depending on how it is organized, stored, and represented. Understanding these different types of data is important because AI and Machine Learning systems require different methods to process and analyze different forms of data.

In AI and LLM Engineering, the three major categories are:

- Structured Data
- Semi-Structured Data
- Unstructured Data

                         DATA
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     Structured      Semi-Structured   Unstructured
          │                │                │
       Tables           JSON / XML       Text / Images
       SQL              HTML             Audio / Video

       Data can be broadly classified into three major categories based on its level of organization: structured, semi-structured, and unstructured data.

   ## 1. Structured Data

### Definition

Structured data is data organized according to a predefined schema, usually in rows and columns, where each field has a specific meaning and data type.

EXAMPLE:
Customer_ID | Name  | Age | Country
------------|-------|-----|--------
C001        | Ravi  | 25  | India
C002        | Anu   | 28  | India
C003        | John  | 31  | USA

REAL WORLD EXAMPLE:

Banking System
      │
      ▼
Customer Records
      │
      ▼
Transactions
      │
      ▼
SQL Database
      │
      ▼
Structured Data

### LLM Perspective

Structured data is important in LLM applications when the model needs to access information stored in databases, APIs, or other structured sources.

For example, an LLM-powered customer support system can retrieve customer or order information from a SQL database and use that information to generate a natural-language response.

BLOCK DIAGRAM

                 User Question
                       │
                       ▼
                LLM Application
                       │
                       ▼
                 SQL Query
                       │
                       ▼
                  Database
                       │
                       ▼
                Structured Data
                       │
                       ▼
                 Query Result
                       │
                       ▼
                     LLM
                       │
                       ▼
            Natural Language Answer


Structured data is well-organized data that follows a predefined format. Each piece of information has a specific place and meaning.

It is commonly represented using rows and columns, similar to a spreadsheet or database table.

For example, in a customer table, `Customer_ID`, `Name`, `Age`, and `Country` are predefined fields, and each customer is represented by one row.

### Why It Matters

Structured data is important because it is organized, consistent, and easy to store, query, and analyze.

In AI and LLM engineering, structured data is useful for:

- Storing customer, product, and transaction information
- Providing reliable data to AI applications
- Connecting LLMs with SQL databases and APIs
- Supporting Machine Learning training and analysis
- Building enterprise AI applications

For example, an LLM application can retrieve the latest customer or transaction information from a database instead of relying only on information learned during model training.

### Characteristics

The main characteristics of structured data are:

- **Predefined Schema:** The structure and fields are defined in advance.
- **Rows and Columns:** Data is commonly organized in a tabular format.
- **Defined Data Types:** Each field has a specific type such as integer, string, date, or decimal.
- **Consistent Structure:** Records generally follow the same format.
- **Easy to Query:** Structured data can be efficiently searched and filtered using SQL.
- **Easy to Analyze:** It can be processed using databases, Python, Pandas, and Machine Learning tools.

### Working

Structured data is created, stored, processed, and analyzed according to a predefined schema.

Data Collection
      │
      ▼
Define Schema
      │
      ▼
Store in Database
      │
      ▼
Query / Process Data
      │
      ▼
Analyze Data
      │
      ▼
Generate Result

### Practical Engineering Perspective

Structured data is commonly used in AI applications through databases, APIs, and data-processing tools.

A typical engineering workflow is:

User / Application
        │
        ▼
   SQL / API Query
        │
        ▼
     Database
        │
        ▼
 Structured Data
        │
        ▼
 Processed Result
        │
        ▼
 ML / LLM Application
        │
        ▼
      Output

### Real-World Example

**Banking System**

Banks use structured databases to store customer information, account details, transactions, loan records, and payment history.

Customer / Transaction Data
            │
            ▼
      Structured Database
            │
            ▼
        SQL Queries
            │
            ▼
    Business Operations
            │
            ▼
 Reports / Analytics / AI