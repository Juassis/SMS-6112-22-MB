# NBIS Support SMS-6112

## Introduction

Myotis brandtii are known to have at least a ten-fold longer life expectancy compared to mice of similar body mass, and the highest relative longevity of any mammals. To this end we have collected fresh snap-frozen complete organ systems from these bats during both winter hibernation and summer active period. We thus want to compare gene expressions and control of gene expressions across organs and between these groups. The whole genome is sequenced and available, but the pipeline from sequences to count tables is not established.

## Results

https://github.com/Juassis/SMS-6112-22-MB/tree/main/results/salmon

salmon.merged.gene_counts.rds
salmon.merged.gene_counts.tsv
salmon.merged.gene_counts_length_scaled.rds
salmon.merged.gene_counts_length_scaled.tsv
salmon.merged.gene_counts_scaled.rds
salmon.merged.gene_counts_scaled.tsv
salmon.merged.gene_tpm.tsv
salmon.merged.transcript_counts.rds
salmon.merged.transcript_counts.tsv
salmon.merged.transcript_tpm.tsv
salmon_tx2gene.tsv

results: Plots
https://github.com/Juassis/SMS-6112-22-MB/tree/main/results/salmon/results

01-T
gProfiler_m.png
TopVar100.tsv

02-DE
HeatMap_rlog.png
HeatMap_topvar100.png
HeatMap_topvar100_clus.png
PCA_bat.png
PCA_bat_lremoved.png
PCA_library.png
PCA_library_removed.png
adistribution.png
distribution.png
samples_correlation.png

## Report
https://github.com/Juassis/SMS-6112-22-MB/tree/main/reports/rmarkdown/Report_SMS_6112

Report_SMS_6112.Rmd
Report_SMS_6112.html
