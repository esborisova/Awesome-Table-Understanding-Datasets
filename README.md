# Awesome Table Understanding Datasets <img src="icon.png" alt="drawing" width="60"/>
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) <a><img src='https://img.shields.io/badge/PRs-welcome-lightgreen'></a>

A curated list of datasets which can be either directly used or adopted for various table understanding tasks. 

Note that some of the datasets only provide metadata and annotations, but not the source files. Also, several datasets have download links that are no longer active. Since this issue may be fixed by the authors in the future, such data is still included in the list.

The repository will be continuously updated ✏️. If you find this resource useful for your research, just ⭐️ it and stay tuned!


| Dataset     | Source             | Task(s)           | Size          | Modality| Origin  |
|-------------|--------------------|-------------------|---------------|---------|---------|
|PubTables-1M <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2110.00061'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/bsmock/pubtables-1m'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li></ul>|<ul><li>Table detection</li><li>Table structure recognition</li><li>Functional analysis</li></ul>|947.64K tables|Image|Real world|             
|SciGen <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2104.08296'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/UKPLab/SciGen/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table-to-text generation</li></ul>|1.3K table-text description pairs|Text|Real world|  
|ComTQA <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2406.01326'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/ByteDance/ComTQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li><li>Financial reports of S&P 500 companies</li></ul>|<ul><li>Visual question answering</li></ul>|1.5K tables and 9K QA pairs|Image|Real world| 
|DocGenom <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2406.11633'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/UniModal4Reasoning/DocGenome/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table-to-LaTeX generation</li></ul>|3K table-LaTeX pairs|Image|Real world|
|numericNLG <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.acl-long.115.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/kasnerz/numericnlg?row=0'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from ACL Anthology</li></ul>|<ul><li>Text-to-table generation</li></ul>|1.3K text-table pairs|Text|Real world| 
|SEM-TAB-FACTS <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.semeval-1.39/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://sites.google.com/view/sem-tab-facts'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from Elsevier</li></ul>|<ul><li>Statement fact verification</li><li>Cell evidence selection</li></ul>|3K tables|Text|Real world|
|TAT-QA <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.acl-long.254/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://nextplusplus.github.io/TAT-QA/'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Annual reports</li></ul>|<ul><li>Question answering</li></ul>|2K hybrid contexts (tables and text) and 16.5K QA pairs|Text|Real world|
|WikiBio <img src='https://img.shields.io/badge/ACL-2016-red'> <a href='https://aclanthology.org/D16-1128/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/michaelauli/wiki_bio'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Biography generation</li></ul>|728.32K biographies|Text|Real world|
|ToTTo <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.emnlp-main.89/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/google-research-datasets/ToTTo'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Table-to-text</li></ul>|120K table-text pairs|Text|Real world|
|TabFact <img src='https://img.shields.io/badge/arXiv-2020-darkred'> <a href='https://arxiv.org/abs/1909.02164'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://tabfact.github.io'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Fact-checking</li></ul>|16K tables and 118K statements|Text|Real world|
|TableBench <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2408.09174'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Multilingual-Multimodal-NLP/TableBench?row=0'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|3.6K tables and 886 QA pairs|Text|Real world|
|TableInstruct <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2408.09174'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Multilingual-Multimodal-NLP/TableInstruct'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|3.6K tables and 20K QA pairs|Text|Real world|
|FinQA <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.emnlp-main.300/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/czyssrs/FinQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|8.2K QA pairs|Text|Real world|
|LogicNLG <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.acl-main.708/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/LogicNLG'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Logical natural language generation</li></ul>|7.3K tables|Text|Real world|
|TabIS <img src='https://img.shields.io/badge/ACL-2024-red'> <a href='https://aclanthology.org/2024.findings-acl.82.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/coszero/TabIS'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Statistical reports from Statistics Canada and National Science Foundation</ul>|<ul><li>Information seeking from tables</li></ul>|61K tables|Text|Real world|
|DataBench <img src='https://img.shields.io/badge/ELRA-2024-purple'> <a href='https://aclanthology.org/2024.lrec-main.1179/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/cardiffnlp/databench'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Forbes</li><li>Kaggle</li><li>Graphext</li><li>City of New York</li><li>US Gov</li><li>Inside Airbnb</li><li>Data World</li><li>AEMET</li><li>INE</li><li>TrustPilot </li><li>World Happiness</li><li>Brown University</li><li>US Census</li><li>X</li><li>SBA</li><li>Spotify</li><li>BigQuery</li><li>CIS</li><li>Brandwatch</li><li>DataMarket</li><li>UCI ML</li><li>[Kern et al, PNAS’20](https://github.com/behavioral-ds/VocationMap)</li></ul>|<ul><li>Question answering</li></ul>|56K tables|Text|Real world|
|GitTables <img src='https://img.shields.io/badge/ACM-2023-darkblue'> <a href='https://dl.acm.org/doi/10.1145/3588710'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://gittables.github.io'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>GitHub</li></ul>|<ul><li>Semantic column type detection</li><li>Schema compilation</li></ul>|1M tables|Text|Real world| 
|AxCell: Segmented Tables <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.emnlp-main.692/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/paperswithcode/axcell'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table segmentation</li><li>Table type classification</li></ul>|1.9K tables|Text|Real world|
|WDC Web Table Corpus 2012 <a href='http://webdatacommons.org/webtables/#results-2012'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Data search</li><li>Table extension/completion</li><li>Knowledge base construction</li><li>Table matching</li><li>NLP tasks</li></ul>|147M tables|Text|Real world|
|WDC Web Table Corpus 2015 <a href='http://webdatacommons.org/webtables/#results-2015'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Data search</li><li>Table extension/completion</li><li>Knowledge base construction</li><li>Table matching</li><li>NLP tasks</li></ul>|233M tables|Text|Real world|
|T2D <img src='https://img.shields.io/badge/ACM-2015-darkblue'> <a href='https://dl.acm.org/doi/10.1145/2797115.2797118'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='http://webdatacommons.org/webtables/goldstandard.html#toc5'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Matching web tables to DBpedia</li></ul>|1.7K tables|Text|Real world|
|T2Dv2 <img src='https://img.shields.io/badge/EDBT-2017-lightpink'> <a href='https://openproceedings.org/2017/conf/edbt/paper-148.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://webdatacommons.org/webtables/goldstandardV2.html'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Matching web tables to DBpedia</li></ul>|779 tables|Text|Real world|
|WikiTables <img src='https://img.shields.io/badge/ISWC-2015-darkblue'> <a href='https://link.springer.com/chapter/10.1007/978-3-319-25007-6_25#citeas'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='http://websail-fe.cs.northwestern.edu/TabEL/'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Entity linking</li></ul>|1.6M tables|Text|Real world|
|WikiTableQuestions <img src='https://img.shields.io/badge/ACL-2015-red'> <a href='https://aclanthology.org/P15-1142/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/ppasupat/WikiTableQuestions'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|2.1K tables and 22K QA pairs|Text|Real world|
|WikiSQL <img src='https://img.shields.io/badge/arXiv-2017-darkred'> <a href='https://arxiv.org/abs/1709.00103'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/salesforce/WikiSQL'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Text-to-SQL/Question answering</li></ul>|24.2K tables|Text|Real world|
|Spider 1.0 <img src='https://img.shields.io/badge/ACL-2018-red'> <a href='https://aclanthology.org/D18-1425/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://yale-lily.github.io/spider'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>College database courses<li>DatabaseAnswers</li><li>Wikipedia</li></ul>|<ul><li>Text-to-SQL/Question answering</li></ul>|N/A|Text|Real world|
|OTT-QA <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2010.10439'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/OTT-QA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|400K tables|Text|Real world|
|HybridQA <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.findings-emnlp.91/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/HybridQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|13K tables and 70K QA pairs|Text|Real world|
|FEVEROUS <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.fever-1.1/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://fever.ai/dataset/feverous.html'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Fact extraction and verification</li></ul>|87K claims|Text|Real world|
|TableBank <img src='https://img.shields.io/badge/ELRA-2020-purple'> <a href='https://aclanthology.org/2020.lrec-1.236/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/liminghao1630/TableBank'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Word documents from the internet</li><li>LaTex documents from arXiv</li></ul>|<ul><li>Table detection and recognition</li></ul>|417K tables|Image|Real world|
|PubTabNet <img src='https://img.shields.io/badge/arXiv-2020-darkred'> <a href='https://arxiv.org/abs/1911.10683'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/ibm-aur-nlp/PubTabNet'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li></ul>|<ul><li>Table detection and recognition</li></ul>|568K tables|Image|Real world|
|PubLayNet <img src='https://img.shields.io/badge/arXiv-2020-darkred'> <a href='https://arxiv.org/abs/1908.07836'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/ibm-aur-nlp/PubLayNet'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li></ul>|<ul><li>Document layout recognition</li></ul>|94K pages with tables and 113K tables|Image|Real world|
|FinTabNet <img src='https://img.shields.io/badge/WACV-2021-pink'> <a href='https://www.computer.org/csdl/proceedings-article/wacv/2021/047700a697/1uqGJGAB5EA'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://developer.ibm.com/data/fintabnet/#use-the-dataset4'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Table structure recognition</li></ul>|89K pages and 112.8K tables|Image|Real world|
|WTW <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2109.02199'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wangwen-whu/wtw-dataset'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Images from natural scenes</li><li>Archival document images</li><li>Printed document images</li></ul>|<ul><li>Table structure recognition</li></ul>|14.5K tables|Image|Real world|
|SciTSR <img src='https://img.shields.io/badge/arXiv-2019-darkred'> <a href='https://arxiv.org/abs/1908.04729'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/Academic-Hammer/SciTSR?tab=readme-ov-file'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</ul>|<ul><li>Table structure recognition</li></ul>|15K tables|Image|Real world|
|TNCR <img src='https://img.shields.io/badge/Neurocomputing-2022-pink'> <a href='https://dl.acm.org/doi/abs/10.1016/j.neucom.2021.11.101'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/abdoelsayed2016/TNCR_Dataset'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Web</ul>|<ul><li>Table detection</li><li>Table classification</li></ul>|6.6K images and 9.4K tables|Image|Real world|
|DeepFigures <img src='https://img.shields.io/badge/arXiv-2018-darkred'> <a href='https://arxiv.org/abs/1804.02445'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/allenai/deepfigures-open?tab=readme-ov-file'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv and PubMed</ul>|<ul><li>Table extraction</li></ul>|1.4M tables|Text|Real world|
|WikiTableSet <img src='https://img.shields.io/badge/arXiv-2023-darkred'> <a href='https://arxiv.org/abs/2303.07641'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/namtuanly/WikiTableSet'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Table recognition</li></ul>|5M tables|Image|Real world|
|Tab2Know <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2107.13306'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://zenodo.org/records/3983013'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from AAAI, ACL, Artif. Intell., arXiv, CIKM, COLING, CoNLL, EACL, ECAI, EMNLP, HLT-NAACL, IJCAI, ISWC, NeurIPS, NIPS, PVLDB, VLDB, and WWW </ul>|<ul><li>Table-to-knowledge base</li></ul>|73k tables|Image and text|Real world|
|Logic2Text <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.findings-emnlp.190/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/czyssrs/Logic2Text'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Natural language generation</li></ul>|5.6K tables and 10.8k (logical form, description) pairs|Text|Real world|
|SQA <img src='https://img.shields.io/badge/ACL-2017-red'> <a href='https://aclanthology.org/P17-1167//'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://www.microsoft.com/en-us/download/details.aspx?id=54253'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Question answering</li></ul>|17.5K QA pairs|Text|Real world|
|FeTaQA  <img src='https://img.shields.io/badge/ACL-2022-red'> <a href='https://aclanthology.org/2022.tacl-1.3/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/Yale-LILY/FeTaQA/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Question answering</li></ul>|10.3K (table, question, answer, table cells) pairs|Text|Real world|





# Contributing 

Feel free to create a pull request or to open an issue if you would like to add other awesome datasets.

