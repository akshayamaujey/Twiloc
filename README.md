Twi-Loc: Location Based Analysis Using Machine Learning
This repository contains the research paper "Twi-Loc: Location Based Analysis Using Machine Learning," presented in the International Journal of Creative Research Thoughts (IJCRT), Volume 12, Issue 4, April 2024.

Abstract
In the era of digital communication, social media platforms like Twitter generate vast amounts of data that offer invaluable insights into human behavior and trends.
Among these insights, the geographical location of users is critical for applications ranging from targeted advertising to emergency response coordination. 
This project presents Twi-Loc, a state-of-the-art system for predicting the geolocation of Twitter users based on their tweets, utilizing advanced machine learning techniques.

Authors
Tanmay Kapale
Akshaya Maujey
Shubham Mohod
Vedant Karande
Sakshi Raghorte
Institution
Priyadarshani College of Engineering, Nagpur, India

Keywords
Twitter
Geolocation
Machine Learning
Deep Learning
Natural Language Processing
Data Analytics
Social Media Intelligence
Introduction
The study harnesses the potential of Twitter data to accurately predict a user's location based on their tweets. The challenges include the small fraction of geotagged tweets, informal and context-dependent textual content, and the dynamic nature of social media data. Twi-Loc addresses these with advanced machine learning algorithms, integrating linguistic patterns, user network connections, and temporal activity patterns into a cohesive predictive model.

Literature Review
Prior research has leveraged various machine learning techniques for geolocation prediction, including probabilistic models, decision trees, and neural networks. Recent studies have explored deep learning techniques, yet gaps remain in effectively integrating these methods with comprehensive feature extraction from both tweet content and metadata.

Proposed Method
The methodology involves:

Data Collection: 
Gathering tweets using the Twitter API, focusing on tweets with location tags or explicit mentions of locations.

Data Preprocessing:
Cleaning text, removing stop words, and tokenizing tweets using TF-IDF.

Feature Extraction:
Utilizing CNNs for image processing and various NLP techniques for text data.

Algorithm:
A CNN architecture designed to capture textual patterns indicative of geographical locations.

Training Process: 
Splitting data into training, validation, and testing sets, using cross-validation, and employing the Adam optimizer.

Results
The CNN model demonstrated significant capability in predicting tweet geolocation with metrics including 85% accuracy, 82% precision, 79% recall, and 80.5% F1-score.

Conclusion
Twi-Loc represents a significant advancement in geolocation prediction, showing notable gains over current methods. Future research will focus on augmenting model accuracy by integrating a wider range of data sources and exploring real-time analytics.

References
Refer to the paper for a comprehensive list of references.

Acknowledgements
We acknowledge contributions from peers who provided insights or data, financial support from institutions, and software or tool providers.

Usage
This repository includes the full research paper in PDF format. To read the paper, download the PDF file and open it with any PDF viewer.

Contact
For any inquiries or further information, please contact [akshayamaujey@.com].
