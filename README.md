# FinalProject_IDLS


## Stock Market Predictions with Natural Language Processing and Deep Learning


This project analyzes Amazon Stock data using Python. 

Feature Extraction is performed and ARIMA and Fourier series models are made. 

LSTM is used with multiple features to predict stock prices and then sentimental analysis is performed using news and reddit sentiments. 

GANs are used to predict stock data too where Amazon data is taken from an API as Generator and CNNs are used as discriminator.

Natural Language Processing(NLP) will also be used in this project to analyze the influence of News on stock prices.


Accurately predicting the stock markets is a complex task as there are millions of events and pre-conditions for a particilar stock to move in a particular direction. So we need to be able to capture as many of these pre-conditions as possible. We also need make several important assumptions: 1) markets are not 100% random, 2) history repeats, 3) markets follow people's rational behavior, and 4) the markets are 'perfect'.

### LSTM Networks
<img width="809" alt="Screen Shot 2022-05-15 at 3 58 58 PM" src="https://user-images.githubusercontent.com/61389741/168491581-e450432a-6f7d-4130-bed0-94a01dac2a63.png">

### GAN
<img width="862" alt="Screen Shot 2022-05-15 at 4 02 00 PM" src="https://user-images.githubusercontent.com/61389741/168491661-e45ba9ce-a1e5-481a-86dc-b0887eefdd17.png">

### AMZN Data
<img width="898" alt="Screen Shot 2022-05-15 at 3 54 00 PM" src="https://user-images.githubusercontent.com/61389741/168491684-ee6d8424-3d52-41ed-ad7f-136bc709a533.png">

### Overall Architecture
<img width="851" alt="Screen Shot 2022-05-15 at 3 03 39 PM" src="https://user-images.githubusercontent.com/61389741/168491694-cc1ac9df-d376-49cb-bd70-ce227485a21b.png">

### Results
<img width="664" alt="Screen Shot 2022-05-16 at 4 47 35 AM" src="https://user-images.githubusercontent.com/61389741/168570133-c6c2c12d-6e5f-4a13-90c0-0210017e11db.png">
<img width="618" alt="Screen Shot 2022-05-16 at 4 47 40 AM" src="https://user-images.githubusercontent.com/61389741/168570161-d290e03a-ae11-4b92-a161-9bb88568e551.png">
<img width="789" alt="Screen Shot 2022-05-16 at 4 37 14 AM" src="https://user-images.githubusercontent.com/61389741/168570207-57de3ebb-309e-4910-8223-c879be861f62.png">
<img width="804" alt="Screen Shot 2022-05-16 at 4 38 39 AM" src="https://user-images.githubusercontent.com/61389741/168570231-9e3436b6-0d07-4308-bd86-1054196c17f5.png">
<img width="857" alt="Screen Shot 2022-05-16 at 4 44 39 AM" src="https://user-images.githubusercontent.com/61389741/168570273-922b10fb-f917-4c1a-931b-bf9291cb797f.png">


The Repo contains following files and folder:

* Data- Datasets used in the codes:
    - AMZN.csv
    - CLOSE.csv
    - market
    - stock
    - news
* Model -LSTM model used in file
* Screenshots - important plots
* Requirements.txt- Necessary files, libraries and packages
* Notebooks 1,2,3,4,5,6- Advancement wise Notebooks
* References - Credits to every source I used and referred
 
NOTE: Some New Version Tensorflow functions were not working as expected and hence I have downgraded 'some' files with older version
