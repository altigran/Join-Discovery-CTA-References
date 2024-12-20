## Table Discovery & CTA References

This repository is designed to maintain a curated list of references related to semantic table annotation, dataset discovery, and semantic join discovery. The included references span various topics such as cloud data warehouses, data lakes, column type annotation, and knowledge graph integration for tabular data.

### Table Discovery
- **[Fan@SIGMOD23]** **Tutorial** - Grace Fan, Jin Wang, Yuliang Li, and Renée J. Miller. 2023. [Table Discovery in Data Lakes: State-of-the-art and Future Directions.](https://dl.acm.org/doi/pdf/10.1145/3555041.3589409) Tutorial.  [Slides](https://github.com/northeastern-datalab/table-discovery-tutorial/blob/main/table-discovery-slides.pdf) [GitHub](https://northeastern-datalab.github.io/table-discovery-tutorial/). SIGMOD'2023

### Join Discovery
- **[Liu@HILDA-SIGMOD24]** Junfei Liu, Shaotong Sun, Fatemeh Nargesian: [Causal Dataset Discovery with Large Language Models](https://dl.acm.org/doi/pdf/10.1145/3665939.3665968). HILDA@SIGMOD 2024: 1-8
- **[Deng@PVLDB24]** **(LakeBench)** Yuhao Deng et al.: [LakeBench: A Benchmark for Discovering Joinable and Unionable Tables in Data Lakes](https://www.vldb.org/pvldb/vol17/p1925-chai.pdf). Proc. VLDB Endow. 17(8): 1925-1938 (2024)
- **[Dong@PVLDB23]** **(DeepJoin)** Yuyang Dong, Chuan Xiao, Takuma Nozawa, Masafumi Enomoto, Masafumi Oyamada:
[DeepJoin: Joinable Table Discovery with Pre-trained Language Models](https://www.vldb.org/pvldb/vol16/p2458-dong.pdf). Proc. VLDB Endow. 16(10): 2458-2470 (2023) CoRR abs/2212.07588 (2022)
- **[Cong@PVLDB23]** **(Observatory)**  Tianji Cong, Madelon Hulsebos, Zhenjie Sun, Paul Groth, H. V. Jagadish: [Observatory: Characterizing Embeddings of Relational Tables](https://arxiv.org/abs/2310.07736). Proc. VLDB Endow. 17(4): 849-862 (2023) CoRR abs/2310.07736 (2023)
- **[Cong@CIDR23]** **(WarpGate)** Tianji Cong, James Gale, Jason Frantz, H. V. Jagadish, Çağatay Demiralp, [WarpGate: A Semantic Join Discovery System for Cloud DataWarehouses](https://arxiv.org/pdf/2212.14155) CIDR, 2023. arXiv:2212.14155 
- **[Dong@ICDE21]** **(PEXESO)** Yuyang Dong, Kunihiro Takeoka, Chuan Xiao, Masafumi Oyamada:[Efficient Joinable Table Discovery in Data Lakes: A High-Dimensional Similarity-Based Approach](https://arxiv.org/pdf/2010.13273)  ICDE (2021) and CoRR abs/2010.13273
- **[Fernandez@ICDE18]** **(AURUM)** Raul Castro Fernandez, Ziawasch Abedjan, Famien Koko, Gina Yuan, Samuel Madden, and Michael Stonebraker. (2018). [Aurum: A Data Discovery System](https://ieeexplore.ieee.org/iel7/8476188/8509221/08509315.pdf). In 34th IEEE International Conference on Data Engineering (ICDE 2018). IEEE Computer Society, 1001–1012 .
- **[Flores@EDBT2021]** **(NextiaJD)** Javier Flores, Sergi Nadal, Oscar Romero: [Effective and Scalable Data Discovery with NextiaJD](https://doi.org/10.5441/002/edbt.2021.85) "Advances in Database Technology: EDBT 2021, 24th International Conference on Extending Database Technology: Nicosia, Cyprus, March 23-26, 2021: proceedings". Konstanz: OpenProceedings, 2021, p. 690-693.
- **[Flores@EDBT2021]** **(NextiaJD)** Javier Flores, Sergi Nadal, Oscar Romero: [Towards Scalable Data Discovery](https://doi.org/10.5441/002/edbt.2021.47)"Advances in Database Technology: EDBT 2021, 24th International Conference on Extending Database Technology: Nicosia, Cyprus, March 23-26, 2021: proceedings". Konstanz: OpenProceedings, 2021, p. 433-438.
- **[Koutras@2024]** **(OmniMatch)** Christos Koutras, Jiani Zhang, Xiao Qin, Chuan Lei, Vasileios Ioannidis, Christos Faloutsos, George Karypis, Asterios Katsifodimos: [OmniMatch: Effective Self-Supervised Any-Join Discovery in Tabular Data Repositories](https://arxiv.org/abs/2403.07653). arXiv preprint arXiv:2403.07653, 2024.
- **[Maynou@2024]** **(FREYJA)** Marc Maynou, Sergi Nadal, Raquel Panadero, Javier Flores, Oscar Romero, Anna Queralt: [FREYJA: Efficient Join Discovery in Data Lakes](https://arxiv.org/abs/2412.06637). arXiv preprint arXiv:2412.06637, 2024.

### Union Discovery
- **[Fan@PVLDB23]** **(Starmie)** Grace Fan, Jin Wang, Yuliang Li, Dan Zhang, Renée J. Miller: [Semantics-aware Dataset Discovery from Data Lakes with Contextualized Column-based Representation Learning](https://arxiv.org/pdf/2210.01922). Proc. VLDB Endow. 16(7): 1726-1739 (2023)

### Keyword-Based Table Search
- **[Cafarela@VLDB09]** (**Octopus**) Michael J. Cafarella, Alon Y. Halevy, and Nodira Khoussainova. 2009. Data Integration for the Relational Web. Proc. VLDB Endow. 2, 1 (2009), 1090–1101. https://doi.org/10.14778/1687627.1687750
- **[Halevy@SIGMOD16]** (**Goods**) Alon Y. Halevy, Flip Korn, Natalya Fridman Noy, Christopher Olston, Neoklis Polyzotis, Sudip Roy, and Steven Euijong Whang. 2016. Goods: Organizing Google’s Datasets. In Proceedings of the 2016 International Conference on Management of Data, SIGMOD Conference 2016, San Francisco, CA, USA, June 26 - July 01, 2016. ACM, 795–806. https://doi.org/10.1145/2882903.2903730
- **[Wang@SIGMOD19]** (**SmartCrawl**) Pei Wang, Ryan Shea, Jiannan Wang, and Eugene Wu. 2019. Progressive Deep Web Crawling Through Keyword Queries For Data Enrichment. In Proceedings of the 2019 International Conference on Management of Data, SIGMOD Conference 2019, Amsterdam, The Netherlands, June 30 - July 5, 2019 https://doi.org/10.1145/3299869.3319899
- **[Brickley@WWW19]** (**Google Dataset Search**) Dan Brickley, Matthew Burgess, Natasha F. Noy: [Google Dataset Search: Building a search engine for datasets in an open Web ecosystem](https://dl.acm.org/doi/pdf/10.1145/3308558.3313685). WWW 2019: 1365-1375

 
### Table Annotation
- **Table Annotation**
	- **[Feuer@PVLDB24]** **(ArcheType)**  Benjamin Feuer, Yurong Liu, Chinmay Hegde, Juliana Freire: [ArcheType: A Novel Framework for Open-Source Column Type Annotation using Large Language Models](https://arxiv.org/pdf/2310.18208). **Proc. VLDB Endow. 17(9)**: 2279-2292 (2024). CoRR abs/2310.18208 (2023)
	- **[Korini@Tada-VLDB23]** **(CTA-GPT)**  Keti Korini, Christian Bizer: [Column Type Annotation using ChatGPT](https://arxiv.org/pdf/2306.00745). **VLDB Workshops 2023** CoRR abs/2306.00745 (2023)
	- Phuc Nguyen, Natthawut Kertkeidkachorn, Ryutaro Ichise, Hideaki Takeda: [MTab4D: Semantic annotation of tabular data with DBpedia](https://content.iospress.com/download/semantic-web/sw223098?id=semantic-web%2Fsw223098). Semantic Web, vol. Pre-press, no. Pre-press, pp. 1-25, 2022.
	- Udayan Khurana, Sainyam Galhotra: [Semantic Concept Annotation for Tabular Data](https://dl.acm.org/doi/abs/10.1145/3459637.3482295). CIKM 2021: 844-853
	- Dorodnykh N.O., Yurin A.Yu. **[TabbyLD: A Tool for Semantic Interpretation of Spreadsheets Data](https://link.springer.com/chapter/10.1007/978-3-030-68527-0_20).** Communications in Computer and Information Science. Modelling and Development of Intelligent Systems (MDIS 2020), 2021, Vol. 1341, P. 315-333. DOI: 10.1007/978-3-030-68527-0_20
	- Udayan Khurana, Sainyam Galhotra: [Semantic Annotation for Tabular Data](https://arxiv.org/pdf/2012.08594). CoRR abs/2012.08594 (2020)
	- Jiaoyan Chen, Ernesto Jiménez-Ruiz, Ian Horrocks, Charles Sutton: [Learning Semantic Annotations for Tabular Data](https://arxiv.org/pdf/1906.00781). IJCAI 2019: 2088-2094 CoRR abs/1906.00781 (2019)

- **Extended Semantic Web Conference** (ESWC)
	-  **[Korini@ESWC24]** **(CPA-LLM)** Keti Korini, Christian Bizer: [Column Property Annotation using Large Language Models](https://2024.eswc-conferences.org/wp-content/uploads/2024/05/77770060.pdf) **Extended Semantic Web Conference** (ESWC) 2024
	- Marco Cremaschi, Anisa Rula, Alessandra Siano, Flavio De Paoli: [MantisTable: A Tool for Creating Semantic Annotations on Tabular Data](https://boa.unimib.it/bitstream/10281/246778/2/MantisTable_tool.pdf). ESWC (Satellite Events) 2019: 18-23
	- Nora Abdelmageed, Sirko Schindler: [JenTab: A Toolkit for Semantic Table Annotations](https://openreview.net/pdf?id=aZUGsoLdpa). KGCW@ESWC 2021
	
-  **Semantic Web Challenge on Tabular Data to Knowledge Graph Matching**
	- SemTab: Semantic Web Challenge on Tabular Data to Knowledge Graph Matching - https://www.cs.ox.ac.uk/isg/challenges/sem-tab/
	-  Vishvapalsinhji Ramsinh Parmar, Alsayed Algergawy: [DREIFLUSS: A Minimalist Approach for Table Matching](https://www.csd.uoc.gr/~vefthym/SemTab2023/paper4.pdf). SemTab@ISWC 2023: 50-60
	- Ioannis Dasoulas, Duo Yang, Xuemin Duan, Anastasia Dimou: [TorchicTab: Semantic Table Annotation with Wikidata and Language Models](https://lirias.kuleuven.be/retrieve/733695). SemTab@ISWC 2023: 21-37
	- Viet-Phi Huynh, Yoan Chabot, Thomas Labbé, Jixiong Liu, Raphaël Troncy: [From Heuristics to Language Models: A Journey Through the Universe of Semantic Table Interpretation with DAGOBAH](https://hal.science/hal-04170873/document). SemTab@ISWC 2022: 45-58
	- Keti Korini, Ralph Peeters, Christian Bizer: [SOTAB: The WDC Schema.org Table Annotation Benchmark](https://madoc.bib.uni-mannheim.de/63868/1/paper1.pdf). SemTab@ISWC 2022: 14-19
	- Phuc Nguyen, Ikuya Yamada, Natthawut Kertkeidkachorn, Ryutaro Ichise, Hideaki Takeda: [MTab4Wikidata at SemTab 2020: Tabular Data Annotation with Wikidata](https://ceur-ws.org/Vol-2775/paper9.pdf?ref=https://githubhelp.com). SemTab@ISWC 2020: 86-95
	- Nora Abdelmageed, Sirko Schindler: [JenTab: Matching Tabular Data to Knowledge Graphs](https://ceur-ws.org/Vol-2775/paper4.pdf). SemTab@ISWC 2020: 40-49
	
- **Repositories/Datasets/Benchmarks**
	- Column Type Annotation - Papers With Code https://paperswithcode.com/task/column-type-annotation
	- tBiomed: Semantic Table Annotations Benchmark for Biomedical Domain https://zenodo.org/records/10996334
	- [NextiaJD.](https://github.com/dtim-upc/NextiaJD) Flores et al. [14] composes four testbeds of datasets from open repositories such as Kaggle and OpenML. Datasets are divided into testbeds according to their file size. **They also label the join quality of pairs of attributes based on a measure that considers both containment and cardinality proportion with empirically determined thresholds**. In experiments, we use attribute pairs with quality labeled as Good and High by [14].
	- [Spider.](https://zenodo.org/records/5205322#.YTts_o5Kgab) Released as a large-scale semantic parsing and text-to-SQL dataset, Spider [22] includes 5,693 SQL queries on 200 databases across domains. We parse schema SQL files and retrieve join paths between primary keys and foreign keys as ground truth. **Spider has both the training set and the development set, and we currently use join paths from the development set for evaluation**.
