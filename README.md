# Awesome Table Understanding Datasets <img src="icon.png" alt="drawing" width="60"/>
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) <a><img src='https://img.shields.io/badge/PRs-welcome-lightgreen'></a>

A curated list of datasets which can be either directly used or adopted for various table understanding tasks. 

Note that some of the datasets only provide metadata and annotations, but not the source files. Also, several datasets have download links that are no longer active. Since this issue may be fixed by the authors in the future, such data is still included in the list.

The repository will be continuously updated ✏️. If you find this resource useful for your research, just ⭐️ it and stay tuned!


| Dataset     | Source             | Task(s)           | Size          | Modality|
|-------------|--------------------|-------------------|---------------|---------|
|PubTables-1M <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2110.00061'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/bsmock/pubtables-1m'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li></ul>|<ul><li>Table detection</li><li>Table structure recognition</li><li>Functional analysis</li></ul>|947.64K tables|Image|           
|SciGen <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2104.08296'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/UKPLab/SciGen/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table-to-text generation</li></ul>|1.3K table-text description pairs|Text|
|ComTQA <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2406.01326'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/ByteDance/ComTQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li><li>Financial reports of S&P 500 companies</li></ul>|<ul><li>Visual question answering</li></ul>|1.5K tables and 9K QA pairs|Image| 
|DocGenom <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2406.11633'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/UniModal4Reasoning/DocGenome/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table-to-LaTeX generation</li></ul>|3K table-LaTeX pairs|Image|
|numericNLG <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.acl-long.115.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/kasnerz/numericnlg?row=0'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from ACL Anthology</li></ul>|<ul><li>Text-to-table generation</li></ul>|1.3K text-table pairs|Text| 
|SEM-TAB-FACTS <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.semeval-1.39/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://sites.google.com/view/sem-tab-facts'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from Elsevier</li></ul>|<ul><li>Statement fact verification</li><li>Cell evidence selection</li></ul>|3K tables|Text|
|TAT-QA <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.acl-long.254/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://nextplusplus.github.io/TAT-QA/'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Annual reports</li></ul>|<ul><li>Question answering</li></ul>|2K hybrid contexts (tables and text) and 16.5K QA pairs|Text|
|WikiBio <img src='https://img.shields.io/badge/ACL-2016-red'> <a href='https://aclanthology.org/D16-1128/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/michaelauli/wiki_bio'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Biography generation</li></ul>|728.32K biographies|Text|
|ToTTo <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.emnlp-main.89/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/google-research-datasets/ToTTo'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Table-to-text</li></ul>|120K table-text pairs|Text|
|TabFact <img src='https://img.shields.io/badge/arXiv-2020-darkred'> <a href='https://arxiv.org/abs/1909.02164'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://tabfact.github.io'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Fact-checking</li></ul>|16K tables and 118K statements|Text|
|TableBench <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2408.09174'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Multilingual-Multimodal-NLP/TableBench?row=0'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|3.6K tables and 886 QA pairs|Text|
|TableInstruct <img src='https://img.shields.io/badge/arXiv-2024-darkred'> <a href='https://arxiv.org/abs/2408.09174'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Multilingual-Multimodal-NLP/TableInstruct'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|3.6K tables and 20K QA pairs|Text|
|FinQA <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.emnlp-main.300/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/czyssrs/FinQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Question answering</li></ul>|8.2K QA pairs|Text|Real world|
|LogicNLG <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.acl-main.708/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/LogicNLG'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Logical natural language generation</li></ul>|7.3K tables|Text|
|TabIS <img src='https://img.shields.io/badge/ACL-2024-red'> <a href='https://aclanthology.org/2024.findings-acl.82.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/coszero/TabIS'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Statistical reports from Statistics Canada and National Science Foundation</ul>|<ul><li>Information seeking from tables</li></ul>|61K tables|Text|
|DataBench <img src='https://img.shields.io/badge/ELRA-2024-purple'> <a href='https://aclanthology.org/2024.lrec-main.1179/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/cardiffnlp/databench'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Forbes</li><li>Kaggle</li><li>Graphext</li><li>City of New York</li><li>US Gov</li><li>Inside Airbnb</li><li>Data World</li><li>AEMET</li><li>INE</li><li>TrustPilot </li><li>World Happiness</li><li>Brown University</li><li>US Census</li><li>X</li><li>SBA</li><li>Spotify</li><li>BigQuery</li><li>CIS</li><li>Brandwatch</li><li>DataMarket</li><li>UCI ML</li><li>[Kern et al, PNAS’20](https://github.com/behavioral-ds/VocationMap)</li></ul>|<ul><li>Question answering</li></ul>|56K tables|Text|
|GitTables <img src='https://img.shields.io/badge/ACM-2023-darkblue'> <a href='https://dl.acm.org/doi/10.1145/3588710'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://gittables.github.io'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>GitHub</li></ul>|<ul><li>Semantic column type detection</li><li>Schema compilation</li></ul>|1M tables|Text|
|AxCell: Segmented Tables <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.emnlp-main.692/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/paperswithcode/axcell'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</li></ul>|<ul><li>Table segmentation</li><li>Table type classification</li></ul>|1.9K tables|Text|
|WDC Web Table Corpus 2012 <a href='http://webdatacommons.org/webtables/#results-2012'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Data search</li><li>Table extension/completion</li><li>Knowledge base construction</li><li>Table matching</li><li>NLP tasks</li></ul>|147M tables|Text|
|WDC Web Table Corpus 2015 <a href='http://webdatacommons.org/webtables/#results-2015'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Data search</li><li>Table extension/completion</li><li>Knowledge base construction</li><li>Table matching</li><li>NLP tasks</li></ul>|233M tables|Text|
|T2D <img src='https://img.shields.io/badge/ACM-2015-darkblue'> <a href='https://dl.acm.org/doi/10.1145/2797115.2797118'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='http://webdatacommons.org/webtables/goldstandard.html#toc5'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Matching web tables to DBpedia</li></ul>|1.7K tables|Text|
|T2Dv2 <img src='https://img.shields.io/badge/EDBT-2017-lightpink'> <a href='https://openproceedings.org/2017/conf/edbt/paper-148.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://webdatacommons.org/webtables/goldstandardV2.html'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Common Crawl</li></ul>|<ul><li>Matching web tables to DBpedia</li></ul>|779 tables|Text|
|WikiTables <img src='https://img.shields.io/badge/ISWC-2015-darkblue'> <a href='https://link.springer.com/chapter/10.1007/978-3-319-25007-6_25#citeas'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='http://websail-fe.cs.northwestern.edu/TabEL/'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Entity linking</li></ul>|1.6M tables|Text|
|WikiTableQuestions <img src='https://img.shields.io/badge/ACL-2015-red'> <a href='https://aclanthology.org/P15-1142/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/ppasupat/WikiTableQuestions'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|2.1K tables and 22K QA pairs|Text|
|WikiSQL <img src='https://img.shields.io/badge/arXiv-2017-darkred'> <a href='https://arxiv.org/abs/1709.00103'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/salesforce/WikiSQL'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Text-to-SQL/Question answering</li></ul>|24.2K tables|Text|
|Spider 1.0 <img src='https://img.shields.io/badge/ACL-2018-red'> <a href='https://aclanthology.org/D18-1425/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://yale-lily.github.io/spider'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>College database courses<li>DatabaseAnswers</li><li>Wikipedia</li></ul>|<ul><li>Text-to-SQL/Question answering</li></ul>|N/A|Text|
|OTT-QA <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2010.10439'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/OTT-QA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|400K tables|Text|
|HybridQA <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.findings-emnlp.91/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wenhuchen/HybridQA'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Question answering</li></ul>|13K tables and 70K QA pairs|Text|
|FEVEROUS <img src='https://img.shields.io/badge/ACL-2021-red'> <a href='https://aclanthology.org/2021.fever-1.1/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://fever.ai/dataset/feverous.html'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Fact extraction and verification</li></ul>|87K claims|Text|
|TableBank <img src='https://img.shields.io/badge/ELRA-2020-purple'> <a href='https://aclanthology.org/2020.lrec-1.236/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/liminghao1630/TableBank'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Word documents from the internet</li><li>LaTex documents from arXiv</li></ul>|<ul><li>Table detection and recognition</li></ul>|417K tables|Image|
|PubTabNet <img src='https://img.shields.io/badge/arXiv-2020-darkred'> <a href='https://arxiv.org/abs/1911.10683'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/ibm-aur-nlp/PubTabNet'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li></ul>|<ul><li>Table detection and recognition</li></ul>|568K tables|Image|
|PubLayNet <img src='https://img.shields.io/badge/arXiv-2020-darkred'> <a href='https://arxiv.org/abs/1908.07836'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/ibm-aur-nlp/PubLayNet'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from PubMed</li></ul>|<ul><li>Document layout recognition</li></ul>|94K pages with tables and 113K tables|Image|
|FinTabNet <img src='https://img.shields.io/badge/WACV-2021-pink'> <a href='https://www.computer.org/csdl/proceedings-article/wacv/2021/047700a697/1uqGJGAB5EA'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://developer.ibm.com/data/fintabnet/#use-the-dataset4'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Earnings reports of S&P 500 companies</li></ul>|<ul><li>Table structure recognition</li></ul>|89K pages and 112.8K tables|Image|
|WTW <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2109.02199'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/wangwen-whu/wtw-dataset'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Images from natural scenes</li><li>Archival document images</li><li>Printed document images</li></ul>|<ul><li>Table structure recognition</li></ul>|14.5K tables|Image|Real world|
|SciTSR <img src='https://img.shields.io/badge/arXiv-2019-darkred'> <a href='https://arxiv.org/abs/1908.04729'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/Academic-Hammer/SciTSR?tab=readme-ov-file'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv</ul>|<ul><li>Table structure recognition</li></ul>|15K tables|Image|
|TNCR <img src='https://img.shields.io/badge/Neurocomputing-2022-pink'> <a href='https://dl.acm.org/doi/abs/10.1016/j.neucom.2021.11.101'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/abdoelsayed2016/TNCR_Dataset'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Web</ul>|<ul><li>Table detection</li><li>Table classification</li></ul>|6.6K images and 9.4K tables|Image|
|DeepFigures <img src='https://img.shields.io/badge/arXiv-2018-darkred'> <a href='https://arxiv.org/abs/1804.02445'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/allenai/deepfigures-open?tab=readme-ov-file'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from arXiv and PubMed</ul>|<ul><li>Table extraction</li></ul>|1.4M tables|Text|
|WikiTableSet <img src='https://img.shields.io/badge/arXiv-2023-darkred'> <a href='https://arxiv.org/abs/2303.07641'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/namtuanly/WikiTableSet'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Table recognition</li></ul>|5M tables|Image|
|Tab2Know <img src='https://img.shields.io/badge/arXiv-2021-darkred'> <a href='https://arxiv.org/abs/2107.13306'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://zenodo.org/records/3983013'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Scholary papers from AAAI, ACL, Artif. Intell., arXiv, CIKM, COLING, CoNLL, EACL, ECAI, EMNLP, HLT-NAACL, IJCAI, ISWC, NeurIPS, NIPS, PVLDB, VLDB, and WWW </ul>|<ul><li>Table-to-knowledge base</li></ul>|73k tables|Image and text|
|Logic2Text <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.findings-emnlp.190/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/czyssrs/Logic2Text'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Natural language generation</li></ul>|5.6K tables and 10.8k (logical form, description) pairs|Text|
|SQA <img src='https://img.shields.io/badge/ACL-2017-red'> <a href='https://aclanthology.org/P17-1167//'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://www.microsoft.com/en-us/download/details.aspx?id=54253'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Question answering</li></ul>|17.5K QA pairs|Text|
|FeTaQA  <img src='https://img.shields.io/badge/ACL-2022-red'> <a href='https://aclanthology.org/2022.tacl-1.3/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/Yale-LILY/FeTaQA/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Question answering</li></ul>|10.3K (table, question, answer, table cells) pairs|Text|
|ICDAR 2019 cTDaR <img src='https://img.shields.io/badge/ICDAR-2019-pink'> <a href='https://ieeexplore.ieee.org/document/8978120'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/cndplab-founder/ICDAR2019_cTDaR/tree/master'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Modern and archival documents</ul>|<ul><li>Table detection</li></ul>|N/A|Image|
|SportsTables <img src='https://img.shields.io/badge/Datenbank Spektrum-2023-pink'> <a href='https://link.springer.com/article/10.1007/s13222-023-00457-y'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/DHBWMosbachWI/SportsTables'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Web</ul>|<ul><li>Semantic type detection</li></ul>|1.1K tables|Text|
|SemTab2019 <img src='https://img.shields.io/badge/ESWC-2020-darkblue'> <a href='https://link.springer.com/chapter/10.1007/978-3-030-49461-2_30#citeas'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://zenodo.org/records/3518539'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>T2Dv2</li><li>Wikipedia</li><li>Syntheticly generated tables</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|14.9K tables|Text|
|Tough Tables (2T) <img src='https://img.shields.io/badge/ISWC-2020-darkblue'> <a href='https://link.springer.com/chapter/10.1007/978-3-030-62466-8_21'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://zenodo.org/records/7419275'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Web</li><li>Syntheticly generated tables</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|180 tables|Text|
|SemTab2020 <a href='https://www.cs.ox.ac.uk/isg/challenges/sem-tab/2020/index.html'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Tough Tables</li><li>Syntheticly generated tables</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|131.4K tables|Text|
|HardTables <a href='https://zenodo.org/records/6154708'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>N/A</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|N/A|Text|
|BiodivTab <a href='https://zenodo.org/records/5584180'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>BExIS6</li><li>BEFChina</li><li>data.world</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|N/A|Text|
|BioTable <a href='https://zenodo.org/records/5606585'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>N/A</li></ul>|<ul><li>Semantic table annotation</li></ul>|N/A|Text|
|SemTab2021 <a href='https://www.cs.ox.ac.uk/isg/challenges/sem-tab/2021/index.html'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>HardTables<li>Tough Tables</li><li>BioTable</li><li>BiodivTab</li><li>GitTables</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|9.1K tables|Text|
|SemTab2022 <a href='https://sem-tab-challenge.github.io/2022/'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>HardTables<li>Tough Tables</li><li>BiodivTab</li><li>GitTables</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|N/A|Text|
|NumDB <img src='https://img.shields.io/badge/EKAW-2018-pink'> <a href='https://link.springer.com/chapter/10.1007/978-3-030-03667-6_11'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://figshare.com/articles/dataset/numdb_0105_zip/6205814/4?file=11283284'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>DBpedia</li></ul>|<ul><li>Semantic labeling</li></ul>|389 tables|Text|
|MammoTab <img src='https://img.shields.io/badge/ISWC-2022-darkblue'> <a href='https://ceur-ws.org/Vol-3320/paper3.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://zenodo.org/records/7014472'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</ul>|<ul><li>Cell/mentions to KG entity matching (CEA)</li><li>Column to KG class matching (CTA)</li></ul>|980K tables|Text|
|SOTAB <img src='https://img.shields.io/badge/ISWC-2022-darkblue'> <a href='https://ceur-ws.org/Vol-3320/paper1.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://webdatacommons.org/structureddata/sotab/#toc8'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Schema.org Table Corpus</ul>|<ul><li>Column type annotation (CTA)</li><li>Column property annotation (CPA)</li></ul>|107K tables|Text|
|Wikary <img src='https://img.shields.io/badge/ISWC-2022-darkblue'> <a href='https://ceur-ws.org/Vol-3320/paper2.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://zenodo.org/records/7025005'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Tabular data to knowledge graph matching</li></ul>|32K tables|Text|
|HiTab <img src='https://img.shields.io/badge/ACL-2022-red'> <a href='https://aclanthology.org/2022.acl-long.78/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/microsoft/HiTab/tree/main'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li><li>Statistical reports from Statistics Canada and National Science Foundation</li></ul>|<ul><li>Question answering</li><li>Table-to-text generation</li></ul>|3.5K tables|Text|
|INFOTABS <img src='https://img.shields.io/badge/ACL-2020-red'> <a href='https://aclanthology.org/2020.acl-main.210/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/infotabs/infotabs'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>Wikipedia</li></ul>|<ul><li>Natural language inference</ul>|2.3K tables and 23.7K premise-hypothesis pairs|Text|
|Rotowire <img src='https://img.shields.io/badge/ACL-2017-red'> <a href='https://aclanthology.org/D17-1239/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/harvardnlp/boxscore-data'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>RotoWire website</li></ul>|<ul><li>Table-to-text generation</ul>|4.8K summaries|Text|
|SBNation <img src='https://img.shields.io/badge/ACL-2017-red'> <a href='https://aclanthology.org/D17-1239/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://github.com/harvardnlp/boxscore-data'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>SBNation website</li></ul>|<ul><li>Table-to-text generation</ul>|10.9K summaries|Text|
|MMTab <img src='https://img.shields.io/badge/ACL-2024-red'> <a href='https://aclanthology.org/2024.acl-long.493/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/SpursgoZmy/MMTab'><img src='https://img.shields.io/badge/Dataset-lightgreen'></a>|<ul><li>WTQ</li><li>FeTaQA</li><li>HiTab</li><li>AIT-QA</li><li>TabMCQ</li><li>TABMWP</li><li>TAT-QA</li><li>TabFact</li><li>InfoTabs</li><li>PubHealthTab</li><li>ToTTo</li><li>HiTab_T2T</li><li>Rotowire </li><li>WikiBIO</li><li>TSU</li></ul>|<ul><li>Question answering</li><li>Fact verification</li><li>Table-to-text generation</li><li>Table structure understanding</li><li>Table recognition</li></ul>|202K tables|Image|

 





# 🛠️ Contributing 

Feel free to create a pull request or to open an issue if you would like to add other awesome datasets.

