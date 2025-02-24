# Credit-Card-Fraud-Detection-System
This project leverages machine learning models to detect fraudulent credit card transactions. The goal is to improve fraud detection accuracy and reduce false positives, ultimately helping institutions save resources and maintain customer trust in their systems.
# Credit Card Fraud Detection Using Machine Learning

## Overview
In today's cashless world, digital payments are at the heart of the global economy. However, this convenience also brings security risks, with credit card fraud being a major concern. In 2022, payment fraud losses amounted to over $32 billion globally. This project applies machine learning to improve fraud detection systems, aiming to reduce false positives and improve overall prediction accuracy.

## Motivation
My passion for machine learning, coupled with the importance of customer trust in financial systems, motivated me to explore this project. As digital transactions increase, fraud detection systems must evolve to be more accurate, ensuring that financial institutions can better protect their customers and resources. This project also aligns with my goal of leveraging ML to help businesses reduce inefficiencies and maintain customer confidence.

## Dataset
The dataset used for this project consists of credit card transactions from European cardholders in September 2013. It contains both legitimate and fraudulent transactions, with an imbalanced class distribution, which poses challenges for traditional fraud detection methods.

## Machine Learning Models Tested
- **Logistic Regression**
- **Shallow Neural Network** (Implemented using TensorFlow/Keras)
- **Random Forest Classifier**
- **Linear Support Vector Machine (SVM)**
- **Gradient Boosting Classifier**

## Development Environment
- **Google Colab**: Used for writing and executing Python code.

## Libraries and Tools
- **Pandas**: For data preprocessing and manipulation.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For implementing machine learning models like Logistic Regression, Random Forest, and Linear SVM.
- **TensorFlow/Keras**: For building and training the Shallow Neural Network.

## Methodology
- **Data Preparation**: Shuffling and scaling the features to ensure consistent training.
- **Model Training**: Models were trained on the imbalanced dataset using various algorithms.
- **Model Evaluation**: Evaluated models based on metrics like accuracy, precision, recall, and F1-score.
- **Data Balancing**: Applied techniques to balance the dataset for better model performance.
- **Model Selection**: The best-performing model was chosen based on the highest F1-score.

## How to Download and Test on Your Own

### Prerequisites
To run this project on your local machine, you need to have the following tools installed:
- **Python** 3.x
- **Google Colab** (for running the code in the cloud without local installation)

### Step
1. **Clone the repository**:
   You can clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/CarineMunezero/Credit-Card-Fraud-Detection-System.git

## Conclusion
This project successfully tested different machine learning models to detect fraudulent credit card transactions. The model with the highest F1-score was selected for future use, showcasing the potential of machine learning in improving fraud detection systems. With these advanced techniques, financial institutions can better protect their customers and reduce unnecessary resource allocation on false fraud flags.

## Future Work
- Implementing the selected model in a real-world environment for continuous learning and adaptation.
- Exploring additional features for further improving detection accuracy.
