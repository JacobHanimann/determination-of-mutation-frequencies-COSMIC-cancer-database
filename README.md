# Determination of mutation frequencies of COSMIC cancer database
This is a python 2.7 scripts to extract, evaluate and visualise the annotation frequency of point mutations from the Catalogue of Somatic Mutations in Cancer (Cosmic) database. The filters are set to discard SNP's, remove multiple annotated samples and only include mutation with known AA position. The script determines for each gene and for each transcript the mutation count, the relative frequency and a rank. The output is a tab separated file including the information 'Mutation', 'Gene', 'Transcript', 'Mutation Count', 'Gene Count', 'Relative frequency', 'Rank', 'Rank score', 'Total ranks', 'Relative position' and 'Classification' per Amino Acid position. The classifier (second half of script) determines for each point mutation an outlier score to discriminate between 'Highly, Mediumly and Poorly' annotated mutation in a non-parametrical manner. The results of the classification can either be visualised in histogram plots or appended to the output file.
