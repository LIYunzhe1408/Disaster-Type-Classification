# Disaster-Type-Classification
In disaster situations, it is important for emergency response efforts to have access to quick and accurate information about an area in order to respond effectively. This project will explore how data science techniques can be useful for such efforts.

## Project Goals
* Learn to work with image data by learning to use common feature extraction techniques like Sobel edge filtering.
* Learn to work on real-world data with common complexities such as class imbalance, low signal-to-noise ratio, and high dimensional data.
* Learn how to design effective preprocessing and featurization pipelines for solving difficult machine learning tasks.
Mission

## Dataset Description
The agency would like you to develop your approach on their internal dataset, derived from the xView2 Challenge Dataset. This dataset contains satellite images of buildings after various natural disasters. The buildings are labeled based on the level of damage sustained on a scale ranging from 0 (no damage) to 3 (destroyed).

## Task
The agency consists of different subdivisions for assisting with different disaster types, e.g., fires, floods, etc. In the event of a disaster, the agency mounts its response effort by first assessing the type of disaster and then requesting the appropriate subdivision to assist with the disaster.

Your task is to assist the agency with making this initial call quickly by automatically classifying images based on the disaster scenario. Specifically, your role will be to build a classifier that can distinguish images from the `midwest-flooding` disaster and the `socal-fire` disaster.

To assess your performance, please submit predictions for the `test_images_flooding-fire.npz` images. This should be in a csv file `test_images_flooding-fire_predictions.csv` consisting of a single column named `pred`, with a 0 to indicate a `midwest-flooding` prediction and a 1 to indicate a `socal-fire` prediction. The prediction in row i should correspond to the ith image.

## Progress
Milestone 1: EDA. [Report](https://docs.google.com/document/d/1RUBewmjUfKPpRcgTdssZq3jhmc9AIs0d26-glOFoRA0/edit?tab=t.0#heading=h.qs13alwirz8x)
Milestone 2: Close the loop for classification with logistic regression. [Report](https://docs.google.com/document/d/1xDWnAdLS_3OnO-LArFH798HMRDGuQPYTaCULiqV0s20/edit?usp=sharing)