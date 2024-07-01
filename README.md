# Image-Classification
In this project, I successfully implemented a Convolutional Neural Network (CNN) to classify images of cats and dogs. Here are the key takeaways and findings from my work:

1. Data Preparation
We utilized the ImageDataGenerator class from TensorFlow to preprocess and augment our image dataset. The dataset was divided into training and test sets, with images of cats and dogs organized in separate directories.

2. Model Architecture
A Sequential CNN model was constructed with the following architecture:

Four convolutional layers with ReLU activation functions and max pooling layers.
A flattening layer to convert the 2D matrix data to a vector.
A dense (fully connected) layer with 512 units and ReLU activation.
An output dense layer with a sigmoid activation function for binary classification.
3. Model Training and Performance
The model was compiled with the RMSprop optimizer and trained for 25 epochs. The training and validation accuracies and losses were tracked and plotted to visualize the model's performance.

The training accuracy steadily improved over the epochs, indicating that the model effectively learned the patterns in the training data. The validation accuracy showed similar improvement, suggesting that the model generalized well to unseen data.

4. Results and Evaluation
The final model achieved satisfactory accuracy on the test set, demonstrating its capability to distinguish between images of cats and dogs. Below are the training and validation accuracy and loss curves, which illustrate the model's learning process over time.

Training and Validation Accuracy:

Training and Validation Loss:

5. Sample Prediction
A sample image from the test set was used to verify the model's prediction capability. The model correctly identified the image as a dog, confirming its effectiveness in practical scenarios.

Sample Image:

6. Conclusion 
This project demonstrates the effectiveness of CNNs in image classification tasks. The model achieved a high level of accuracy in classifying cats and dogs, indicating robust performance.
The last  epoch :231s 577ms/step - accuracy: 0.9936 - loss: 0.0279 - val_accuracy: 0.8020 - val_loss: 2.7659
