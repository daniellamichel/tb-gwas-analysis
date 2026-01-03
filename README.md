🧬 Tuberculosis GWAS Analysis

🔍 Overview

This project performs a Genome-Wide Association Study (GWAS) on 1521 Mycobacterium tuberculosis isolates to analyze genetic variations linked to rifampicin resistance.

📊 Data

1521 isolates, each with genotype & phenotype data.

Columns: isolate_ID, ROLLINGDB_ID, group (phylogenetic classification), RIF_midpoint (MIC for rifampicin), and genomic positions.

Minor allele filter applied (≥1%) to reduce dataset size.

🧪 Analysis

Log-transformed MIC values to adjust for distribution.

Linear regression to test genotype-phenotype associations.

Bonferroni correction for multiple comparisons.

Manhattan plot to visualize significant SNPs.

📌 Key Results

2377 SNPs significant at p < 0.001.

615 SNPs significant after Bonferroni correction.

Identified potential variants linked to drug resistance.

🔧 Requirements

Libraries: numpy, pandas, scipy, sklearn, matplotlib, statsmodels

🎯 Conclusion

This study highlights genetic markers associated with rifampicin resistance, aiding research on drug resistance mechanisms.
