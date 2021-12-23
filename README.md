
# Crick Bioinformatics and Biostatistics scRNA-seq Interview Data Challenge

This repository contains the questions and data for the interview data
challenge set by the Bioinformatics & Biostatistics (BABS) group at
the Francis Crick Institute.

# The Samples

Samples were obtained from two human donors and enriched for CD3+
cells. Each sample was split into two populations and one was
activated via TCR stimulation. The sample labels are shown in the
table below. The lables are also defined in the file design.csv

| sample_id     | state         | donor        |
|:--------------|:--------------|:-------------|
| s1            | resting       | d1           |
| s2            | activated     | d1           |
| s3            | resting       | d2           |
| s4            | activated     | d2           |

# The Data

The data consists of four single cell RNA-seq samples. Each per-sample
raw-count matrix can be found in data/. The matrices are formatted with genes as
rows and cells as columns. Ensembl gene ids are used as the gene (row)
identifier. The file data/id_map.csv contains Ensembl id to gene
symbol mappings. There are 60,725 genes in each matrix. The
number of cells are as follows., s1:3809, S2:2463, s3:5757 and
s4:4365.

# The questions

## Question 1

Present a QC assessment of each sample.

## Question 2

Integrate the four samples together.

## Question 3

Identify the CD8A positive cells.

## Question 4

Identify an activation gene signature within the CD8A T cell population.

# Contact

If you have any questions regarding the data challenge please contact philip.east@crick.ac.uk
