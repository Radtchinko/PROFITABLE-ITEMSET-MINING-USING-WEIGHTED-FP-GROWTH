# PROFITABLE-ITEMSET-MINING-USING-WEIGHTED-FP-GROWTH
## 1. INTRODUCTION
**Mining frequent patterns or Itemsets is an important issue in\
the field of data mining due to its wide applications.\
Traditional Itemset mining is, however, done based on\
parameters like support and confidence. The most widely\
used algorithms to obtain frequent Itemsets are Apriori and\
Frequent pattern growth. They are binary in nature. It means\
that they only consider whether the product is sold or not. If\
the product is sold, then it is considered true and else false.\
And these algorithms produce frequent itemsets, which only\
consider the occurrence of items but do not reflect any other\
factors, such as price or profit. Profitable Itemset Mining has\
recently been proposed, in which transactions are attached\
with weighted values according to some criteria. It is\
important because if support and confidence are only the\
parameters assumed, we may miss some of the profitable\
patterns.. However, the actual significance of an Itemset\
cannot be easily recognized if we do not consider some of\
the aspects like quantity and profit per each item.. The\
problem of Profitable Itemset mining is to find the complete\
set of Itemsets satisfying a minimum profit constraint in the\
database. When we are calculating the Profitable Itemsets\
we can consider minimum weight as constraint and we can\
ignore the support as our goal is to find the Profitable\
patterns. In the real world, there several applications where\
specific patterns and items have more importance or priority\
than the other patterns. Profitable Itemset mining has been\
suggested to find Profitable patterns by considering the\
profits as well as quantity of Items. The concept of Profitable\
Itemset mining is attractive in that profitable patterns are\
discovered. We can use the term, Profitable Itemset to\
represent a set of profitable items. The Itemsets we get are\
frequent profitable itemsets as well as infrequent profitable\
itemsets.**



## 1.1 BASIC CONCEPTS
**Itemset mining helps us to find the frequent patterns or\
itemsets . The two most widely used algorithms are Apriori\
and FP Growth. These two algorithms are binary in nature.\
They concerned about whether the product is sold or not.\
The measures considered by these algorithms are support\
and confidence. But in reality they are not sufficient for\
decision making in the large organizations. So In this\
framework we consider two measures named Quantity and\
Profit. By using both the parameters we calculate Weight.\
Consider the following two transactions:\
T1: {20 Buns, 5 Chocolates}\
T2: {1 Bun, 1 Chocolate}\
In the support-confidence frame work the above two\
transactions are considered to be the same, since the\
quantity of an item is not taken into account. But in reality, it\
is quite clear that the transaction T1 gives more profit than\
the transaction T2. Thus to make efficient marketing we take\
in to account the quantity of each item in each transaction. In\
addition we also consider the intensity of each item, which is\
represented using profit per item p.\
Consider the following two transactions:\
T3: {10 Buns, 1 Chocolate}\
T4: {2 Buns, 3 Chocolates}\
In reality the quantity sold in transaction T3 is greater than\
transaction T4, but the amount of profit gained by selling a\
chocolate (Say Dairy milk) is 10 times that of a Bun. So, the\
profit is also given priority represented by p. “p” may\
represent the retail price / profit per unit of an item.**



## 1.2 PROBLEM DEFINITION
**In this paper taking into account the profit / intensity of the\
item and the quantity of each item in each transaction of the\
given database, we propose two algorithms Profitable\
Apriori and Profitable FP Growth. These algorithms take into\
account two parameters Quantity and Profit. In this by\
incorporating the profit per item and quantity we generate\
Profitable Apriori and Profitable FP Growth. In this paper,\
the notations corresponding to the new structure is given\
below.\
Universal Itemset = I\
I = { i1 :q1*p1 , i2 : q2*p2 , . . . , im :qm* pm } ,\
{ i1 , i2 , . . . , im } represents the items purchased,\
{q1,q2,q3.....qm} represents quantity of purchase,\
{p1,p2,p3.....pm} represents their respective profits.\
The ith transaction of the database D is of the form\
Ti={wir,....}\
r represents item number,\
w = q*p.**



## 2 PROFITABLE FP GROWTH
**Profitable FP-Growth algorithm is based on FP-Growth\
algorithm in data mining. Generally FP-Growth algorithm is\
binary in nature. It doesn’t consider quantity and weight per\
unit in a transaction. So In our algorithm we consider\
quantities and profits per items in a transaction.**


## 2.1 ALGORITHM
![](https://drive.google.com/file/d/1Cah0KD7LpsevD_r1DaSDvUDRcL1ih5RH/view?usp=sharing)

1[](https://drive.google.com/file/d/1KmvVLCUuzQZQRISBE2Nj7lZFviMty1vW/view?usp=sharing)
