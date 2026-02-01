This folder will contain any and all datasets that we plan on using for the machine learning algorithms. 

1-24-2026
Finalized the RF, DT, and KNN models, but you MUST use a kaggle.json file in order to download and use the datasets.

To get a kaggle.json file:
1. Create a Kaggle account
2. Click your account on the top left and then "Settings"
3. Scroll down until you see "Legacy API Credentials" and then you want to click "Create Legacy API Key"

When you go to run the program it will always ask for you to input your kaggle.json. 

The first dataset I used was: https://www.kaggle.com/c/rsna-pneumonia-detection-challenge NOTE: you will have to accept the challenge on Kaggle (it should be fine though, the competition is done)
The second dataset was: https://www.kaggle.com/datasets/sjagadeeshgiet/image-tamper-dataset

(You can try to use the csv files, but honestly it might just be better to use the .ipynb file in the Algorithms folder and go through all the steps of the code)

1-25-2026

I updated the program to use CT-GAN instead of the simple tamper dataset. Please refer to the .ipynb in the Algorithms for how to install the CT-GAN dataset and how to use it.

2-1-2026

Datasets currently in use:
1. BTD - MRI and CT deepfake test sets (https://www.kaggle.com/datasets/freddiegraboski/btd-mri-and-ct-deepfake-test-sets)
2. COVID-19 Digital X-rays Forgery Dataset (https://www.kaggle.com/datasets/nourmahmoud/covid19-digital-xrays-forgery-dataset)
3. Medical Image tamper dataset (https://www.kaggle.com/datasets/sjagadeeshgiet/image-tamper-dataset)
4. COVID-19 chest xray (https://www.kaggle.com/datasets/bachrr/covid-chest-xray)
