# Supervised Machine Learning Project: Text Classification of Song Lyrics
**[NLP, Web Scrapping, Beautiful Soup, Text Vectorization]**

## Introduction

This repository contains the code and data for my supervised machine learning project on text classification of song lyrics. The project aims to predict the artist (Manowar or Hammerfall) from a given piece of text, specifically focusing on lyrics from these two metal bands.

## Project Description

The project involves building a text classification model using supervised machine learning techniques. The process includes web scraping the lyrics of Manowar and Hammerfall songs using the Beautiful Soup package, preprocessing the text data, and vectorizing the lyrics using the bag-of-words method.

The main objectives of this project are as follows:

1. **Web Scraping**: Utilize Beautiful Soup to scrape the lyrics of Manowar and Hammerfall songs from relevant websites. This step involves extracting the lyrics along with their corresponding artist labels.

2. **Data Preprocessing**: Clean and preprocess the scraped lyrics by removing unnecessary characters, stopwords, and performing text normalization techniques such as stemming or lemmatization. This step ensures the text data is in a suitable format for further analysis.

3. **Text Vectorization**: Convert the preprocessed lyrics into numerical representations using the bag-of-words method. This process involves creating a vocabulary of unique words and representing each song lyric as a vector of word frequencies.

4. **Model Training**: Train a supervised machine learning model, such as a Naive Bayes classifier or a Support Vector Machine (SVM), on the vectorized lyrics data. The model learns the patterns and characteristics that differentiate Manowar and Hammerfall lyrics, enabling it to make accurate predictions on unseen lyrics.

5. **Model Evaluation**: Evaluate the trained model's performance using appropriate metrics such as accuracy, precision, recall, and F1 score. This step ensures the model's effectiveness in predicting the artist based on song lyrics.

6. **Deployment**: Deploy the trained model to make real-time predictions on new song lyrics. This allows users to input text and receive the predicted artist based on the model's learned patterns.

## Repository Structure

- `data/`: Contains the scraped lyrics data for Manowar and Hammerfall.
- `notebooks/`: Jupyter notebooks that showcase the step-by-step analysis, including web scraping, data preprocessing, and model training.
- `src/`: Source code files for data preprocessing, model implementation, and deployment.
- `models/`: Saved trained models for text classification.
- `results/`: Output files, visualizations, and evaluation metrics generated during the analysis.
- `README.md`: Project overview and instructions for running the code.

## Getting Started

To replicate and explore the analysis conducted in this project, follow these steps:

1. Clone the repository to your local machine using the command:

   ```
   git clone https://github.com/elendarn/song_artist_prediction.git
   ```

2. Install the required dependencies by running:

   ```
   pip install -r requirements.txt
   ```

3. Navigate to the `notebooks/` directory and open the Jupyter notebooks to examine the step-by-step analysis.

4. Execute the code cells in the notebooks to perform web scraping, data preprocessing, model training, and evaluation.

5. If interested, you can also explore the `src/` directory to deploy the trained model and make real-time predictions.

## Conclusion

By employing supervised machine learning techniques on the Manowar and Hammerfall song lyrics, this project provides a solution for predicting the artist based on a given piece of text. The trained model demonstrates the ability to classify song lyrics accurately and efficiently. This project can be extended to include additional artists or genres, enabling broader applications in music analysis and recommendation systems.

If you have any questions or suggestions, feel free to reach out or open an issue in the repository. Thank you for your interest in this project, and I hope it inspires further exploration and analysis in the field of text classification and music analysis. Happy classifying!
