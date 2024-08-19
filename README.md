# PRODIGY_ML_03
 Classfiaction of cats and dogs using SVM
This project implements a machine learning model to classify images of dogs and cats using Support Vector Machines (SVM). The SVM algorithm is a powerful supervised learning method that is commonly used for classification tasks due to its ability to handle high-dimensional spaces and its effectiveness in binary classification.
**Project Structure**
Dataset: The dataset used consists of labeled images of dogs and cats. Each image is processed and features are extracted to serve as input for the SVM model.
Preprocessing: The images are resized to a consistent dimension and converted to grayscale. Feature extraction techniques such as Histogram of Oriented Gradients (HOG) or pixel intensities are used to represent the images in a feature space suitable for SVM.
Model Training: The SVM classifier is trained on the processed images. A grid search is used to optimize the hyperparameters, such as the kernel type (linear, polynomial, RBF) and regularization parameter (C), to achieve the best classification accuracy.
Evaluation: The model is evaluated using metrics such as accuracy, precision, recall, and F1-score. A confusion matrix is also provided to visualize the performance across the two classes (dogs and cats).
Prediction: Once trained, the model can predict whether a new image is of a dog or a cat. This section includes examples of predictions on unseen images to demonstrate the model's effectiveness.
**Result**
The model achieves a high accuracy in distinguishing between dogs and cats. 
For further Details contact me :beena.hari626623@gmail.com
