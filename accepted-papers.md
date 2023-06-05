---
title: Accepted Papers
layout: default
---

# Accepted Papers

The accepted papers were peer-reviewed by the SSDBM 2023 technical program committee. From the submissions the committee selected 16 full research papers, 8 short research papers, and 1 demonstration paper.

## Accepted Long Research Papers

**ESM$^2$-Tree: An maintenance efficient authentication data structure in blockchain**

_Yuzhou Fang (Zhejiang University), Weiwei Qiu (Hangzhou Qulian Technology Co., Ltd.), Fanglei Huang (Hangzhou Qulian Technology Co., Ltd.) and Liang Cai (Zhejiang University)._

Abstract

Blockchain technology is gaining broader attention. Owing to its immutability property and byzantine fault-tolerance consensus protocol, blockchain offers a brand new trusted data-sharing solution. Some researchers use blockchain to drive autonomous collaboration among smart devices, which face massive spatial data updates and usage. The key challenge lies in designing an authenticated data structure (ADS) that can efficiently process spatial data and queries. However, the previous schemes could not handle spatial data efficiently or did not consider the efficiency of frequent data updates. In this paper, we take a step toward implementing a maintenance-efficient ADS on the blockchain, called ESM$^2$-Tree, which is not only good at processing spatial data but also effective in supporting authenticated spatial queries by partitioning and merging data at different granularities. Theoretical analysis and empirical evaluation validate the performance of our ADS, which reduces the overall data structure maintenance overhead by about 50\% in a uniform data distribution scenario.


**A Computer Vision Approach for Detecting Discrepancies in Map Textual Labels**

_Abdulrahman Salama (University of Washington), Mahmoud Elkamhawy (university of washington tacoma), Mohamed Ali (University of Washington), Ehab Al-Masri (University of Washington), Adel Sabour (University of Washington), Abdeltawab Hendawi (University of Rhode Island), Ming Tan (Microsoft), Vashutosh Agrawal (Microsoft) and Ravi Prakash (Microsoft)._ 

Abstract

Maps provide various sources of information. An important example of such information is textual labels such as cities, neighborhoods, and street names. Although we treat this information as facts, and despite the massive effort done by providers to continuously improve their accuracy, this data is far from perfect. Discrepancies in textual labels rendered on the map are one of the major sources of inconsistencies across map providers. These discrepancies can have significant impacts on the reliability of the derived information and decision-making processes. Thus, it is important to validate the accuracy and consistency in such data. Most providers treat this data as their propriety data and it is not available to the public, thus we cannot compare the data directly. To address these challenges, we introduce a novel computer vision-based approach for automatically extracting and classifying labels based on the visual characteristics of the label, which indicates its category based on the format convention used by the specific map provider. Based on the extracted data, we detect the degree of discrepancies across map providers. We consider three map providers: Bing Maps, Google Maps, and OpenStreetMaps. The neural network we develop classifies the text labels with an accuracy up to 93\% in all providers. We leverage our system to analyze randomly selected regions in different markets. The studied markets are USA, Germany, France, and Brazil. Experimental results and statistical analysis reveal the amount of discrepancies across map providers per region. We calculate the Jaccard distance between the extracted text sets for each pair of map providers, which represents the discrepancy percentage. Discrepancies percentages as high as 90\% were found in some markets.


**A benchmark for Dynamic Graph version management**

_Zeng Chenglin (Computer Network Information Center, Chinese Academy of Sciences,University of Chinese Academy of Sciences), Wang Huajin (Computer Network Information Center, Chinese Academy of Sciences), Shen Zhihong (Computer Network Information Center, Chinese Academy of Sciences) and Hu Chuan (Computer Network Information Center, Chinese Academy of Sciences)._ 

Abstract

