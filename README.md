# Machine_learning_StackOverflow_TAG_Predictor

Project Overview In Stack Overflow’s current system, it allows users to manually assign between one and five tags to a posting. Users are encouraged to use existing tags but they are also allowed to create new ones, so the set of possible tags is infinite. Manual tagging can be challenging for users because it is likely that different users use different orthographic versions of tags that mean the same thing such as “php5” and “php-5”. For these reasons, it is desirable to have a system that is able to either automatically tag questions or to suggest relevant tags to a user based on the question content.

Problem Statement Suggest the tags based on the content that was there in the question posted on Stackoverflow. The tasks involved are the following : 1. Download and loading the stack overflow data. 2. Analysis of Tags(Do statistical analysis of the data). 3. Cleaning and preprocessing of questions. 4. Designing machine learning model by converting tags to multilabel problem. 5. Split the data into train and test dataset. 6. Featurizing the data. 7. Run different machine learning model. The final model is expected to predict as many tags as possible with high precision and recall.

Need to install below API - 

1. Install WordCloud to represent tag usage -  
pip install WordCloud
2. Insall mulitilearn api -  
pip install scikit-multilearn
3. Install stopwords for data cleaning - 
python -m nltk.downloader stopwords
4. Install pretty table - 
sudo pip3 install PTable
