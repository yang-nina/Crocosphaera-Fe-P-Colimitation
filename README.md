# CrocosphaeraFePColimitation

This respository includes the data and code to recreate analyses and figures from "	Diel molecular mechanisms underlying iron and phosphorus co-limitation responses in the nitrogen-fixing cyanobacterium Crocosphaera".

## Files

1. Croco_Colim_annotation_compile.Rmd --> Annotated R Markdown file to re-annotate the low-contig _Crocosphaera_ genome for Gene Ontology and KEGG annotation. Note that to use the script, the file pathways will have to be updated. 
      -  Input file: Croco_annot_diamond.tsv
      -  Input file: Croco_uniprot_blast.tsv
      -  Input file: Croco_uniprot_refseq.tsv
      -  Input file: blast2go_table.txt
      -  Input file: Croco_kegg_annot.csv
      -  Output file: Croco_annot_compiled_final_new.csv
      -  Output file: goterms.csv
      -  Output file: ontology.csv
      -  Output file: goterms.csv
      -  Output file: Croco_GO_KO_database.csv

2. Croco_Colim_DESeq2_final.Rmd --> Annotated R Markdown file for pairwise comparisons using DESeq2. THis also includes count normalization for downstream analysis.
      - Input file: keggassign_counts_fordeduping_stranded.csv
      - Output file: CrocoColim_counts_deduped_forDESeq2.csv
      - Output file: CrocoColim_trimmed_forDESeq2.csv
      - Output file: CrocoColim_normcounts_forDGE.csv
      - Output file: CrocoColim_vstcounts_forDGE.csv
      - Output file: CrocoColim_rldcounts_forDGE.csv
      - The code generates output files for each pairwise comparison appended with the treatments and "DESeqresults.csv"
  
  
