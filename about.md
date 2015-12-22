---
layout: content_page
title: "About"
permalink: /about/
tags: About
redirect_from:
    - /node/3/
nav_buttons:
    - announcements
    - media
    - pilot_paper
    - contacts
---

{::options parse_block_html="true" /}

<div class="enclosed">

# About the 1000 Genomes Project

[Project Overview](#project-overview)  
[Project Design](#project-design)  
[Use of the Project data and samples](#use-of-the-project-data-and-samples)  
[Samples included in the project](#samples-included-in-the-project)  
[Publications and project documents](#publications-and-project-documents)

</div>

<div class="enclosed">

# Project Overview

Recent improvements in sequencing technology ("next-gen" sequencing platforms) have sharply reduced the cost of sequencing. The 1000 Genomes Project is the first project to sequence the genomes of a large number of people, to provide a comprehensive resource on human genetic variation.

As with other major human genome reference projects, data from the 1000 Genomes Project will be made available quickly to the worldwide scientific community through freely accessible public databases. (See [Data use statement](#ProjectDataUse).)

The goal of the 1000 Genomes Project is to find most genetic variants that have frequencies of at least 1% in the populations studied. This goal can be attained by sequencing many individuals lightly. To sequence a person's genome, many copies of the DNA are broken into short pieces and each piece is sequenced. The many copies of DNA mean that the DNA pieces are more-or-less randomly distributed across the genome. The pieces are then aligned to the reference sequence and joined together. To find the complete genomic sequence of one person with current sequencing platforms requires sequencing that person's DNA the equivalent of about 28 times (called 28X). If the amount of sequence done is only an average of once across the genome (1X), then much of the sequence will be missed, because some genomic locations will be covered by several pieces while others will have none. The deeper the sequencing coverage, the more of the genome will be covered at least once. Also, people are diploid; the deeper the sequencing coverage, the more likely that both chromosomes at a location will be included. In addition, deeper coverage is particularly useful for detecting structural variants, and allows sequencing errors to be corrected.

Sequencing is still too expensive to deeply sequence the many samples being studied for this project. However, any particular region of the genome generally contains a limited number of haplotypes. Data can be combined across many samples to allow efficient detection of most of the variants in a region. The Project currently plans to sequence each sample to about 4X coverage; at this depth sequencing cannot provide the complete genotype of each sample, but should allow the detection of most variants with frequencies as low as 1%. Combining the data from 2500 samples should allow highly accurate estimation (imputation) of the variants and genotypes for each sample that were not seen directly by the light sequencing.

</div>




<div class="enclosed">

# Project Design

## Pilot Project

Three pilot studies provided data to inform the design of the full-scale project:

| Pilot | Purpose | Coverage | Strategy | Status
|:-:|:-:|:-:|:-:|:-:|
| 1 - low coverage | Assess strategy of sharing data across samples | 2-4X | Whole-genome sequencing of 180 samples | Sequencing completed October 2008 |
| 2 - trios | Assess coverage and platforms and centers | 20-60X | Whole-genome sequencing of 2 mother-father-adult child trios | Sequencing completed October 2008 |
| 3 - gene regions | Assess methods for gene-region-capture | 50X | 1000 gene regions in 900 samples | Sequencing completed June 2009 |

 Public releases of summary processed data and variant calls are available through the [data tab](/data) of this website. The data from the pilot projects have been analyzed, especially to determine whether the strategy of 4X coverage is adequate to meet the goals of the Project. A paper describing the analyses of the pilot data and design of the full project was published in October in the journal _Nature_ and is available [here](/sites/1000genomes.org/files/docs/nature09534.pdf).

 A summary of sequencing done for each of the three pilot projects is available [here](/sites/1000genomes.org/files/docs/PilotsSummary.pdf). And the list of samples and allocations is provided in a [spreadsheet](/sites/1000genomes.org/files/documents/20101214_1000genomes_samples.xls). Regions targeted in Pilot 3 are available on the project [FTP site](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/pilot_data/technical/reference/).

## Main Project

The plan for the full project is to sequence about 2,500 samples at 4X coverage. The first set of samples for sequencing includes 1167 samples that already existed or could be collected quickly, from 13 populations, for sequencing in 2010 and early 2011\. The second set includes 633 samples that are being collected, from 7 populations, for sequencing in early 2011\. The third set, consisting of 700 samples, is expected to be available for sequencing in late 2011\. Full details of the samples to be sequenced are [below](#ProjectSamples).

</div>

<div class="enclosed">

# Use of the Project data and samples

In genome-wide association (GWA) studies, researchers aim to discover regions of the genome that are associated with particular diseases or traits. They genotype samples from hundreds to thousands of people with a disease and without a disease for hundreds of thousands to about a million SNPs and structural variants. They look for which regions have variants that are more common (containing risk variants) or less common (containing protective variants) in the people with the disease as compared to those without the disease. Because genetic variants in a region are generally associated with many other variants in the region (linkage disequilibrium, LD), a variant associated with a disease is a marker for the region it is in, but the LD patterns do not allow a determination of which particular variant or, frequently, which gene or genetic element, causally contributes to the risk for the disease.

Disease researchers will use 1000 Genomes data in two ways. They will combine the 1000 Genomes data with the genotype data in their disease GWA study to impute the genotypes in their samples for millions of additional variants beyond those they genotyped directly. They will do this computationally, with no genotyping cost. The additional genotype data will allow the researchers to localize the disease-associated regions more precisely.

Once the disease-associated regions are identified, researchers will want to know all of the variants in those regions. The Project will provide data on almost all of the variants with a frequency of at least 1% in the populations studied. This will save disease researchers the time and expense of having to sequence their own samples. Although this list will not tell them which variants cause the increased risk for the disease, it will give them the set of suspects. They will then do experimental studies to determine which genes, genetic elements, and variants functionally cause the increased risk of disease.

Many researchers will compare the allele frequencies and LD patterns that they find in their studies with those in the 1000 Genomes data. Researchers will also examine the 1000 Genomes data to study recombination, natural selection, and population structure and admixture.

DNA from the samples will be available for researchers to follow up with more detailed studies of variation in particular regions. The cell lines will allow researches to study cellular phenotypes such as gene expression, epigenetic patterns, and drug response. The extensive genotype data available on the samples, and the trio samples for some of the populations, will allow researchers to map regions of the genome computationally that affect the cellular phenotypes, and to study the heritability of these phenotypes. See [http://ccr.coriell.org/sections/Collections/NHGRI/hapmap.aspx?PgId=266&coll=GM](http://ccr.coriell.org/sections/Collections/NHGRI/hapmap.aspx?PgId=266&coll=GM)

</div>


<div class="enclosed">

# Samples included in the project

The 1000 Genomes Project developed guidelines on ethical considerations for investigators doing sampling, outlined in the  [Informed Consent Background Document](/sites/1000genomes.org/files/docs/Informed%20Consent%20Background%20Document.pdf) and the [Informed Consent Form Template](/sites/1000genomes.org/files/docs/Informed%20Consent%20Form%20Template.pdf) for new collections. All new collections included in the Project followed these ethical guidelines and model informed consent language. The 1000 Genomes Project Steering Committee, with input from the Project's Samples and ELSI Group, made final decisions about which populations and sample sets to include in the Project.

The samples for the 1000 Genomes Project mostly are anonymous and have no associated medical or phenotype data; for some of the populations the collectors have phenotype data but these data are not at Coriell and are not distributed. Although the 1000 Genomes samples have no phenotype data, the genetic variation data produced by the Project will be used by researchers to study many diseases, in sets of disease and control samples that have been carefully phenotyped. More information about using the 1000 Genomes project data is available on the [data tab](/data) of this website.

Below is a summary of the samples the 1000 Genomes project has sequenced. A full list of these samples is available from our [sample spreadsheet](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130606_sample_info/) . Cell lines for all these samples should be available from the [Coriell Cell Repository](http://ccr.coriell.org/)

## 1000 Genomes Samples

| Population | DNA sequenced from blood | Offspring Samples from Trios Available | Pilot Samples | Phase 1 Samples | Final Phase Discovery Sample | Final Release Sample | Total
|:--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Chinese Dai in Xishuangbanna, China(**CDX**) | no | yes | 0 | 0 | 99 | 93 | 99 |
| Han Chinese in Bejing, China (**CHB**) no | no | 91 | 97 | 103 | 103 | 106 |
| Japanese in Tokyo, Japan (**JPT**) | no | no | 94 | 89 | 104 | 104 | 105 |
| Kinh in Ho Chi Minh City, Vietnam (**KHV**) yes | yes | 0 | 0 | 101 | 99 | 101 |
| Southern Han Chinese, China (**CHS**) | no | yes | 0 | 100 | 108 | 105 | 112 |
|--|
| **Total East Asian Ancestry (EAS)**| | | **185** | **286** | **515** | **504** | **523** |
|--|
| Bengali in Bangladesh (**BEB**) | no | yes | 0 | 0 | 86 | 86 | 86 |
| Gujarati Indian in Houston,TX (**GIH**) | no | yes | 0 | 0 | 106 | 103 | 106 |
| Indian Telugu in the UK (**ITU**) | yes | yes | 0 | 0 | 103 | 102 | 103 |
| Punjabi in Lahore,Pakistan (**PJL**) | yes | yes | 0 | 0 | 96 | 96 | 96 |
| Sri Lankan Tamil in the UK (**STU**) | yes | yes | 0 | 0 | 103 | 102 | 103 |
|--|
| **Total South Asian Ancestry (SAS)** | | | **0** | **0** | **494** | **489** | **494** |
|--|
| African Ancestry in Southwest US (**ASW**) | no | yes | 0 | 61 | 66 | 61 | 66 |
| African Caribbean in Barbados (**ACB**) | yes | yes | 0 | 0 | 96 | 96 | 96 |
| Esan in Nigeria (**ESN**) | no | yes | 0 | 0 | 99 | 99 | 99 |
| Gambian in Western Division, The Gambia (**GWD**) | no | yes | 0 | 0 | 113 | 113 | 113 |
| Luhya in Webuye, Kenya (**LWK**) | no | yes | 102 | 97 | 101 | 99 | 116 |
| Mende in Sierra Leone (**MSL**) | no | yes | 0 | | 85 | 85 | 85 |
| Yoruba in Ibadan, Nigeria (**YRI**) | no | yes | 106 | 88 | 109 | 108 | 116 |
|--|
| **Total African Ancestry (AFR)** | | | **208** | **246** | **669** | **661** | **691** |
|--|
| British in England and Scotland (**GBR**) | no | yes | 0 | 89 | 92 | 91 | 94 |
| Finnish in Finland (**FIN**) | no | no | 0 | 93 | 99 | 99 | 100 |
| Iberian populations in Spain (**IBS**) | no | yes | 0 | 14 | 107 | 107 | 107 |
| Toscani in Italia (**TSI**) | no | no | 66 | 98 | 108 | 107 | 110 |
| Utah residents with Northern and Western European ancestry (**CEU**) | no | yes | 94 | 85 | 99 | 99 | 103 |
|--|
| **Total European Ancestry (EUR)** | | | **160** | **379** | **505** | **503** | **514** |
|--|
| Colombian in Medellin, Colombia (**CLM**) | no | yes | 0 | 60 | 94 | 94 | 95 |
| Mexican Ancestry in Los Angeles, California (**MXL**) | no | yes | 0 | 66 | 67 | 64 | 69 |
| Peruvian in Lima, Peru (**PEL**) | yes | yes | 0 | 0 | 86 | 85 | 86 |
| Puerto Rican in Puerto Rico (**PUR**) | yes | yes | 0 | 55 | 105 | 104 | 105 |
|--|
| **Total Americas Ancestry (AMR)** | | | | **181** | **352** | **347** | **355** |
|==|
| **Total** | | | **553** | **1092** | **2535** | **2504** | **2577** |


## Summary of all Samples

A  [spreadsheet](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130606_sample_info/20130606_sample_info.xlsx)  detailing the samples we are sequencing and related samples for which we have HD genotype data for is available from the  [ftp site](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130606_sample_info/) . The columns are documented in the  [README](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130606_sample_info/README_20130606_sample_info) . There is also a  [pedigree file](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/working/20130606_sample_info/20130606_g1k.ped)  available. 

The samples, as cell lines and DNA, are available to researchers from the non-profit Coriell Institute for Medical Research, or will become available when the cell lines have been made. For some of the populations, additional samples are available, including ones from the children in mother-father-adult child trios. See [http://ccr.coriell.org/sections/Collections/NHGRI/hapmap.aspx?PgId=266&coll=GM](http://ccr.coriell.org/sections/Collections/NHGRI/hapmap.aspx?PgId=266&coll=GM "http://ccr.coriell.org/sections/Collections/NHGRI/hapmap.aspx?PgId=266&coll=GM")

You can see summaries of how much sequencing was carried out for the pilot and phase1 studies in the two respective publication supplementary information [http://www.nature.com/nature/journal/v467/n7319/extref/nature09534-s2.xls](http://www.nature.com/nature/journal/v467/n7319/extref/nature09534-s2.xls) and [http://www.nature.com/nature/journal/v491/n7422/extref/nature11632-s1.pdf](http://www.nature.com/nature/journal/v491/n7422/extref/nature11632-s1.pdf)

</div>




<div class="enclosed">

# Publications and project documents

## Project Documents

###May 2011

[1000 Genomes Browser Quick Start Guide](/sites/1000genomes.org/files/documents/20110517_ensembl_62_quickstart.pdf)

###October 2010

[1000 genomes pilot paper](http://www.nature.com/nature/journal/v467/n7319/full/nature09534.html)

###September 2007

[Report of the 1000 Genomes planning meeting](/sites/1000genomes.org/files/docs/1000Genomes-MeetingReport.pdf)

</div>