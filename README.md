# News Forensics using LDA/LSA Topic Modelling with the help of other NLP Techniques
 The aim of our project is to perform News Clustering focused on grouping news article headlines related to the same story and then to comprehensively group together stories that share a similar theme through Topic Modelling. By doing so we can look at the trends of how the popularity of certain topics have evolved over the years as well as predict what topic and news category headlines broadcast nowadays belong to as well as past news related to them. In simpler terms, we are performing a very rudimentary and primitive task of a much bigger idea that is News Forensics. Our project will make use of mainly unsupervised methods such as Latent Dirichlet Allocation for Topic Modelling and K-Means Clustering. We also plan on experimenting with Latent Semantic Analysis and depending on our needs Density-Based Spatial Clustering of Applications with Noise.

## Dataset: 'A Million News Headlines by ABC News'
##**Context**
The datatset contains a corpus of news headlines posted over a period of almost two decades. Combing through the data the oldest recorded headline is from 19th of February, 2003 and the latest headline is 31st of December 2021. The headlines are all from the same source that is the Australian Broadcasting Corporation abbreviated ABC News. The focus of the dataset is on Australia and as shown below its keywords suggest a good focus on International News for example involving the Iraq War and Elections in the US.
##**Content**
Format: CSV Single File
It has two columns
  1. publish_date: date headline was published in yyyyMMdd format
  2. headline_text: Headline Text in ASCII English Lowercase

Link: https://www.kaggle.com/datasets/therohk/million-headlines
## Sample Results
### Word Cloud (NER Filtered)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/7bb3e0ef-460d-4732-ab8a-04643feaa260)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/ed74be8b-7b33-4950-80a4-98f307ca27f5)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/244e98ff-d00d-48d3-9541-830cd07c690a)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/dd9960af-5963-4bbb-b929-52e40cbcc2ac)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/16940d36-1b6b-4f9b-9449-7383b79bd325)

### Word Cloud (RAW)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/30c8082d-b3ff-401b-ae2d-3aef237ec682)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/314e28ee-00d8-4246-9fe3-68841fc85495)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/76f07f7e-cfb6-4b3d-a50c-b96aa352c3d9)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/49a32442-5444-462d-b9dc-e5f22898548f)
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/c7bd66d3-4c24-47d5-9ac7-5f35d0fdfa08)




### t-SNE Visualisation of LDA Generated Topics
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/2b6d6047-52a7-4311-b27d-8eb1623bce55)
### Heat Map
   ![image](https://github.com/MuhammadTalalFaiz/TopicalModelling/assets/97730886/946ddfe4-be2c-4007-8acf-ef8b3595df27)

