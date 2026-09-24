# Project ideas (2-3 weeks)

Learning projects only. These are ideas for skill-building, not claims of completed work.

1. **Public RNA-seq reanalysis**  
   Pick a small GEO or SRA study (3-6 samples per group). Run FastQC → fastp → salmon or HISAT2+featureCounts → DESeq2. Deliver a MultiQC report, a short methods note, and a volcano/heatmap figure set. Stretch: containerise the pipeline with Nextflow or Snakemake.

2. **Variant calling mini-pipeline**  
   Align a public WGS or amplicon dataset with BWA/minimap2, call variants with bcftools or GATK best practices (subset), and summarise quality metrics. Write a one-page README explaining filters chosen and why.

3. **Plant phenotype + environment dashboard**  
   Combine an open plant or crop phenotype table with weather or soil covariates. Clean in R or Python, fit a simple model (linear or geostatistical if spatial), and publish a static site or Quarto/R Markdown report.

4. **Reproducible notes pack**  
   Convert 5-10 of your own lab or analysis tips into a MkDocs or Quarto handbook (inspired by the [notes](https://github.com/Musfira992/notes) repo pattern). Include a cheatsheet page and a CONTRIBUTING guide.

5. **Clinical data wrangling with MIMIC-Extract concepts**  
   Using credentialed MIMIC-IV access (or a public synthetic substitute if you lack credentials), reproduce a simplified cohort table: demographics, LOS, and a few labs. Document ethics/access steps carefully; do not redistribute restricted data.
