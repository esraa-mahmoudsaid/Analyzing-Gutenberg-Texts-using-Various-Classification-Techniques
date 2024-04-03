## **Text Classification System for Ancient History Books**

### Introduction:
This repository contains the implementation of a text classification system designed to categorize ancient history books based on their content. The system utilizes various natural language processing (NLP) techniques and machine learning algorithms to accurately classify the books into relevant categories. The goal of this project is to provide a valuable resource for researchers, historians, and students interested in the ancient civilizations of Egypt, Carthage, Assyria, Chaldea, Syria, Babylonia, and Persia.

---

### Dataset:
The dataset consists of five Gutenberg books focusing on ancient history and civilizations. Each book is labeled based on its content and author. The books included in the dataset are:
1. "The Ancient History of the Egyptians, Carthaginians, Assyrians"
2. "History of Egypt, Chaldea, Syria, Babylonia, and Assyria"
3. "History of Egypt, Chaldea, Syria, Babylonia, and Assyria in the Light of Recent"
4. "Ancient Egyptian, Assyrian, and Persian costumes and decorations"
5. "Ancient Egypt" by Arthur Gilman

---

### Feature Engineering:
Text transformation techniques such as Bag-of-Words (BOW), TF-IDF, and N-grams are employed to represent the textual data. These transformations help in quantifying the importance of words within the documents and preserving the meaning of words and sentences.

---

### Modeling and Evaluation:
Several machine learning models including SVM, Random Forest, Naïve Bayes, k-Nearest Neighbor, XG-Boost, and Stochastic Gradient Descent (SGD) are trained and tested using different text transformations. The performance of each model is evaluated based on accuracy scores. The champion model, identified as SGD based on TF-IDF, achieves the highest accuracy of 94%.

---

### System Workflow:
The system workflow involves data preparation, feature engineering, model training, and evaluation. Cross-validation techniques are employed to assess the model's performance on unseen data and to avoid overfitting.

---

### Error Analysis:
An error analysis is conducted to identify misclassifications made by the champion model. It is observed that misclassifications occur primarily due to the presence of common words between books belonging to different categories. Additionally, the model's reliance on TF-IDF for feature representation may lead to misclassifications when certain words have high TF-IDF values across different categories.

---

### Conclusion:
The text classification system presented in this project demonstrates the effectiveness of NLP techniques and machine learning algorithms in categorizing ancient history books. By accurately classifying books based on their content, the system provides a valuable resource for researchers, historians, and students interested in exploring the ancient civilizations of the Middle East.

