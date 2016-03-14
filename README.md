# Machine Learning And Data mining
COMP5318
Language: **Python**

## 1. Introduction to Machine Learning
### 1.1 What is data mining?
**Data Mining ≈ Big Data ≈ Predictive Analytics ≈ Data Science**
#### 1.1.1 From wiki:
**Data mining** is the computational process of discovering patterns in large data sets ("big data") involving methods at the intersection of artificial intelligence, machine learning, statistics, and database systems. The overall goal of the data mining process is to extract information from a data set and transform it into an understandable structure for further use.
> NOTE: The goal is the extraction of patterns and knowledge from large amounts of data, not the extraction (mining) of data itself.

#### 1.1.2 From [Mining of Massive Datasets](http://www.mmds.org/)
DATA MINING is **Knowledge discovery from data.** DATA MINING is the discovery of “models” for data.
Data contains value and knowledge. But to extract the knowledge the data needs to be **Stored** and **Managed** And **ANALYZED** (data mining)

#### 1.1.3 Discover patterns and models that are:
- **Valid**:  hold on new data with some certainty
- **Useful**:  should be possible to act on the item 
- **Unexpected**:  non-obvious to the system
- **Understandable**: humans should be able to interpret the pattern
 
#### 1.1.4 Computational Approaches to modeling
two approaches:
 1. Summarizing the data succinctly and approximately (PageRank, clustering)
 2. Extracting the most prominent feature of the data and ignoring the rest.(Bayes nets, Frequent Itemsets, Similar Items-recommand)


#### 1.1.5 Statistical Limits
 1. Total Information Awareness: its feasibility and the realism of its assumptions. The answer is that it all depends on how **narrowly** you define the activities that you look for.->Bonferroni’s Principle
 2. **Bonferroni’s principle**: that helps us avoid treating random occurrences as if they were real.  Calculate the expected number of occurrences of the events you are looking for, on the assumption that data is random. If this number is significantly larger than the number of real instances you hope to find, then you must expect almost anything you find to be bogus, i.e., a statistical artifact rather than evidence of what you are looking for. This observation is the informal statement of Bonferroni’s principle.

### 1.2 Data Mining Tasks and Problems
#### 1.2.1 Descriptive methods
**Clustering, Segementation and Summarisation**-Find patterns in the data: Find human-interpretable patterns that **describe** the data. 

#### 1.2.2 Predictive methods
**Classification and Regression**: Use some variables to **predict** unknown or future values of other variables. Example: Recommender systems

#### 1.2.3 Outlier/anomaly detection
**Find unusual patterns**
**WHY?**: A risk with “Data mining” is that an analyst can “discover” patterns that are meaningless. Statisticians call it 


### 1.3 Data Structure

### 1.4 Things Useful to Know
 1. The TF.IDF measure of word importance.
 2. Hash functions and their use.
 3. Secondary storage (disk) and its effect on running time of algorithms.
 4. The base e of natural logarithms and identities involving that constant.
 5. Power laws.


## Basic Matrix Analysis and Singular Value Decomposition


## READING BOOKS
### I. [Mining of Massive Datasets](http://www.mmds.org/)
This book focuses on data mining of **very large amounts of data**, that is, data so large it does not fit in main memory. So many of its examples is about the WEB DATA. This book includes topics listed below:
 1. Distributed file systems and map-reduce: creating parallel algorithms
 2. Similarity search: minhashing and locality-sensitive hashing
 3. Data-stream processing and specialized algorithms: deal with "fast" data which must be processed immediately or lost
 4. Search engines: Google's PageRank, link-spam detection and the hubs-and-authorities approach
 5. Frequent-itemset mining: association rules, market-baskets, the A-Priori Algorithm and its improvements
 6. Algorithms for clustering very large, high-dimensional datasets
 7. Two key problems for Web applications: managing advertising and recommendation systems.
 8. analyzing and mining the structure of very large graphs, especially social-network graphs.
 9. obtaining the important properties of a large dataset by dimensionality reduction, including singular-value decomposition and latent semantic indexing
 10. Machine-learning algorithms that can be applied to very large data, such as perceptrons, support-vector machines, and gradient descent.
 11. 
