# Facial-Expression-Recognition
## Project on Facial Expression Recognition with Keras
<span style='color: blue'>Link for Dataset: https://drive.google.com/open?id=1adZCwxr8Th7CfMMGytCTvO_LMicGfneH</span>
This Project is based on kaggle competition on Facial expression recognition. Here is asummarized report on task completed in this project.
## Task 1: Dataset
* Dataset is also from the same competition.
## Task 2: Exploring the Dataset
* Display some images from every expression type in the Emotion FER dataset.
* Check for class imbalance problems in the training data.
## Task 3: Generated Training and Validation Batches
* Generate batches of tensor image data with real-time data augmentation.
* Specify paths to training and validation image directories and generates batches of augmented data.
## Task 4: Created a Convolutional Neural Network (CNN) Model
* Design a convolutional neural network with 4 convolution layers and 2 fully connected layers to predict 7 types of facial expressions.
* Use Adam as the optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric.
!model.png
## Task 5: Trained and Evaluated Model
* Train the CNN by invoking the model.fit() method.
* Use ModelCheckpoint() to save the weights associated with the higher validation accuracy.
* Observe live training loss and accuracy plots in Jupyter Notebook for Keras.
## Task 6: Saved and Serialized Model as JSON String
* Sometimes, you are only interested in the architecture of the model, and you don't need to save the weight values or the optimizer.
* Use to_json(), which uses a JSON string, to store the model architecture.
## Task 7: Created a Flask App to Serve Predictions
* Use open-source code from "Video Streaming with Flask Example" to create a flask app to serve the model's prediction images directly to a web interface.
## Task 8: Created a Class to Output Model Predictions
* Create a FacialExpressionModel class to load the model from the JSON file, load the trained weights into the model, and predict facial expressions.
## Task 9: Designed an HTML Template for the Flask App
* Design a basic template in HTML to create the layout for the Flask app.
## Task 10: Used Model to Recognize Facial Expressions in Videos
* Run the main.py script to create the Flask app and serve the model's predictions to a web interface.
* Apply the model to saved videos on disk.