Dynamic Graph data have an increasingly growing usage in domain knowledge graph and large-scale scientific data management. Managing dynamic graph data needs a storage engine that can keep up with their constantly growing volumes while providing an acceptable version query latency. To understand how the store structures design of a dynamic graph database affects its performance, we design SciDG, an easy-use and foundational benchmark for dynamic graph data. Benchmark studies the version query capabilities of dynamic graph databases especially as the versions of data grow up with time. It also studies the latencies of 5 kinds of fundamental queries from the scientific experiments use case. We use SciDG to evaluate the performance of 3 databases of 3 distinct storage principles: Sp-DB, Dp-DB, and Tp-DB. The results of the experiments suggest that SciDG is a valuable tool in evaluating the strengths and weaknesses of different dynamic graph databases. As such, it can assist researchers in selecting the most appropriate dynamic graph data management system for their scientific work.


**Accelerating Machine Learning Queries with Linear Algebra Query Processing**

_Wenbo Sun (Delft University of Technology), Asterios Katsifodimos (Delft University of Technology) and Rihan Hai (Delft University of Technology)._ 

Abstract

The rapid growth of large-scale machine learning (ML) models has led numerous commercial companies to utilize ML models for generating predictive results to help business decision-making. As two primary components in traditional predictive pipelines, data processing, and model predictions often operate in separate execution environments, leading to redundant engineering and computations. Additionally, the diverging mathematical foundations of data processing and machine learning hinder cross-optimizations by combining these two components, thereby overlooking potential opportunities to expedite predictive pipelines.

In this paper, we propose an operator fusing method based on GPU-accelerated linear algebraic evaluation of relational queries. Our method leverages linear algebra computation properties to merge operators in machine learning predictions and data processing, significantly accelerating predictive pipelines by up to 317x. We perform a complexity analysis to deliver quantitative insights into the advantages of operator fusion, considering various data and model dimensions. Furthermore, we extensively evaluate matrix multiplication query processing utilizing the widely-used Star Schema Benchmark. Through comprehensive evaluations, we demonstrate the effectiveness and potential of our approach in improving the efficiency of data processing and machine learning workloads on modern hardware.


**Less is More: How Fewer Results Improve Progressive Join Query Processing**

_Xin Zhang (UNIVERSITY OF CALIFORNIA, RIVERSIDE) and Ahmed Eldawy (University of California, Riverside)._ 

Abstract

With the requirements to enable data analytics and exploration interactively and efficiently, progressive data processing, especially progressive join, became essential to data science. Join queries are particularly challenging due to the correlation between input datasets which causes the results to be biased towards some join keys. Existing methods carefully control which parts of the input to process in order to improve the quality of the results. If the quality is not satisfactory, they will process more data to improve the result. In this paper, we propose an alternative approach that initially seems counter-intuitive but surprisingly works very well. After query processing, we intentionally report fewer results to the user with the goal of improving the quality. The key idea is that if the output is deviated from the correct distribution, we temporarily hide some results to correct the bias. As we process more data, the hidden results are inserted back until the full dataset is processed. The main challenge is that we do not know the correct output distribution while the progressive query is running. In this work, we formally define the progressive join problem with quality and progressive result rate constraints. We propose an input&output quality-aware progressive join framework (QPJ) that (1) provides input control that decides which parts of the input to process; (2) estimates the final result distribution progressively; (3) automatically controls the quality of the progressive output rate; and (4) combines input&output control to enable quality control of the progressive results. We compare QPJ with existing methods and show QPJ can provide the progressive output that can represent the final answer better than existing methods.


**Federated Learning on Personal Data Management Systems: Decentralized and Reliable Secure Aggregation Protocols**

_Julien Mirval (Inria), Luc Bouganim (INRIA-UVSQ) and Iulian Sandu Popa (DAVID Laboratory, University of Versailles Saint-Quentin & INRIA Saclay-Ile-de-France)._ 

Abstract

