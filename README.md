# AI Feasibility & Experimental Study for Customer Churn Reduction

## 1. Business Context
Customer churn directly impacts revenue and long-term growth in subscription-based businesses. 
Understanding which customers are likely to churn enables targeted retention strategies, 
improves customer lifetime value, and reduces acquisition costs.

## 2. Problem Framing
This project evaluates whether machine learning can be used as a reliable decision-support tool 
to predict customer churn and inform retention strategies.

Key questions:
- Is customer churn predictable using the available features?
- Which customer segments are most at risk?
- Do more complex models provide meaningful performance improvements over simpler baselines?

## 3. Hypotheses
- Tree-based models will outperform linear models due to non-linear feature interactions.
- Feature engineering on tenure and service usage will significantly improve recall for churned customers.

## 4. Evaluation Approach (Planned)
Models will be evaluated using metrics aligned with business impact, such as precision, recall, and F1-score, 
with particular focus on minimizing false negatives (missed churners).

## 5. Expected Outcomes
The outcome of this study will be an evidence-based recommendation on:
- Whether deploying an ML-based churn prediction system is justified
- Which modeling approach is most suitable
- Key limitations and next steps for a potential production rollout
