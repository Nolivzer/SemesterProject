# Main track:

I want to use in my project the database of Huang, because the database is good represented.

  ## First axis:
- Represent ingredients database as decision trees for the organization of the dataset :
  - for instance : flour can be subdivised in corn flour, maïs flour...or sugar in white sugar , brown sugar...
  - easier view on the dataset
we'll can create classes by type of ingredients

### Why decision trees as classifiers ?

Decision trees are powerful to represent large amount of data.
Facility of implementation and transparency
hierarchical classification: sometimes in recipe it is more relevant to know the type of ingredient whether the ingredient in particular (for instance the sugar: _Brown or white?_)

### Problems:

Definition of classes: the number of them => the size of the tree and the granularity.
Find the partition function: what can be the target value: _Nutrition mark, frequency, if it is a volume a mass, a spoon (unit of measure)..._

How to find a the target? Indeed, we have a set of aliments (ingre_dict), but now I have to find a dataset to create a target.




### Finality:

A new ingredient will be automatically placed in a class.

The database will be more scalable it is profitable for the processing time.

### Technical goals:

- Create trees for each target value (on the part of the data set):
  - Nutrition mark
  - Frequency
  - type (liquid / solid and then all the posibilities)
  - unit of measure


Find metrics to define the most relevant target value:
  - Measure of the best information gain mean
  - the deep or the wide criteria  



### Bibliography:

 _DATA MINING WITH DECISION TREES Theory and application_ , __Lior Kokach and Oded Maimon _

 https://www.shiveshskitchen.com/2015/09/classification-of-vegetables.html for the vegetables classification
