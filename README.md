# 1000G_workflows

Nextflow pipelines of 1000 Chilean Genomes project

# Genome Assembly and Analysis Tools

This repository contains several tools and pipelines used for genome assembly, scaffolding, polishing, and analysis. Below are the descriptions of each tool.

## [wengan](https://github.com/1000GCh/wengan)
**An accurate and ultra-fast hybrid genome assembler**

- **Language**: Perl/C++  
- **License**: GNU Affero General Public License v3.0  
- **Description**: Wengan is a high-performance hybrid genome assembler designed for speed and accuracy. It integrates data from different sequencing technologies to produce high-quality genome assemblies, making it ideal for complex genomes.  
- **Stars**: 88  
- **Updated**: Apr 10  

---

## [hic-scaffolding-nf](https://github.com/1000GCh/hic-scaffolding-nf)
**Nextflow pipeline for scaffolding genome assemblies with Hi-C reads**

- **Language**: Nextflow  
- **License**: MIT License  
- **Description**: A Nextflow pipeline for improving genome assembly by leveraging Hi-C sequencing data. Hi-C reads help to scaffold contigs and improve chromosome-level assembly.  
- **Stars**: 4  
- **Updated**: Feb 11  

---

## [ppilon](https://github.com/1000GCh/ppilon)
**Nextflow pipeline for polishing a large genome using Pilon**

- **Language**: Nextflow  
- **License**: MIT License  
- **Description**: This Nextflow pipeline uses Pilon to polish genome assemblies, correcting errors in base-calling and improving the overall quality of large genome assemblies.  
- **Stars**: 2  
- **Updated**: Aug 13, 2023  

---

## [alnsl](https://github.com/1000GCh/alnsl)
**Nextflow pipeline for short-read alignment**

- **Language**: Nextflow  
- **License**: MIT License  
- **Description**: A pipeline for aligning short-read sequencing data, designed to handle large datasets efficiently and produce alignments for downstream analysis.  
- **Stars**: 1  
- **Updated**: May 25, 2023  

---

## [assemblyStats](https://github.com/1000GCh/assemblyStats)
**Run assembly statistics on a genome assembly (BUSCO, assemblyStats, and new_Assemblathon.pl)**

- **Language**: Perl  
- **License**: Unspecified  
- **Description**: A tool for evaluating genome assembly quality using various metrics including BUSCO, assemblyStats, and Assemblathon statistics, providing a comprehensive view of the assembly's completeness and accuracy.  
- **Stars**: 5  
- **Updated**: Apr 28, 2023  

---

## [longreadstats](https://github.com/1000GCh/longreadstats)
**Tool for computing long-read statistics**

- **Language**: Groovy  
- **License**: MIT License  
- **Description**: This tool computes statistical measures on long-read sequencing data, helping to assess the quality and distribution of reads for large genome projects.  
- **Stars**: 1  
- **Updated**: Mar 26, 2023  

---

## [k-count-nf](https://github.com/1000GCh/k-count-nf)
**A Nextflow pipeline to count k-mers and estimate genome size from WGS data**

- **Language**: Nextflow  
- **License**: MIT License  
- **Description**: This Nextflow pipeline estimates genome size by counting k-mers in whole-genome sequencing (WGS) data. K-mer counting is essential for understanding genome complexity and guiding assembly strategies.  
- **Stars**: 2  
- **Updated**: Dec 29, 2021  
