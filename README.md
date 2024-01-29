# SMS_Spam_Detector

Overview-
This project involves the development of a machine learning model to accurately classify SMS messages as spam (unsolicited) or ham (legitimate). Utilizing a robust blend of NLP techniques and machine learning, the model offers an effective solution for filtering out unwanted text messages, enhancing user experience in digital communication.

Dataset-
The model is trained on a dataset from the UCI Machine Learning Repository, consisting of pre-labeled SMS messages. This dataset provides a diverse range of real-world text data, crucial for training an effective classifier.

Features-
Preprocessing: Standardization of text data by converting to lowercase and removing special characters, followed by tokenization.

GloVe Embeddings: Implementation of GloVe (Global Vectors for Word Representation) 100-dimensional embeddings to convert text into meaningful numerical vectors.

Support Vector Machine (SVM): Utilization of SVM for binary classification, chosen for its efficiency in high-dimensional spaces.

Enhancements-
Hyperparameter Tuning: Application of GridSearchCV to optimize SVM's 'C' and 'gamma' parameters, ensuring the best model performance.

Heuristic Rules: Integration of heuristic rules for immediate flagging of messages containing sensitive keywords (like 'password', 'bank account').

Sentiment Analysis: Employment of sentiment analysis as an additional layer to assess the tone of messages.

Evaluation-
The model's performance is measured using accuracy, precision, and recall metrics, and its effectiveness is further validated through precision-recall trade-off analysis.

Conclusion
This project showcases the power of combining natural language processing and machine learning to tackle the ever-persistent issue of spam in digital communication. It demonstrates not only technical proficiency in these domains but also a keen understanding of practical application in everyday scenarios.
