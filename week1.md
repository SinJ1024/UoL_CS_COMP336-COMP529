# COMP 336 Note

## Week1 : overview
First week means relax...

Only 2 hours lesson in Monday

Mainly overview and intro


### 1. Intro 
Big Data... I don't like this name, it is not strict and clear.
But it might be most suitable name for a large scale field...
Otherwise...
Massive Heterogeneous Fast Confidence Flex... Data :(

From My Prospective:
Big data is a procedure which mapping informations from our real world space to a abstruct math space, and use some traditional statistical method/ ML method/ simple excel way to extract  features in these Massive Heterogeneous Fast Confidence Flex... Data. Use these features and relations among different features to optimize decisions.

#### 1.1 Characteristics of Big Data:
Big data comes in many shapes and sizes, but it can be characterised in 6 Vs

##### 1.1.1 6 Vs' definition
1. Volume: the amount of data in a given dataset. --数据集大
2. Velocity: Data can be generated at a range of possible speeds. --产生快
3. Variety: Dara comes in different formats, including structured, semi-structure, and unstructured. --数据格式(类型)多
4. Veracity: Data quality and accuracy can vary. --准确性和质量不同
5. Value: which derives from the ability to transform big data into actionable insights. --可以通过数据得到可用于指导实际决策和行动的价值？
6. Variability: Data can be inconsistent or change rapidly. --数据不一致or千变万化

##### 1.1.2 Volume:
1. Volume refers to the quantity of data
2. Ranges from GBs upwards

Overall: 数据量，最低的单元数据大小是GigaByte

##### 1.1.3 Velocity:
1. Velocity refers to the speed at which data is being generated, processed, and analysed.
2. For some big data applications, data arrives continuously from multiple sources in real time.
3. Example: Stock trading platforms and Autonomous vehicles

Overall: 数据生成处理和分析的速度，在一些real time系统中有较高要求

##### 1.1.4 Variety:
1. Variety refers to the wide range of data types and formats
2. Structured data: Databases, spreadsheets, CSV, Parquet
3. Unstructured data: Emails, videos, social media posts, images

Overall: 数据格式不同，分为结构数据和非结构数据

##### 1.1.5 Veracity:
1. Veracity refers to the accuracy, quality, and trustworthiness of data.
2. Big data often includes noisy, incomplete, or inconsistent data.
3. Example: social media data(misleading and basis), sensor(error and noisy)
4. Improve veracity: 1. Data Cleaning 2. Data Validation (Ensure data is correct before analysis)

Overall: 真实性(准确性, 质量和置信度)

##### 1.1.6 Value:
1. Value refers to the insights and actionable information extracted from big data.
2. Big data is often valuable if it can be transformed into meaningful insights
3. A range of techniques to extract value from big data, including: machine learning; statistical analysis; natural language processing; network science; signal processing.

Overall: 数据中可提取到的价值

##### 1.1.7 Variability:
1. Variability refers to the changing nature of data and the inconsistency in its flow.
2. Data can be generated at unpredictable rates and can vary in its meaning and relevance.
3. Handling variability requires adaptive algorithms and real-time monitoring to respond quickly to data changes

Overall: 可变性，adaptive algorithms 确保应对不同的数据类型、生成速度都可以handle.

#### 1.2 Dataset Representations:
Big datasets come in various shapes and sizes. We tend to think about matrices of variables and samples, even when the data isn’t originally presented to us.
##### 1.2.1 Tall and Wide Dataset
These datasets can be very large: millions to billions variables and samples.
Column is Samples, Row is Variables
Example: Social networks, contagion networks...

##### 1.2.2 Tall Datasets
Hundreds to thousands of variables
Thousands to milllions of samples
Often suitable for ML (training set is big and less parameters, easy to build model and training)
Examples: NLP, Image databases, Scientific-computing, RL

##### 1.2.3 Wide Datasets
Thousands to millions of variables
Hundreds to thousands of samples
Variables $\gg$ Samples
Example: Genomocs Datasets, Document modeling

##### 1.2.4 Streaming Datasets
Samples continually created in real time.
Example: Sensor data, Social media feeds, Financial data.

##### 1.2.5 Dense vs Sparse Matrix
1. Dense Matrix:
   1.1 if most of the elements are non-zero, the matrix is considered dense
   1.2 All elements are stored, including the zeroes
   1.3 Memory usage is proportional to the total number of elements(Quite a smart way to define dense matrix under computer science view)
2. Sparse Matrix:
   2.1 By contrast, the number of non-zero elements is roughly equal to the number of rows or columns.
   2.2 Only non-zero elements are stored, often as a coordinate list, which stores triplets (row, column, value)
   2.3 Memory usage is proportional to the number of non-zero elements

### 2. Course Overview
#### 2.1 Big Data Middleware
Datasets in big data are typically too large to be processed on a single computer, so software has been developed to process such datasets across multiple computers in a data centre. The software is called _**big data middleware**_
2 most popular open source big data middleware framework:
1. Hadoop: based on Google’s MapReduce and Google File System papers
   1.1 HDFS(Hadoop Distributed File System): A scalable and fault-tolerant file storage system. The Hadoop Distributed File System (HDFS) provides scalable, fault-tolerant data storage
   1.2: HDFS splits large files into blocks and distributes them across multiple machines for parallel storage and retrieval
   1.3 MapReduce:  programming model for processing large datasets in parallel. Performs fairly simple operations (map and reduce) at huge scales
2. Spark:
   2.1 Spark was developed after Hadoop to address some of its perceived limitations
   2.2 often faster than Hadoop (due to a more sophisticated use of RAM on cluster nodes), and can perform a broader range of tasks
   2.3 Spark’s MLLib library supports a wide range of machine learning algorithms, and GraphX lib enables complex graph computations
   
#### 2.2 Network Science
Network Science studies the structure, dynamics, and behaviour of networks
Use graph theory((un)directional graph or adjacency matrix) to represent network and relations.
Scale-free networks are a type of network characterised by a power-law degree distribution, in these networks, most nodes have few connections, while a few nodes (called "hubs") have many connections

#### 2.3 Unsupervised Learning
PCA and Clustering...
一碗冷饭炒三年

#### 2.4 Supervised Learning
SVM...
What can I say...
Mamb...
If COMP336 contains SVM 

#### 2.5 NLP
I don't have any NLP experiences and knowledges before, looking forward!

#### 2.6 Bayes Stat and Filters
I love math, specially mathematical analysis, some algebra and conbinatorics things.
Uhmmm, statistic....
Not bad, at least better than software dev.




### $End.$