The development and adoption of personal data management systems (PDMS) has been fueled by legal and technical means such as smart disclosure, data portability and data altruism. By using a PDMS, individuals can effortlessly gather and share data, whether generated directly by their devices or as a result of their interactions with companies or institutions. In this context, federated learning appears to be a very promising technology, but it requires secure, reliable, and scalable aggregation protocols to preserve user privacy and account for potential PDMS dropouts. Despite recent significant progress in secure aggregation for federated learning, we still lack a solution suitable for the fully decentralized PDMS context. This paper proposes a family of fully decentralized protocols that are scalable and reliable with respect to dropouts. We focus in particular on the reliability property which is key in a peer-to-peer system wherein aggregators are system nodes and are subject to dropouts in the same way as contributor nodes. We show that in a decentralized setting, reliability raises a tension between the potential completeness of the result and the aggregation cost. We then propose a set of strategies that deal with dropouts and offer different trade-offs between completeness and cost. Finally, we extensively evaluate the proposed protocols and show that they cover the design space allowing to favor completeness or cost in all settings.


**LearnedSort as a learning-augmented SampleSort: Analysis and Parallelization**

_Ivan Carvalho (The University of British Columbia) and Ramon Lawrence (The University of British Columbia)._ 

Abstract

This work analyzes and parallelizes LearnedSort, the novel algorithm that sorts using machine learning models based on the cumulative distribution function. LearnedSort is analyzed under the lens of algorithms with predictions, and it is argued that LearnedSort is a learning-augmented SampleSort. A parallel LearnedSort algorithm is developed combining LearnedSort with the state-of-the-art SampleSort implementation, IPS4o. Benchmarks on synthetic and real-world datasets demonstrate improved parallel performance for parallel LearnedSort compared to IPS4o and other sorting algorithms.


**Indexing Temporal Relations for Range-Duration Queries**

_Matteo Ceccarello (University of Padova), Anton Dignös (University of Bozen), Johann Gamper (University of Bozen) and Christina Khnaisser (Université de Sherbrooke)._ 

Abstract

Temporal information plays a crucial role in many database applications, however support for queries on such data is limited. We present an index structure, termed RD-Index, to support range-duration queries over interval timestamped relations, which constrain both the range of the tuples' positions on the timeline and their duration. RD-Index is a grid structure in the two-dimensional space, representing the position on the timeline and the duration of timestamps, respectively.  Instead of using a regular grid, we consider the data distribution for the construction of the grid in order to ensure that each grid cell contains approximately the same number of intervals.  RD-Index features provable bounds on the running time of all the operations, allow for a simple implementation, and supports very predictable query performance.

We benchmark our solution on a variety of datasets and query workloads, investigating both the query rate and the behavior of the individual queries.  The results show that RD-Index performs better than the baselines on range-duration queries, for which it is explicitly designed.  Furthermore, it outperforms state of the art indexes also on mixed workloads containing queries that constrain either only the duration or the range along with range-duration queries.  Finally, the size of the RD-Index is in all settings smaller than the competitors.


**Privacy-Preserving OLAP via Modeling and Analysis of Query Workloads: Innovative Theories and Theorems**

_Alfredo Cuzzocrea (University of Calabria)._ 

Abstract

This paper proposes innovative theories and theorems in the context of a state-of-the-art paper that computes privacy-preserving OLAP cubes via modeling and analyzing query workloads. The work contributes to actual literature by devising a solid theoretical framework that can be used for future optimization opportunities.


**Heterogeneous Graph Neural Network via Knowledge Relations for Fake News Detection**

_Bingbing Xie (School of Computing, Macquarie University), Xiaoxiao Ma (School of Computing, Macquarie University), Jia Wu (School of Computing, Macquarie University), Jian Yang (School of Computing, Macquarie University), Shan Xue (School of Computing, Macquarie University) and Hao Fan (School of Information Management, Wuhan University)._ 

Abstract

