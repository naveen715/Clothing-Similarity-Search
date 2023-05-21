# Clothing Item Similarity Search

This project aims to create a machine learning model capable of receiving text describing a clothing item and returning a ranked list of links to similar items from different websites. The solution is implemented in a single notebook on Google Colab, which performs data collection, preprocessing, similarity calculation, and returns ranked results.

## Project Structure

The project is divided into the following steps:

1. **Step 1: Data Collection**: Web scrape clothing item descriptions from various websites and store them in CSV files.
2. **Step 2: Data Preprocessing**: Preprocess and cleanse the collected data, including removing punctuation, converting text to lowercase, tokenization, removing stop words, and performing stemming.
3. **Step 3: Similarity Calculation**: Extract features from the preprocessed data and compute the similarity index between the input text and the items in the dataset.
4. **Step 4: Ranked Results**: Return ranked results by sorting the similarity scores and retrieving the top-N most similar item URLs.

## Implementation

The implementation is done in a single notebook file, which includes the following sections:

1. **Data Collection**: Contains the code to web scrape clothing item descriptions from various websites and store them in CSV files.
2. **Data Preprocessing**: Implements the data preprocessing steps, including text cleaning, tokenization, and stemming.
3. **Similarity Calculation**: Computes the similarity index between the input text and the dataset using TF-IDF and cosine similarity.
4. **Ranked Results**: Ranks the results based on similarity scores and returns the top-N most similar item URLs.

## Usage

To use the clothing item similarity search, follow these steps:

1. Open the notebook file in Google Colab.
2. Run each section sequentially, starting from data collection, data preprocessing, similarity calculation, and ranked results.
3. Provide the input text and the desired number of results in the ranked results section to get the top-N most similar item URLs.
4. The ranked results will be displayed in the output.

## Result
![Project Result](https://github.com/naveen715/Clothing-Similarity-Search/blob/main/result.png)

## Conclusion

The clothing item similarity search project implemented in a single notebook provides a straightforward way to gather clothing item descriptions, preprocess the data, calculate similarity, and return ranked results. By following the provided steps, you can easily use the functionality of the project and explore different clothing item recommendations.

Feel free to reach out if you have any questions or need further assistance!
