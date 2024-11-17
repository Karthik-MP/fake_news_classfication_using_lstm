# Fake News Classification Using LSTM

This project implements a Fake News Detection system using a Long Short-Term Memory (LSTM) model, a type of Recurrent Neural Network (RNN), to classify news articles as either **real** or **fake**. The dataset used consists of over 44,000 news articles, combining both real and fake news. The goal of the project is to accurately predict the authenticity of news articles, which can help prevent the spread of misinformation.

## Dataset

The dataset consists of two CSV files:
- `True.csv`: Contains over 21,417 real news articles scraped from Reuters.com.
- `Fake.csv`: Contains over 23,481 fake news articles collected from unreliable sources flagged by fact-checking organizations like PolitiFact and Wikipedia.

Each article in the dataset includes the following attributes:
- **id**: Unique identifier for the article
- **title**: The title of the article
- **author**: The author of the article
- **text**: The content of the article
- **type**: The type of the article (real or fake)
- **date**: The publication date of the article

The dataset covers a wide range of topics, with a focus on politics and world news, and was mainly collected from articles published between 2016 and 2017.

## Problem Statement

With the increasing spread of misinformation, detecting fake news has become an important challenge. Fake news often aims to manipulate public opinion or generate revenue through advertisements. The goal of this project is to create an automated system that can classify news articles as real or fake using machine learning techniques. This system can help media outlets, journalists, and social media platforms control the spread of fake news.

## Objective

The main objective of this project is to build a machine learning model to classify news articles as real or fake using a **Long Short-Term Memory (LSTM)** network. The project leverages NLP libraries like **SpaCy** and **NLTK**, along with **TensorFlow**, **pandas**, and various visualization libraries (e.g., **Matplotlib**, **Seaborn**, **WordCloud**) for data preprocessing and model evaluation.

### Key Steps:
1. **Preprocessing**: Clean and preprocess the dataset, including removing stop words, punctuation, and irrelevant characters.
2. **Feature Extraction**: Convert text data into numerical features using techniques like tokenization and word embeddings.
3. **Model Building**: Train an LSTM model to classify news articles as real or fake.
4. **Evaluation**: Test the model and evaluate its performance using metrics like accuracy, precision, recall, and F1-score.

## Libraries and Tools Used

- **SpaCy**: For advanced Natural Language Processing (NLP).
- **NLTK**: For text processing and stopword removal.
- **TensorFlow**: For building the LSTM model.
- **pandas**: For data manipulation and processing.
- **Seaborn, Matplotlib**: For data visualization.
- **WordCloud**: For generating word cloud visualizations.

## How to Run the Code

### Prerequisites:
1. Install the required libraries:
   ```bash
   pip install spacy nltk tensorflow pandas seaborn matplotlib wordcloud

## Contributing
We welcome contributions! If you have any ideas, bug fixes, or improvements, feel free to fork the repository and submit a pull request.

### Steps to Contribute:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Open a pull request describing your changes.

## Contact
For further inquiries, please contact the project maintainer at:
- Website: [karthikmp.com](https://karthikmp.com)
