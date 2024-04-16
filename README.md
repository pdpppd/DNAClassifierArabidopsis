# DNAClassifierArabidopsis
**This is an Neural Network that has been trained on the Arabidopsis Genome to predict the idenitity of any DNA sequence. **

This tool is available on Google Colab: 
[Google Colab](https://colab.research.google.com/github/pdpppd/DNAClassifierArabidopsis/blob/master/ArabidopsisDNAClassifier.ipynb)

## Pipeline:
1. Encode DNA Sequence: Vectorize by counting hexamers, or embed using DNABERT
2. Embedding is fed to NN
3. Softmax is applied to NN output to generate a probability distribution of the type of DNA sequence

## Instructions:
Input your DNA sequence in the first cell and then go to `Runtime` and then `Run all`
- Note: The notebook will take care of all dependencies and etc.

