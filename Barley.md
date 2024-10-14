# The Barley pangenome databases

This section include the Introduction and Tutorials for the Barley pangenome tools available on the database.

# I. Introduction

# II. Current available data


# III. Tools overview

## 1. Barley genome browser  

For a detailed instruction about using the Barley genome browser, please refer to this link: [The Barley genome browsers](jbrowse.md)

[The Barley genome browsers](jbrowse.md) were built based on [Jbrowse v2](https://jbrowse.org/jb2/) with whole genome sequences and annotations of 76 Barley accessions.
Information about navigating the genome browsers can be found [here](jbrowse.md)

The Barley pan genome browsers currently support:
* Genes lookup by gene IDs  
* Gene and CDS sequences extraction, including up stream and down stream regions  
* Cross-variant gene ID search. Search using Morex gene IDs on Morex V3 positions, gene IDs matching.
* Genetic variants view with annotations  

**TO DO:**  
* Add SNP matrix of current Morex V3. Only Morex V1 currently available for variant DB.

## 2. Barley panache database

For a detailed instruction about using the Barley panache database, please refer to this link: [The Barley panache browsers](barley_panache.md)

[The Barley panache browsers](barley_panache.md) was built from the barley pangenome graph (generated from [PGGB](https://github.com/pangenome/pggb) and [Panache](https://github.com/SouthGreenPlatform/panache) of 76 Barley accessions.

The Barley panache supports:
* Gene search by gene ID
* Genomic region search
* Sorting by gene PAV, local PAV, phylogeny, and alphanumeric

## 3. Barley variant database

For a detailed instruction about using the Barley variant database, please refer to this link: [The Barley variant databases](variantdb.md)

[The Barley variant databases](variantdb.md) contains approximately XX million SNPs and XX million InDels, from a collection of XX Balrey accessions.
These variants were called based on Morex v1 sequence and annotated using Morex v1 annotation.

The variant database currently support:
* Query using physical position or gene IDs
* Extraction of genetic information around the variants for primers designing
* Result table export to csv format
