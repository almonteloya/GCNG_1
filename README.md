# GCNG
using graph convolutional neural network and spaital transcriptomics data to infer cell-cell interactions
# Title, GCNG: Graph convolutional networks for inferring cell-cell interactions
# https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02214-w


># GCNG generate_data

Uses the spatial location data to generate normalized adjacent matrix of cells, and save it in `seqfish_plus` folder; also uses the expression data to generate expression matrix for ten fold cross validation, and save it in `rand_1_10fold` folder.

This was modified from the orginal paper given that it relied in spektra 0.5, a version that's deprecated.
