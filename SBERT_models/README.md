# SBERT models
Creating SBERT models to help identify contradictions and Entailments in literature  [Link to author's Github](https://github.com/UKPLab/sentence-transformers)

Since the primary purpose of the model is to help identify claims in BioMedical literature, 
it is trained on versions of BERT which are trained on Biomedical data, for example:
* BioBERT: Trained on Biomedical Literature to identify NLI in text data [link to github](https://github.com/dmis-lab/biobert)
(can be installed using:!pip install biobert-embedding)
* Covid-ERT: Trained on Covid literature data, hence has data about Covid related terms [link to Github](https://huggingface.co/deepset/covid_bert_base)
(found used inside [Huggingface Transformers](https://github.com/huggingface/transformers)



