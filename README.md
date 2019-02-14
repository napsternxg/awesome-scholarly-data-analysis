[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://licensebuttons.net/l/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

# Awesome Scholarly Data Analysis

List of resources on scholarly data analysis ranging from datasets, papers, and code about bibliometrics, citation analysis, and other scholarly commons resources.


# Table of Contents
- [Awesome Scholarly Data Analysis](#awesome-scholarly-data-analysis)
- [Table of Contents](#table-of-contents)
- [Datasets](#datasets)
  * [Publication and Citation](#publication-and-citation)
  * [Academic Genealogy](#academic-genealogy)
  * [Author Profiles](#author-profiles)
  * [Author name disambiguation](#author-name-disambiguation)
  * [Thesis datasets](#thesis-datasets)
  * [Information Extraction and NLP](#information-extraction-and-nlp)
  * [Networks](#networks)
  * [Taxonomies and Ontologies](#taxonomies-and-ontologies)
- [Code](#code)
- [Tools](#tools)
  * [User interface to publication datasets](#user-interface-to-publication-datasets)
  * [Tools for collecting open access papers](#tools-for-collecting-open-access-papers)
  * [Visualizations](#visualizations)
  * [NLP](#nlp)
- [Publication Venues](#publication-venues)
  * [Journals](#journals)
  * [Conferences](#conferences)
  * [Workshops](#workshops)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Datasets

## Publication and Citation
* [Arnet Miner](http://aminer.org/citation)
* [Microsoft Academic Graph](https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/)
* [Open Academic Graph](https://www.openacademic.ai/oag/) - MAG + AMiner
* [Semantic Scholar Corpus](http://labs.semanticscholar.org/corpus/)
* [CiteSeer](http://csxstatic.ist.psu.edu/about/data)
* [PubMed](https://www.ncbi.nlm.nih.gov/pubmed)
* [CORA datasets](https://people.cs.umass.edu/~mccallum/data.html)
* [CrossRef DOI URLs](https://archive.org/details/doi-urls)
* [DBLP Citation dataset](https://kdl.cs.umass.edu/display/public/DBLP)
* [NBER Patent Citations](http://nber.org/patents/)
* [Scopus Citation Database](https://www.elsevier.com/solutions/scopus)
* [Papers, patents, and grants from Indiana University](http://iv.slis.indiana.edu/db/index.html)
* [Small Network Data - Mark Newman's Lab](http://www-personal.umich.edu/~mejn/netdata/)
* [The Koblenz Network Collection](http://konect.uni-koblenz.de/)
* [Google Scholar citation relations](http://www3.cs.stonybrook.edu/~leman/data/gscholar.db)
* [Open citations project](http://opencitations.net/)
* [Wikicite Project](https://meta.wikimedia.org/wiki/WikiCite)
* [Ecnonomic Papers](http://repec.org/)
* [ArXiv data dump](https://arxiv.org/help/bulk_data)
* [Complete ACL anthology as bibtex file](http://aclanthology.info/anthology.bib)
* [ACL Anthology Reference Corpus](http://acl-arc.comp.nus.edu.sg/)
* [Astrophysics data system (ADS) - All physics papers](https://ui.adsabs.harvard.edu/)
* [CORE 37M full text open access papers](https://core.ac.uk/services#dataset)
* [Inspire database for high energy physics articles](http://inspirehep.net/?ln=en)
* [Scholarly Data of workshops and conferences in RDF triplets](http://www.scholarlydata.org/)
* [The Collection of Computer Science Bibliographies](http://liinwww.ira.uka.de/bibliography/)
* [OpenCitations corpus](http://opencitations.net/corpus)
* [COCI Doi-Doi citation data](https://figshare.com/articles/Crossref_Open_Citation_Index_CSV_dataset_of_all_the_citation_data/6741422/2)


## Academic Genealogy
* [Mathematics Genealogy Project](https://genealogy.math.ndsu.nodak.edu/index.php)
* [Academic Tree - Cross discipline academic genealogies](http://academictree.org)
* [MPACT project - Library Sciences](http://www.ibiblio.org/mpact/)
* [PhDTree](http://phdtree.org/)
* [Chemistry Genealogy - curated at UIUC](http://www.scs.illinois.edu/~mainzv/Web_Genealogy/index.php)
* [Notre Dame Genealogy Project](http://library.nd.edu/physics/resources/genealogy/genealogyproject.shtml)
* [UIUC Chemistry, Chemical Engineering, and Biochemistry](http://www.scs.illinois.edu/alumnilist/)
* [Software Engineering Academic Genealogy](http://web.engr.illinois.edu/~taoxie/sefamily.htm)
* [Other lists of genealogy projects](http://libguides.caltech.edu/c.php?g=512661&p=3502496)
* [Wikipedia - Computer Science Genealogy](https://en.wikipedia.org/wiki/Academic_genealogy_of_computer_scientists)
* [Wikipedia - Theorecical Physicits Genealogy](https://en.wikipedia.org/wiki/Academic_genealogy_of_theoretical_physicists)
* [Wikipedia - Chemists Genealogy](https://en.wikipedia.org/wiki/Academic_genealogy_of_chemists)
* [SCIENTIFIC GENEALOGY MASTER LIST - Scientists Associated with Concepts in Chemistry & Physics](http://www.careerchem.com/NAMED/Genealogy-List.pdf)
* [Economic Geneology](http://www-personal.umich.edu/~alandear/tree/INDEX.HTM) [Text Format](http://www-personal.umich.edu/~alandear/tree/Tree-In.txt)


## Author Profiles
* [Temporal profiles of PubMed authors](http://abel.lis.illinois.edu/legolas/)
* [ORCID data dump](https://orcid.org/content/download-file)
* [National Library of Medicine Profiles](https://profiles.nlm.nih.gov/)
* [UIUC Professors database - Publications, Affiliations](https://experts.illinois.edu/)
* [Author Profiles of scholarly authors in Wikipedia](https://tools.wmflabs.org/scholia/)

## Author name disambiguation
* [INSPIRE dataset](https://github.com/glouppe/paper-author-disambiguation)
* [Lee Giles dataset](http://clgiles.ist.psu.edu/data/nameset_author-disamb.tar.zip)
* [Cleaner version of Lee Giles dataset](https://figshare.com/articles/DBLPderived_labeled_data_for_author_name_disambiguation/6840281)
* [DBLP Korean Authors](http://www.lbd.dcc.ufmg.br/lbd/collections/disambiguation/DBLP.tar.gz/at_download/file)
* [Arnet Miner](http://arnetminer.org/lab-datasets/disambiguation/rich-author-disambiguation-data.zip)
* [DBLP Name disambiguation dataset](https://github.com/yaya213/DBLP-Name-Disambiguation-Dataset)
* [rexa-coref-data](https://github.com/tapilab/rexa-coref-data)

## Thesis datasets
* [Open Access Theses and Dissertations](https://oatd.org/)
* [The Networked Digital Library of Theses and Dissertations (NDLTD)](http://www.ndltd.org/)
* [PhD Dissertations in the Area of Software Engineering](http://www.sigsoft.org/dissertations.php)
* [ProQuest Dissertations & Theses Global](http://www.proquest.com/products-services/pqdtglobal.html)

## Information Extraction and NLP
* [Citation Parsing](http://csxstatic.ist.psu.edu/about/scholarly-information-extraction)
* [Document Summarization](https://github.com/WING-NUS/scisumm-corpus)
* [Keyphrase Extraction](https://github.com/snkim/AutomaticKeyphraseExtraction)
* [Related Work Summarization](https://github.com/WING-NUS/RelatedWorkSummarizationDataset)
* [Biomedical NLP annotated datasets](https://www.ncbi.nlm.nih.gov/research/bionlp/Data/)
* [Chemical compound and drug name recognition task](http://www.biocreative.org/tasks/biocreative-iv/chemdner/)
* [Semantic Scholar Dataset](https://allenai.org/data/data-all.html)
* [ScienceIE](https://scienceie.github.io/)
* [ACL RD TEC 2.0](http://pars.ie/lr/acl_rd-tec) also at [@CLARIN](https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-1661)
* [SEPID Corpus - Segmended ACL ARC 1.0](http://pars.ie/lr/sepid-corpus)
* [PubMed Central Open Access - BioC](https://www.ncbi.nlm.nih.gov/research/bionlp/APIs/BioC-PMC/)
* [PubMed Fulltext - protein-protein and genetic interactions](http://bioc.sourceforge.net/BioC-BioGRID.html)
* [BioNLP - Argo](http://argo.nactem.ac.uk/bioc/)
* [Biomedical NLP - Stav](http://corpora.informatik.hu-berlin.de/)
* [Biomedical sentence simplification](https://research.bioinformatics.udel.edu/isimp/corpus.html)
* [PubMed - Colorado Richly Annotated Full-Text](https://github.com/UCDenver-ccp/CRAFT)
* [Biomedical NER datasets](https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data) [related publication](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1776-8)
* [BioVerbNet](https://github.com/cambridgeltl/bio-verbnet)
* [Lunar and Planetary Science abstracts for NER and Relations](https://zenodo.org/record/1048419#.XAW0m2hKh3h)
* [ACM data affiliations](https://dbs.uni-leipzig.de/en/research/projects/bibliometrics)
* [ACM entity resolution](https://dbs.uni-leipzig.de/en/research/projects/object_matching/fever/benchmark_datasets_for_entity_resolution)

## Networks

* [ACL Anthology Network](http://clair.eecs.umich.edu/aan/index.php)

## Taxonomies and Ontologies
* [SciGraph Springer Nature](https://scigraph.springernature.com/explorer/downloads/)
* [Medical Subject Headings](https://meshb.nlm.nih.gov/search)
* [Computer Science Ontology](https://cso.kmi.open.ac.uk/home)
* [Physics Subject Headings](https://physh.aps.org/)
* [Open Biological and Biomedical Ontology (OBO) Foundry](http://obofoundry.org/)


# Code
* [CiteSeer tools](https://github.com/SeerLabs)
* [Novelty quantification in PubMed articles](https://github.com/napsternxg/Novelty)
* [Science-Parse](https://github.com/allenai/science-parse)


# Tools

## User interface to publication datasets

* [Google Scholar](https://scholar.google.com/)
* [Semantic Scholar](https://www.semanticscholar.org/)
* [Microsoft Academic Graph](http://academic.research.microsoft.com/)
* [AceMap](http://acemap.sjtu.edu.cn/)
* [GitXiv](http://www.gitxiv.com/)
* [ACL Anthology](http://aclanthology.info/)
* [NIPS papers](https://papers.nips.cc/)
* [Abel tools for PubMed data](http://abel.lis.illinois.edu/resources.html)
* [infolis: linking research data and publications](http://infolis.github.io/)

## Tools for collecting open access papers

* [ContentMine - getpapers](https://github.com/ContentMine/getpapers)

## Visualizations
* [Nobel nominations and recipients](https://ria.ru/infografika/20151210/1339535142.html?lang=en)

## NLP

* [Biomedical - BioSentVec Embeddings](https://github.com/ncbi-nlp/BioSentVec)
* [Biomedical embeddings - CambridgeLTL](https://github.com/cambridgeltl/BioNLP-2016)
* [NIH scientific paper pre-processing](https://github.com/NIHOPA/NLPre)

# Publication Venues

## Journals
* [Frontiers in Research Metrics and Analytics](https://www.frontiersin.org/journals/research-metrics-and-analytics) 
* [Scientometrics](https://link.springer.com/journal/11192) 


## Conferences
TODO

## Workshops
* [SIGMET - Metrics workshop](https://www.asist.org/SIG/SIGMET/workshop/)
* [International Workshop on Mining Scientific Publications](https://wosp.core.ac.uk/)
