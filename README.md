# 🏎💨vroom <a href='https:/vroom.r-lib.org'><img src='man/figures/logo.png' align="right" height="135" /></a>
# Databases, tools, and computational methods for lncRNA-miRNA interaction prediction: a survey 
![GitHub stars](https://img.shields.io/github/stars/sheng-n/lncRNA-miRNA-interaction-methods?color=red) ![GitHub forks](https://img.shields.io/github/forks/sheng-n/lncRNA-miRNA-interaction-methods?color=green&label=Fork) ![visitors](https://visitor-badge.glitch.me/badge?page_id=sheng-n.lncRNA-miRNA-interaction-methods)

## What is lncRNA and miRNA?
RNA can be divided into two categories based on its coding function: (1) RNAs with coding potential, and (2) RNAs without coding potential, also known as non-coding RNA (ncRNA), which includes microRNAs (miRNA), snoRNAs, circRNAs and lncRNAs. Long non-coding RNAs (lncRNAs) and miRNAS are a major class of important ncRNAs with the lengths more than 200 nucleotides and the lengths about 20–23 nt. 

## Table of Contents
* [Overview](#Overview) 
* [ Databases and tools](#Databases-and-tools) 
* [Computational methods for lncRNA-miRNA interaction prediction](#Computational-methods-for-lncRNA-miRNA-interaction-prediction) 
  - [Network-based methods](#Network-based-methods)
  - [Sequence-based methods](#Sequence-based-methods)
* [A Summary of Methodology Details for predicting lncRNA-miRNA interactions](#A-Summary-of-Methodology-Details-for-predicting-lncRNA-miRNA-interactions) 
* [ Welcome to contribute](#Welcome-to-contribute) 

## Overview
* We are presented databases and tools related to animal and plant lncRNA-miRNA interactions prediction, covering lncRNA-miRNA interactions data, lncRNA- and miRNA-related data (such as expression profiles, sequences, and functions). These databases are widely used in computational methods and are still being updated and accessed.. 
* We reviewed 18 computational methods for lncRNA-miRNA interactions prediction that are divided into two groups, including network-based methods and sequence-based methods, as shown below figure 1.
![image](https://user-images.githubusercontent.com/95516781/193453306-4aadb7c0-d6f6-4b2a-8eb6-7273abd9ba52.png)



Fig 1: Taxonomy of computational methods for lncRNA-miRNA interaction prediction.

## Databases and tools
| Database  |Latest version |Description  | URL | 
|:-------------:|:------:|:-------------: |:----------:|
|lncRNASNP | lncRNASNP2 | It contains SNPs in lncRNAs, SNP effects on lncRNA structure, a mutation in lncRNAs and lncRNA-miRNA interactions|http://bioinfo.life.hust.edu.cn/lncRNASNP#!/|
|LNCipedia |LNCipedia (v5.2) |It provides lncRNA sequence and annotation. The current release contains 127802 transcripts and 56946 genes | https://lncipedia.org/|
|miRBase |miRbase (v22.1) |It records published miRNA sequences and annotation, involving 38589 miRNAs entries | https://mirbase.org/|
| NONCODE|NONCODE (v6.0) |An integrated knowledge database dedicated to the ncRNAs database. It collects lncRNA expression profiles and putative functional annotations of lncRNA | http://www.noncode.org/|
|microRNA.org | NA|It provides miRNA target predictions and expression profiles | http://www.microrna.org|
| miRTarBase|Update 2022 |It presents experimentally validated miRNA-target interactions |https://miRTarBase.cuhk.edu.cn/ |
|CANTATAdb |CANTATAdb (2.0) |It records 239631 lncRNAs predicted in 36 plant species and 3 algae, and presents lncRNA sequences, genomic locations |http://yeti.amu.edu.pl/CANTATA/ |
|PMRD |Updated 2014 |A plant miRNA database, including miRNA sequences and their target genes, secondary, dimension structure, expression profiling, etc. |http://bioinformatics.cau.edu.cn/PMRD/ |
| GreeNC|GreeNC (v2.0) |A plant lncRNAs database, recording lncRNA sequences, genomic coordinates, coding potential and folding energy | http://greenc.sequentiabiotech.com/wiki2/Main_Page|
|RNAhybrid | RNAhybrid 2.1.2|It is a tool for finding the minimum free energy hybridization of a long and a short RNA, and is primarily meant as a means for microRNA target prediction |https://bibiserv.cebitec.uni-bielefeld.de/rnahybrid |
| psRNATarget|psRNATarget (v2) |It is a plant small RNA target analysis server, and used as the miRNA-lncRNA interaction prediction tool |https://www.zhaolab.org/psRNATarget/ |

## Computational methods for lncRNA-miRNA interaction prediction
### Network-based methods
1. **[EPLMI]** Huang Y-A, Chan KCC, You Z-H. Constructing prediction models from expression profiles for large scale lncRNA–miRNA interaction profiling, Bioinformatics 2017;34(5):812-819. [**[Download]**](https://academic.oup.com/bioinformatics/article/34/5/812/4562502 "Click") [**[Code]**](https://github.com/TYLH/EPLMI "Click") 

2. **[GCLMI]** Huang Y-A, Huang Z-A, You Z-H et al. Predicting lncRNA-miRNA Interaction via Graph Convolution Auto-Encoder, Frontiers in genetics 2019;10. [**[Download]**](https://www.frontiersin.org/articles/10.3389/fgene.2019.00758/full "Click")

3. **[LNRLMI]** Wong L, Huang Y-A, You Z-H et al. LNRLMI: Linear neighbour representation for predicting lncRNA-miRNA interactions, Journal of Cellular and Molecular Medicine 2020;24(1):79-87. [**[Download]**](https://onlinelibrary.wiley.com/doi/full/10.1111/jcmm.14583 "Click") 

4. **[LMNLMI]** Hu P, Huang YA, Chan KCC et al. Learning Multimodal Networks From Heterogeneous Data for Prediction of lncRNA–miRNA Interactions, IEEE/ACM Transactions on Computational Biology and Bioinformatics 2020;17(5):1516-1524. [**[Download]**](https://ieeexplore.ieee.org/abstract/document/8918443 "Click")

5. **[GEEL-PI, GEEL-FI]** Zhao C, Qiu Y, Zhou S et al. Graph embedding ensemble methods based on the heterogeneous network for lncRNA-miRNA interaction prediction, BMC Genomics 2020;21(13):867. [**[Download]**](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-020-07238-x "Click") 

6. **[GNMFLMI]** Wang MN, You ZH, Li LP et al. GNMFLMI: Graph Regularized Nonnegative Matrix Factorization for Predicting LncRNA-MiRNA Interactions, IEEE Access 2020;8:37578-37588. [**[Download]**](https://ieeexplore.ieee.org/abstract/document/9001074 "Click") [**[Code]**](https://github.com/haichengyi/GNMFLMI "Click") 

7. **[LMFNRLMI]** Liu H, Ren G, Chen H et al. Predicting lncRNA–miRNA interactions based on logistic matrix factorization with neighborhood regularized, Knowledge-Based Systems 2020;191:105261. [**[Download]**](https://www.sciencedirect.com/science/article/pii/S0950705119305684 "Click") 

8. **[LMI-DForest]** Wang W, Guan X, Khan MT et al. LMI-DForest: A deep forest model towards the prediction of lncRNA-miRNA interactions, Computational Biology and Chemistry 2020;89:107406. [**[Download]**](https://www.sciencedirect.com/science/article/pii/S1476927120308021 "Click") 

9. **[SNFHGILMI]** Fan Y, Cui J, Zhu Q. Heterogeneous graph inference based on similarity network fusion for predicting lncRNA–miRNA interaction, RSC advances 2020;10(20):11634-11642. [**[Download]**](https://pubs.rsc.org/en/content/articlehtml/2020/ra/c9ra11043g "Click") [**[Code]**](https://github.com/cj-DaSE/SNFHGILMI-master "Click") 

10. **[LMI-INGI]** Zhang L, Liu T, Chen H et al. Predicting lncRNA–miRNA interactions based on interactome network and graphlet interaction, Genomics 2021;113(3):874-880. [**[Download]**](https://www.sciencedirect.com/science/article/pii/S0888754321000537 "Click") [**[Code]**](https://github.com/Liu-Lab-Lnu/LMI-INGI "Click") 

11. **[NDALMA]** Zhang L, Yang P, Feng H et al. Using Network Distance Analysis to Predict lncRNA–miRNA Interactions, Interdisciplinary Sciences: Computational Life Sciences 2021;13(3):535-545. [**[Download]**](https://link.springer.com/article/10.1007/s12539-021-00458-z "Click") [**[Code]**](https://github.com/Liu-Lab-Lnu/NDALMA "Click") 

### Sequence-based methods
1. **[LncMirNet]** Yang S, Wang Y, Lin Y et al. LncMirNet: Predicting LncRNA–miRNA Interaction Based on Deep Learning of Ribonucleic Acid Sequences, Molecules 2020;25(19):4372. [**[Download]**](https://www.mdpi.com/1420-3049/25/19/4372 "Click") [**[Code]**](https://github.com/abcair/LncMirNet "Click") 

2. **[CIRNN]** Zhang P, Meng J, Luan Y et al. Plant miRNA–lncRNA Interaction Prediction with the Ensemble of CNN and IndRNN, Interdisciplinary Sciences: Computational Life Sciences 2020;12(1):82-89. [**[Download]**](https://link.springer.com/article/10.1007/s12539-019-00351-w "Click") 

3. **[PmliPred]** Kang Q, Meng J, Cui J et al. PmliPred: a method based on hybrid model and fuzzy decision for plant miRNA–lncRNA interaction prediction, Bioinformatics 2020;36(10):2986-2992. [**[Download]**](https://academic.oup.com/bioinformatics/article/36/10/2986/5728636?login=false "Click") [**[Code]**](https://github.com/kangzhai/PmliPred "Click") 

4. **[PmliPEMG]** Kang Q, Meng J, Shi W et al. Ensemble Deep Learning Based on Multi-level Information Enhancement and Greedy Fuzzy Decision for Plant miRNA–lncRNA Interaction Prediction, Interdisciplinary Sciences: Computational Life Sciences 2021;13(4):603-614. [**[Download]**](https://link.springer.com/article/10.1007/s12539-021-00434-7 "Click") [**[Code]**](https://github.com/kangzhai/PmliPEMG "Click")

5. **[Kang’s method]** Kang Q, Meng J, Su C et al. Mining plant endogenous target mimics from miRNA–lncRNA interactions based on dual-path parallel ensemble pruning method, Briefings in Bioinformatics 2021;23(1). [**[Download]**](https://academic.oup.com/bib/article-abstract/23/1/bbab440/6399881?login=false "Click") [**[Code]**](https://github.com/kangzhai/DPEP "Click")

6. **[MD-MLI]** Song J, Tian S, Yu L et al. MD-MLI: Prediction of miRNA–lncRNA Interaction by Using Multiple Features and Hierarchical Deep Learning, IEEE/ACM Transactions on Computational Biology and Bioinformatics 2022;19(3):1724-1733. [**[Download]**](https://ieeexplore.ieee.org/abstract/document/9246277 "Click") 

7. **[preMLI]** Yu X, Jiang L, Jin S et al. preMLI: a pre-trained method to uncover microRNA–lncRNA potential interactions, Briefings in Bioinformatics 2021;23(1). [**[Download]**](https://academic.oup.com/bib/article-abstract/23/1/bbab470/6446267?login=false "Click") [**[Code]**](https://github.com/BioSequenceAnalysis/preMLI "Click")

## A Summary of Methodology Details for predicting lncRNA-miRNA interactions
| Methods  |Data types |Description | Code | 
|:----------------:|:--------------------------------:|:----------------------------------------------: |:-----------------:|
|EPLMI | lncRNA-miRNA interaction, lncRNA/miRNA expression profile, lncRNA/miRNA sequence, lncRNA putative functional annotations, miRNAs-target genes interaction| A graph-based method based on two-way diffusion that uses expression profile similarity, sequence similarity, and functional similarity of lncRNA and miRNA| https://github.com/TYLH/EPLMI|
|GCLMI |same as EPLMI |An end---to-end prediction model using graph convolution autoencoder to infer lncRNA-miRNA interactions | NA|
| LNRLMI|same as EPLMI |An approach based on linear neighbor representation for prediction, which uses known interaction and expression profile similarity to construct a bipartite network |NA |
|LMNLMI |same as EPLMI |A framework based on network fusion technique and matrix completion technique for predicting interaction |NA |
|GEEL-PI, GEEL-FI |lncRNA-miRNA interaction, lncRNA/miRNA sequence |A computational method based on graph embedding learning and ensemble learning  | NA|
| GNMFLMI|lncRNA-miRNA interaction, lncRNA/miRNA expression profile | A graph regularized nonnegative matrix factorization for inferring interactions|https://github.com/haichengyi/GNMFLMI |
|LMFNRLMI |same as EPLMI | A method based on logistic matrix factorization with neighborhood regularized for discovering interactions|NA |
|LMI-DForest |lncRNA-miRNA interaction, lncRNA/miRNA expression profile |A machine learning approach that combines deep forest and autoencoder |NA |
|SNFHGILMI |lncRNA-miRNA interaction, lncRNA/miRNA expression profile |A heterogeneous graph inference method based on similarity network fusion to predict interactions |https://github.com/cj-DaSE/SNFHGILMI-master |
| LMI-INGI|same as EPLMI |A semi-supervised approach based on interactome work and graphlet interaction for prediction | https://github.com/Liu-Lab-Lnu/LMI-INGI|
|NDALMA |lncRNA-miRNA interaction, lncRNA/miRNA sequence | A model based on network distance analysis that integrates sequence similarity and GIPK similarity of lncRNA and miRNA|https://github.com/Liu-Lab-Lnu/NDALMA |
|LncMirNet |lncRNA-miRNA interaction, lncRNA/miRNA sequence | A method based on CNN, which uses lncRNA and miRNA sequence features, including k-mer, CTD, Doc2vec, and Role2vec features|https://github.com/abcair/LncMirNet |
|CIRNN |plant lncRNA-miRNA interaction, plant lncRNA and miRNA sequence |An ensemble deep-learning model based on CNN and IndRNN, which adopts plant lncRNA and miRNA sequence | NA|
| PmliPred|same as CIRNN |A framework based on deep learning model (CNN and BiGRU) and shallow machine learning model (RF) that uses sequence features and manually extracted features, involving k-mer frequency, GC content, number of base pairs, and minimum free energy. The hybridized based on fuzzy decision for prediction |https://github.com/kangzhai/PmliPred |
|PmliPEMG | same as CIRNN| An ensemble deep learning model based on multi-level information enhancement (CNN and LSTM with attention mechanism) and greedy fuzzy decision for plant lncRNA-miRNA interaction prediction|https://github.com/kangzhai/PmliPEMG |
|Kang’s method |same as CIRNN |An adaptively prunes the base models based on dual-path parallel ensemble method to meet the challenge of cross-species prediction. it uses PmliPEMG as the base model |https://github.com/kangzhai/DPEP |
|MD-MLI | same as CIRNN|A hierarchical deep learning framework that integrates capsule network, an IndRNN with attention mechanism and Bi-LSTM |NA |
|preMLI | same as CIRNN|A model based on rna2vec pre-training and deep feature mining mechanism (CNN, BI-GRU, and attention layer) |(https://github.com/BioSequenceAnalysis/preMLI) |

## Welcome to contribute
```
@article{SN_LMI,
  title={Databases, tools, and computational methods for lncRNA-miRNA interaction prediction: a survey},
  author={Nan Sheng, Lan Huang, Ling Gao, Xuping Xie, Yangkun Cao, Yan Wang},
  journal={Genomics, Proteomics & Bioinformatics (Awaiting submissions)},
  year={2022},
  publisher={ELSEVIER}
}
```
If you would like to help contribute this list, please feel free to contact me by email:

* Email: shengnan21@mails.jlu.edu.cn
