# Opinosis

## What is Opinosis
The Opinosis Summarization framework is a graph based algorithm that focuses on generating very short abstractive summaries from large amounts of text. These summaries can resemble micropinions or "micro-reviews" that you see on sites like twitter and four squares. The idea of the algorithm is to use a word graph data structure referred to as the Opinosis-Graph to represent the text to be summarized. Then, the resulting graph is repeatedly explored to find meaningful paths which in turn becomes candidate summary phrases. The Opinosis summarizer is considered a "shallow" abstractive summarizer as it uses the original text itself to generate summaries (this makes it shallow) but it can generate phrases that were previously not seen in the original text because of the way paths are explored (and this makes it abstractive rather than purely extractive). The summarization framework was evaluated on an opinion (user review) dataset. The approach itself is actually very general in that, it can be applied to any corpus containing high amounts of redundancies, for example, Twitter comments or user comments on blog/news articles


## Opinosis Software Distribution

- Download the zip file for the software and corresponding documentation. 
- Visit my [website](http://kavita-ganesan.com/opinosis) for the Opinosis paper and other information 

