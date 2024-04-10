FaceAI is an advanced artificial intelligence-based system focused on analysing facial images to detect and diagnose a variety of facial skin conditions and diseases. The aim is to provide a fast and accurate method of diagnosis, assisting dermatologists and improving the availability of quality dermatological care for facial skin problems.

Programming language: Python
Libraries: TensorFlow, Keras, NumPy, Matplotlib, scikit-learn

Features: Fast and accurate processing of facial skin images to detect potential diseases. Use of advanced artificial intelligence algorithms to classify identified skin conditions. Simple and user-friendly user interface, designed for ease of use by medical professionals. AI models based on the latest research, offering high accuracy in the diagnosis of skin conditions.

Input: Facial image dataset with labels

Output: Model accuracy assessment, confusion matrix, classification report, accuracy and loss visualisations and sample images with predictions

Description of script operation:

Loading the model: The script starts by loading the trained weights into the CNN model that performed best on the validation data.

Model evaluation: The model is evaluated on a test dataset. Evaluation results, including accuracy and loss, are displayed on the console.
Predictions: Based on the model, predictions are made for the images in the test set. The script assigns the most likely diagnosis class for each image.

True labels: Preparation of a vector of true labels using data from the test generator.

Visualisation of training history: Presentation of accuracy and loss graphs for training and validation data to assess the progress of model learning over time.

Confusion matrix: Generation and display of a confusion matrix, allowing a graphical representation of classification results and identification of classes that are frequently confused by the model.

Classification report: Create a classification report with precision, completeness (recall) and F1 score for each class of diagnoses.
Sample predictions: Displaying examples of test images with their true and predicted labels, giving insight into the effectiveness of the model.
