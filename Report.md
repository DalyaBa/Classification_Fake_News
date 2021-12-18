![1_m9d7IXkza5VEYjsJU9FL2w](https://user-images.githubusercontent.com/74211933/146641248-2238f68b-b2f8-4140-b5a8-78f0c7dd9a30.jpeg)


<h1> Abstract: </h1>
Fake news has become one of the most serious problems of our generation. It has a huge impact on our online and offline conversations. Fake news still poses a clear and timely threat to western democracy and social stability. Social media is a huge pool of content and is the most watched part of all the content available to users. Politicians, television stations, newspaper websites, and even the public can post this information. The credibility of these posts is a serious problem in today's world, as many companies are taking steps to educate the public about the dangers of spreading false information. Need to be verified. Manual classification of messages is tedious, time consuming, and biased, so it is not possible to clearly determine the level of reliability of messages posted online.

<h1> Design: </h1>
The progress of this project will be as follows. First gathering data from Kaggle, then exploratory Data
Analysis (EDA) will be performed on the data we gathered. Finally, preparing data to be used in different
Classification models and some NLP was applyed. In this project, we analyze the relationship between the target variable “Label” and the
features “title, text” after cleaning feature engneering.

<h1> Data: </h1>
The dataset used in this project was extracted from american news the news was during election days 2016. There were 2000 news with 12 features initially.
The dataset becomes almost 1668 records with 2 features after we have done some cleaning and feature engineering
on the original dataset.

<h1> Algorithms: </h1>
<h2> ● Feature Engineering: </h2>
1. to use text mining techniques, we put all of text type columns in one column for ease of processing
2. TFIDFVectorizer on features to highlight words that are more interesting
3. doing clustring on real and fake news 
<h2> ● Models:</h2>
We have explored many classification machine learning models
in order to choose the best for our case. The models are Kneighbors Classification KNN, Random Forest RF,
Adaboost Classification with DecisionTreeClassifier. The data was splitted into 60 percent
training, 20 percent validating, and 20 percent testing. The model we selected was Adaboost Classification
because it shows the best score between all models.

<h3> Best Model: Adaboost Classification: </h3>
   - Adaboost Classification Testing Acuracy Score: 0.9850
<h1> Tools: </h1>
<h3> ● Technologies: </h3> Jupyter Notebook, google colab, spyder, Python.
<h3> ● Libraries: </h3> Pandas, NumPy, Matplotlib, Seaborn,Sklearn, NLTK, KMeans, 

<h1> Communication: </h1>

<img width="533" alt="Screen Shot 2021-12-15 at 2 33 31 PM" src="https://user-images.githubusercontent.com/74211933/146641205-e32ba8e2-8560-4254-9a69-db22ef6203b8.png">
<img width="375" alt="Screen Shot 2021-12-15 at 1 57 35 PM" src="https://user-images.githubusercontent.com/74211933/146641213-a51e94f0-ce5a-4d14-832c-0e0a073bc726.png">
<img width="407" alt="Screen Shot 2021-12-15 at 3 40 59 PM" src="https://user-images.githubusercontent.com/74211933/146641217-53e15ec7-7d40-4db5-9749-9d41e6048c2a.png">
<img width="533" src="https://user-images.githubusercontent.com/74211933/146641412-0e9e9f0c-209a-4678-845d-8605000af4c8.png">
<img width="533" src="https://user-images.githubusercontent.com/74211933/146641418-6ceb6790-5b40-4f44-84f7-d56a0389be57.png">






