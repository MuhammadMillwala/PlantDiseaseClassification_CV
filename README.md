# Plant Disease Classification

**METHODS:**
The method used for this project is deep learning classification using Convolutional Neural Networks (CNNs). CNNs have been widely used in image classification tasks and are particularly effective for tasks involving spatially correlated data. The primary reason for using CNNs is their ability to automatically learn hierarchical features from raw images. This process of learning features enables the model to generalize well and improves the classification accuracy. 

The following are the steps we followed in this project:

1. **Data Collection:** We used the Plant Pathology Apple Tree Disease Dataset from Kaggle. This dataset contains around 3800 train and test images combined, with each image containing either a healthy leaf or a leaf with diseases such as scab, rust, or more than one disease.

2.** Data Preprocessing:** We resized all the images to 224 x 224 pixels and converted them to grayscale. We also normalized the pixel values to be between 0 and 1.

3. **Data Augmentation**: We applied data augmentation techniques such as rotation, horizontal and vertical flip, and zooming to generate more data and improve the model's robustness.

4. **Model Architecture**: We used a custom CNN architecture with five convolutional layers  followed by five max-pooling layers, two fully connected layers, and a softmax output layer. We used Adam optimizer with a learning rate of 0.0001 and ran 30 epochs.

5. **Model Evaluation**: We evaluated our model on the test dataset and achieved an accuracy of over 90%. We also plotted the confusion matrix to visualize the model's performance on different classes.

**CONCLUSION:**
In this project, we have proposed an automatic detection and diagnosis algorithm using deep learning classification to detect diseases in apple tree leaves. We have successfully developed and trained a custom CNN model that can classify whether a leaf is healthy or has diseases such as scab, rust, or more than one disease. Our model has an accuracy of over 90% on the test dataset, and we have demonstrated its effectiveness in detecting diseases in apple tree leaves. We believe our model can be used in apple tree cultivation smart systems to prevent crop loss and minimize the use of pesticides. Furthermore, our project can be 
extended to detect diseases in other plant species as well.
