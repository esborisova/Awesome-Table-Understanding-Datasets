# Awesome Table Understanding Datasets <img src="icon.png" alt="drawing" width="60"/>
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) <a><img src='https://img.shields.io/badge/PRs-welcome-lightgreen'></a>

A curated list of datasets for table understanding tasks. Note that some of the datasets only provide metadata and annotations, but not the source files. Also, several datasets have download links that are no longer active. Since this issue may be fixed by the authors in the future, such data is still included in the list.

The repository will be continuously updated ✏️. If you find this resource useful for your research, just click the ⭐️ and stay tuned!


| Dataset     | Source             | Task(s)           | Size          | Modality| Origin  |
|-------------|--------------------|-------------------|---------------|---------|---------|
|PubTables-1M <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2110.00061'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/bsmock/pubtables-1m'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li></ul>|<ul><li>Table detection</li><li>Table structure recognition</li><li>Functional analysis</li></ul>|947.64K tables|Image|Real world|             
|SciGen <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2104.08296'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/UKPLab/SciGen/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table-to-text generation</li></ul>|1.3K tables|Text|Real world|  
|ComTQA <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2406.01326'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/ByteDance/ComTQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li><li>Financial reports of S&P 500 companies</li></ul>|<ul><li>Visual Question answering</li></ul>|1.5K tables|Image|Real world| 
|DocGenom <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2406.11633'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/UniModal4Reasoning/DocGenome/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table-to-LaTeX generation</li></ul>|3K tables|Image|Real world|
|numericNLG <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.acl-long.115.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/kasnerz/numericnlg?row=0'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from ACL Anthology</li></ul>|<ul><li>Text-to-table generation</li></ul>|1.3K tables|Text|Real world| 
|SEM-TAB-FACTS <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.semeval-1.39.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://sites.google.com/view/sem-tab-facts'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from Elsevier</li></ul>|<ul><li>Statement fact verification</li><li>Cell evidence selection</li></ul>|3K tables|Text|Real world|
|TAT-QA <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.acl-long.254.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://nextplusplus.github.io/TAT-QA/'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Annual reports</li></ul>|<ul><li>Question answering</li></ul>|2K hybrid contexts (tables and text)|Text|Real world|
|WikiBio <img src='https://img.shields.io/badge/ACL-2016-red'> <a href='https://aclanthology.org/D16-1128.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/michaelauli/wiki_bio'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Biography generation</li></ul>|728.32K biographies|Text|Real world|
|ToTTo <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.emnlp-main.89.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/google-research-datasets/ToTTo'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Table-to-text</li></ul>|120K tables|Text|Real world|
|TabFact <img src='https://img.shields.io/badge/arXiv-2020-darkred'> <a href='https://arxiv.org/pdf/1909.02164'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://tabfact.github.io'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Fact-checking</li></ul>|16K tables|Text|Real world|
|TableBench <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/pdf/2408.09174'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Multilingual-Multimodal-NLP/TableBench?row=0'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|886 tables|Text|Real world|
|TableInstruct <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/pdf/2408.09174'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Multilingual-Multimodal-NLP/TableInstruct'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|20K tables|Text|Real world|
|FinQA <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.emnlp-main.300.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/czyssrs/FinQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|8K tables|Text|Real world|
|LogicNLG <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.acl-main.708.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/LogicNLG'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Logical natural language generation</li></ul>|7.3K tables|Text|Real world|
|TabIS <img src='https://img.shields.io/badge/ACL-2024-red'> <a href='https://aclanthology.org/2024.findings-acl.82.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/coszero/TabIS'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Statistical reports from Statistics Canada and National Science Foundation</ul>|<ul><li>Information seeking from tables</li></ul>|61K tables|Text|Real world|
|DataBench <img src='https://img.shields.io/badge/LREC-2024-purple'> <a href='https://aclanthology.org/2024.lrec-main.1179.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/cardiffnlp/databench'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Forbes</li><li>Kaggle</li><li>Graphext</li><li>City of New York</li><li>US Gov</li><li>Inside Airbnb</li><li>Data World</li><li>AEMET</li><li>INE</li><li>TrustPilot </li><li>World Happiness</li><li>Brown University</li><li>US Census</li><li>X</li><li>SBA</li><li>Spotify</li><li>BigQuery</li><li>CIS</li><li>Brandwatch</li><li>DataMarket</li><li>UCI ML</li><li>[Kern et al, PNAS’20](https://github.com/behavioral-ds/VocationMap)</li></ul>|<ul><li>Question answering</li></ul>|56K tables|Text|Real world|
|GitTables <img src='https://img.shields.io/badge/ACM-2023-darkblue'> <a href='https://dl.acm.org/doi/10.1145/3588710'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://gittables.github.io'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>GitHub</li></ul>|<ul><li>Semantic column type detection</li><li>Schema compilation</li></ul>|1M tables|Text|Real world| 
|AxCell: Segmented Tables <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.emnlp-main.692.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/paperswithcode/axcell'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table segmentation</li><li>Table type classification</li></ul>|1.9K tables|Text|Real world|
|WDC Web Table Corpus 2012 <a href='http://webdatacommons.org/webtables/#results-2012'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Data search</li><li>Table extension/completion</li><li>Knowledge base construction</li><li>Table matching</li><li>NLP tasks</li></ul>|147M tables|Text|Real world|
|WDC Web Table Corpus 2015 <a href='http://webdatacommons.org/webtables/#results-2015'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Data search</li><li>Table extension/completion</li><li>Knowledge base construction</li><li>Table matching</li><li>NLP tasks</li></ul>|233M tables|Text|Real world|
|T2D <img src='https://img.shields.io/badge/ACM-2015-darkblue'> <a href='https://dl.acm.org/doi/10.1145/2797115.2797118'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='http://webdatacommons.org/webtables/goldstandard.html#toc5'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Matching web tables to DBpedia</li></ul>|1.7K tables|Text|Real world|
|T2Dv2 <img src='https://img.shields.io/badge/EDBT-2017-lightpink'> <a href='https://openproceedings.org/2017/conf/edbt/paper-148.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://webdatacommons.org/webtables/goldstandardV2.html'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Matching web tables to DBpedia</li></ul>|779 tables|Text|Real world|
|WikiTables <img src='https://img.shields.io/badge/ISWC-2015-darkblue'> <a href='https://link.springer.com/chapter/10.1007/978-3-319-25007-6_25#citeas'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='http://websail-fe.cs.northwestern.edu/TabEL/'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Entity linking</li></ul>|1.6M tables|Text|Real world|
|WikiTableQuestions <img src='https://img.shields.io/badge/arXiv-2015-darkred'> <a href='https://arxiv.org/pdf/1508.00305'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/ppasupat/WikiTableQuestions'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|2.1K tables|Text|Real world|
|WikiSQL <img src='https://img.shields.io/badge/arXiv-2017-darkred'> <a href='https://arxiv.org/pdf/1709.00103'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/salesforce/WikiSQL'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Text-to-SQL/Question answering</li></ul>|24.2K tables|Text|Real world|
|Spider 1.0 <img src='https://img.shields.io/badge/ACL-2018-red'> <a href='https://aclanthology.org/D18-1425.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://yale-lily.github.io/spider'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>College database courses<li>DatabaseAnswers</li><li>Wikipedia</li></ul>|<ul><li>Text-to-SQL/Question answering</li></ul>|N/A|Text|Real world|
|OTT-QA <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/pdf/2010.10439'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/OTT-QA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|400K tables|Text|Real world|
|HybridQA <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.findings-emnlp.91.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/HybridQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|13K tables|Text|Real world|





# Contributing 


Feel free to create a pull request if you would like to add other awesome datasets.

