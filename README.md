**Project Title: Pneumonia Detection Using CNNs with 96% Accuracy**

**Overview:**
This project aims to detect pneumonia in chest X-ray images through the implementation of a Convolutional Neural Network (CNN) system. CNNs have proven to be effective in image classification tasks, making them suitable for medical image analysis. The project focuses on preprocessing the image data, building a CNN model, training it on labeled datasets, and evaluating its performance.

**Technologies Used:**

OpenCV

TensorFlow

os

**Key Features:**

**Data Preprocessing:**
a) Importing necessary libraries such as OpenCV for image processing.

b) Defining allowed image extensions and removing inconsistent formats.

c) Creating a dataset from image folders using tf.keras.utils.image_dataset_from_directory.

d) Normalizing image data to enhance training efficiency.

**Train-Test-Validation Split:**
a) Dividing the dataset into training, testing, and validation sets for model evaluation.

b) Monitoring model performance on the validation set to prevent overfitting.

**Building the CNN Model:**
a) Creating a sequential model using models.Sequential().

b) Implementing convolutional layers to extract image features.

c) Utilizing ReLU activation for introducing non-linearity.

d) Incorporating max-pooling layers to reduce image size.

e) Adding fully connected layers with ReLU activation for further feature learning.

f) Using a sigmoid activation in the output layer for binary classification.

**Model Compilation and Training:**
a) Compiling the model with the Adam optimizer and binary cross-entropy loss function.

b) Training the model on the training data while monitoring performance on the validation set.

c) Adjusting the number of epochs based on validation results.

**Model Evaluation:**
a) Assessing model performance on unseen testing data.

b) Calculating metrics such as accuracy, precision, and recall.

c) Printing the final evaluation metrics.

**Saving and Loading the Model:**
a) Saving the trained model for future use.

b) Demonstrating model loading and making predictions on new chest X-ray images.

**Contributions:**

Contributions to this project are encouraged, focusing on areas such as:

a) Exploration of more complex architectures and hyperparameter tuning.

b) Incorporation of advanced data augmentation techniques.

c) Addressing potential biases in the training data.

d) Documentation improvements for clarity and usability.
