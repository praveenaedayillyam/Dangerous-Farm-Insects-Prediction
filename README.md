## Dangerous Farm Insects Prediction
- This project is designed to predict dangerous farm insects using image classification with a Convolutional Neural Network (CNN) model based on ResNet50. 
- It classifies insect images into 15 different classes, helping farmers quickly identify harmful pests and take preventive action.
-  CNN is used to automatically extract important features from images, and ResNet50, a deep 50-layer residual network, improves accuracy by using skip connections to avoid vanishing gradients.
-   he model was fine-tuned on a custom insect dataset. 
- A simple and user-friendly interface was created using Gradio, allowing users to upload insect images and instantly get predictions about the insect's class.

 <br><br>
- **training.ipynb:** Contains the code for training the CNN (ResNet50) model on the insect image dataset.
- **prediction.ipynb**: Used for loading the trained model and making predictions on new insect images.
- **insects_model.keras**: This file stores the trained CNN (ResNet50) model in Keras format, including its architecture and learned weights, used for making predictions.
- **class_names.npy**: A NumPy file that stores the list of 15 insect class names used for labeling predictions.

