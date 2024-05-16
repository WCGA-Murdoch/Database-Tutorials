# Barly databases
Tutorials for Barley genome browser and variant database

# I. Barley genome browser  

[The Barley genome browsers](jbrowse.md) were built based on [Jbrowse v2](https://jbrowse.org/jb2/) with whole genome sequences and annotations of 76 Barley accessions.
Information about navigating the genome browsers can be found [here](jbrowse.md)

The Barley pan genome browsers currently support:
* Genes lookup by gene IDs  
* Gene and CDS sequences extraction, including up stream and down stream regions  
* Cross-variant gene ID search. Search using Morex gene IDs on Morex V3 positions, gene IDs matching.
* Genetic variants view with annotations  

**TO DO:**  
* Add SNP matrix of current Morex V3. Only Morex V1 currently available for variant DB.

# II. Barley variant database

[The Barley variant databases](variantdb.md) contains approximately XX million SNPs and XX million InDels, from a collection of XX Balrey accessions.
These variants were called based on Morex v1 sequence and annotated using Morex v1 annotation.

The variant database currently support:
* Query using physical position or gene IDs
* Extraction of genetic information around the variants for primers designing
* Result table export to csv format 
