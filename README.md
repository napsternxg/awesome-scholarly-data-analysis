[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://licensebuttons.net/l/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

# Awesome Scholarly Data Analysis

List of resources on scholarly data analysis ranging from datasets, papers, and code about bibliometrics, citation analysis, and other scholarly commons resources.
Available online at https://shubhanshu.com/awesome-scholarly-data-analysis/


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
  * [Taxonomies and Ontologies of Research Concepts](#taxonomies-and-ontologies-of-research-concepts)
  * [Affiliations](#affiliations)
  * [Altmetrics and Dimensions](#altmetrics-and-dimensions)
- [Tools](#tools)
  * [User interface to publication datasets and analysis](#user-interface-to-publication-datasets-and-analysis)
  * [Tools for collecting open access papers](#tools-for-collecting-open-access-papers)
  * [Tools for classifying research papers](#tools-for-classifying-research-papers)
  * [Visualizations](#visualizations)
  * [Language Processing and Information Extraction](#language-processing-and-information-extraction)
  * [Citation and metadata extraction](#citation-and-metadata-extraction)
- [Publication Venues](#publication-venues)
  * [Journals](#journals)
  * [Conferences](#conferences)
  * [Workshops](#workshops)
- [Summer Schools](#summer-schools)
- [Associations & Community](#associations---community)
- [Contributions](#contributions)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Datasets

## Publication and Citation
* [Arnet Miner](http://aminer.org/citation)
* [Microsoft Academic Graph](https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/)
* [Open Academic Graph](https://www.openacademic.ai/oag/) - MAG + AMiner
* [Semantic Scholar Corpus](http://labs.semanticscholar.org/corpus/)
* [CiteSeer](http://csxstatic.ist.psu.edu/about/data)
* [PubMed](https://www.ncbi.nlm.nih.gov/pubmed)
* [CORA datasets for citation string parsing](https://people.cs.umass.edu/~mccallum/data.html)
* [Humanities and multilingual citation string parsing Flux-CiM and ICONIP](https://github.com/knmnyn/ParsCit/tree/master/doc) see [Neural ParsCit paper](https://link.springer.com/article/10.1007/s00799-018-0242-1) for details
* [Citation string parsing data for social sciences for English and German citations](https://github.com/exciteproject/EXgoldstandard) - [comparison with Grobid and Cermine](https://github.com/exciteproject/Exparser/tree/master/Evaluation/Ours)
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
* [DOAJ API (Directory of Open Access Journals)](https://doaj.org/api/v1/docs)
* [ROAD (Directory of Open Access Scholarly Resources)](https://road.issn.org/)
* [Sherpa/Romeo (Publisher copyright policies & self-archiving)](http://www.sherpa.ac.uk/romeo/index.php)
* [OpenAPC (fees paid for open access journal articles)](https://www.intact-project.org/openapc/)
* [OSF API (Open Science Framework)](https://developer.osf.io/)
* [Digital tools for researchers](http://connectedresearchers.com)
* [Fatcat - versioned, publicly-editable catalog of research publications](https://fatcat.wiki/)
* [Microsoft Academic Knowledge Graph - RDF dump](http://ma-graph.org/)
* [arXiv CS citation in context](http://citation-recommendation.org/publications/#A_High-Quality_Gold_Standard_for_Citation-based_Tasks)
* [arXiv fulltext + citations dataset](https://zenodo.org/record/2609187#.XKe86JhKh3g)
* [Self-citation analysis data based on PubMed Central subset (2002-2005)](https://doi.org/10.13012/B2IDB-9665377_V1)
* [Unpaywalled Corpus - PDF to 23M DOIs](https://unpaywall.org/products/snapshot) [Data Schema](https://unpaywall.org/data-format)
* [A dataset of publication records for Nobel laureates](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/6NJ5RN) - [paper](https://www.nature.com/articles/s41597-019-0033-6#Abs1)
* [126+ Million literature-dataset and dataset-dataset links  between 12+ Million objects](https://zenodo.org/record/2674330#.XOU6gshKh3g) - [About the data](http://scholexplorer.openaire.eu/index.html#/about)
* [Manually annotated citation data from the ACL Anthology into uses, motivation, future, extends, compare or contrast, and background](http://jurgens.people.si.umich.edu/citation-function/)
* [iCite - NIH Open Citation Collection](https://nih.figshare.com/collections/iCite_Database_Snapshots_NIH_Open_Citation_Collection_/4586573)
* [MEDLINE/PubMed Baseline Repository (MBR) - All Medline abstracts and paper paper meta-data in XML](https://mbr.nlm.nih.gov)
* [American Physical Society Data Sets for Research](https://journals.aps.org/datasets)
* [Co-citation networks of all Nature papers](https://www.nature.com/immersive/d41586-019-03165-4/index.html)
* [Semantic Scholar Graph of References in Context (GORC) dataset](https://github.com/allenai/s2-gorc/)
* [Multiple journal publication datasets](https://github.com/dmsquare/tube)
* [Structured citations in the English Wikipedia](https://zenodo.org/record/55004#.XgLol7dOmdM)

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
* [Career Transitions of CS students](https://github.com/tsafavi/career-transitions-data)
* [Author name gender and ethnicity dataset based on PubMed](https://doi.org/10.13012/B2IDB-9087546_V1)
* [MapAffil 2016 dataset -- PubMed author affiliations mapped to cities and their geocodes worldwide](https://doi.org/10.13012/B2IDB-4354331_V1)
* [Conceptual novelty scores for PubMed articles](https://doi.org/10.13012/B2IDB-5060298_V1)
* [100,000 top-scientists that provides standardized information on citations, h-index, co-authorship adjusted hm-index, citations to papers in different authorship positions and a composite indicator](https://data.mendeley.com/datasets/btchxktzyw/1)
* [Canadian PhD career survey](https://www.sgs.utoronto.ca/about/10000-phds-project-overview/10kphds-dashboard/) - [Science report](https://www.sciencemag.org/careers/2018/03/trend-toward-transparency-phd-career-outcomes)
* [Data from the CVs of over 150 assistant professors in psychology in top-ranked research universities and small liberal art colleges in the US](https://osf.io/z8rhg/) - [Used in this blog](https://socialsciences.nature.com/users/325112-diego-a-reinero/posts/55118-the-path-to-professorship-by-the-numbers-and-why-mentorship-matters)
* [Wikidata Author Disambiguation Dataset](https://github.com/arthurpsmith/author-disambiguator)

## Author name disambiguation
* [INSPIRE dataset](https://github.com/glouppe/paper-author-disambiguation)
* [Lee Giles dataset](http://clgiles.ist.psu.edu/data/nameset_author-disamb.tar.zip)
* [Cleaner version of Lee Giles dataset](https://figshare.com/articles/DBLPderived_labeled_data_for_author_name_disambiguation/6840281)
* [DBLP Korean Authors](http://www.lbd.dcc.ufmg.br/lbd/collections/disambiguation/DBLP.tar.gz/at_download/file)
* [Arnet Miner](http://arnetminer.org/lab-datasets/disambiguation/rich-author-disambiguation-data.zip)
* [Arnet Miner - Manual Name Disambiguation data 210 authors](https://aminer.org/na-data)
* [DBLP Name disambiguation dataset](https://github.com/yaya213/DBLP-Name-Disambiguation-Dataset)
* [rexa-coref-data](https://github.com/tapilab/rexa-coref-data)
* [Dedped author names on IEEE Vis papers 1990-2018](https://sites.google.com/site/vispubdata/home)
* [Author-ity dataset for PubMed 2009](https://doi.org/10.13012/B2IDB-4370459_V1)
* [ACL Anthology dataset](https://github.com/acl-org/acl-anthology/blob/master/data/yaml/name_variants.yaml)

## Thesis datasets
* [Open Access Theses and Dissertations](https://oatd.org/)
* [The Networked Digital Library of Theses and Dissertations (NDLTD)](http://www.ndltd.org/)
* [PhD Dissertations in the Area of Software Engineering](http://www.sigsoft.org/dissertations.php)
* [ProQuest Dissertations & Theses Global](http://www.proquest.com/products-services/pqdtglobal.html)

## Information Extraction and NLP
* [Citation Parsing](http://csxstatic.ist.psu.edu/about/scholarly-information-extraction)
* [Citation Parsing in humanities](https://github.com/dhlab-epfl/LinkedBooksDeepReferenceParsing)
* [Sentences tagged for Drug Disease pairs](https://github.com/roamanalytics/roamresearch/tree/master/BlogPosts/Features_for_healthcare)
* [Document Summarization and citation span identification](https://github.com/WING-NUS/scisumm-corpus)
* [ACL Anthology human summaries for 1000 papers](https://michiyasunaga.github.io/projects/scisumm_net/)
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
* [GENIA - BioNLP 2011](http://2011.bionlp-st.org/home)
* [Genia Treebank used for SciSpacy training](https://nlp.stanford.edu/~mcclosky/biomedical.html) - [SciSpacy link](https://allenai.github.io/scispacy/)
* [Full GENIA corpus](http://www.geniaproject.org/genia-corpus/term-corpus)
* [Anatomical Entity Mention (AnEM) corpus](http://www.nactem.ac.uk/anatomy/)
* [CellFinder - Entity detection](https://www.informatik.hu-berlin.de/de/forschung/gebiete/wbi/resources/cellfinder)
* [Multi-Level Event Extraction (MLEE)](http://nactem.ac.uk/MLEE/)
* [Biomedical sentence simplification](https://research.bioinformatics.udel.edu/isimp/corpus.html)
* [PubMed - Colorado Richly Annotated Full-Text](https://github.com/UCDenver-ccp/CRAFT)
* [Biomedical NER datasets](https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data) [related publication](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1776-8)
* [BioVerbNet](https://github.com/cambridgeltl/bio-verbnet)
* [Lunar and Planetary Science abstracts for NER and Relations](https://zenodo.org/record/1048419#.XAW0m2hKh3h)
* [ACM data affiliations](https://dbs.uni-leipzig.de/en/research/projects/bibliometrics)
* [ACM - DBLP database entry matching](https://dbs.uni-leipzig.de/en/research/projects/object_matching/fever/benchmark_datasets_for_entity_resolution)
* [Colorado Richly Annotated Full-Text](https://github.com/UCDenver-ccp/CRAFT) - PubMed abstract annotated with entities mapped to 10 biomedical ontology terms. 
* [CLEF datasets for multilingual Biomedical NLP+IE](https://sites.google.com/site/clefehealth/home)
* [MedMentions - UMLS entities in PubMed](https://github.com/chanzuckerberg/MedMentions)
* [Colright Initiatve - Rich text competition](https://coleridgeinitiative.org/richcontextcompetition#phase1)
* [SciERC - scientific entities, their relations, and coreference clusters for 500 AI conf abstracts](http://nlp.cs.washington.edu/sciIE/)
* [PubMed200k_RCT - Label abstract sentences into Objective, Background, Method, Results, Conclusions](https://github.com/Franck-Dernoncourt/pubmed-rct)
* [NER, Parsing, Classification datasets from SciBert](https://github.com/allenai/scibert/tree/master/data)
* [ACA Wiki - Paper summaries of more than 1600 papers](https://acawiki.org/Home)
* [SemEval-2018 task 7 Semantic Relation Extraction and Classification in Scientific Papers](https://competitions.codalab.org/competitions/17422#learn_the_details-subtasks)
* [A Compendium of Free, Public Biomedical Text Mining Tools Available on the Web](http://arrowsmith.psych.uic.edu/arrowsmith_uic/tools.html)
* [Medical Information Extraction from PubMed abstracts](https://www.figure-eight.com/dataset/medical-sentence-summary-and-relation-extraction/)
* [Corpus of 40 scientific papers manually annotated by multiple scientific discourse facets](http://sempub.taln.upf.edu/dricorpus)
* [PharmaCoNER: Pharmacological Substances, Compounds and proteins and Named Entity Recognition track](http://temu.bsc.es/pharmaconer/index.php/data/) - [Train](http://temu.bsc.es/pharmaconer/wp-content/uploads/2019/06/train-set_1.1.zip) - [Dev](http://temu.bsc.es/pharmaconer/wp-content/uploads/2019/06/dev-set_1.1.zip) - [Test](http://temu.bsc.es/pharmaconer/wp-content/uploads/2019/06/test-set_1.1.zip) - [Background Test set](http://temu.bsc.es/pharmaconer/wp-content/uploads/2019/05/background-set.zip)
* [Bacteria Biotope (BB) Task - NER, NEL, Relation, KB Extraction](https://sites.google.com/view/bb-2019/dataset?authuser=0)
* [Entity/relation recognition and GOF/LOF mutated gene text identification task based on the Active Gene Annotation Corpus](https://sites.google.com/view/bionlp-ost19-agac-track/description?authuser=0)
* [The Regulatory Network of Plant Seed Development (SeeDev) Task - NER, Relation](https://sites.google.com/view/seedev2019/home?authuser=0)
* [TalkSumm - Summary of papers via alignment to talks](https://github.com/levguy/talksumm)
* [SeminalSurveyDBLP - Classification of seminal or survey papers](https://zenodo.org/record/3258164#.XWac_-hKh3g)
* [A Dataset of Peer Reviews (PeerRead)](https://github.com/allenai/PeerRead)
* [CiteTracked: A Longitudinal Dataset of Peer Reviews and Citations](http://ceur-ws.org/Vol-2414/paper12.pdf)
* [Supp.ai - PubMed supplement-drug interactions and supplement-supplement interactions](https://github.com/lucylw/supp-ai-extracted-sdi-data/)
* [GENETAG](https://github.com/openbiocorpora/genetag) - More recent versions [Publication](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-6-S1-S3) and [Download 2005](ftp://ftp.ncbi.nlm.nih.gov/pub/tanabe/GENETAG.tar.gz)
* [MedTag: A Collection of Biomedical Annotations](https://www.aclweb.org/anthology/W05-1305) - [Download](ftp://ftp.ncbi.nlm.nih.gov/pub/lsmith/MedTag/)
* [Open Biomedical corpora](https://github.com/openbiocorpora)
* [Biomedical Abstract Meaning Representation corpus based on PubMed Fulltext](https://web.archive.org/web/20170501120500/http://amr.isi.edu/download.html) - Also see [other NLM curated biomedical resources](https://www.nlm.nih.gov/databases/download/data_distrib_main.html)
* [SciDTB: Discourse Dependency TreeBank for Scientific Abstracts](https://github.com/PKU-TANGENT/SciDTB)
* [SciDTB corpus annotated for argumentation mining](http://scientmin.taln.upf.edu/argmin/) - [Paper](https://www.aclweb.org/anthology/W19-4505.pdf)
* [Dr. Inventor Multi-layer Scientific Corpus for multiple scientific discourse facets](http://sempub.taln.upf.edu/dricorpus)
* [ART corpus - 225 papers manually annotated the CISP labels (i.e. "Goal", "Method", "Result").](https://www.aber.ac.uk/en/media/departmental/computerscience/cb/art/gz/ART_Corpus.tar.gz)- [Browse files](http://www.ukoln.ac.uk/projects/ART_Corpus/menu.html) - [Project details](http://www.ukoln.ac.uk/projects/ART_Corpus/index.html)
* [Multi-CoreSC CRA corpus (MCCRA) - 50 papers annotated with multiple CoreSC labels per sentence.](http://www.sapientaproject.com/wp-content/uploads/2016/05/consensus_annotated.zip) - [Project details](http://www.sapientaproject.com/links)
* [PubMedQA - Question answering on PubMed](https://github.com/pubmedqa/pubmedqa)
* [Corposaurus - Collection of biomedical corpus for NER](https://corposaurus.github.io/corpora/)
* [BioNER corpus](https://github.com/xhuang28/NewBioNer/tree/master/corpus)
* [NeuroQuery - 14,000 full-text publications and 400,000 peak activations](https://github.com/neuroquery/neuroquery_data) - [NeuroQuery website](https://neuroquery.org/about)
* [Medical Information Extraction dataset](https://www.figure-eight.com/dataset/medical-sentence-summary-and-relation-extraction/)
* [A Large Parallel Corpus of Full-Text Scientific Articles](https://figshare.com/s/091fcaf8ad66a3304e90)
* [Annotated Corpus of Scientific Conference's Homepages for Information Extraction](https://archive.org/details/conferences-data-0.2)
* [Chi QA - Health Question Answering dataset from NLM](https://chiqa.nlm.nih.gov/)
* [Corpus of Open Access articles from multiple fields in Science, Technology, and Medicine - Includes wikification data](https://github.com/elsevierlabs/OA-STM-Corpus)
* [Grounding Scientific Entity References in STEM Scholarly Content to Authoritative Encyclopedic and Lexicographic Sources](https://gitlab.com/TIBHannover/orkg/orkg-nlp/tree/master/STEM-ECR-v1.0)
* [Open Research Knowledge Graph project](https://gitlab.com/TIBHannover/orkg) - [Website](https://www.orkg.org/orkg/)
* [Academic PhraseBank](http://www.phrasebank.manchester.ac.uk/)
* [SciKG - Statement extraction datasets](https://github.com/dmsquare/SciKG) 


## Networks
* [ACL Anthology Network](http://clair.eecs.umich.edu/aan/index.php)

## Taxonomies and Ontologies of Research Concepts
* [SciGraph Springer Nature](https://scigraph.springernature.com/explorer/downloads/)
* [Medical Subject Headings](https://meshb.nlm.nih.gov/search) maintained by the [National Library of Medicine of the United States](https://www.nlm.nih.gov)
* [Computer Science Ontology](https://cso.kmi.open.ac.uk/home) maintained by [Scholarly Knowledge: Modeling, Mining and Sense Making](http://skm.kmi.open.ac.uk)
* [Physics Subject Headings](https://physh.aps.org/) maintained by [American Physical Society (APS)]()
* [Open Biological and Biomedical Ontology (OBO)](http://obofoundry.org/) maintained by the [OBO Foundry](http://obofoundry.org)
* [ACM Computing Classification System](https://www.acm.org/publications/class-2012) maintained by the [Association for Computing Machinery](https://www.acm.org)
* [Physics and Astronomy Classification Scheme (PACS)](https://web.archive.org/web/20131122200802/http://www.aip.org/pacs/pacs2010/about.html) maintained by [American Institute of Physics (AIP)]() *discontinued* in 2010 and replaced by [Physics Subject Headings](https://physh.aps.org/)
* [Mathematics Subject Classification (MSC)](https://mathscinet.ams.org/msc/msc2010.html) mantained by [Mathematical Reviews](http://www.ams.org/mr-database) and [zbMATH](https://zbmath.org)
* [Journal of Economic Literature (JEL)](https://www.aeaweb.org/econlit/jelCodes.php) maintained by the [American Economic Association](https://www.aeaweb.org)
* [STW Thesaurus for Economics](http://zbw.eu/stw/version/latest/about) maintained by [ZBW - Leibniz Information Centre for Economics](http://www.zbw.eu/de/)
* [Australian and New Zealand Standard Research Classification (ANZSRC)](https://www.arc.gov.au/grants/grant-application/classification-codes-rfcd-seo-and-anzsic-codes) maintained by [Australian Bureau of Statistics](http://www.abs.gov.au), it consists of 3 sub-classification schemes:
  * [Fields of Research (FoR)](http://www.abs.gov.au/Ausstats/abs@.nsf/Latestproducts/6BB427AB9696C225CA2574180004463E?opendocument) classification
  * [Research Fields, Courses and Disciplines (RFCD)](http://www.abs.gov.au/ausstats/abs@.nsf/66f306f503e529a5ca25697e0017661f/955FFA4EB1B23847CA25697E0018FB14?opendocument) classification
  * [Socio-Economic Objective (SEO)](http://www.abs.gov.au/Ausstats/abs@.nsf/Latestproducts/CF7ADB06FA2DFD69CA2574180004CB82?opendocument) classification
* [Library of Congress Classification (LCC)](https://www.loc.gov/catdir/cpso/lcc.html) maintained by [Library of Congress](https://www.loc.gov)
* [Fields of Study (FoS)](https://academic.microsoft.com/#/topics/0/) maintained by [Microsoft Academic](https://academic.microsoft.com)

## Affiliations

* [Global Research Identifier Database (GRID)](www.grid.ac)
* [CS Rankings with people linked to institutes](http://csrankings.org/#/index?all)

## Altmetrics and Dimensions
* [Altmetrics API](https://api.altmetric.com/)
* [Dimensions.ai API](https://metrics-api.dimensions.ai) - [documentation](https://figshare.com/articles/Dimensions_Metrics_API_Documentation/5783694), [example](http://metrics-api.dimensions.ai/doi/10.7717/peerj-cs.119)
* [Core Conference Rankings](http://www.core.edu.au/conference-portal/2018-conference-rankings-1)
* [China Computer Federation Conference Rankings](https://www.ccf.org.cn/xspj/rgzn/)

# Tools

## User interface to publication datasets and analysis

* [Google Scholar](https://scholar.google.com/)
* [Semantic Scholar](https://www.semanticscholar.org/)
* [Microsoft Academic Graph](http://academic.research.microsoft.com/)
* [AceMap](http://acemap.sjtu.edu.cn/)
* [GitXiv](http://www.gitxiv.com/)
* [ACL Anthology](http://aclanthology.info/)
* [NIPS papers](https://papers.nips.cc/)
* [Abel tools for PubMed data](http://abel.lis.illinois.edu/resources.html)
* [infolis: linking research data and publications](http://infolis.github.io/)
* [Metrics toolkit](http://www.metrics-toolkit.org/)
* [Rcrossref (R library)](https://github.com/ropensci/rcrossref)
* [Rscopus (R library)](https://cran.r-project.org/web/packages/rscopus/index.html)
* [Scholar (R library)](https://cran.r-project.org/web/packages/scholar/index.html)
* [Bibliometrix (R library)](http://www.bibliometrix.org/)
* [CITAN (R library)](https://cran.r-project.org/web/packages/CITAN/index.html)
* [BibeR (BibeR: A Web-based tool for bibliometric analysis in scientific literature)](https://yangliufr.shinyapps.io/BibeR/)
* [scihub.py (Python library)](https://github.com/zaytoun/scihub.py)
* [SoPaper (Python library)](https://github.com/ppwwyyxx/SoPaper)
* [CiteSeer tools](https://github.com/SeerLabs)
* [Novelty quantification in PubMed articles](https://github.com/napsternxg/Novelty)
* [TidyPMC - R based PMC XML parser](https://github.com/cstubben/tidypmc)


## Tools for collecting open access papers

* [ContentMine - getpapers](https://github.com/ContentMine/getpapers)
* [rcoreoa](https://github.com/ropensci/rcoreoa) - [CORE](core.ac.uk) API R client
* [metaknowledge - A Python library for doing bibliometric and network analysis in science and health policy research](https://github.com/networks-lab/metaknowledge)

## Tools for classifying research papers

* [CSO-Classifier](https://github.com/angelosalatino/cso-classifier)

## Visualizations
* [Rexplore](https://technologies.kmi.open.ac.uk/rexplore/)
* [VOSviewer](http://www.vosviewer.com)
* [CitNetExplorer](http://www.citnetexplorer.nl/)
* [CiteSpace](http://cluster.cis.drexel.edu/~cchen/citespace/)
* [Nobel nominations and recipients](https://ria.ru/infografika/20151210/1339535142.html?lang=en)
* [WOS2Pajek](http://vladowiki.fmf.uni-lj.si/doku.php?id=pajek:wos2pajek)

## Language Processing and Information Extraction

* [Biomedical - BioSentVec Embeddings](https://github.com/ncbi-nlp/BioSentVec)
* [Biomedical embeddings - CambridgeLTL](https://github.com/cambridgeltl/BioNLP-2016)
* [NIH scientific paper pre-processing](https://github.com/NIHOPA/NLPre)
* [SciSpacy - Spacy models for Biomedical NLP from AllenAI](https://allenai.github.io/scispacy/)
* [Multitask Biomedical NER](https://github.com/yuzhimanhua/Multi-BioNER)
* [SciBERT - Bert LM for Biomedical and CS papers](https://github.com/allenai/scibert)

## Citation and metadata extraction
* [CERMINE](https://github.com/CeON/CERMINE)
* [Grobid](https://grobid.readthedocs.io/en/latest/)
* [EXCITE (Extraction of Citations from PDF Documents)](http://excite.west.uni-koblenz.de/website/)
* [Science-Parse](https://github.com/allenai/science-parse)
* [unarXiv (Citation in context from arXiv)](https://github.com/IllDepence/unarXive)

# Publication Venues

## Journals
* [Frontiers in Research Metrics and Analytics](https://www.frontiersin.org/journals/research-metrics-and-analytics) 
* [Scientometrics](https://link.springer.com/journal/11192) 
* [Journal of Informetrics](https://www.journals.elsevier.com/journal-of-informetrics)
* [Quantitative Science Studies](https://www.mitpressjournals.org/loi/qss) (Open Access)
* [Science, technology and human values](https://journals.sagepub.com/home/sth)
* [Social Studies of Science](https://journals.sagepub.com/home/sss)
* [Science and Public Policy](https://academic.oup.com/spp)

## Conferences
* [Joint Conference on Digital Libraries (JCDL)](http://www.jcdl.org)
* [International Conference on Theory and Practice of Digital Libraries (TPDL)](http://www.tpdl.eu)
* [European Semantic Web Conference (ESWC), Research of Research Track](https://2019.eswc-conferences.org/call-for-papers-research-of-research-track/)
* [STI Conference series (Science and Technology indicators, e.g., 2018)](http://sti2018.cwts.nl/)
* [ISSI Conference series (INTERNATIONAL CONFERENCE ON  SCIENTOMETRICS & INFORMETRICS, e.g., 2019)](https://www.issi2019.org/)

## Workshops
* [SIGMET - Metrics workshop](https://www.asist.org/SIG/SIGMET/workshop/)
* [International Workshop on Mining Scientific Publications](https://wosp.core.ac.uk/)
* [Semantics, Analytics, Visualisation: Enhancing Scholarly Dissemination (SAVE-SD)](https://save-sd.github.io/2018/)
* [Workshop on Reframing Research (RefResh)](http://refresh.kmi.open.ac.uk)
* [Enabling Open Semantic Science (SemSci)](https://semsci.github.io/SemSci2018/)
* [Workshop on Scholarly Document Processing](https://ornlcda.github.io/SDProc/index.html)

# Summer Schools
* [CWTS Scientometrics Spring School (CS3)](https://www.cwts.nl/education/cwts-scientometrics-spring-school)
* [European Summer School of Scientometrics (ESSS)](https://www.scientometrics-school.eu/)

# Associations & Community
* [International Society for Informetrics and Scientometrics (ISSI)](http://issi-society.org)
* [European Network of Indicator Designers (ENID)](http://www.forschungsinfo.de/ENID/)
* [4S (Society for Social Studies of Science)](http://4sonline.org/)
* [SIG/MET - Special Interest Group for the measurement of information production and use](https://www.asist.org/SIG/SIGMET/)

# Contributions
The following people have contributed to the items on this list. 
* [Shubhanshu Mishra](https://shubhanshu.com) - Maintainer of the list. 
* [Angelo Antonio Salatino](https://github.com/angelosalatino)
* [Philipp Zumstein](https://github.com/zuphilip)
* [Ali (Aliakbar Akbaritabar)](http://akbaritabar.netlify.com)
