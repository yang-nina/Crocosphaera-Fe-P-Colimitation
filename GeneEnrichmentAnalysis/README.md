This folder includes code and relevant files for gene enrichment analysis and heatmap, dot plot, and box plot visualizations. All visualizations were formatted with minor edits for clarity and indicators of statistical significance, and compiled for composite figures using Affinity Designer for macOS (https://affinity.serif.com/en-us/).

## Folders and Files

1. Croco_Colim_clusterProfiler.Rmd --> Annotated R Markdown file for gene enrichment analyses using clusterProfiler functions enricher (for GO) and enrichKEGG (for KEGG).

    A. clusterProfiler analyses
      - Input file: Croco_GO_KO_database.csv (see Croco_Annotation)
      - Input file: Venn Diagram gene lists
      - Output files: enricher / enrichKEGG results

    B. Dot Plot visualization
      - Input files: clusterProfiler outputs 
      - Output file: dot plot visualization of enriched "core gene" results for Gene Ontology (BP & MF terms only), and KEGG Pathways (KO).

2. Croco_Colim_Heatmaps.Rmd --> Annotated R Markdown file for heatmap visualizations

    A. Heatmaps visualization
        - Input file: CrocoColim_normcounts_forDGE.csv (see DESeq2)
        - Input file: CrocoColim_trimmed_forDESeq2.csv (see DESeq2)
        - Input file: Croco_kegg_annot.csv (see Croco_annotation)
        - 


