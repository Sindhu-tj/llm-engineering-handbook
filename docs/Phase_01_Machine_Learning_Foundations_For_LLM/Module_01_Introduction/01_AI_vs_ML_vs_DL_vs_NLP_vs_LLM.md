#AI vs Machine Learning vs Deep leaning vs Natural Language Processing vs Large language model

AI is a broad field that includes systems capable of learning,reasoning,perception,and language understanding.

BLOCK DIAGRAM
                      Artificial Intelligence
                              │
      ┌─────────────┬──────────────┬──────────────┬
      │             │              │              │
   Learning     Reasoning     Perception     Language
      │             │              │              │
  Pattern       Decision      Vision        Speech & Text
 Recognition     Making
  
 WORKING 
 
             Input
              │
              ▼
      Receive Information
              │
              ▼
      Process Information
              │
              ▼
      Make Decision
              │
              ▼
           Output

EXAMPLE:

Camera Image
      │
      ▼
AI detects a traffic light
      │
      ▼
Traffic Light = RED
      │
      ▼
Decision: STOP
  
MACHINE LEARNING
Machine Learning teaches computers to learn from data instead of following manually written rules.

AI vs ML

Traditional AI       Machine Learning

Rules → Output       Data → Learning → Output

BLOCK DIAGRAM
                  Machine Learning
                         │
       ┌─────────────────┴─────────────────┐
       │                                   │
       ▼                                   ▼
 Training Data                  Learning Algorithm
       │                                   │
       └──────────────► Learn Patterns ◄───┘
                        │
                        ▼
                Trained Model
                        │
                        ▼
            Prediction / Decision

WORKING DIAGRAM
Training Data
      │
      ▼
Train ML Model
      │
      ▼
Learn Patterns
      │
      ▼
Trained Model
      │
      ▼
New Data
      │
      ▼
Prediction

EXAMPLE:
Gmail

Input:

Millions of emails

↓

ML learns spam patterns.

↓

Filters spam automatically.

DEEP LEARNING
automatically learn features and patterns from large amounts of data using neural networks.

BLOCK DIAGRAM
                  Deep Learning
                        │
        ┌───────────────┴───────────────┐
        │                               │
        ▼                               ▼
      Raw Data                  Neural Network
                                        │
                                        ▼
                            Multiple Hidden Layers
                                        │
                                        ▼
                             Learn Complex Features
                                        │
                                        ▼
                                 Prediction

WORKING DIAGRAM
Raw Data
      │
      ▼
Input Layer
      │
      ▼
Hidden Layers
      │
      ▼
Automatically Learn Features
      │
      ▼
Output Layer
      │
      ▼
Prediction

EXAMPLE:           User Prompt
                     │
                     ▼
          Deep Learning Model
        (Transformer Network)
                     │
                     ▼
       Learns Language Patterns
                     │
                     ▼
          Predicts Next Token
                     │
                     ▼
          Generates Response

NATURAL LANGUAGE PROCESSING
NLP teaches computers to understand and communicate using human language.

BLOCK DIAGRAM
               Human Language
             (Text / Speech)
                     │
                     ▼
          Natural Language Processing
                     │
      ┌──────────────┼──────────────┐
      │              │              │
      ▼              ▼              ▼
 Understand     Analyze Meaning   Generate Text
                     │
                     ▼
              Perform NLP Task
                     │
                     ▼
        Translation / Chatbot / Search

WORKING
User Input
"Best restaurants near me"
          │
          ▼
     Text Processing
          │
          ▼
 Understand Meaning
(Intent + Context)
          │
          ▼
 Find Relevant Information
          │
          ▼
 Generate Result
          │
          ▼
Display Nearby Restaurants

PRACTICAL EXAMPLE(CHATGPT)
User Prompt
"What is Machine Learning?"
          │
          ▼
       NLP System
          │
Understands Language
          │
          ▼
 Finds Context
          │
          ▼
 Generates Response
          │
          ▼
Displays Answer

LARGE LANGUAGE MODEL



BLOCK DIAGRAM
                  Large Language Model (LLM)
                           │
                 User Prompt / Question
                           │
                           ▼
                     Tokenization
                           │
                           ▼
                  Transformer Model
                           │
         Understands Context & Patterns
                           │
                           ▼
                Predicts Next Token
                           │
                           ▼
                 Generates Response
                           │
                           ▼
                    Final Output

WORKING

User Prompt
"Explain Machine Learning"
          │
          ▼
Tokenization
(Break sentence into tokens)
          │
          ▼
Transformer
(Understands context)
          │
          ▼
Next Token Prediction
          │
          ▼
Response Generation
          │
          ▼
Machine Learning is a subset of AI...

 EXAMPLE:
Developer Writes Code
         │
         ▼
   Tokenization
         │
         ▼
Transformer-based LLM
         │
         ▼
Understands Context
         │
         ▼
Predicts Next Token
         │
         ▼
Code Completion
