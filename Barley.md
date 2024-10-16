# The Barley pangenome databases

This section include the Introduction and Tutorials for the Barley pangenome tools available on the database.

## <span style="color:#023047"> I. Introduction </span>

## <span style="color:#023047"> II. Current available data </span>

### 1. Genome assembly and annotation

**a. Barley Pangenome phase 2 assemblies**

Including genome assemblies and annotations from 76 barley accessions. Detailed accession list can be seen [here](/info/pangenome_accessions.md)

**b. Australian Barley assemblies**

Including genome assemblies and annotations from XX Australian Barleys. Detailed accession list can be seen [here](Link)

### 2. Genetic variants

Genetic variants including InDels and SNPs were obtained from a wide range of datasets, including:

**a. Approximately 1,000 barley accession from a world-wide collection**

Detailed accession list can be seen [here](https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/362/E-MTAB-7362/Files/E-MTAB-7362.sdrf.txt).

Genetic variants from this dataset:

* Low coverage - whole genome sequence

* Targeted enrichment of gene regions associated with flowering time

* Variants from Diversity Array Technology Sequence (DArT-seq)

**b. Pan-genome phase 2 collection**

Including variant data from 76 barley accessions from the pan-genome graph, with about 10 million InDels and over 80 million SNPs. Detailed accession list can be seen [here](/info/pangenome_accessions.md)

**c. Australian Barley collection**

Including variant data from 90 barley accessions related to Australian Barley germplasm. Detailed accession list can be seen [here](Link)

### 3. Pan-genomic Present/Absent variations

The Pangenome Present/Absent variations (PAV) data were obtained from ODGI and loaded into Panache for interactive browsing. Details about Panache can be located [here](Link)

### 4. Pan-transcriptome data



## <span style="color:#023047"> III. Tools overview </span>

### 1. Barley genome browser  

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

### 2. Barley panache database

For a detailed instruction about using the Barley panache database, please refer to this link: [The Barley panache browsers](barley_panache.md)

[The Barley panache browsers](barley_panache.md) was built from the barley pangenome graph (generated from [PGGB](https://github.com/pangenome/pggb) and [Panache](https://github.com/SouthGreenPlatform/panache) of 76 Barley accessions.

The Barley panache supports:
* Gene search by gene ID
* Genomic region search
* Sorting by gene PAV, local PAV, phylogeny, and alphanumeric

### 3. Barley variant database

For a detailed instruction about using the Barley variant database, please refer to this link: [The Barley variant databases](variantdb.md)

[The Barley variant databases](variantdb.md) contains approximately XX million SNPs and XX million InDels, from a collection of XX Balrey accessions.
These variants were called based on Morex v1 sequence and annotated using Morex v1 annotation.

The variant database currently support:
* Query using physical position or gene IDs
* Extraction of genetic information around the variants for primers designing
* Result table export to csv format
