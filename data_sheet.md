Datasheet

#Motivation

For what purpose was the dataset created?
The dataset was created to benchmark energy consumption prediction models for commercial buildings. The dataset was part of the ASHRAE - Great Energy Predictor III competition, aimed at improving the prediction of energy usage in buildings, contributing to energy efficiency efforts in the construction and building management industries.

Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organisation)? Who funded the creation of the dataset?
The dataset was created by ASHRAE (American Society of Heating, Refrigerating, and Air-Conditioning Engineers) in collaboration with other partners. ASHRAE is a global society advancing human well-being through sustainable technology for the built environment. 

Composition
What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)?
The instances in the dataset represent energy usage records for commercial buildings, including features such as weather data (e.g., air temperature, dew point) and building-specific metadata (e.g., square footage, year built).
How many instances of each type are there?
The dataset contains over 20 million meter readings from buildings, each paired with its respective features such as weather data, building type, and other relevant parameters.
Is there any missing data?
Yes, the dataset contains missing values for some of the features such as weather-related fields (e.g., air temperature, dew point) and building data (e.g., year built). Preprocessing is required to handle these missing values.
Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?
No

#Collection Process
How was the data acquired?
The data was acquired from building management systems and smart meters installed in commercial buildings. Weather data was collected from publicly available meteorological databases.
If the data is a sample of a larger subset, what was the sampling strategy?
The dataset represents a sample of energy usage data across various buildings
Over what time frame was the data collected?
The data was collected over several years, with energy readings collected hourly or daily depending on the building’s metering infrastructure.

Preprocessing/Cleaning/Labelling
Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)?
Yes
Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data?
The raw data was saved and made publicly available on Kaggle, allowing researchers to perform their own preprocessing steps if needed.

Uses
What other tasks could the dataset be used for?
The dataset could be used for other tasks related to building performance, such as predicting the impact of different HVAC systems, optimising energy-efficient design choices, or studying the effect of external weather conditions on energy usage. It could also be repurposed for predictive maintenance applications in building management systems.
Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses?
The dataset primarily includes commercial buildings, so models trained on this data may not generalise well to residential or rural buildings. Moreover, the dataset’s geographical bias toward certain urban areas may limit its applicability to less developed regions. Additionally, the imputation of missing weather data might introduce inaccuracies that could affect model performance.
Are there tasks for which the dataset should not be used?
The dataset should not be used for tasks requiring residential building data or for predicting energy usage in regions where weather patterns and building designs differ significantly from those represented in the dataset. 

Distribution
How has the dataset already been distributed?
The dataset has been distributed publicly on Kaggle as part of the ASHRAE - Great Energy Predictor III competition. It is freely available for research and educational purposes.
Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?
The dataset is subject to Kaggle’s terms of use and the licensing agreements of ASHRAE, which allow for non-commercial research and development usage. 

Maintenance
Who maintains the dataset?
The dataset is maintained by ASHRAE in collaboration with Kaggle. ASHRAE is responsible for any updates, corrections, or expansions of the dataset. Any issues with the dataset are typically handled through Kaggle’s platform, where users can report errors or anomalies.

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 
