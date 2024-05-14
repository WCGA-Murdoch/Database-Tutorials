# Oat databases
Tutorials for Oat genome browser and variant database

# I. Oat genome browser  

[The Oat genome browsers](jbrowse.md) were built based on [Jbrowse v2](https://jbrowse.org/jb2/) with whole genome sequences and annotations of 24 Oat accessions.
Information about navigating the genome browsers can be found [here](jbrowse.md)

The Oat pan genome browsers currently support:
* Genes lookup by gene IDs  
* Gene and CDS sequences extraction, including up stream and down stream regions  
* Cross-variant gene ID search. Search using GS7 and Bannister gene IDs on OT3098v2 positions, gene IDs matching.
* Genetic variants view with annotations  

**TO DO:**  
* Combine functional annotations with current gene annotations for all accessions. Currently, only OT3098v2 have functional annotations included.

# II. Oat variant database

[The Oat variant databases](variantdb.md) contains approximately 350 million SNPs and 35 million InDels, from a collection of 564 Oat accessions.
These variants were called based on PepsiCo OT3098 Oat v2 sequence and annotated using PepsiCo OT3098 Oat v2 annotation.

The variant database currently support:
* Query using physical position or gene IDs
* Extraction of genetic information around the variants for primers designing
* Result table export to csv format 
