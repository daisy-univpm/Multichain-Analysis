# ReadMe for the GitHub Repository

This GitHub repository contains several folders and notebooks related to the analysis of cryptocurrency swaps. Below is a brief description of each of the folders and their contents.

## Folders

### dataset
This folder contains the main reference dataset named "final_dataset.csv", which is used for the analysis performed in the notebooks.

### longest_pathsv2
This folder contains the longest paths identified from the swaps in the dataset. 

### PathToCyclev2
This folder contains the cycles identified from the swaps in the dataset.

### WalletCentrality
This folder contains the values of the wallet centrality and its components for each wallet analyzed.

## Notebooks

### EDA.ipynb
This notebook performs exploratory data analysis to describe the content of the dataset and the swaps present in it.

### Wallet Centrality.ipynb
This notebook contains the code to calculate the wallet centrality (along with all its components) of each wallet. It uses the "swap_dict.p" file to get informations about swaps.

### Path.ipynb, Cycle.ipynb, and Analisi Cicli-Path.ipynb
These notebooks identify paths and cycles from the swaps in the dataset and perform the analysis on them.

Overall, this repository provides valuable insights into the cryptocurrency swaps and the analysis of the network structure surrounding them. The notebooks and the datasets included can serve as a starting point for further research in this field.