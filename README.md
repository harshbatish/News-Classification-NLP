
---

# News Classification based on text:

---

This project aims to __classify news into 23 classes__ based on the text of headlines and their short descriptions using differnt machine learning algorithms.

Number of samples taken into consideration while making this project is more than __250 thousand__, which is whole as raw data. 


---

### Data dictionary:

1. __link__: This is the URL of the particular sample of news.
2. __headline__: This represents the text of the headline of the news.
3. __short_description__: This represents short descriptions of the particular sample of news.
4. __authors__: This column shows the names and qualification of the authors in the dataset.
5. __date__: This represents the date on which the news was published.

---

### Data Files:

1. __news.json__: Main data file extracted from kaggle (raw)
2. __finaldata.csv__: Proccessed data __including__ short_description column
3. __file_name.csv__: Proccessed data __excluding__ short_description column

---

For this project, I made 4 different jupyter notebooks which are described as follows:

### Structure of Project:

1. __EDAfile.ipynb__ : This file shows all the cleaning of the data and pre-processing of text columns using NLP techniques. Feature engineering is also done to know more about the data and its features.

2. __Randomforest.ipynb__ : This file contains RANDOM FOREST algorithm being applied to pre-processed data. Data is imported semi-procced from EDAfile.ipynb and then tokenizing is done in this file.

3. __XGBoost.ipynb__ : This file conatins XGBOOST algorithm being applied to pre-processed data. Data is imported semi-procced from EDAfile.ipynb and then tokenizing is done in this file.

4. __NN.ipynb__ : This file contains various types of neural networks being deployed on the pre-processed data. Data is imported semi-procced from EDAfile.ipynb and then tokenizing is done in this file.

---

### Environments:

1. For the ___EDA.ipynb___ file jupyter notebook should be the suitable environment. However, if you have a small RAM in your device, your session may crash when you preprocessing of the data.

2. For other .ipynb files Google Colaboratory is the right environment to run all the algorithms. ___Google Colab Pro___ is recommended otherwise session can crash.

---

### Future Prospects:

1. Based on the text of __headline__ and __short_description__, the ___writing styles___ of differnt authors can be figured out.

2. Some more analysis can be done on the most popular words on different classes of news.

3. In terms of modelling, more complex algorithms and deep learning models can be used to improve the accuracy of the model.

4. For tokenizing the text, I used ___TF-IDF___, but there are more advanced libraries which can be implemented for tokenizing, which will definately improve the evaluation metrics of the model.


---