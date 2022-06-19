# Energy-Intensity-Estimation-by-DNN
The code and data provided here is from the paper "Building a top-down method based on machine learning for evaluating energy intensity at a fine scale" published on Energy.

To run the code of this project, you should be able to use Python and Google Earth Engine.

## The workflow is shown as below:
1. use the JavaScript code under the folder of _extracting features_ to extract features;
2. train all the Deep Neural Network(DNN) under the folder of _training and testing_, and save all the results including models' parameters;
3. apply all the trained DNNs to predict city scale energy intesnity under the folder of _applying_.

The finnal predicted _city scale energy intesnity.csv_ is provided under the folder of _applying_.
