---
title: Designing a Classifier
---

## Designing a Classifier (30 mins)

A **classifier** makes predictions by assigning labels to observations. In the video we saw several classifiers that observed facts about the world (amount of daylight, human behavior), then decided what actions to take (turning lights on and off) based on these observations. 

In this exercise, you will design a classifier that a credit card company will use to identify potentially fraudulent activities. 

<br>

### Think/Pair/Share (10 min)

Imagine that you were hired by a credit card company to design an algorithm that cuts down on fraudulent activity. What kinds of data can you use that might indicate when fraud is happening? Spend 5 minutes brainstorming a list of ideas, considering how each input feature helps accomplish your goal and how you would collect that data. 

```
NAME THE FEATURE     WHY IS THIS FEATURE INFORMATIVE?     HOW WOULD YOU GET THIS FEATURE?

1.
2.
3.
(...)
```

In pairs or small groups, compare your lists of features and choose the two data sources that you see as most important for detecting fraudulent credit card usage. Use the structure below to design two rules that your classifiers can use to predict whether a transaction is *fraudulent* or *not fraudulent*.

```
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
* What did you want to achieve with your rule? (E.g., catch every possible case of fraud, minimize inconvenience for people travelling)
* How would you check that your classifier works?
* What are the errors your classifier might make, and what are the consequences of these errors? 
* Who benefits from the classifier’s decisions and who is harmed by its mistakes? Do you see any patterns in the distribution of benefits and harms?

<br>

### Wrap-Up (5 min)

In the video we watched together, we saw how machines learn from data. We then followed up with an activity that explored how data can help identify credit card fraud. We started by forming a mental picture, or a “model”, of what constitutes fraud, then looked at different types of information we could use to encode that model as a logical rule, or a classifier. 

Models guide how we define problems, and help identify ways to diagnose or solve them. When machines learn models from the data we give them, the results are logical rules that are only as good as the data on which they are trained. 

Consider the classifiers shared by the group and spend a few minutes reflecting as a group:
* Were you surprised by any of the rules that were created?
* Did experiences from your life guide how you approached solving this problem? 
* Was there anything about this activity that felt frustrating or challenging?
