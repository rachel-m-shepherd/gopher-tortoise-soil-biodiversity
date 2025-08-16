This analysis uses mctoolsr to manage the data
link to the source code: 
https://github.com/leffj/mctoolsr

The resulting files from the function load_taxa_table() are large lists. 
Each of these files is connected by matching sample IDs and taxonomy (ASV ID). 
Here is a breakdown of each file:  
data_loaded = ASV ID (row names) by sample ID (column names)  
map_loaded = sample ID (row names) by metadata attributes (column names)  
taxonomy_loaded = ASV ID (row names) by taxonomic strings (column names)  
