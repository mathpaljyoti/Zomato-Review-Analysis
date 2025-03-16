# Zomato-Review-Analysis
Sentiment Analysis on Zomato Reviews using Logistic Regression

This project aims to analyze Zomato reviews to determine whether the content on a user's feed is positive or negative. By leveraging Natural Language Processing (NLP) and Machine Learning techniques, the model classifies reviews as positive or negative based on the sentiment expressed.

## Features 🌟
- Sentiment Analysis of Zomato reviews.
- Uses NLP techniques to preprocess and clean textual data.
- Trained on a large dataset to ensure high accuracy.
- Model accuracy: **97.13%**
- Confusion Matrix and Classification Report included for performance evaluation.

## Dataset 📊
The dataset used for this project was obtained from **Kaggle**. You can access the dataset using the link below:
(https://www.kaggle.com/datasets/prepinstaprime/tomato-reviews)

The dataset contains a large number of reviews along with their sentiments (positive/negative), which were used to train and evaluate the model.

## Technologies Used 🛠️
- **Python**: Programming Language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Scikit-learn**: Machine Learning library
- **NLTK**: Natural Language Processing
- **Google Colab**: Model training and testing
- **Git and GitHub**: Version control and code hosting

## Model and Techniques 🧠
- Text Preprocessing:
  - Tokenization
  - Removing special characters
  - Lowercasing
  - Stopwords removal
- Feature Extraction:
  - TF-IDF (Term Frequency-Inverse Document Frequency)
- Model:
  - Logistic Regression Classifier
- Evaluation:
  - Accuracy: **97.13%**
  - Precision, Recall, F1-Score
  - Confusion Matrix

## How to Run the Project 🚀
1. Clone the repository:
   ```
   git clone https://github.com/mathpaljyoti/Zomato-Review-Analysis.git
   ```
2. Navigate to the project directory:
   ```
   cd Zomato-Review-Analysis
   ```
3. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script:
   ```
   jupyter notebook ZomatoReviewAnalysis.ipynb
   ```
5. Follow the instructions in the notebook to train and test the model.

## Results 📈
The model achieved an accuracy of **97.13%** on the test data. It successfully distinguishes between positive and negative reviews with high precision and recall. 

Confusion Matrix:
```
[[2216  201]
 [  93 7720]]
```

## Contributions 🤝
Feel free to fork the project, make changes, and submit pull requests. Contributions are always welcome!
