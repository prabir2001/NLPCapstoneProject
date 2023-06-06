# NLPCapstoneProject




Overall activities for Capstone project:
1.	Defining the problem
2.	Defining the data requirement
3.	Defining the dimensions to be captured
4.	Notebook 1: Used beautiful to extract the data with name of authors
5.	Data pre-processing: Nan removal, text cleaning
6.	Data splitting in train-test
7.	Working on the train data by further splitting in train and validation data
8.	Domain classification:
  Developing model for domain classification with multiple variation on train-valid data
  
      i.	Naïve based
  
      ii.	1D – 5 variations
  
      iii.	Pretrained_Token_Embed(USE)_Conv1D
  
      iv.	Custom_Char_Embed_Conv1D
  
       v.	Hybrid_Char_Token_Embed_BiLSTM
  
9.	Generating H5 file for the best model
10.	MBTI
a.	Developed algorithm for dataset available on MBTI dataset available from Kaggle
b.	Generating h5 file for the best model
11.	Extracting other features for all articles
a.	Readability score: through textstat for flesch_reading_ease
b.	Difficult word %: through textstat for all two syllable words
c.	Sentimental analysis: through textblob by calculating polarity
d.	Subjectivity: through textblob by calculating Subjectivity
e.	Other dimensions: through different libraries
12.	Combining all the data and predicted features for new articles
a.	All the features are derived for each of the articles.
b.	Master data created for all the articles and authors
13.	Recommendation
a.	From the features of the new articles, recommended top 5 authors 
