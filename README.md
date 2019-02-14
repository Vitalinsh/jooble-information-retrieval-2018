# "information retrieval 2018" course from Jooble company
The main purpose of course is creating model of search engine.
Appart from this, our team have developed 2 additional features:
- vacancy classifier by prof area (intersecting classes)
- vacandy segmentation model for search requirements field in the raw text

### setup.py scripts
Loads all necessary data to project from google drive:
- initial datasets and index
- doc_to_vec vectorizer

### Run search engige
- run all "server" scripts

### Services adresses
- server_indexer: port=13500
- server_text_processing: port=13501
- server_ranking: port=13502
- server_snippets: port=13503
- server_result_page_form: port=13504
- server_manager: port=13505

