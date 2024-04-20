# Asteroid-Classification
Neural Network based classification of an Asteroid as Hazardous or Non-Hazardous using the NASA's NEO (Near Earth Object) data obtained from Kaggle.

## Data Collection
The dataset was obtained from Kaggle - https://www.kaggle.com/datasets/lovishbansal123/nasa-asteroids-classification

## EDA

### Distribution of Hazardous and Non-Hazardous Asteroid data:-

<img width="384" alt="pie" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/2524e8c4-d314-4416-a090-72803c681c5e">

### Histograms with the probability densities of the features based on the value of the target variable 'Hazardous'

<img width="426" alt="Relative Velocity km per hr" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/4a5bffff-2ffc-49ba-8b2d-1feaf1d6dfbc">

<img width="408" alt="Miss Dist (kilometers)" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/65f7b007-5f2b-431d-b2ae-d4b2cad7ad8a">

<img width="427" alt="Asc Node Longitude" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/bbd4ba73-de4d-4005-b85c-07fb57232cf2">

<img width="421" alt="Perihelion Arg" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/456885d9-10d5-4d98-b852-1e0397e31b44">

<img width="408" alt="Aphelion Dist" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/ebeea699-50a9-4935-a0e0-3dad9d3c6f03">

<img width="434" alt="Perihelion Time" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/4b642d3b-b728-4237-850e-b8b354e520d2">

<img width="427" alt="Mean Anomaly" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/6986bcef-c97b-4878-bd70-a610787c8b92">

<img width="408" alt="Miss Dist (kilometers)" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/6d73ec49-89ac-4beb-964a-d03115117531">

### Correlation Heatmap

<img width="514" alt="Heatmap" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/04975b79-05d7-4db8-8ea2-e42779972d50">

### Neural Network Architechture

Input Layer : 8 Inputs
Hidden Layer : 1 Hidden Layer with 4 Nodes
Output Layer : Single Output with Sigmoid Activation

### Training 

<img width="408" alt="Accuracy" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/3f8cc5d0-d3bd-4664-9907-cc5abc98768b">

<img width="408" alt="Loss" src="https://github.com/AgKing3242/Asteroid-Classification/assets/139226792/1e80964b-c4b6-4231-8e2e-e6eef685b624">

### Results

The model achieved a testing accuracy of 85.02 %
