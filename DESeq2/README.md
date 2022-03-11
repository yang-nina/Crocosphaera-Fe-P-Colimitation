This folder includes files needed to run pairwise comparisons. It also includes results from pairwise comparisons.

## Files
2. Croco_Colim_DESeq2_final.Rmd --> Annotated R Markdown file for pairwise comparisons using DESeq2. THis also includes count normalization for downstream analysis.
      - Input file: keggassign_counts_fordeduping_stranded.csv
      - Output file: CrocoColim_counts_deduped_forDESeq2.csv
      - Output file: CrocoColim_trimmed_forDESeq2.csv
      - Output file: CrocoColim_normcounts_forDGE.csv
      - Output file: CrocoColim_vstcounts_forDGE.csv
      - Output file: CrocoColim_rldcounts_forDGE.csv
      - The code generates output files for each pairwise comparison appended with the treatments and "DESeqresults.csv"
