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


UNSUPERVISED LEARNING:

Unsupervised Learning is a type of Machine Learning where a model learns from unlabeled data to discover hidden patterns, relationships, or groups without predefined labels.

BLOCK DIAGRAM

              Unlabeled Dataset
          (Input Features Only)
                     │
                     ▼
           Data Preprocessing
                     │
                     ▼
     Unsupervised Learning Algorithm
                     │
                     ▼
      Discover Hidden Patterns
                     │
                     ▼
      Groups / Clusters / Relationships

EXAMPLE:(Netflix)
Customer Segmentation

PROBLEM:Netflix has millions of users.It only has user behavior.

EXAMPLE BLOCK DIAGRAM

           User Watching History
      (Movies, Genres, Watch Time)
                    │
                    ▼
          Unlabeled User Data
                    │
                    ▼
      Unsupervised Learning Model
                    │
                    ▼
     Discover Similar User Behavior
                    │
                    ▼
        Create User Clusters
                    │
                    ▼
   Personalized Movie Recommendations

   WORKING

   User Watching History
        │
        ▼
Collect User Behavior
        │
        ▼
No Labels Available
        │
        ▼
Find Similar Viewing Patterns
        │
        ▼
Group Similar Users
        │
        ▼
Recommend Similar Movies
