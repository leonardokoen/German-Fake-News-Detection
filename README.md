# German-Fake-News-Detection
German Fake News Detection using hybrid(CNN- LSTM) model

Code\01Libraries Installation:
Contains code in jupyter notebook format that it downloads the necessary libraries.

Code\02Preprocess:
Contains 2 files in jupyter notebook format. Each file preprocesses the data stated by its name.  

Code\03Model:
Contains code in jupyter notebook format, that creates, trains and evaluates a model.

If you want to use the already preprocessed data you can change the file paths:
df_news = pd.read_csv('..\\..\\Datasets\\Preprocessed\\df_preprocessed_news', index_col=0)
df_germanFakeNC = pd.read_csv('..\\..\\Datasets\\Preprocessed\\df_preprocessed_GermanFakeNC', index_col=0)

Code\03Model\Weights:
Contains .txt files with already trained weights and a folder that contains weights that can be loaded to our model


Code\04CalculateTime:
Contains code that compute time needed for training and testing.

Datasets: 
It contains the datasets used in our program for training and testing
GermanFakeNC (https://data.mendeley.com/datasets/p4c49m3pvr/3)
News (https://www.kaggle.com/code/kerneler/starter-fake-news-dataset-german-9cc110a2-9/data)

Datasets\Preprocessed: 
Contains our preprocessed datasets.
