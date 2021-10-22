# Spider-RNA-seq-analysis-Table S2

This folder contains raw data and R scripts needed to reproduce the *Additional File 3: Table S2.csv*

Run the *Table S2.rmd*, and *clock_de_gene_cor_r.csv* and *clock_de_gene_cor_p.csv* will be generated.

The column names were manually changed in *clock_de_gene_cor_r.csv* and *clock_de_gene_cor_p.csv*:

- TRINITY_DN59140_c0_g1--Cycle
- TRINITY_DN2943_c0_g1--Clock
- TRINITY_DN4945_c0_g1--Doubletime  
- TRINITY_DN146_c0_g1--Period  
- TRINITY_DN42615_c0_g1--Timeless  
- TRINITY_DN2770_c0_g1--Cry1  
- TRINITY_DN308_c1_g1--Cry2

The two tables were then manually combined into *Additional File 3: Table S2.csv*.

Match_id, corresponding protein name, and the protein function, if applicable, were added into columns "match_id"，"ProteinName"， and "Function." 
