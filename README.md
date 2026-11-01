Data Description
This document describes all datasets used in this study and corresponds to the Data Availability Statement in the paper.

**1. General Information**
Dataset name: A Hybrid Beam Search Framework with Deep Representation Learning — Datasets
Repository: https://github.com/green286/-
Data release page: https://github.com/green286/-/releases/tag/data
Creator/Contact: Hailin Ran, Guizhou University of Finance and Economics, 2839037341@qq.com
Data version: v1.0
Last updated: 2026-11-01

**2. Dataset Overview**
Dataset	Type	Source	 Location
Simulated/Random dataset	Synthetic	Generated as described in Section 5.1	  random/
Real biological dataset	Public data	Complete bacteriophage genome sequences from the NCBI Nucleotide database	real/, 50realsequences.fasta, 100realsequences.fasta

**3. Simulated/Random Dataset (random/)**
Generation method: Generated as described in the Experimental Setup section of the paper.
Data dimensions: Each sequence file contains 30 sequences, each with a length of 1000 bp.
File list:
File name / Directory	Content	Format	Records per file
random/length/	Simulated datasets grouped by sequence length	FASTA	30 sequences × 1000 bp
random/number1/	Simulated datasets grouped by sequence number	FASTA	30 sequences × 1000 bp

**4. Real Biological Dataset (real/)**
**4.1 File list**
File name / Directory	Content	Format	Records per file
real/length/	Real bacteriophage genome sequences grouped by sequence length	FASTA	30 sequences × 1000 bp
real/number/	Real bacteriophage genome sequences grouped by sequence number	FASTA	30 sequences × 1000 bp
50realsequences.fasta	50 real bacteriophage genome sequences	FASTA	50 sequences × 1000 bp
100realsequences.fasta	100 real bacteriophage genome sequences	FASTA	100 sequences × 1000 bp
Note: The FASTA files in the real/length/ and real/number/ directories contain 30 sequences of 1000 bp each, used for specific experimental settings.

**4.2 Description**
Source: NCBI Nucleotide database (https://www.ncbi.nlm.nih.gov/nucleotide/)
Data type: Public complete bacteriophage genome sequences
Sequence type: DNA
Data nature: All data are public and non-sensitive; no personal or private information is included.
FASTA format:
Lines starting with > are sequence headers, followed by the sequence.
Sequence characters are A/T/G/C; unknown bases are represented by N (if any).
Line width: 70 characters per line.
Sequences are in the original orientation; no reverse complement was applied.

**5. Usage Restrictions and Citation**  
License: CC BY 4.0
Usage requirements: Please cite the data source when using these data; cite this study when using the simulated data.
Citation format:
Hailin Ran. A Hybrid Beam Search Framework with Deep Representation Learning — Datasets (v1.0) [DS]. 2026. https://github.com/green286/-
Disclaimer: The data are provided for reference only. Users should evaluate their suitability independently; the authors are not responsible for any consequences of use.
