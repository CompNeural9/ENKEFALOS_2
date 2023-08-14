<p align="center">
  <img width="355" alt="image" src="https://github.com/KrishU27/Enkefalos/assets/132734331/cc7bc648-a2a7-4367-9802-24e2c0df23f0">
</p>

Here you will find the code, as well as the input and output data, for our Enkefalos computational tool. Data was derived from a study done by the Pavlidis Lab at the University of British Columbia. You can find the description of the data and how it was derived [here](https://github.com/PavlidisLab/transcriptomic_correlates).

# Notebook
You can access the Jupyter Notebook with the code [here](https://mybinder.org/v2/gh/KrishU27/Enkefalos/main?labpath=ENKEFALOS.ipynb). Do make sure to run the cells in order. There are several sections in this notebook.
- Takes in your genes of interest (GOI) as well as a FDR threshold for analyses.
- Displays genes from your (GOI) that had significant correlations with electrophysiological/morphological measures.
- Prints out the number of enriched genes as well as what the genes with significant correlations are.
- Calls StringDB to create a gene interactome of your enriched genes. Will tabulate the number of interactions each gene has.
- Will give the option to create a smaller subset network given certain parameters.
- Will allow you to obtain multiple or singular correlation plots of a gene of interest and electrophysiological/morphological measures.
- Shows the plot data of the correlation plots of a gene of interest.
- 
#Citations
