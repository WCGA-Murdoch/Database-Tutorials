# The Barley pangenome databases

This section include the Introduction and Tutorials for the Barley pangenome tools available on the database.

## <span style="color:#023047"> I. Introduction </span>

Pan-genomic resources are getting more and more popular since they cover a wider range of genetic information compared to single references. At the Western Crop Genetics Alliance, we utilised cutting-edge sequencing technologies to obtain high-quality sequences from a wide range of commercial and wild barley accessions. The sequence data was used to generate high-quality genome assemblies, capture genetic variants and construct reference pan-genome graphs. These information were put together to form an interactive and searchable database, which could be made available to breeders to improve the genetic selection process and deliver improved varieties to growers across Australia.

## <span style="color:#023047"> II. Current available data </span>

### 1. Genome assembly and annotation

**a. Barley Pangenome phase 2 assemblies**

Including genome assemblies and annotations from 76 barley accessions. Detailed accession list can be seen [here](/info/pangenome_accessions.md)

**b. Australian Barley assemblies**

Including genome assemblies and annotations from 22 Australian Barleys. Detailed accession list can be seen [here](/info/AUbarley_accessions.md)

### 2. Genetic variants

Genetic variants including InDels and SNPs were obtained from a wide range of datasets, including:

**a. Approximately 1,000 barley accession from a world-wide collection**

Detailed accession list can be seen [here](https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/362/E-MTAB-7362/Files/E-MTAB-7362.sdrf.txt).

Genetic variants from this dataset:

* Low coverage - whole genome sequence

* Targeted enrichment of gene regions associated with flowering time

* Variants from Diversity Array Technology Sequence (DArT-seq)

**b. Pan-genome phase 2 collection**

Variant data from 76 barley accessions from the pan-genome graph, with about 10 million InDels and over 80 million SNPs. Detailed accession list can be seen [here](/info/pangenome_accessions.md)

**c. Australian Barley collection**

Variant data from 90 barley accessions related to Australian Barley germplasm. Detailed accession list can be seen [here](info/AU_90_variant.md)

### 3. Pan-genomic Present/Absent variations

The Pangenome Present/Absent variations (PAV) data were obtained from ODGI and loaded into Panache for interactive browsing. Details about Panache can be located [here](https://github.com/SouthGreenPlatform/panache)

### 4. Pan-transcriptome data

The Barley Pan-transcriptome database is obtained 5 different tissues of 20 Barley accessions. More information about the data can be seen from the below publication:

[A barley pan-transcriptome reveals layers of genotype-dependent transcriptional complexity](https://www.researchsquare.com/article/rs-3787876/v1)

## <span style="color:#023047"> III. Tools overview </span>

### 1. Getting start

The WCGA barley pangenome database can be accessed using this [link](database.barleypangenome.com)  
To start using the WCGA barley pangenome database, you need to register an account. Please refer to this [link](tools/registration.md) for information about the registration process.  
For more information about each tool and available data, please refer to the below sections.  

### 2. Barley genome browser  

For a detailed instruction about using the Barley genome browser, please refer to this link: [The Barley genome browsers](tools/barley_jbrowse.md)

The Barley genome browsers were built based on [Jbrowse v2](https://jbrowse.org/jb2/) with whole genome sequences and annotations of 76 Barley accessions in the Barley pangenome phase 2 collection and 22 accessions in the Australian barley collection.

Information about navigating the genome browsers can be found [here](tools/barley_jbrowse.md)

**a. Features**

* Genes lookup by gene IDs  
* Gene and CDS sequences extraction, including up stream and down stream regions  
* Cross-variant gene ID search. Search using Morex gene IDs on Morex V3 positions, gene IDs matching.
* Genetic variants view with annotations

**b. Data currently available on the genome browsers**

**Genome assembly tracks**

* Genome assemblies of 76 barley accession from the [Pan-genome collection](/info/pangenome_accessions.md)  
* Genome assemblies of 22 barley accession from the [Australian barley collection](/info/AUbarley_accessions.md)   

**Annotations tracks**

* Functional annotations for 76 barley accession of the [Pan-genome collection](/info/pangenome_accessions.md)  
* Functional annotations of 22 barley accession from the [Australian barley collection](/info/AUbarley_accessions.md)  
* Morex version 1 and version 2 lift off to Morex version 3 for quick gene ID convert (reference: MorexV3 assembly)  


**Variant tracks - Morex V3 reference**

* Diversity Array Technology Sequence (DArT-seq) for [1,000 barley accessions](https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/362/E-MTAB-7362/Files/E-MTAB-7362.sdrf.txt)
* Variants from Low-coverage whole genome sequence of [1,000 barley accessions](https://ftp.ebi.ac.uk/biostudies/fire/E-MTAB-/362/E-MTAB-7362/Files/E-MTAB-7362.sdrf.txt)  
* Variant data from [90 barley accessions related to Australian Barley germplasm](info/AU_90_variant.md)  
* Pangenome variant data from [76 pangenome accessions](/info/pangenome_accessions.md)  
* Variant data lifted off from Clipper of [22 Australian barley with genome assemblies](/info/AUbarley_accessions.md)  

**Variant tracks - Clipper reference**

* Variant data of [22 Australian barley with genome assemblies](/info/AUbarley_accessions.md)  

### 3. Barley panache database

For a detailed instruction about using the Barley panache database, please refer to this link: [The Barley panache browsers](tools/barley_panache.md)  

The Barley panache browsers was built from the barley pangenome graph (generated from [PGGB](https://github.com/pangenome/pggb) and [Panache](https://github.com/SouthGreenPlatform/panache) of 76 Barley accessions.

**a. Features**

* Gene search by gene ID  
* Genomic region search  
* Sorting by gene PAV, local PAV, phylogeny, and alphanumeric  

**b. Data currently available for Panache**

* PAV data of [76 barley in the pangenome collection](/info/pangenome_accessions.md)  

### 4. Barley variant database

For a detailed instruction about using the Barley variant database, please refer to this link: [The Barley variant databases](tools/barley_variantdb.md)

**a. Features**

* Query using physical position or gene IDs  
* Extraction of genetic information around the variants for primers designing  
* Result table export to csv format  

**b. Data currently available**

[The Barley variant databases](tools/barley_variantdb.md) contains approximately 54 million SNPs and 3.6 million InDels, from a collection of 21 Barley accessions.
These variants were called based on Morex v1 sequence and annotated using Morex v1 annotation.

### 5. Barley Linear Pan-transcriptome database

Detailed instruction about using the [Barley Linear Pan-transcriptome database](tools/barley_panbart20.md)

**a. Features**

* Query for gene expression using Morex V3 gene IDs    
* Heatmap of gene expression of 5 different tissues from 20 Barley accessions

**b. Data currently available**

The [Barley Linear Pan-transcriptome database](tools/barley_panbart20.md) features gene expression heatmap of 5 different tissues:

| Caryopsis | Coleoptile | Inflorescence | Root | Shoot |
|-----------|------------|---------------|------|-------|

from 20 barley accessions of the barley pangenome phase 1 collection. List of the barley accession can be seen [here](info/barley_panbart20.md)

## <span style="color:#023047"> IV. Work in progress </span>
