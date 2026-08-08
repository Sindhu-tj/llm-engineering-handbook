Data sources are the places or systems from which data is collected, accessed, or retrieved for processing, analysis, Machine Learning, and LLM applications.
In real-world AI systems, data can come from databases, APIs, files, websites, cloud storage, applications, and user-generated content.

MAJOR DATA SOURCES

                         DATA SOURCES
                              │
       ┌──────────────┬───────┼────────┬──────────────┐
       ▼              ▼       ▼        ▼              ▼
   Databases        APIs    Files    Web Data     Applications
       │              │       │        │              │
    SQL/NoSQL      JSON    PDF/CSV   Websites     Logs/Events

1. DATA BASES
A database is a system used to store, organize, manage, and retrieve data efficiently.

COMMON TYPES
SQL: MySQL, PostgreSQL, SQLite
NoSQL: MongoDB, DynamoDB, Redis

LLM ENGINEER PERSPECTIVE
LLM applications use databases when they need access to structured, application-specific, or frequently updated information.

User Question
      │
      ▼
LLM Application
      │
      ▼
Database Query
      │
      ▼
Relevant Data
      │
      ▼
LLM
      │
      ▼
Final Response

REAL WORLD EXAMPLE
An enterprise support assistant retrieves a customer's order status from a database and uses the result to answer the customer's question.

2.APIs
An API (Application Programming Interface) allows one software system to communicate with another and exchange data or perform operations.

Common Formats
JSON
XML

LLM ENGINEER PERSPECTIVE

LLM Application
      │
      ▼
   API Request
      │
      ▼
External Service
      │
      ▼
  API Response
      │
      ▼
LLM / Application
      │
      ▼
Final Result

REAL WORLD EXAMPLE
An AI assistant calls a company's CRM API to retrieve customer information before generating a response.