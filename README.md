# HackBio-internship-stage-4

This repository contains a Bash script designed to automate the process of downloading sequencing data, performing quality control, trimming, genome mapping, and variant calling for multiple datasets. The script utilizes various bioinformatics tools, including FastQC, FastP, BWA, Samtools, and FreeBayes.
Contents
**Data Download:** Downloads forward and reverse sequence files along with a reference genome.

**Quality Control:** Uses FastQC to assess the quality of raw and trimmed FASTQ files.

**Trimming:** Utilizes FastP to trim low-quality bases from the sequences.
**Genome Mapping:** Maps the cleaned reads to a reference genome using BWA.
**Variant Calling:** Calls variants from the mapped reads using FreeBayes.
**MultiQC Reporting:** Aggregates results from various analyses into a single report.