The proliferation of fake news in social media has been recognized as a severe problem for society, and substantial attempts have been devoted to fake news detection to alleviate the detrimental impacts. Knowledge graphs (KGs) comprise rich factual relations among real entities, which could be utilized as ground-truth databases and enhance fake news detection. However, most of the existing methods only leveraged natural language processing and graph mining techniques to extract features of fake news for detection and rarely explored the ground knowledge in knowledge graphs. In this work, we propose a novel Heterogeneous Graph Neural Network via Knowledge Relations for Fake News Detection (HGNNR4FD). The devised framework has four major components: 1) A heterogeneous graph (HG) built upon news content, including three types of nodes, i.e., news, entities, and topics, and their relations. 2) A KG that provides the factual basis for detecting fake news by generating embeddings via relations in the KG. 3) A novel attention-based heterogeneous graph neural network that can aggregate information from HG and KG, and 4) a fake news classifier, which is capable of identifying fake news based on the news embeddings generated by HGNNR4FD. We further validate the performance of our method by comparison with seven state-of-art baselines and verify the effectiveness of the components through a thorough ablation analysis. From the results, we empirically demonstrate that our framework achieves superior results and yields improvement over the baselines regarding evaluation metrics of accuracy, precision, recall, and F1-score on four real-world datasets.


**Evaluating Autoencoders for Dimensionality Reduction of MRI-derived Radiomics and Classification of Malignant Brain Tumors**

_Mikayla Biggs (Foundation Medicine), Yaohua Wang (The University of Iowa), Neetu Soni (University of Rochester Medical Center), Sarv Priya (The University of Iowa), Girish Bathla (Mayo Clinic) and Guadalupe Canahuate (The University of Iowa)._ 

Abstract

Malignant brain tumors including parenchymal metastatic (MET) lesions, glioblastomas (GBM), and lymphomas (LYM) account for $29.7$\% of brain cancers. However, the characterization of these tumors from MRI imaging is difficult due to the similarity of their radiologically observed image features. Radiomics is the extraction of quantitative imaging features to characterize tumor intensity, shape, and texture. Applying machine learning over radiomic features could aid diagnostics by improving the classification of these common brain tumors. However, since the number of radiomic features is typically larger than the number of patients in the study, dimensionality reduction is needed to balance feature dimensionality and model complexity.

Autoencoders are a form of unsupervised representation learning that can be used for dimensionality reduction. It is similar to PCA but uses a more complex and non-linear model to learn a compact latent space. In this work, we examine the effectiveness of autoencoders for dimensionality reduction on the radiomic feature space of multiparametric MRI images and the classification of malignant brain tumors: GBM, LYM, and MET.  We further aim to address the class imbalances imposed by the rarity of lymphomas by examining different approaches to increase overall predictive performance through multiclass decomposition strategies.


**A Long term Time Series Forecasting method with Multiple Decomposition**

_Yang Wang (North Minzu University), Shuyang Wang (North Minzu University), Xu Chen (North Minzu University) and Yongjun Jing (School of Computer Science and Engineering, North Minzu University, Yinchuan 750021, China.)._ 

Abstract

In various real world applications such as weather forecasting, energy consumption planning, and traffic flow prediction, time serves as a critical variable. These applications can be collectively referred to as time series prediction problems. Despite recent advancements with Transformer based solutions yielding improved results, these solutions often struggle to capture the semantic dependencies in time series data, resulting predominantly in temporal dependencies. This shortfall often hinders their ability to effectively capture long term series patterns. In this research, we apply time series decomposition to address this issue of long term series forecasting. Our method involves implementing a time series forecasting approach with deep series decomposition, which further decomposes the long term trend components generated after the initial decomposition. This technique significantly enhances the forecasting accuracy of the model. For long term time series forecasting (LTSF), our proposed method exhibits commendable prediction accuracy on three publicly available datasets weather, energy, and traffic when compared to prevailing methods. The code for our method is accessible at https://github.com/wangyang970508/LSTF_MD.


**Multi-representations Space Separation based Graph-level Anomaly-aware Detection**

