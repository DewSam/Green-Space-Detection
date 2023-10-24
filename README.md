# GreenSpaceDetection
### Goal:
Detection of Green Spaces in an Urban Region for Future Urban Revitalization
### Project Details
The Governance Aspect utilizes high-resolution imagery obtained from the Green Expo Park Center (Zhengzhou City, China) via an unmanned aerial vehicle (UAV).
Sample selection is carried out randomly with input from on-site experts and the project holder.
Each sample consists of a 30 by 30-pixel image categorized into one of five classes: 'bldg' (representing buildings and structures), 'park' (denoting green spaces), 'pav' (indicating paved areas like plazas and sidewalks), 'water' (corresponding to lakes and ponds), and 'trans' (representing transportation spaces such as roads and streets).
A Governance dataframe is constructed by extracting pixel values from these image samples.
The dataframe is divided into training and test datasets, each containing 500 samples spread across the five classes.
Each observation within the dataset is defined by 2,700 pixel values, which serve as features.
The main goal of this study is to classify numeric attributes for the purpose of detecting green spaces.
