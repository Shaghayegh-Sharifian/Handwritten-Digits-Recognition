# Handwritten-Digits-Recognition
In this file, I used multiple methods for English Handwritten-Digits-Classification which is a data set in the Sklearn library, and used a convolutional network for Persian Digits.<br>

For English digits, I used classification models such as SVM, KNN Adaboost, and RandomForest.<br>
In these classifications, I tried to use adequately simple concepts of vectors and statistics in Python.<br>
Overall, after fitting the classifiers to the dataset, the classifiers were able to gain f1 scores stated below:<br>
<br>
**SVM Classifier: 96%**<br>
**KNN Classifier: 96%**<br>
**Adaboost Classifier: 94%**<br>
**RandomForest Classifier: 90%**<br>
<br>
For Persian digits, as mentioned before I used a multiple-layer convolutional network from the Hoda data set images that are flattened and become a vector in the function we have written before, load_hoda.<br>
In this call, the length and width of the images are set to 28, so the output of this function is 784 vectors.<br>
Overall, after Defining model architecture and fitting the model on training data, the model was able to predict the test data as below:<br>
<br>
**Convolutional network final test set loss: 0.071973**<br>
**Convolutional network final test set accuracy: 0.985000**<br>
<br>
## Conclusion
Accordingly, the convolutional network is the best model, which was able to explain **98.5% of its final test set accuracy**, with the loss of 7%.<br>
