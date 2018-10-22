# marta-eDNA data analysis
# eDNA analysis - Deciphering community structure from Intertidal Puget Sound water samples 

My project involves analyzing data published by Ryan Kelly and his team at SMEA. I will start with the raw data, and from two of the files (forward and reverse sequences), I will determine what taxa is present following their established protocols and pipeline.

## My goals are:
- To learn how to use all the bioinformatic platforms necessary for my project like Markdown, Github, GitBash, Jupiter, etc.
- To get familiar with all the specific programs needed to clean, pair, and cluster data (PEAR, usearch, cutadapt,seqtk, blastn, and MEGAN)
- Apply what I learn during the quarter to the analyze my own data when I collect my samples in December 2018

## Objectives

1. Merge paired-end reads with PEAR
2. Quality filter with usearch
3. Remove primers with cutadapt
4. Reverse complement appropriate sequences with seqtk
5. Remove sequences containing homopolymers (BSD Unix: grep; awk)
6. Consolidate identical sequences with usearch
7. Remove singletons with usearch
8. Cluster sequences into OTUs using usearch
9. BLAST clusters using blastn
10. Perform common ancestor grouping in MEGAN.


## Timeline

* Week 4: Install and get familiar with PEAR, usearch, and cutadapt. 
* Week 5: Steps 1 & 2 in objectives


## Repository Organization

### Data 
Raw data and other data files being generated as the analysis progresses 
### Analysis
All files that contain code for analysis of data
### README
Markdown files documenting steps of analyses and progress


#### NOTE: other folders will be added if additional information does not fit the originally established project organization.
