# AI-enabled Car Model Search using Image and Keywords

User can upload a car front image or type in car keywords and get the most relevant search results.

A summary of the folders and fies:
a. DataPreprocessing.ipynb: Show the steps to preprocess the images before feeding into the Image Search.ipynb
b. Image Search.ipynb: Contains all the image classification steps using pre-trained CNN models and ensemble learning. Generate best model weights which are used by model.ipynb
c. Upload.ipynb: Construct an API to link with the templates' html. Import libraries from keywordsearch.ipynb and model.ipynb
d. best_model_baseline.hdf5: Weight of best baseline model. Weights of pretrained models are not uploaded due to size limit.
e. keywordsearch.ipynb: Contains the keyword search library that will be upload.ipynb
f. model.ipynb: Contains the image search libary that will be imported to upload.ipynb
