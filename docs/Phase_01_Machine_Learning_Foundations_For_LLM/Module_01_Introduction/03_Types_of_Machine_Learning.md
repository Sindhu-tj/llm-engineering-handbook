BLOCK DIAGRAM

                    Machine Learning
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
        ▼                  ▼                  ▼
  Supervised         Unsupervised       Reinforcement
    Learning            Learning           Learning

1. Supervised Learning:
Supervised Learning is a type of Machine Learning where a model learns from labeled data to predict the correct output for new, unseen inputs.

BLOCK DIAGRAM

                 Labeled Dataset
          (Input Features + Target Label)
                        │
                        ▼
                 Data Preprocessing
                        │
                        ▼
          Supervised Learning Algorithm
                        │
                        ▼
                 Learn Patterns
                        │
                        ▼
                  Trained Model
                        │
                        ▼
                   New Input Data
                        │
                        ▼
                Predict Target Output

Company-Level Example (Meta)
Facebook / Instagram Feed Ranking.
Problem: Which post should appear first in a user's feed?

BLOCK DIAGRAM

      Historical User Interactions
 (Likes, Comments, Shares, Watch Time)
                    │
                    ▼
          Labeled Training Data
      (Engaged / Not Engaged)
                    │
                    ▼
        Supervised Learning Model
                    │
                    ▼
     Learns User Engagement Patterns
                    │
                    ▼
            Trained ML Model
                    │
                    ▼
            New Facebook Post
                    │
                    ▼
      Predict Engagement Probability
                    │
                    ▼
        Rank Posts in User Feed