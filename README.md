# Assignment 1
## Understanding the Encoding
What I've done is essentially map all of the values of each feature to a number. Here is how I have mapped it:

- Age:
  - Young = 0
  - Prepresbyopic = 1
  - Presbyopic = 2
- Spectacle Prescription:
  - Myopic = 0
  - Hypermetropic = 1
- Astigmatism:
  - No = 0
  - Yes = 1
- Tear Production Rate:
  - Reduced = 0
  - Normal = 1

## Colors and Directionals

Something to note, if the color is of a shade of orange, it is the "Yes" class of the parent boxes decision question. As for shades of blue, it is the "No" class. The shade is to show how pure the decision is for being in that class.  

Now for directions, the boxes that extend to the left are the "True" answers to the parent question. Boxes that extend to the right are the "False" answers to the previous questions. 

For example, if the parent question is "Tear <= 0.5", the box to the left is the box that says the previous condition is true, that Tear Production Rate, according to the encoding, is less than 0.5 meaning "Reduced". The box to the right is saying the previous condition is false and that Tear Production Rate is greater than 0.5, or "Normal".   

In essence: Left = True, Right = False  

***
With all of these in mind, when examining the outputted decision tree, it will make understanding the decision tree and how the decisions are made significantly easier.  
  
![output plot from the decision tree code](/decisionTree_output.png)
