# Meal suggestion for kidney protection patient

Final project for the Building AI course

## Summary

Create a system to show the meal's require to buy for each date with nutrition contain suggestion from hosiptal, and provide the list of shop can buy these food. The method for cooking also will show base on each food suggestion.


## Background

Some of the patients with kidney performance dropping, their doctor will suggest their meal's food with low Salt, Sugar or Potassium or for all.

## How is it used?

Each of patients choice of the nutrition need to keep limit the level, the AI will base on each food nutrition information (fill out fake or outdate inform) and base on the standard of type of limit level suggest by the standard, create a meal list suggestion to patient to choice in each date and provide the list of shop where to buy them.

## Data sources and AI methods
System will get below information from the web or some known database:
1. food nutrition.
2. updated date (as it will outdate on different times of checking)
3. the shop contain this food with photo and the near to patient home.
4. some cooking method to remove some unwant ion like potassium.
5. some common meal list to patient if they want.

AI method:
1. Near neightbor to previde some recommandation list base on trainning data.
2. linear regression to predict the damage level baes on patients choice.

Output of the recommendation system will be one or more items which will be then displayed to the Customer during order generation process.

## Challenges

In order to get more patient trainning date to the system, it require to get the information from the relative problems patients directly and keep collection to their behaviour for food and provide a common list to other patients

## What next?

Next step would be to create data model for data sources provide by patients with or without the kidney problems.


## Acknowledgments
The Elements of AI Team for inspiring me to try this project
...

