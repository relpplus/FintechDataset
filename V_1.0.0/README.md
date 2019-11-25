# README

# FintechDataset

 
   - TXT (txt que usamos pra processar RelP)
   - NER (arquivos CoNNeL com anotação NER)
   - ExtractionRelation (excel com a anotação manual de Extração Relação)
   - Original (arquivo original do dataset fintechs)

# Description

   - In this work we discuss the application of NER and RE tool to a news data set collected in the context of Sicredi Bank's Competitive  	Intelligence, where 200 news about Fintechs were selected to build a knowledge base. By applying our RE framework we were able to track 	  events and facts in the financial market. It is not possible to present comparative results at this stage, since our application 	   	considers only relations among named entities, whereas other tools for RE consider noun phrases in general for the generation of the  	relation triples.

     As positive outcomes of this work we can cite: the development of a pipeline of Relation Extraction using Open Source tools, which    	enables replication of the experiments for other texts, the framework code will be available\footnote{This footnote will be replaced with 	    the GitHub link for the camera-ready submission}; a new RE CRF model trained more annotated data; the end-to-end development of a 	   	knowledge base related to Fintechs that was made available to Competitive Intelligence analysts for decision support.

   - To apply the trained model, 200 news about Fintechs were collected by the Sicredi Competitive Intelligence in the period of August 2018   	    to September 2019. These news were collected from online newspapers, magazines and information portals. In module 1, prepossessing steps, 	    such as segmentation and tokenization, were applied to the sentences contained in the news. Following, in module 2 -- NER  --, the named  	    entities of categories Organization, Person and Place contained in these sentences were identified. Next, in module 3, the sentences that 	    did not contain any pair of named entities of interest were discarded, remaining 142 sentences as candidates for relation extraction.
