# CNN-Model-Hand-Digit-Recognition
Recognising handwritten digits using CNN model


In this project you will discover how to develop a deep learning model to achieve high performance on the handwritten digit recognition task using the MNIST dataset and build a GUI App based on Tkinter where, you can draw the digits (single as well as multiple) and recognize it straight away by draw a bounding box surrounding each digit.

It is easy for the human to perform a task accurately by practicing it repeatedly and memorizing it for the next time. Human brain can process and analyse images easily. Also, recognize the different elements present in the images. The challenge in handwritten digit recognition is mainly caused by the writing style variations of every single individual. So, it is not easy for the machine to recognize the handwritten digits accurately like the humans do. Hence, robust feature extraction is very important to improve the performance of machines. Deep learning is a class of machine learning that uses multiple layers to progressively extract higher level features from the input. Therefore, deep learning reduces the task of developing new feature extractor for every problem. This characteristic of Deep Learning is a major step ahead of traditional Machine Learning. Most modern deep learning models are based on artificial neural networks, specifically, Convolutional Neural Networks (CNN) that we will use in this project.

This project involves developing a Convolutional Neural Network (CNN) model to recognize handwritten digits using the MNIST dataset. The model is designed to classify digits from 0 to 9 with high accuracy.

Key Features:

Dataset: The project utilizes the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits.

Model Architecture: A CNN model is implemented with multiple convolutional layers, max pooling, and fully connected layers to achieve robust feature extraction and classification.

Accuracy: The model achieves a high accuracy of 99.28% on the test set, demonstrating its effectiveness in recognizing handwritten digits.

GUI Application: The trained model is integrated into a Tkinter GUI application, allowing users to draw digits and receive real-time predictions.

Technical Details:

Model Training: The model is trained using the Adam optimizer with categorical cross-entropy loss.

Data Preprocessing: Images are preprocessed by resizing to 28x28 pixels, converting to grayscale, and normalizing pixel values between 0 and 1.

GUI Functionality: The application captures user-drawn digits from the canvas, processes them, and displays the predicted digit along with its confidence level.

Code Structure:

Model Definition: The CNN model is defined in a separate function for clarity and reusability.

Training and Evaluation: Scripts for training the model and evaluating its performance on the test set are included.

GUI Application: The Tkinter application is structured to handle user input, process images, and display predictions.
