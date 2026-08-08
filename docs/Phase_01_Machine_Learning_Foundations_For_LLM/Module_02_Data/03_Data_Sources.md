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

3.FILES AND DOCUMENTS
Files and documents are data sources containing information stored in formats such as PDF, DOCX, TXT, CSV, Markdown, and spreadsheets.

Common Formats
PDF
DOCX
TXT
CSV
Markdown
XLSX

LLM ENGINEER PERSPECTIVE
Files and documents are one of the most important sources for RAG and enterprise knowledge systems.

Documents
    │
    ▼
Text / Content Extraction
    │
    ▼
Cleaning
    │
    ▼
Chunking
    │
    ▼
Embeddings
    │
    ▼
Vector Database
    │
    ▼
Retrieval
    │
    ▼
LLM

REAL WORLD EXAMPLE
A company uploads internal HR policies and technical documentation into a RAG system so employees can ask questions about company information.

4.WEB DATA
Web data is information available on websites and web pages, typically represented using HTML and related web technologies.

Common Sources
Websites
Online documentation
Knowledge bases
Articles
Public web pages

LLM ENGINEER PERSPECTIVE
Web data can be collected or accessed to provide information that is current, external, or not available in an application's internal database.

Website
   │
   ▼
Web Retrieval / Crawling
   │
   ▼
Content Extraction
   │
   ▼
Processing
   │
   ▼
Search / RAG
   │
   ▼
LLM

REAL WORLD EXAMPLE
An AI research assistant retrieves information from technical documentation and uses it to answer developer questions.

5.APPLICATIONS
Application data is data generated, collected, or stored by software applications during their normal operation and through user interactions.

Examples include logs, events, user actions, chat history, and application-generated records.

LLM ENGINEER PERSPECTIVE
Application data is useful because it provides information about how users and systems interact with an application.

It can be used for:

Monitoring and debugging
Analytics
Personalization
LLM evaluation
Improving AI applications
Understanding user interactions

EXAMPLE
Consider an enterprise AI assistant:
                    AI Application
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
      User Queries     Events          Logs
          │               │               │
          └───────────────┼───────────────┘
                          ▼
                    Application Data
                          │
                          ▼
                  Processing / Analysis
                          │
                          ▼
                    AI / ML System

Practical Engineering Workflow
Application
     │
     ▼
User Interaction / Events
     │
     ▼
Logs / Application Data
     │
     ▼
Collection
     │
     ▼
Processing / Storage
     │
     ▼
Analytics / AI / LLM
     │
     ▼
Result / Improvement