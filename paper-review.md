Paper Review Guidelines
=======================


### Logistics


-   The following are the approved papers for the paper review assignments. You need to select two papers from **different** topic areas.

-   Both reviews are due March 25th. Of course, you can submit them whenever you are ready, but this is the deadline.

-   The reviews should be about 2,500–3,000 words, roughly 5 pages single-spaced in 11-12pt font with 1in margins.

-   The reviews should be submitted in PDF (and only PDF). Name your files as <student-id,last-name-review1.pdf> (and similarly for the second one).

-   Drop your review files in the appropriate Dropbox folder.

### Review Outline


Your review should be balanced between (a) discussing the paper so that someone who hasn't read the paper can understand what the paper is about (consider you are presenting the paper to your boss at work), and (b) a critique of the paper (what is good, what is not so good, what do you think about it). 

It should contain the following (you do not need section headings for these):

1. What is the problem? Clear statement of what the paper is solving.
1. Why is this problem important? Why do we need to solve this problem? What practical need  or a theoretical understanding need is it addressing?
1. Is this a novel solution? Why does the world need another solution to this problem (unless it is the first one to solve it)?
1. What are the technical challenges addressed and how do the authors solve them?
1. What is your view on how _effective_ and _efficient_ the solution(s) are?
1. What are 3-4 lines of research you think would be good topics to pursue as extensions to this work. Consider one or two short-term extensions (work that can be done in less than one year) and a few topics of longer term research.

### Some Background Material

You may also find the following useful:

