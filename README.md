# Information retrieval and topic modeling to match WHO information and covid conspiracy tweets
By /pernillekober & /EkaterinaBatueva

Libraries: nltk, top2vec, pyLDAvis, PyTerrier, BeautifulSoup, regex, demoji, pickle.\
Techniques: Topic modeling (Latent Dirichlet Allocation, top2vec), Information Retrieval, Webcawling/scraping.

Approach to informing Twitter users about the presence of false information in a tweets and provide reliable information scraped from the WHO website to reduce the spread of misinformation. A dataset (consists of 213 069 and 71 614 observations, before and after preprocessing, respectively) consisting of user information and tweets tagged with keywords "plandemic" and "scamdemic" from March to June 2021 was used for topic modeling. Two topic modeling techniques - LDA and top2vec - was used to compare the  quality of extracted topics on short text and to determine applicability of topics as queries to retrieve reliable information from WHO. It was concluded that topics derived using LDA model are more sufficient as queries for information retrieval from WHO data, and that top2vec could be useful to find related hashtags and twitter-language.
