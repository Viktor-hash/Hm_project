# Hm Project

In order to do this project I will use *recommendations systems* :

First I will try to predict by articles categories the 7 days futur purchases of a client (for simplification):

## Using scikit-surprise 

What we need :

ratings_dict = {
    "item": [1, 2, 1, 2, 1, 2, 1, 2, 1],
    "user": ['A', 'A', 'B', 'B', 'C', 'C', 'D', 'D', 'E'],
    "rating": [1, 2, 2, 4, 2.5, 4, 4.5, 5, 3],
}


For us the item will be the "product_group_name" in order to have less data and a simplified model.
The user will be the "customer_id".
And finally the rating will be number of times a customer has bought a "product_group_name".


### Sources 

[recommendations systems with python](https://realpython.com/build-recommendation-engine-collaborative-filtering/#using-python-to-build-recommenders)

