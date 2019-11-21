## QLD AI NLP Fundamnetals
### 1.0 Overview
Slides, notebooks and a down-sampled datatset from the QLD AI NLP Fundamentals workshop (21.11.19). 

#### 1.1 Up and Running
Clone repo and install dependencies via:
* `pip install -r requirements.txt`

Additionally, also install the spacy medium model via:
* `python -m spacy download en_core_web_md`

#### 1.2 Notebook Overview
`trove_scrape` - pulling content from the trove archives via the [trove API](https://trove.nla.gov.au/), API key requires creating a trove account (see website)
`spacy_analysis` - preprocessing, processing, formatting and analysis of trove documents
`spacy_vis_benchmarking` - visualising spacy dependency parses, NER outputs and some very rough benchmarking around the multi-core processing and simple/complex spacy pipelines