_Fu Lin (School of Computer Science, Wuhan University, China), Haonan Gong (School of Computer Science, Wuhan University, China), Mingkang Li (School of Computer Science, Wuhan University, China), Zitong Wang (School of Computer Science, Wuhan University, China), Yue Zhang (School of Computer Science, Wuhan University, China) and Xuexiong Luo (School of Computing, Macquarie University, Australia)._ 

Abstract

Graph structure pattern is widely used to model different area data recently. How to detect anomalous graph information on these graph data has become a popular research problem. In this work, we focus on the specific problem that how to detect abnormal graphs within a graph set. The previous works have observed that abnormal graphs mainly show node-level and graph-level anomalies, but these methods equally treat two anomaly forms above in the evaluation of abnormal graphs, which is contrary to the fact that different types of abnormal graph data have different degrees in terms of node-level and graph-level anomalies. Furthermore, abnormal graphs that have subtle differences from normal graphs are easily escaped detection by the existing methods. Thus, in this paper, we propose a multi-representations space separation based graph-level anomaly-aware detection framework. To consider the different importance of node-level and graph-level anomalies, we design an anomaly-aware module to learn the specific weight between them in the abnormal graph evaluation process. In addition, we learn strictly separate normal and abnormal graph representation spaces by four types of weighted graph representations against each other including anchor normal graphs, anchor abnormal graphs, training normal graphs, and training abnormal graphs. And we can effectively judge whether the test graph is an abnormal graph according to the distance error of graph representations of the test graph with normal and abnormal graph representation spaces. Extensive experiments with baselines on ten public graph datasets verify the effectiveness of our method. The code of our work is available on https://github.com/whb605/MssGAD.git.


**ST-CopulaGNN : A Multi-View Spatio-Temporal Graph Neural Network for Traffic Forecasting**

_Pitikorn Khlaisamniang (Chulalongkorn University) and Suronapee Phoomvuthisarn (Chulalongkorn University)._ 

Abstract

Modern cities heavily rely on complex transportation, making accurate traffic speed prediction crucial for traffic management authorities. Classical methods, including statistical techniques and traditional machine learning techniques, fail to capture complex relationships, while deep learning approaches may have weaknesses such as error accumulation, difficulty in handling long sequences, and overlooking spatial correlations. Graph neural networks (GNNs) have shown promise in extracting spatial features from non-Euclidean graph structures, but they usually initialize the adjacency matrix based on distance and may fail to detect hidden statistical correlations. The choice of correlation measure can have a significant impact on the resulting adjacency matrix and the effectiveness of graph-based models. This paper proposes a novel approach for accurately forecasting traffic patterns by utilizing a multi-view spatio-temporal graph neural network that captures data from both realistic and statistical domains. Unlike traditional correlation measures such as Pearson correlation, copula models are utilized to extract hidden statistical correlations and construct multivariate distribution functions to obtain the correlation relationship among traffic nodes. A two-step approach is adopted, which involves selecting and testing different types of bivariate copulas to identify the ones that best fit the traffic data, and utilizing these copulas to create multi-weight adjacency matrices. The second step involves utilizing a graph convolutional network to extract spatial information and capturing temporal trends using dilated causal convolutions. The proposed ST-CopulaGNN model outperforms other models in spatio-temporal traffic forecasting, accurately predicting traffic 15, 30, and 60 minutes ahead on the METR-LA dataset. It also achieves the lowest MAE for 30 and 60 minutes ahead and the lowest MAPE for 15 minutes ahead on the PEMS-BAY dataset. The model incorporates copulas, and the study explores copula function selection and the impact of using paired time-series with a time lag. The findings suggest that using copula-based adjacency matrix configurations, particularly those including Clayton and Gumbel copulas, can enhance traffic forecasting accuracy.


**Towards Efficient Discovery of Spatially Interesting Patterns in Geo-referenced Sequential Databases**

_Uday Kiran Rage (The University of Aizu) and Shota Suzuki (The University of Aizu)._ 

