# News Forensics using K-Means/DBSCAN Clustering and LDA/LSA Topic Modelling with the help of other NLP Techniques
 The aim of our project is to perform News Clustering focused on grouping news article headlines related to the same story and then to comprehensively group together stories that share a similar theme through Topic Modelling. By doing so we can look at the trends of how the popularity of certain topics have evolved over the years as well as predict what topic and news category headlines broadcast nowadays belong to as well as past news related to them. In simpler terms, we are performing a very rudimentary and primitive task of a much bigger idea that is News Forensics. Our project will make use of mainly unsupervised methods such as Latent Dirichlet Allocation for Topic Modelling and K-Means Clustering. We also plan on experimenting with Latent Semantic Analysis and depending on our needs Density-Based Spatial Clustering of Applications with Noise.

## Dataset: 'A Million News Headlines by ABC News'
##**Context**
The datatset contains a corpus of news headlines posted over a period of almost two decades. Combing through the data the oldest recorded headline is from 19th of February, 2003 and the latest headline is 31st of December 2021. The headlines are all from the same source that is the Australian Broadcasting Corporation abbreviated ABC News. The focus of the dataset is on Australia and as shown below its keywords suggest a good focus on International News for example involving the Iraq War and Elections in the US.
##**Content**
Format: CSV Single File
It has two columns
  1. publish_date: date headline was published in yyyyMMdd format
  2. headline_text: Headline Text in ASCII English Lowercase
## Sample Results
1. Word Cloud
2. t-SNE Visualisation of LDA Generated Topics
3. Heat Map 
