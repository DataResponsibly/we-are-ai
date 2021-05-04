---
title: Designing a Classifier
---

## Designing a Classifier (30 mins)

A **classifier** is an algorithm that makes predictions by assigning labels to observations. In the video, we saw several classifiers that observed facts about the world (amount of daylight, human behavior), then decided what actions to take (turning lights on and off) based on these observations. 

In this exercise, you will design a classifier that a credit card company will use to identify potentially fraudulent transactions. 

<br>

### Think/Pair/Share (15 min)

Imagine that you were hired by a credit card company to design an algorithm that cuts down on fraudulent activity. What kinds of data can you use that might indicate when fraud is happening? Spend 5 minutes brainstorming a list of ideas, considering how each input feature helps accomplish your goal and how you would collect that data. Ask one participant to take notes for the group.

<center><img src="../../../img/02-04-designing-classifiers.png" alt="Table showing a 3x5 grid. The top cells are labels for each column and read: INPUT FEATURE, WHY IS THIS FEATURE INFORMATIVE?, and HOW WOULD YOU GET THIS FEATURE?. There is a corresponding example for each underneath: example: transaction amount, unusually high amount may indicate fraud, and credit card company has this information. The rest of the cells are blank." width="100%"/></center>

In pairs or small groups, compare your lists of features and choose the two data sources that you see as most important for detecting fraudulent credit card usage. Use the structure below to design two rules that your classifiers can use to predict whether a transaction is *fraudulent* or *not fraudulent*.

```
Example Rule:
If transaction amount 3 times higher than monthly average 
Then fraudulent
Otherwise not fraudulent

Rule 1:  
If (...)
Then fraudulent
Otherwise not fraudulent

Rule 2:  
If (...)
Then fraudulent
Otherwise not fraudulent
```

<br>

### Group Discussion (15 min)

Return to the full group and take turns sharing your fraud detection classifiers. Authors can share the written text or read the description of the features and of the rules out loud. 

For each classifier, ask the author to answer the following questions:
* What did you want to achieve with your classifier rule? (E.g., catch every possible case of fraud, minimize inconvenience for people travelling)
* How would you check that your classifier works?
* Who benefits when the classifier works?
* What errors might the classifier make, and who is harmed by these errors?
