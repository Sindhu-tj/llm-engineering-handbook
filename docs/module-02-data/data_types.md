# Types of Data

## Overview

Data is the foundation of Machine Learning and Artificial Intelligence systems. 
Different types of data require different methods for storage, preprocessing, 
analysis, and modeling.

The three major types of data are:

1. Structured Data
2. Semi-Structured Data
3. Unstructured Data

---

## 1. Structured Data

Structured data is organized in a fixed format, usually rows and columns.

### Examples

- Customer databases
- Sales records
- Financial transactions
- Sensor measurements
- CSV files
- SQL tables

### Example

| Customer_ID | Age | Monthly_Charges | Churn |
|-------------|-----|-----------------|-------|
| 1001 | 25 | 70.50 | Yes |
| 1002 | 42 | 55.20 | No |

### Machine Learning Usage

Structured data is commonly used for:

- Classification
- Regression
- Clustering
- Forecasting

---

## 2. Semi-Structured Data

Semi-structured data does not follow a strict table format but contains 
organizational elements such as keys, tags, or metadata.

### Examples

- JSON
- XML
- YAML
- HTML
- API responses
- Configuration files

### Example

{
  "customer_id": 1001,
  "name": "Alex",
  "subscription": {
    "plan": "premium",
    "active": true
  }
}
### Machine Learning Usage

Semi-structured data is often transformed into structured features before
being provided to traditional Machine Learning models.

---

## 3. Unstructured Data

Unstructured data does not have a predefined tabular structure.

### Examples

- Text documents
- Images
- Audio
- Video
- PDFs
- Emails
- Social media posts

### Machine Learning and LLM Usage

Unstructured data is extremely important for modern AI systems.

Examples:

- Text → NLP and LLMs
- Images → Computer Vision
- Audio → Speech Recognition
- Video → Video Understanding

LLM systems commonly process unstructured text from documents, websites,
PDFs, conversations, and other sources.

---

## Data Types in AI Systems


                         DATA
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
     Structured       Semi-Structured    Unstructured
          |                |                |
       CSV/SQL         JSON/XML/YAML      Text/Images
          |                |                |
          +----------------+----------------+
                           |
                           v
                    Data Processing
                           |
                           v
                    Machine Learning
                           |
                           v
                     AI / LLM System


## Key Takeaway

Understanding data types is essential because the data format determines how
the data should be collected, cleaned, transformed, represented, and supplied
to Machine Learning or LLM systems.
