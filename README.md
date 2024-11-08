**The source code for: "MSA clustering enhances AF-Multimer's ability to predict conformational landscapes of protein-protein interactions"**


![image](https://github.com/user-attachments/assets/f6332117-d3fe-4726-a794-187a34bb31a7)

Fig. 1. Workflow for predicting conformational landscape of protein-protein interactions using AlphaFold and unpaired sequence clustering. Initially, the MSA of the metamorphic protein is sampled or clustered using various techniques and predicted by AlphaFold2 models. Then, an unpaired MSA, comprising the full ligand MSA and the sampled/clustered MSA of the metamorphic protein, is constructed and provided as input to the AlphaFold model.




-data/

  Structure files and AF2/AF2-M scores for predicted proteins (files with big size weren't upload to GitHub - contact authors to get them)
  
-AF_Multimer_Cluster.ipynb

  Easy Google Colab notebook for easy access to our pipeline.
