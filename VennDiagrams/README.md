
This folder includes files needed to process the data in a Venn Diagram analysis as well as Venn Diagram visualizations. This analysis also generates gene lists that are then used for gene enrichment analysis (see clusterProfiler_enrichment)

## Files
2. Croco_Colim_VennDiagrams_final.Rmd --> Annotated R Markdown file for Venn Diagrams. 
      - Input files include all the files from DESeq2 pairwise comparisons (see DESeq2 folder for code and output files)
      - Output files include Venn Diagram visualizations and lists of genes: core genes upregulated / downregulated across all treatments, shared genes between at least two treatments, and unique genes only for one treatment. 
      - The analysis cover diel genes, nutrient-limited vs. replete genes.
