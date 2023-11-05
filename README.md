# Movie-Plot-Similarity-with-Natural-Language-Processing-NLP-
# Project Overview:
Natural Language Processing (NLP) is a fascinating field that empowers data scientists to develop algorithms capable of understanding and interpreting human language. In this project, we leverage NLP techniques to measure the degree of similarity between movies based on their plot summaries, sourced from both IMDb and Wikipedia. By analyzing the narratives of the top 100 IMDb movies, we aim to uncover intriguing patterns and relationships within the film industry.

# Key Project Tasks:
1. Import and Observe Dataset: Start by importing the dataset, which contains the titles of the top 100 IMDb movies and their respective plot summaries from both IMDb and Wikipedia.
2. Combine Wikipedia and IMDb Plot Summaries: Merge and unify the plot summaries from IMDb and Wikipedia for comprehensive analysis.
3. Tokenization: Break down the text data into individual tokens, such as words and phrases, for further analysis.
4. Stemming: Reduce words to their root forms to improve text analysis efficiency.
5. Club Together Tokenize & Stem: Combine tokenization and stemming for text preprocessing.
6. Create TfidfVectorizer: Utilize the Term Frequency-Inverse Document Frequency (TF-IDF) vectorization method to convert text data into numerical vectors.
7. Fit Transform TfidfVectorizer: Apply the TF-IDF vectorizer to transform the movie plot summaries into feature vectors.
8. Import KMeans and Create Clusters: Introduce KMeans clustering to group movies with similar plot summaries.
9. Calculate Similarity Distance: Compute the similarity distances between movies, unveiling hidden connections among the top IMDb films.
10. Import Matplotlib, Linkage, and Dendrograms: Utilize Matplotlib for data visualization and create linkage and dendrograms to depict hierarchical clustering.
11. Create Merging and Plot Dendrogram: Combine movies based on similarity and visualize the dendrogram to understand the cluster structure.
12. Which Movies Are Most Similar?: Explore and analyze which movies exhibit the highest degree of similarity, offering insights into movie plot relationships.

# Project Focus Areas:

Data Manipulation: Processing and manipulating text data for analysis.
Data Visualization: Using Matplotlib to create graphical representations.
Machine Learning: Implementing KMeans clustering for grouping similar movie plots.
Probability & Statistics: Utilizing TF-IDF vectorization and similarity distance calculations.

This project serves as an exciting journey into the realm of NLP, offering a unique perspective on movie plot similarity and the potential applications of NLP in the film industry. Join us in unraveling the narratives behind your favorite IMDb movies!
