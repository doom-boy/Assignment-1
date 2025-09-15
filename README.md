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

Something to note, if the color is of a shade of orange, it is the "Yes", or "True", direction of the parent boxes decision question. As for shades of blue, it is the "No", or "False", direction.

For example, if the parent question is "Tear <= 0.5" the the orange shaded box that extends from it is the "Yes" answer to that question. The blue shaded box that extends from it is the "No" answer to that question.  

In essence: Orange = True, Blue = False
 

***
With all of these in mind, when examining the outputted decision tree, it will make understanding the decision tree and how the decisions are made significantly easier. 