#  Binary Text Classification

This project can be used for applications where input data is a string of large text data and output is a binary classification of data. 
An example of the use of the below project could be sentiment classification ofcomments, hate speech detection, etc.

## Dataset Used:  Movie Review Database. Two columns review, sentiment(positive or negative)

Following Algorithms are used fro prediction.

1. Support Vector Machine
Results: 
SVM Accuracy Score ->  88.48336594911937
SVM Precision Score ->  89.45297127115309
SVM Recall Score ->  87.64218237902448

2. Multinomial Naive Bayes
Results:
MNB Accuracy Score ->  85.53816046966732
MNB Precision Score ->  84.90751672569854
MNB Recall Score ->  85.85356148030243

3. Random Forest Classifier
RF Accuracy Score ->  84.45205479452055
RF Precision Score ->  83.96300669027941
RF Recall Score ->  84.64590359055742

4. K-Nearest Neighbors
KNN Accuracy Score ->  76.81996086105674
KNN Precision Score ->  69.46084218811491
KNN Recall Score ->  81.20542903151599



Data used for this project: @InProceedings{maas-EtAl:2011:ACL-HLT2011, author = {Maas, Andrew L. and Daly, Raymond E. and Pham, Peter T. and Huang, Dan and Ng, Andrew Y. and Potts, Christopher}, title = {Learning Word Vectors for Sentiment Analysis}, booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies}, month = {June}, year = {2011}, address = {Portland, Oregon, USA}, publisher = {Association for Computational Linguistics}, pages = {142--150}, url = {http://www.aclweb.org/anthology/P11-1015} }

Reference: https://medium.com/@bedigunjit/simple-guide-to-text-classification-nlp-using-svm-and-naive-bayes-with-python-421db3a72d34