Abstract

Geo-referenced sequence database represents the sequential data generated by a set of stationary spatial items observing a phenomenon for some time. Beneficial patterns that can empower the users to achieve socio-economic development lie hidden in this database. Unfortunately, finding such vital patterns is challenging as the existing sequential pattern mining studies disregard the spatial information of the items in a database. This paper considers the items' spatial information and proposes a novel model of geo-referenced frequent sequential patterns that may exist in a database. A novel \emph{neighborhood-aware exploration technique} has been presented to effectively reduce the search space and the computational cost of finding the desired patterns. We also present an efficient algorithm to find all desired patterns in a database. Experimental results demonstrate that the proposed algorithm is efficient. Finally, we demonstrate the usefulness of our patterns with a case study, which involves finding congestion patterns in road network data.


**Data Driven Dimensionality Reduction to Improve Modeling Performance**

_Joshua Chung (Lawrence Berkeley National Laboratory), Marcos Lopez de Prado (Lawrence Berkeley National Laboratory), Horst Simon (Lawrence Berkeley National Laboratory) and Kesheng Wu (Berkeley Lab)._ 

Abstract

In a number of applications, data may be anonymized, obfuscated, or highly noisy. In such cases, it is difficult to use domain knowledge or low-dimensional visualizations to engineer the features for tasks such as machine learning. In this work, we study dimensionality reduction (DR) as a data-driven approaches for engineering these low-dimensional representations. Through a careful examination of available feature selection and feature extraction techniques, we propose a new class named \emph{feature clustering}. These new methods could utilize different forms of clustering approaching to help evaluate the relative importance of features and could take on properties different from the well-known DR algorithms. To evaluate these algorithms, we next develop a parallel computing framework to optimize their hyperparameters on a sample of the application date. This framework harnesses the parallel computing power available on current computers to examine a large number of parameter combinations. It enables hyperparameter tuning and model tuning purely based on observed performance without domain knowledge. Tests show that the optimization framework is able to examine many parameter choices in seconds. On a set of building energy data, the optimized DR algorithms indeed identify expected main drivers, outdoor temperature and solar radiance, of building electricity usage. On two different tests, a distance correlation based feature clustering method outperforms other DR algorithms including the well-known KPCA, LLE, and UMAP.


## Accepted Short Research Papers

**Fast Algorithm for Embedded Order Dependency Validation**

_Daichi Amagata (Osaka University), Alejandro Ramos (Osaka University), Ryo Shirai (Osaka University) and Takahiro Hara (Osaka University)._ 

Abstract

Order Dependencies (ODs) have many applications, such as query optimization, data integration, and data cleaning. Although many works addressed the problem of discovering OD (and its variants), they do not consider datasets with missing values, a standard observation in real-world datasets. This paper introduces the novel notion of Embedded ODs to deal with missing values, and we propose an efficient algorithm for validating embedded ODs. We conduct experiments on real-world datasets, and the results confirm the efficiency of our algorithm.


**Early ICU Mortality Prediction with Deep Federated Learning: A Real-World Scenario**

_Athanasios Georgoutsos (National Technical University of Athens), Paraskevas Kerasiotis (National Technical University of Athens) and Verena Kantere (National Technical University of Athens)._ 

Abstract

The generation of large amounts of healthcare data has mo- tivated the use of Machine Learning (ML) to train robust models for clinical tasks. However, the limitations of local datasets and the privacy restrictions on patient data sharing, impede the use of traditional ML workflows. Consequently, Federated Learning (FL) has emerged as a potential solution for training ML models among multiple healthcare centers. In this study, we focus on the binary classification task of early ICU mortality prediction using Multivariate Time Series. We evaluate the performance of Deep FL, using the FedAvg and FedProx algorithms, to tackle this task with a real world multi-center benchmark database. Our results show that FL models outperform local ML models, thus indicating that FL is a promising solution for Time-Series classification prob- lems in real-world, non-IID dataset scenarios, even though they do not approximate the ideal performance of CML.


