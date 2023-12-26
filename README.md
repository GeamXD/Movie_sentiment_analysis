# **Sentiment Analysis of IMDb Movie Reviews**

## **Project Overview**

This project explores sentiment analysis of movie reviews in the IMDb dataset. It demonstrates:

- Text preprocessing techniques for cleaning and preparing reviews for analysis
- Feature extraction using TF-IDF Vectorizer to represent reviews as numerical vectors
- Machine learning model development with Logistic Regression for sentiment prediction
- Visualizing frequent words and model performance using WordCloud and confusion matrix

## **Key Steps**

1. **Data Loading and Exploration:**
    - Load the IMDb dataset.
    - Analyze the balance of positive and negative reviews.

2. **Text Preprocessing:**
    - Count words per review.
    - Encode sentiment labels as 0s and 1s.
    - Remove noise from text using regular expressions.
    - Stem words to reduce them to their base forms.

3. **Feature Extraction:**
    - Apply TF-IDF Vectorizer to create a numerical representation of reviews.

4. **Model Building:**
    - Train a Logistic Regression model for sentiment prediction.

5. **Evaluation and Visualization:**
    - Create a `sentiment_analysis` function to predict sentiment on new reviews.
    - Generate a WordCloud to visualize frequent words.
    - Construct a confusion matrix to evaluate model performance.

## **Getting Started**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/sentiment-analysis-imdb
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the main script:**

   ```bash
   python main.py
   ```

## **Repository Structure**

- **requirements.txt:** Lists required Python packages.
- **main.py:** Contains the primary code for data preprocessing, modeling, and analysis.
- **data/imdb_reviews.csv:** (Optional) The IMDb dataset (if not downloaded automatically).
- **README.md:** This file (provides project overview and instructions).

## **Additional Information**

- **Project report:** A detailed report outlining the project methodology and findings is available in `report.pdf`(N/A)

- **Contact:** For questions or feedback, reach out to <musa.godwin8112@gmail.com>.
