# GMLNormalize
# Language: R
# Input: TXT
# Output: GML 
# Tested with: PluMA 1.1, R 4.0.0
# Dependencies: igraph_1.3.5  stringr_1.5.0

PluMA plugin to take a GML file and normalize the data

Input is a tab-delimited file of keyword-value pairs:

network: GML file of input network
meanAbundance: TXT file of node abundances

The output will be the same GML file, with normalized data
