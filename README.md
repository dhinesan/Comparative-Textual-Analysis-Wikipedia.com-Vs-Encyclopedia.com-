# Comparative-Textual-Analysis-Wikipedia.com-Vs-Encyclopedia.com-
This project provides a comprehensive comparative analysis of content quality and sentiment in by using 11 common topics from Wikipedia.com and Encyclopedia.com, by leveraging python - web scraping, text analysis, and data visualization techniques, we gain insights into how these platforms present information on those common topics.

In this project, we aim to compare the content quality and sentiment of article on eleven selected topics from both Wikipedia and Encyclopedia. We employ web scraping techniques using Python to extract text data from these sources, followed by text cleaning and feature extraction. The extracted features include word counts, sentence counts, complex word counts, syllable counts, and readability metrics such as the FOG index. Additionally, sentiment analysis is performed to calculate positive score, negative score, polarity score, and subjectivity score for each entry.

Methods:
1. Web scraping: Utilize Python libraries such as BeautifulSoup and requests to scrape text data from Wikipedia and Encyclopedia articles.
2. Text cleaning: Remove HTML tags, punctuation, stopwords, and perform lemmatization to preprocess the text data.
3. Feature extraction: Calculate word counts, sentence counts, complexity metrics (e.g., FOG index), and sentiment scores using natural language processing techniques.
4. Data visualization: Construct pandas dataframes with the extracted features and utilize matplotlib or seaborn libraries to create visualizations for comparative analysis.


Conclusion:
  Overall, the analysis underscores the distinct characteristics of Wikipedia and Encyclopedia articles in terms of content length, readability, sentiment, and subjectivity. While Wikipedia offers comprehensive coverage with a tendency towards positive sentiment and objective presentation, Encyclopedia provides concise information with a balanced sentiment distribution and a wider range of subjectivity. Understanding these differences is essential for readers seeking reliable and comprehensive information from diverse sources.T(hrough vaious Visualization techniques I came to this conclusion)

To try out the same: 
  1. Install required libraries through 'pip install' command
       pip install newspaper3k
       pip install nltk
  2. Url - Inputs.xlsx file contains the url to web scraping.
  3. FILE PATH; I have used my choise of irecoty to save each extracted text and use the input.xlsx file, kindly change the file path while running the python code in 'Textual Analysis.ipynb'
  4. Extracted data file contains all the extracted text data through web-scraping
  5. Vectorized-data will have the dataframe in excel format
  6. Textual Analysis.pdf will contains the entire project report and explanation.
  7. # Avg.Sent -> Average word count in sentences, Avg.Word -> Average word length

Feel free to provide your comments and feedback about my project which will be a great motivation for me to do more projects and improvise myself.
