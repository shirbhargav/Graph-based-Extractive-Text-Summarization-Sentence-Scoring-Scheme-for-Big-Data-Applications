
# Extractive Text Summarization

Text Summarization is an emerging field in Natural Language Process (NLP) domain. It
is very full for summarizing full-length document automatically. We have proposed the
statistical model for the text summarization process. Because of features like easy-to-
use, less complex, low computation resources requirement. We have also used a graph-based
model to establish relations between sentences, and mathematical operations to establish
a relation between words and sentences. We have used documents from the “WiKiHow”
dataset to test our model. We have also demonstrated the effect of the sentence clustering
method by including the graph clustering stage in the post-processing phase. We have
used the GraphFrame module from the Apache Spark environment as it has the ability
to parallel the execution of graph-based operations. To evaluate our model we have used
Recall-oriented Understudying Gisting Evaluation (ROUGE) parameters. Based on the
obtained results, it is clear that graph clustering is dependent on the type of documents
provided in the dataset.
## Brief Architechture

![App Screenshot](https://lh3.googleusercontent.com/drive-viewer/AITFw-wyl3LiOFFsYmOW5aC8CLWnfF93FC3TVWyCGPw_nbz9IRN2wBNSaaEwRP7i1Go9x6jgJjqK_Trwz6yjaw0Pl3xz4kh_oQ=w2560-h1315)


## Dataset

For this project we have used 'WikiHow Dataset'. The dataset is introduced in https://arxiv.org/abs/1810.09305. Please refer to the paper for more information regarding the dataset and its properties.

Each article consists of multiple paragraphs and each paragraph starts with a sentence summarizing it. By merging the paragraphs to form the article and the paragraph outlines to form the summary, the resulting version of the dataset contains more than 200,000 long-sequence pairs.


Sample of first 5000 article and Sentence CSVs and Reference CSV  can be found in .

Full Dataset Link: [Link](https://drive.google.com/file/d/1vK2YGuZT9WoX1hntUUcqpkRzy6Cq9_A_/view?usp=drive_link)

Repo Link: [Link](https://github.com/mahnazkoupaee/WikiHow-Dataset)
## Deployment

- Extract the Sentance CSV and Reference Summary CSV from the 
- Import CSVs to Apache Spark
- Use Spark based tables to generate summary from the 

## Requirement:
Hardware:
   
- Intel i5 and Higher
- 4+ Cores @2.80 GHz
- 8 GB Ram

Software

- Language: Python v3.8.5+
- Jupyter Notebook
- Packages:
    
    - Pandas v1.1.3+
    - Numpy v1.19.2+
    - NLTK v3.5+
    - Rake NLTK v3.5+
    - ROUGE v1.0.4+
    - PySpark v 3.1.0+
    - Graphframe v0.8.1+
## Tech Stack

Python, Apache Spark, GraphFrames
