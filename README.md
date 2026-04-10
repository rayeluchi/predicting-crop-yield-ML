# Which modeling approach performs best for yield prediction?
Dataset: https://www.kaggle.com/competitions/agriyield-2025/data 

Compare:
Linear regression

Random Forest

Gradient Boosting (XGBoost/lightGBM)

Shallow neural networks

Changes to weather patterns and landscape characteristics can happen swiftly and without warning, taking farmers by surprise and impeding critical harvest yields. There has been significant research concerning the prediction of agricultural yields including Haggerty et al. (2025), which uses climate indicators to rank the suitability of landscapes in southern Brazil for corn growth and production. Without knowledge of feature importance, however, these models would produce insignificant valuations of crop predictions and remain unhelpful for agricultural policy-making, food security evaluations, and resource allocation. 

The data we selected from Kaggle explores maize (corn) yields as a target of environmental features like soil characteristics, weather, and remote sensing properties. The challenge of this Kaggle competition was to “support precision agriculture by enabling early yield forecasting and smarter farm management”. By using this dataset, we hope to identify which method of machine learning and data analysis from our class is the most applicable to this kind of agricultural prediction and explore the feature importance of environmental indicators for yield predictions. Detailed knowledge on modelling methods and feature importance strengthens modelling outputs and better informs both agriculture producers and consumers. 

Features:
field_id: Unique identifier for each field
soil_ph: Soil acidity (pH scale)
organic_matter: Percentage of organic matter in the soil
sand_pct: Percentage of sand in soil composition
temperature: Average temperature (°C) during the growing season
humidity: Average relative humidity (%) during growing season
rainfall: Total rainfall (mm) during growing season
ndvi: Normalized Difference Vegetation Index (remote sensing) 

Target:
yield: Maize yield measured in kilograms per hectare (kg/ha) 
