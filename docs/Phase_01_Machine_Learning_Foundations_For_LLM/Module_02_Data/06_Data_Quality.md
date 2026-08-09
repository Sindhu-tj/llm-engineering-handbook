Data quality is the measure of how accurate, complete, consistent, relevant, timely, and reliable data is for its intended use.

Data Collection
       │
       ▼
Data Storage
       │
       ▼
Data Quality Check
       │
       ▼
Reliable Data
       │
       ▼
AI / ML / LLM Application

KEY DIMENSIONS OF DATA QUALITY
Accuracy: Data correctly represents the real-world value.
Completeness: Required data is not missing.
Consistency: Data does not conflict across sources or records.
Validity: Data follows the required format and rules.
Timeliness: Data is sufficiently up to date.
Uniqueness: Duplicate records are identified and handled.

LLM ENGINEER PERSPECTIVE
Data quality is especially important in LLM and RAG systems because poor-quality source data can lead to poor retrieval and unreliable responses.
EXAMPLE:If company documents contain outdated, duplicated, or incorrect information, the RAG system may retrieve that information and the LLM may generate an incorrect answer.

PRATICAL EXAMPLE
Consider a enterprise RAG System:
Company Documents
       │
       ▼
Data Collection
       │
       ▼
Data Storage
       │
       ▼
Data Quality Checks
       │
       ├── Remove duplicates
       ├── Handle missing data
       ├── Validate content
       └── Check outdated information
       │
       ▼
Clean / Reliable Data
       │
       ▼
RAG Pipeline
       │
       ▼
LLM
       │
       ▼
Reliable Response