# Clothing Item Similarity Search

This project aims to create a machine learning model capable of receiving text describing a clothing item and returning a ranked list of links to similar items from different websites. The solution is implemented in a single notebook on Google Colab, which performs data collection, preprocessing, similarity calculation, and returns ranked results.

## Project Structure

The project is divided into the following steps:

1. **Step 1: Data Collection**: 

   - The notebook includes code to scrape clothing item descriptions from various websites.
   - The collected data is saved in CSV files, which serve as the dataset for the similarity search.

2. **Step 2: Data Preprocessing**:

   - The code performs data preprocessing tasks such as cleaning, tokenization, and stemming.
   - These steps help to normalize the text data for similarity calculation.

3. **Step 3: Similarity Calculation**:

   - The notebook implements a similarity calculation method using TF-IDF and cosine similarity.
   - It compares the input text with the preprocessed data and computes similarity scores.

4. **Step 4: Ranked Results**:

   - The code ranks the results based on similarity scores.
   - It returns the top-N most similar item URLs.

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
