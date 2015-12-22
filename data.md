---
layout: content_page
title: "Data"
permalink: /data/
tags: Data
nav_buttons:
    - announcements
    - files_formats
    - software_tools
    - pilot_paper
    - contacts
---

{::options parse_block_html="true" /}

<div class="enclosed">

# 1000 Genomes Data and Sample Information

The 1000 Genomes Project is a community resource project that aims to release data rapidly for the benefit of the scientific community.

[Description of data released by the project](#data-released-by-the-1000-genomes-project)  
[How to Access 1000 Genomes Data](#how-to-access-1000-genomes-data)  
[Data Release Policy](#data-release-policy)  
[Sample Availability](#sample-availability)  
[Use of the Project data, presentations and publications, and authorship](#DataUse)

</div>



<div class="enclosed">

# Data released by the 1000 Genomes Project

## Sample lists and sequencing progress

A summary of sequencing done for each of the three pilot projects is available [here](/sites/1000genomes.org/files/docs/PilotsSummary.pdf). The list of samples and allocations is provided in a [spreadsheet](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/wo
rking/20130606_sample_info/20130606_sample_info.xlsx).

## Variant Calls

Our variant calls are always released in [vcf format](/wiki/Analysis/Variant%20Call%20Format/vcf-variant-call-format-version-41). The released can be found in the release directory [EBI](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/release)\|[NCBI](ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/release).

## Alignments

The main project alignments are available in [BAM](http://samtools.sourceforge.net/) format. A list of the files currently available can be found in the alignment index [EBI](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/alignment.index)\|[NCBI](ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/alignment.index). Alignment statistics can be found in the alignment_indices directory [EBI](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/alignment_indices)\|[NCBI](ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/alignment_indices). There is also a [README](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/historical_data/former_toplevel/README.alignment_data.md) which explains the alignment process and file layout

## Raw sequence files

The main project raw sequence data is available in fastq format. A list of files currently available can be found in the sequence.index [EBI](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/sequence.index)\|[NCBI](ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/sequence.index) Sequence statistics can be found in the sequence_indices directory [EBI](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/sequence_indices)\|[NCBI](ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/sequence_indices). There is also a [README](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/historical_data/former_toplevel/README.sequence_data) which explains the sequence processing and the file layout

</div>




<div class="enclosed">

# How to Access 1000 Genomes Data

## Download data

The data for this project can be downloaded from the 1000 Genomes FTP site hosted at the EBI [ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/)

The data can be downloaded via FTP, aspera and globus gridftp. More information about using aspera or globus can be found in our FAQ

[How to download files using aspera](http://www.1000genomes.org/faq/how-download-files-using-aspera)  
[How to download files using globus](http://www.1000genomes.org/faq/can-i-access-1000-genomes-data-globus-online)

The NCBI and the Amazon S3 bucket still hosts 1000 Genomes data but no longer mirrors new data posted by the ongoing project. Both these locations reflect the structure of the FTP site in August 2015 and hold all the pilot, phase1 and phase3 data.

NCBI FTP Site : [ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp  
](ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp)Amazon S3 : [s3://1000genomes](denied:s3://1000genomes)

<span style="font-size: 1.5em;">FTP Hierarchy </span>

The FTP structure was changed in September 2015\. The new structure is described in the [FTP site structure README](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/README_ftp_site_structure.md) 

## Browse data

The first set of SNP calls representing the [July 2010](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/pilot_data/release/2010_07/) data release can be viewed directly through the 1000 Genomes browser at [http://browser.1000genomes.org](http://browser.1000genomes.org "http://browser.1000genomes.org"). Launch the browser and [view a sample region here.](http://browser.1000genomes.org/Homo_sapiens/Location/View?r=6:133017695-133161157)

**For more information about using the 1000 Genomes browser, download the [Quick start guide](/sites/1000genomes.org/files/documents/1000genomes_browser_quickstart.pdf)**

## Amazon Web Services

The alignment files for the 1000 Genomes Pilot Porject are available as a [public data set](http://aws.amazon.com/publicdatasets/) via Amazon Web Services (AWS). Further information can be found on 1000 Genomes [public data set page](http://aws.amazon.com/datasets/4383) or directly on [http://s3.amazonaws.com/1000genomes](http://s3.amazonaws.com/1000genomes).

</div>

<div class="enclosed">

# Data release policy

As a community resource project, the 1000 Genomes Project publicly releases data on a regular basis. The sequencing centers release the raw reads to the SRA. The Data Processing Group, Analysis Group, and DCC release alignments, re-calibrated error rates, and SNP calls on individual samples. Data that passed quality filters are the most visible, but data that did not pass quality filters are also available. When the Structural Variation Group has developed its methods, the structural variant calls on individual samples will be released. Eventually the Project will release haplotypes and imputed variant calls. Data formats and analysis software developed by the Project are also made publicly available.

</div>


<div class="enclosed">

# Sample Availability

All the samples studied by the 1000 Genomes Project are or will be available as DNA and cell lines to scientific investigators for research projects. Many of the samples are currently available from the non-profit [Coriell Institute for Medical Research](http://ccr.coriell.org/sections/Collections/NHGRI/hapmap.aspx?PgId=266&coll=GM). Cell lines and DNA from additional populations will become available through 2011.

</div>

<div class="enclosed">

# Use of the Project data, presentations and publications, and authorship
{: #DataUse}

The data producers release the Project data quickly, prior to publication, in the expectation that they will be valuable for many researchers. In keeping with [Fort Lauderdale principles](http://www.genome.gov/Pages/Research/WellcomeReport0303.pdf), data users may use the data for many studies, but are expected to allow the data producers to make the first presentations and to publish the first paper with global analyses of the data.

### Global analyses of Project data

The Project plans to publish global analyses of the sequence data and quality, SNPs, structural variants, STRs and <span>microsatellites</span> and haplotypes and LD patterns, population genetic phenomena such as population comparisons, mutation rates, and signals of selection, and functional annotations, as well as analyses of regions of general interest such as HLA. Talks, posters, and papers on all such analyses are to be published first by the 1000 Genomes Consortium, by approved presenters on behalf of the Project, with the Consortium as author. When the first major Project paper on these analyses is published, then researchers inside and outside the Project are free to present and publish using the Project data for these and other analyses.

### Large-scale analyses of Project data

Groups within the Project may make presentations and publish papers on more extensive analyses of topics to be included in the main analysis presentations and papers, coincident with the main project analysis presentations and papers. The major points would be included in the main Project presentations and papers, but these additional presentations and papers allow more focused discussion of methods and results. The author list would include the Consortium.

### Methods development using Project data

Researchers who have used small amounts of Project data (<= one chromosome) may present methods development posters, talks, and papers that include these data prior to the first major Project paper, without needing Project approval or authorship, although the Project should be acknowledged. Methods presentations or papers on global analyses or analyses using large amounts of Project data, on topics that the Consortium plans to examine, would be similar to large-scale analyses of Project data: researchers within the Project may make presentations or submit papers at the same time as the main Project presentations and papers, and others could do so after the Project publishes the first major analysis paper.

### Disease studies using Project data

Researchers may present and publish on use of Project data in specific chromosome regions (that are not of general interest) or as summaries (such as the total number of variants) for disease studies without Project approval, prior to the first major Project paper being published. The Project should not be listed as an author.

### Population comparisons using Project data

Researchers may use Project data as controls or additional information for comparisons with their samples from people with particular diseases or from other populations, prior to the major Project paper being published, as long as the analyses that the Project plans to do are not included. These are not Project studies, and the Project should not be listed as an author.

Researchers who have questions about whether they may make presentations or submit papers using Project data, or whether to include the 1000 Genomes Consortium as an author, may [contact](/contact) Richard Durbin, David Altshuler, Gil McVean, Gonçalo Abecasis, or Lisa Brooks.

</div>
