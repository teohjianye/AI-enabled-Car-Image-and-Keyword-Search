# AI-enabled Car Model Search using Image and Keywords

User can upload a car front image or type in car keywords and get the most relevant search results.
<br>
<br>
<b>A summary of the folders and fies:</b>
<br>
<br>
<b>a. DataPreprocessing.ipynb: </b>Show the steps to preprocess the images before feeding into the Image Search.ipynb
<br>
<br>
<b>b. Image Search.ipynb: </b>Contains all the image classification steps using pre-trained CNN models and ensemble learning. Generate best model weights which are used by model.ipynb
<br>
<br>
<b>c. Upload.ipynb: </b>Construct an API to link with the templates' html. Import libraries from keywordsearch.ipynb and model.ipynb
<br>
<br>
<b>d. best_model_baseline.hdf5: </b>Weight of best baseline model. Weights of pretrained models are not uploaded due to size limit.
<br>
<br>
<b>e. keywordsearch.ipynb: </b>Contains the keyword search library that will be upload.ipynb
<br>
<br>
<b>f. model.ipynb: </b>Contains the image search libary that will be imported to upload.ipynb
