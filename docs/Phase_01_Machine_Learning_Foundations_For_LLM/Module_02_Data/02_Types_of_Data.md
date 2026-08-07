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