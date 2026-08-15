Feature engineering means creating, transforming, or selecting useful features from raw data so that a machine-learning model can learn better patterns.

Feature Engineering — Practical Example
Suppose we have this customer dataset:
| Customer | Age | Monthly Income | Total Spending | Months |
| -------- | --: | -------------: | -------------: | -----: |
| A        |  25 |        ₹30,000 |        ₹60,000 |     12 |
| B        |  40 |        ₹50,000 |      ₹1,20,000 |     24 |
| C        |  35 |        ₹40,000 |        ₹90,000 |     18 |

Step 1: Raw features
We already have:

Age
Monthly Income
Total Spending
Months

Step 2: Create new features
We can derive:
Annual Income

Annual Income = Monthly Income × 12

For customer A:

30,000 × 12 = ₹3,60,000

Average Monthly Spending

Average Monthly Spending = Total Spending ÷ Months

For customer A:

60,000 ÷ 12 = ₹5,000

Step 3: Final dataset
| Customer | Age | Monthly Income | Months | Annual Income | Avg Monthly Spending |
| -------- | --: | -------------: | -----: | ------------: | -------------------: |
| A        |  25 |        ₹30,000 |     12 |     ₹3,60,000 |               ₹5,000 |
| B        |  40 |        ₹50,000 |     24 |     ₹6,00,000 |               ₹5,000 |
| C        |  35 |        ₹40,000 |     18 |     ₹4,80,000 |               ₹5,000 |
