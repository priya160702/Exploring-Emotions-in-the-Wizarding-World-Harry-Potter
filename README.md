# Exploring-Emotions-in-the-Wizarding-World-Harry-Potter

## Objective

To perform a text-based sentiment analysis of Professor Snape’s story, identifying his dominant emotions and the most frequent words that define his character using web scraping, NLP, and data visualization techniques.

## Chapter 1: Web Scraping

The first step was to extract Snape’s narrative from a dedicated webpage. Using Python’s BeautifulSoup, I scraped textual content and structured it into a CSV dataset. This dataset serves as the foundation for all downstream NLP tasks.

## Chapter 2: Sentiment Analysis

Snape’s text was analyzed using VADER SentimentIntensityAnalyzer, a lexicon- and rule-based sentiment analysis tool suitable for short passages. Each sentence was scored for positive, negative, and neutral sentiment, and mapped to emotional categories such as worry, anger, protectiveness, and contempt.

Findings:

Worry: 22.51% – reflects Snape’s persistent vigilance

Contempt: 19.32% – captures his moments of disdain

Anger: 14.94% – highlights frustration in his interactions

Protectiveness: 10.06% – indicates his guardianship over Harry and others

Other subtle emotions like sarcasm, sacrifice, ambiguity, and affection contribute to a multidimensional emotional profile

## Chapter 3: Word Frequency Analysis

To extract key terms, the text was preprocessed using tokenization, lemmatization, and stopword removal. A frequency analysis revealed the most prominent entities and concepts in Snape’s story:

Top Words:

Snape – 703 occurrences

Harry

Dumbledore

Voldemort

Lily

This shows not only Snape’s central role but also his emotional and narrative connections with other key characters.

## Key Insights

Snape’s emotions are layered and complex, dominated by worry and protective instincts.

Contempt and anger highlight the darker facets of his character, while subtle emotions indicate internal conflict.

Word frequency analysis confirms his narrative is strongly interconnected with Harry, Dumbledore, Voldemort, and Lily.

This approach demonstrates how NLP and sentiment analysis can uncover hidden patterns in literary texts, providing both quantitative insights and interpretive depth.

## Tools & Technologies

Python – Core programming language

BeautifulSoup – Web scraping

NLTK – Tokenization, lemmatization, and stopword removal

VADER Sentiment Analyzer – Sentiment scoring

Pandas – Data manipulation and CSV handling

Matplotlib / Seaborn – Data visualization
