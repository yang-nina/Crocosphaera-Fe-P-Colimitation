This folder includes files and code necessary to annotate the Crocosphaera genome. 

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
