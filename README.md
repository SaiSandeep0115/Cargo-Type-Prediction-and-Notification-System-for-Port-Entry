# Cargo Type Prediction and Notification System for Port Entry

## Languages:
- **Python**

## Important Libraries:
- **Pandas**
- **NumPy**
- **TensorFlow/Keras**
- **NLTK**
- **Langchain**

## Technologies:
- **Deep Learning**
- **Natural Language Processing (NLP))**
- **Large Language Models (LLMs)**
- **Data Analysis**

### Abstract: 
This project focuses on developing a system for predicting cargo types entering ports and notifying relevant authorities. Utilizing a Convolutional Neural Network (CNN) for image classification and NLP techniques for communication, the system aims to enhance operational efficiency and security at port entries.

### Dataset:
Deep Learning Dataset: Sourced from Kaggle, this dataset consists of images for training the CNN model to classify various cargo types.

### Methodology:
Data Preprocessing: Images were cleaned and augmented to improve model performance.
Model Development: A CNN was trained to classify cargo types based on images, providing real-time predictions.
Notification System: Developed using NLP techniques, specifically with NLTK and Langchain, to process incoming vessel messages.

### Models: 
The CNN model was implemented for cargo type classification, leveraging deep learning techniques to achieve high accuracy in identifying different cargo types from images. After training, the model demonstrated robust performance in predicting cargo classifications.
The notification system utilizes NLP to handle messages from vessels. When a vessel sends a message containing the ship ID and cargo type, the system checks the ship ID against a database. If the predicted cargo type from the image matches the cargo type mentioned in the vessel's message, an access granted notification is generated and sent.

### Results and Conclusion: 
The implemented system significantly enhances the process of cargo type verification, leading to improved operational efficiency and streamlined port entry protocols. The integration of CNN for image classification and NLP for communication ensures a robust solution for modern maritime logistics.

### Disclaimer: 
The model must be trained with more epochs, as the current model is trained with only 1 epoch considering the computational limitation. However, the model will be further trained. Cargo Type Prediction and Notification System is designed for demonstration purposes and may require further development and testing to ensure reliability and effectiveness in real-world scenarios. The accuracy of cargo type predictions and the efficiency of the notification system depend on various factors, including data quality and system integration. The findings from this project may not accurately reflect real-world scenarios. Further validation and refinement are necessary to ensure reliability and effectiveness in practical applications.
