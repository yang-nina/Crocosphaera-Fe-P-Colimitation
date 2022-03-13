This folder includes code and relevant files for gene enrichment analysis and heatmap, dot plot, and box plot visualizations.

## Folders and Files

1. Croco_Colim_clusterProfiler.Rmd --> Annotated R Markdown file for gene enrichment analyses using clusterProfiler functions enricher (for GO) and enrichKEGG (for KEGG).
    A. clusterProfiler analyses
      - Input file: Croco_GO_KO_database.csv (see Croco_Annotation)
      - Input file: Venn Diagram gene lists
      - Output files: enricher / enrichKEGG results

    B. Dot Plot visualization
      - Input files: clusterProfiler outputs 
      - Output file: dot plot visualization of enriched "core gene" results for Gene Ontology (BP & MF terms only), and KEGG Pathways (KO).

    C. Summary tables of all enriched results for Supplementary Tables