**InfoMoD: Information-theoretic Model Diagnostics**

_Armin Esmaeilzadeh (UNLV), Lukasz Golab (University of Waterloo) and Kazem Taghva (UNLV)._ 

Abstract

Validating and debugging machine learning models is done by testing them on unseen data.  Analyzing model performance on various subsets of the data is critical for fairness, trust, bias detection and explainablility.  In this paper, we describe a new way to do this.  Our solution, called InfoMoD, applies recent work in information-theoretic data summarization to the problem of model diagnostics.  Using real-life datasets, we show how InfoMod concisely describes how a model performs across different subsets of the data and produces expected performance indicators for individual test instances.


**MSLS: Meta-graph Search with Learnable Supernet for Heterogeneous Graph Neural Networks**

_Yili Wang (Central South University), Chen Jiamin (Central South University), Qiutong Li (Central South University), Changlong He (Central South University) and Jianliang Gao (Central South University)._ 

Abstract

In recent years, heterogeneous graph neural networks (HGNNs) have achieved excellent performance. The efficient HGNNs consist of meta-graphs and aggregation operations. Since manually designing meta-graph is an expert-dependent and time-consuming process, the performance of HGNNs is limited. To address this challenge, the differentiable meta-graph search has been proposed to obtain promising meta-graph automatically. However, the previous differentiable meta-graph search constructs the supernet without learnable aggregation operations, which limits the semantics extracting ability of HGNNs with automatically designed meta-graph for downstream tasks. To solve this problem, we propose the Meta-graph Search with Learnable Supernet for Heterogeneous Graph Neural Networks (MSLS). Specifically, to obtain better performance HGNNs, MSLS constructs a supernet with learnable aggregation operations based on the meta-graphs. MSLS adopts decoupling training to train the learnable supernet and obtains the optimal meta-graph with learnable aggregation operations using a constrained evolution strategy. Extensive experiments show that our method (MSLS) achieves the best performance in different tasks.


**Decoupled Graph Neural Architecture Search with Variable Propagation Operation and Appropriate Depth**

_Jianliang Gao (Central South University), Changlong He (Central South University), Jiamin Chen (Central South University), Qiutong Li (Central South University) and Yili Wang (Central South University)._ 

Abstract

To alleviate the over-smoothing problem caused by deep graph neural networks, decoupled graph neural networks (DGNNs) are proposed. DGNNs decouple the graph neural network into two atomic operations, the propagation (P) operation and the transformation (T) operation. Since manually designing the architecture of DGNNs is a time-consuming and expert-dependent process, the DF-GNAS method is designed, which can automatically construct the architecture of DGNNs with fixed propagation operation and deep layers. The propagation operation is a key process for DGNNs to aggregate graph structure information. However, DF-GNAS automatically designs DGNN architecture using fixed propagation operation for different graph structures will cause performance loss. Meanwhile, DF-GNAS designs deep DGNNs for graphs with simple distributions, which may lead to overfitting problems. To solve the above challenges, we propose the Decoupled Graph Neural Architecture Search with Variable Propagation Operation and Appropriate Depth (DGNAS-PD) method. In DGNAS-PD, we design a DGNN operation space with variable efficient propagation operations in order to better aggregate information on different graph structures. We build an effective genetic search strategy to adaptively design appropriate DGNN depths instead of deep DGNNs for the graph with simple distributions in DGNAS-PD. The experiments on five real-world graphs show that DGNAS-PD outperforms state-of-art baseline methods.


**Selecting Efficient Cluster Resources for Data Analytics: When and How to Allocate for In-Memory Processing?**

_Jonathan Will (Technische Universität Berlin), Lauritz Thamsen (University of Glasgow), Dominik Scheinert (Technische Universität Berlin) and Odej Kao (Technische Universität Berlin)._ 

Abstract

