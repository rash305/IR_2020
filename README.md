# Information Retrieval Project: Increasing Topic Diversity of BM25 Ranking Results 
Project by Group 6: Sjoerd van Dijk, Marit Hagens, and Joris Sunnotel

 - Data
	 - clean 
	 	--- Contains all preprocessed datasets---
	 - nfcorpus 
		 --- Contains all original datasets---
	 - results 
		 --- Contains the output and results of the applied algorithms--- 
- Notebooks
	- Analyse LDA group datasets from preprocessed datasets.ipynb
		--- Analyses the LDA parameters and createst a dataset---
	- Create ranking datasets BM25.ipynb
		--- Preprocess the raw datasets---
	- DiversificationAlgorithm.ipynb 
		--- The implementation of the diversity algorithm--
	- Evaluation-Diversity.ipynb
		--- Runs the evaluation metrics and significance tests---
	- Evaluation-TREC-create files and analyse.ipynb 
					--- Calculates the MAP and NDCG scores---
	- LDA_wordcloud.ipynb --- Visualizes the LDA document clusters in wordclouds ---
	- MeSH-Document Topics Downloader.ipynb --- Creates dataset of all the MeSH topics from the PupMed API---
