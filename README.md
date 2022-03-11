# CrocosphaeraFePColimitation

This respository includes the data and code to recreate analyses and figures from "	Diel molecular mechanisms underlying iron and phosphorus co-limitation responses in the nitrogen-fixing cyanobacterium Crocosphaera".

## 

2. Croco_Colim_DESeq2_final.Rmd --> Annotated R Markdown file for pairwise comparisons using DESeq2. THis also includes count normalization for downstream analysis.
      - Input file: keggassign_counts_fordeduping_stranded.csv
      - Output file: CrocoColim_counts_deduped_forDESeq2.csv
      - Output file: CrocoColim_trimmed_forDESeq2.csv
      - Output file: CrocoColim_normcounts_forDGE.csv
      - Output file: CrocoColim_vstcounts_forDGE.csv
      - Output file: CrocoColim_rldcounts_forDGE.csv
      - The code generates output files for each pairwise comparison appended with the treatments and "DESeqresults.csv"
  
  
