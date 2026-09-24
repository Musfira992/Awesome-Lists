# Tools

High-signal bioinformatics, data, and CLI tools. For deeper curated lists and notes, see [bioinformatics-resources](https://github.com/Musfira992/bioinformatics-resources) and the [notes handbook](https://www.musfirajamil.com/notes/).

## Sequencing and alignment

- [samtools](https://www.htslib.org/) - Read/write/filter SAM/BAM/CRAM; essential NGS Swiss army knife.
- [bcftools](https://samtools.github.io/bcftools/) - VCF/BCF variant calling and manipulation.
- [minimap2](https://github.com/lh3/minimap2) - Fast pairwise aligner for short and long reads.
- [BWA](https://github.com/lh3/bwa) - Burrows-Wheeler aligner for short reads against large genomes.
- [HISAT2](https://daehwankimlab.github.io/hisat2/) - Fast spliced alignment for RNA-seq.

## Quantification and expression

- [salmon](https://combine-lab.github.io/salmon/) - Fast, bias-aware transcript quantification.
- [kallisto](https://pachterlab.github.io/kallisto/) - Near-optimal RNA-seq quantification via pseudoalignment.
- [DESeq2](https://bioconductor.org/packages/DESeq2/) - Differential expression for count data in R/Bioconductor.
- [edgeR](https://bioconductor.org/packages/edgeR/) - Empirical Bayes DE for digital gene expression.

## Quality control and reporting

- [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) - Per-sample sequencing QC reports.
- [MultiQC](https://multiqc.info/) - Aggregate QC across tools and samples into one report.
- [fastp](https://github.com/OpenGene/fastp) - Fast all-in-one FASTQ preprocessing.

## Workflow and environment

- [Nextflow](https://www.nextflow.io/) - Portable, reproducible scientific workflows.
- [Snakemake](https://snakemake.github.io/) - Python-based workflow management popular in bioinformatics.
- [conda / mamba](https://mamba.readthedocs.io/) - Environment and package management for scientific stacks.
- [Docker](https://www.docker.com/) / [Singularity/Apptainer](https://apptainer.org/) - Containers for reproducible analysis environments.

## Data analysis and scripting

- [R](https://www.r-project.org/) / [Bioconductor](https://www.bioconductor.org/) - Statistical computing and genomics packages.
- [tidyverse](https://www.tidyverse.org/) - Consistent R packages for data wrangling and visualisation.
- [Python](https://www.python.org/) with [pandas](https://pandas.pydata.org/) and [scanpy](https://scanpy.readthedocs.io/) - General and single-cell analysis.
- [jq](https://jqlang.github.io/jq/) - Command-line JSON processor.
- [csvkit](https://csvkit.readthedocs.io/) - Utilities for CSV on the command line.

## Version control and shells

- [Git](https://git-scm.com/) - Distributed version control (see also [cheatsheets/git.md](../cheatsheets/git.md)).
- [gh](https://cli.github.com/) - Official GitHub CLI for issues, PRs, and API work.