+ [How to read a paper](https://dl.acm.org/doi/10.1145/1273445.1273458) by S. Keshav
+ [Task of the referee](https://www2.eecs.berkeley.edu/Pubs/TechRpts/1989/CSD-89-511.pdf) by A. J. Smith
+ [Efficient Reading of Papers in Science and Technology](https://www.cs.columbia.edu/~hgs/netbib/efficientReading.pdf) by M. J. Hanson and D. McNamee
+ [How to review CS papers](https://dl.acm.org/doi/10.1145/2425676.2425681) by S. Kalwar
+ [Tips for writing technical papers](https://cs.stanford.edu/people/widom/paper-writing.html) by J. Widom

These may be dated, but they are still relevant.

### Reading List

#### A. Core DBMS, Storage, and Query Processing

- P. Selinger, M. Astrahan, D. Chamberlin, R. Lorie, and T. Price.  [Link](https://doi.org/10.1145/582095.582099)
  **Access Path Selection in a Relational Database Management System.**  
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pp. 23–34, 1979.

- P. Boncz, M. Zukowski, and N. Nes. [Link](https://www.cidrdb.org/cidr2005/papers/P19.pdf)
  **MonetDB/X100: Hyper-Pipelining Query Execution.**  
  *Proceedings of the 2nd Biennial Conference on Innovative Data Systems Research (CIDR)*, pp. 225–237, 2005.

- M. Stonebraker, D. J. Abadi, A. Batkin, et al. [Link](https://dl.acm.org/doi/10.5555/1083592.1083658) 
  **C-Store: A Column-Oriented DBMS.**  
  *Proceedings of the 31st International Conference on Very Large Data Bases (VLDB)*, pp. 553–564, 2005.

- D. J. Abadi, S. Madden, and N. Hachem.  [Link](https://doi.org/10.1145/1376616.1376712)
  **Column-Stores vs. Row-Stores: How Different Are They Really?**  
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pp. 967–980, 2008.

---

#### B. OLTP, OLAP, and HTAP Systems

- S. Harizopoulos, D. J. Abadi, S. Madden, and M. Stonebraker.  [Link](https://doi.org/10.1145/3226595.3226635)
  **OLTP Through the Looking Glass, and What We Found There.**  
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pp. 981–992, 2008.

- A. Kemper and T. Neumann.  [Link](https://ieeexplore.ieee.org/document/5767867)
  **HyPer: A Hybrid OLTP & OLAP Main-Memory Database System Based on Virtual Memory Snapshots.**  
  *Proceedings of the IEEE International Conference on Data Engineering (ICDE)*, pp. 195–206, 2011.

- C. Diaconu, C. Freedman, E. Ismert, et al. [Link](https://doi.org/10.1145/2463676.2463710)
  **Hekaton: SQL Server’s Memory-Optimized OLTP Engine.**  
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pp. 1243–1254, 2013.

- J. DeBrabant, A. Pavlo, S. Tu, M. Stonebraker, and S. B. Zdonik.  [Link](https://doi.org/10.14778/2556549.2556575)
  **Anti-Caching: A New Approach to Database Management System Architecture.**  
  *Proceedings of the VLDB Endowment (PVLDB)*, 6(14):1942–1953, 2013.

---

#### C. Big Data Platforms and Cloud-Native Systems

- B. Dageville, T. Cruanes, M. Zukowski, et al.  [Link](https://doi.org/10.1145/2882903.2903741)
  **The Snowflake Elastic Data Warehouse.**  
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pp. 215–226, 2016.

- M. Elhemali, N. Gallagher, N. Gordon, et al.  [Link](https://www.usenix.org/system/files/atc22-elhemali.pdf)
  **Amazon DynamoDB: A Scalable, Predictably Performant, and Fully Managed NoSQL Database Service.**  
  *Proceedings of the USENIX Annual Technical Conference*, pp. 1037–1048, 2022.

- M. Armbrust, A. Ghodsi, R. Xin, M. Zaharia  [Link](https://www.cidrdb.org/cidr2021/papers/cidr2021_paper17.pdf)
  **Lakehouse: A New Generation of Open Platforms that Unify Data Warehousing and Advanced Analytics.**
  *Proceedings of the 11th Biennial Conference on Innovative Data Systems Research (CIDR)*, 2021

---

#### D. Data Streaming and Velocity

- P. Carbone, A. Katsifodimos, S. Ewen, V. Markl, S. Haridi, K. Tzoumas. [Link](http://sites.computer.org/debull/A15dec/p28.pdf) 
  **Apache Flink : Stream and Batch Processing in a Single Engine.**  
  *IEEE Data Engineering Bulletin*, 36(4):28-33, 2015.

- T. Akidau, A. Balikov, K. Bekiroglu, et al.  [Link](https://doi.org/10.14778/2536222.2536229)
  **MillWheel: Fault-Tolerant Stream Processing at Internet Scale.**  
  *Proceedings of the VLDB Endowment (PVLDB)*, 6(11):1033–1044, 2013.

---

#### E. Data Integration and Preparation

- A. Y. Halevy, A. Rajaraman, and J. Ordille. [Link](https://dl.acm.org/doi/10.5555/1182635.1164130)
  **Data Integration: The Teenage Years.**  
  *Proceedings of the International Conference on Very Large Data Bases (VLDB)*, pp. 9–16, 2006.

- H. Do and E. Rahm.  [Link](https://dl.acm.org/doi/10.5555/1287369.1287422)
  **COMA: A System for Flexible Combination of Schema Matching Approaches.**  
  *Proceedings of the International Conference on Very Large Data Bases (VLDB)*, pp. 610–621, 2002.

- R. Dhamankar, Y. Lee, A. Doan, A. Y. Halevy, and P. Domingos. [Link](https://doi.org/10.1145/1007568.1007612)
  **iMAP: Discovering Complex Mappings Between Database Schemas.**  
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pp. 383–394, 2004.

---

#### F. Data Quality and Provenance

- B. Rekatsinas, X. Chu, I. F. Ilyas, and C. Ré. [Link](https://doi.org/10.14778/3137628.3137631)
  **HoloClean: Holistic Data Repairs with Probabilistic Inference.**  
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pp. 119–134, 2017.

- M. Yakout, A. K. Elmagarmid, J. Neville, M. Ouzzani, and I. F. Ilyas. [Link](https://doi.org/10.14778/1952376.1952378)
  **Guided Data Repair.**  
  *Proceedings of the VLDB Endowment (PVLDB)*, 4(5):279–289, 2011.

- H. Yang, Z. Xu, S. Yudin, and A. Davidson. [Link](https://www.vldb.org/pvldb/vol18/p4887-yang.pdf)
  **Unlocking the power of ci/cd for data pipelines in distributed data warehouses.**
  *Proceedings of the VLDB Endowment (PVLDB)*, 18(12):4887–4895, 2025.

---

#### G. LLMs and Modern Data Engineering

- D. Gao, H. Wang, Y. Li, X. Sun, Y. Qian, B. Ding, and J. Zhou. [Link](https://dl.acm.org/doi/10.14778/3641204.3641221)
  **Text-to-SQL Empowered by Large Language Models: A Benchmark Evaluation.**  
  *Proceedings of the VLDB Endowment (PVLDB)*, 17(5):1132–1145, 2024.  
  DOI: 10.14778/3641204.3641221

- M. Parciak, B. Vandevoort, F. Neven, L. M. Peeters, and S. Vansummeren. [Link](https://vldb.org/workshops/2024/proceedings/TaDA/TaDA.8.pdf)
  **Schema Matching with Large Language Models: An Experimental Study.**
  *VLDB 2024 Workshop: Tabular Data Analysis Workshop (TaDA)*, 2024.

- J. Tan, K. Zhao, R. Li, J. Xu Yu, C. Piao, H. Cheng, H. Meng, D. Zhao, and Y. Rong. [Link](https://arxiv.org/abs/2502.05562)
  **Can Large Language Models Be Query Optimizers for Relational Databases?**
  *arXiv preprint, arXiv:2502.05562*, 2025.

---

#### H. Vector Databases and Similarity Search

- J. Johnson, M. Douze, and H. Jégou. [Link](https://ieeexplore.ieee.org/document/8733051)
  **Billion-Scale Similarity Search with GPUs.**
  *Proceedings of the IEEE International Conference on Big Data*, pages 535–544, 2017.

- Z. Wang, Y. Cai, S. Zhang, et al. [Link](https://dl.acm.org/doi/10.1145/3448016.3457550)
  **Milvus: A Purpose-Built Vector Data Management System.**
  *Proceedings of the ACM SIGMOD International Conference on Management of Data*, pages 2619–2632, 2021.

- I. Azizi, K. Echihabi, and T. Palpanas. [Link](https://dl.acm.org/doi/10.1145/3709693)
  **Graph-Based Vector Search: An Experimental Evaluation of the State-of-the-Art.**
  *Proceedings of the ACM on Management of Data (PACMMOD)*, 3(1): Article 43, 2025





