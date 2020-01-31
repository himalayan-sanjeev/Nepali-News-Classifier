# Nepali-News-Classifier
Nepali News Classifier is an application that can classify the unlabelled or unclassified  news/text document into predefined target categories. 
Following steps were followed in making this project:

 1. First Nepali News Datasets were prepared by extracting News articles from various Nepali News Portals usingn BeautifulSoup library of Python  
 2. 12 Classes of News were predefined (Sports, Health, World, Politics etc.) and news extraction was done in each category for train-test purpose
 3. Scikit-learn library was used for training and model building, training news datasets were trained with  different supervised learning algorithms available in scikitlearn (svm,logistic regression, naive bayes etc)  
 4. Model Performances were evaluated with test datasets (82% accuracy was the best)
 5.Best Model were used in the final application (GUI: tkinter and Web: Flask framework)