Distributed dataflow systems such as Apache Spark or Apache Flink enable parallel, in-memory data processing on large clusters of commodity hardware. Consequently, the appropriate amount of memory to allocate to the cluster is a crucial consideration. In this paper, we analyze the challenge of efficient resource allocation for distributed data processing, focusing on memory. We emphasize that in-memory processing with in-memory data processing frameworks can undermine resource efficiency. Based on the findings of our trace data analysis, we compile requirements towards an automated solution for efficient cluster resource allocation.


**Privacy-Preserving Redaction of Diagnosis Data through Source Code Analysis**

_Lixi Zhou (Arizona State University), Lei Yu (Rensselaer Polytechnic Institute), Jia Zou (Arizona State University) and Hong Min (IBM Thomas J. Watson Research Center)._ 

Abstract

Protecting sensitive information in diagnostic data such as logs, is a critical concern in the industrial software diagnosis and debugging process. While there are many tools developed to automatically redact the logs for identifying and removing sensitive information, they have severe limitations which can cause either over redaction and loss of critical diagnostic information (false positives), or disclosure of sensitive information (false negatives), or both. To address the problem, in this paper, we argue for a source code analysis approach for log redaction. To identify a log message containing sensitive information, our method locates the corresponding log statement in the source code with logger code augmentation, and checks if the log statement outputs data from sensitive sources by using the data flow graph built from the source code. Appropriate redaction rules are further applied depending on the sensitiveness of the data sources to preserve the privacy information in the logs. We conducted experimental evaluation and comparison with other popular baselines. The results demonstrate that our approach can significantly improve the detection precision of the sensitive information and reduce both false positives and negatives.


**TGSLN: Time-aware Graph Structure Learning Network for Multi-variates Stock Sector Ranking Recommendation**

_Quan Wan (Central South University), Shuo Yin (Central South University), Xiangyue Liu (Central South University), Jianliang Gao (Central South University) and Yuhui Zhong (Central South University)._ 

Abstract

In the field of financial prediction, most studies focus on individual stocks or stock indices. Stock sectors are collections of stocks with similar characteristics and the indices of sectors have more stable trends and predictability compared to individual stocks. Additionally, stock sectors are subsets of stock indices, which implies that investment portfolios based on stock sectors have a greater potential to achieve excess returns. In this paper, we propose a new method, Time-aware Graph Structure Learning Network (TGSLN), to address the problem of stock sector ranking recommendation. In this model, we use an indicator called Relative Price Strength (RPS) to describe the ranking change trend of the sectors. To construct the inherent connection between sectors, we construct a multi-variable time series that consists of multi-scale RPS sequences and effective indicators filtered through the factor selector. We also build a stock sector relation graph based on authoritative stock sector classifications. Specially, we design a time-aware graph structure learner, which can mine the sector relations from time series, and enhance the initial graph through graph fusion. Our model outperforms state-of-the-art baselines in both A-share and NASDAQ markets.


## Accepted Demonstration Paper

**Interactive Data Mashups for User-Centric Data Analysis**

_Michael Behringer (University of Stuttgart) and Pascal Hirmer (University of Stuttgart)._ 

Abstract

Nowadays, the amount of data is growing rapidly. Through data mining and analysis, information and knowledge can be derived based on this growing volume of data. Different tools have been introduced in the past to specify data analysis scenarios in a graphical manner, for instance, PowerBI, Knime, or RapidMiner. However, when it comes to specifying complex data analysis scenarios, e.g., in larger companies, domain experts can easily become overwhelmed by the extensive functionality and configuration possibilities of these tools. In addition, the tools vary significantly regarding their powerfulness and functionality, which could lead to the need to use different tools for the same scenario. In this demo paper, we introduce our novel user-centric interactive data mashup tool that supports domain experts in interactively creating their analysis scenarios and introduces essential functionalities that are lacking in similar tools, such as direct feedback of data quality issues or recommendation of suitable data sources not yet considered.
