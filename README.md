# Market-Basket-Analysis

Market basket analysis scrutinizes the products customers tend to buy together, and uses the information to decide which products should be cross-sold or promoted together. The term arises from the shopping carts supermarket shoppers fill up during a shopping trip.

We can use MBA to extract interesting association between products from the data. Hence its output consists of a series of product association rules: for example, if customers buy product A they also tend to buy product B. We will follow the three most popular criteria evaluating the quality or the strength of an association rule

## Remember these three import terms of Market basket analysis:

    - Support      -> P(AB)
    - Confidence   -> P(B|A)
    - Lift         -> P(B|A)/P(B)
    
1. Support is the percentage of transactions containing a particular combination of items relative to the total number of transactions in the database. The support for the combination A and B would be,
P(AB) or P(A) for Individual A

2. Confidence measures how much the consequent (item) is dependent on the
antecedent (item). In other words, confidence is the conditional probability of the consequent given the antecedent,
P(B|A)
where P(B|A) = P(AB)/P(A)

3. Lift (also called improvement or impact) is a measure to overcome the
problems with support and confidence. Lift is said to measure the difference — measured in ratio — between the confidence of a rule and the expected confidence. Consider an association rule “if A then B.” The lift for the rule is defined as
P(B|A)/P(B) or P(AB)/[P(A)P(B)].

Each criterion has its advantages and disadvantages but in general we would like association rules that have high confidence, high support, and high lift.
    
