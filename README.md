# Spam-Ham Classification

This project aims to classify the emails into two categories - spam and ham. The project is divided into two versions.

### Version 1:
In this version, the average Word2Vec technique is used to convert the text into numerical vectors. The KNeighborsClassifier model is used to classify the emails into spam or ham. The accuracy achieved by this version is 84%.

### Version 2:
In the second version, the TfidfVectorizer is used to convert the text into numerical vectors. The LogisticRegression model is used to classify the emails into spam or ham. The accuracy achieved by this version is 98%.

The project uses Python and the following libraries: NumPy, Pandas, Scikit-learn, Gensim, and NLTK. The dataset used for this project is the SMS Spam Collection, which contains a collection of SMS messages tagged as spam or ham.

To run the project, download the source code and ensure that all the necessary libraries are installed. The code is divided into two versions, and each version is located in a separate folder. Run the respective Python files to execute the code for the corresponding version.

Future improvements to the project could include exploring different models, such as Naive Bayes or Support Vector Machines, and experimenting with different preprocessing techniques to improve the accuracy further.
