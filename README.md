# EdgeClustering

This repo includes the MATLAB code and datasets needed to run the  DPE (directed path emphasizing), PRE (producer-receptor emphasizing), and RGE (region emphasizing) edge clustering algorithms. 

Code: 
FlowLaplacian: Given a digraph G and the string variable Lstr (which identifies DPE, PRE, or RGE), this computes the flow Laplacian Lf and its normalized counterpart normLf.  
EdgeClusters: Given a digraph, its normalized flow Laplacian normLf, and the desired number of edge clusters K, this computes the edge clusters (represented as MATLAB digraph objects) and edge labels.  
Plot_CElegans, Plot_HumanDMN, Plot_PiazzaMazzini: These provide sample edge cluster plots for three prototype datasets (CElegans, HumanDMN, and PiazzaMazzini). Note: HumanDMN is an undirected graph and therefore Plot_HumanDMN first generates a digraph by replacing each undirected edge with a pair of directed edges in opposite directions.

Datasets:
All the datasets that were used in the manuscript.
