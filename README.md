# Text-Analytics-on-Billoard-top-100-songs-over-years

The Text Analytics coursework in my Fall semester warranted us to apply some cool modelling techniques on text data and unravel the mystery behind the lyrics of songs which have made it to the Top 100 in Billboard over years 

We scraped 11 years of data, containing over 1100 songs by 686 artists. The data was preprocessed by removing punctuations, stop words, converting all text to lower case for easier interpretation, followed by lemmatization 
Following techniques were applied on the processed data:
1. Vader Sentiment Analysis to analyze sentiments of songs
2. Topic Modelling to extract major topics in lyrics
3. Logistic Regression to predict plausible ranks of songs using their lyrics
4. Clustering to group similar songs together and identify reasons behind difference in performances/ranks between them
5. Cosine similarity based on sentiment and topic modelling scores to recommend songs to listeners based on their earlier preferences
