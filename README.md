# WeakLearnr

## Decision Trees

Simplest Decision Tree

![1.png](./images/1.png)

Classification Decision Tree

![2.png](./images/2.png)

Regression Decision Tree

![3.png](./images/3.png)

Simple Classification Decision Tree

![4.png](./images/4.png)

Terminologies

![5.png](./images/5.png)

- Root Node: Statement At The Start (Outgoing Decision Only)
- Intermediate/Internal Node: Incoming And Outgoing Decision
- Leaf Node: Final Value (Incoming Decision Only)

Training Data: Both Continuous And Discrete Data

![6.png](./images/6.png)

Why Not Logistic Regression?

![7.png](./images/7.png)

- Plotting Age Vs Output: Not Separable Using Logistic Regression

Sample Decision Tree For The Above Example

![8.png](./images/8.png)

Purity Of Leaf Nodes

![9.png](./images/9.png)

- Impure Node: Mixture Of Outputs
- Pure Node: Single Type Of Output
- Aim: Choose Statement With Highest Pure Node ("Loves Cartoon" Has More Pure Nodes Than "Loves Movies")

Gini Impurity

- Helps Quantify Leaf Node Purity
- $` G_{leaf} = 1 - P(No)^2 - P(Yes)^2 `$
- $` w_{leaf} = \frac{n_{leaf}}{N} `$
- $` G_T = w_{leaf_1} \times G_{leaf_1} + w_{leaf_2} \times G_{leaf_2}`$

![10.png](./images/10.png)
![11.png](./images/11.png)

Gini Impurity Visualisation

![12.png](./images/12.png)

- The More Unequal The Probabilities, The More Pure The Leaf $`(p=0~or~1)`$
- The More Equal The Probabilities, The More Impure The Leaf $`(p=0.5)`$

Entropy

- $`E_{leaf}=-[P(No)log(P(No)) + P(Yes)log(P(Yes))]`$
- $` w_{leaf} = \frac{n_{leaf}}{N} `$
- $` E_T = w_{leaf_1} \times E_{leaf_1} + w_{leaf_2} \times E_{leaf_2}`$

![13.png](./images/13.png)
![14.png](./images/14.png)

Entropy Visualisation

![15.png](./images/15.png)

# Resources
## Decision Trees
1. [What are decision trees?](https://www.youtube.com/watch?v=JwLKSCJmouU&list=PLPTV0NXA_ZSjXY1XnEmtyHN5do21KCgJR&index=1)
2. [Let us start building a decision tree!](https://www.youtube.com/watch?v=2_DQ-jsDqf0&list=PLPTV0NXA_ZSjXY1XnEmtyHN5do21KCgJR&index=2)
3. [What is Gini Impurity?](https://www.youtube.com/watch?v=R8seoseB-Bc&list=PLPTV0NXA_ZSjXY1XnEmtyHN5do21KCgJR&index=4)
