# KMC 2024 Microbiome Workshop

This repository contains all jupyter notebooks of the two day workshop held in September 2024.

## Missing input files
For running the tutorials you will need files of the GMbC 16S dataset that are currently not publicly available.

Create a directory with the name **inputs**, here following files are required:
* common_significant_features.txt
* feature-table-gmbc1.tsv
* metadata_gmbc_bn10_complete_fixed.tsv
* metagenome (looks like we should have two metagenome(a bit confusing))
* MSM79H87_R_profile.tbl
* taxonomy_gmbc1_form.csv
* tree-gmbc1.nwk

* metagenome [directory]:

  * full_MSM79H87_profile.tbl
  * genome.1.bt2
  * genome.2.bt2
  * genome.3.bt2
  * genome.4.bt2
  * genome.fa
  * genome.rev.1.bt2
  * genome.rev.2.bt2
  * GMbCv3.GTDBr220.genus.sylph_tpm.out
  * gtdb-r220-c200-dbv1.syldb
  * gtdb_taxonomy.tsv
  * MSM79H87_R_R1_clean.fastq.gz
  * MSM79H87_R_R2_clean.fastq.gz
  * MSM79H87_R_single_clean.fastq.gz
  * test_input_MSM79H87_R1.fastq.gz
  * test_input_MSM79H87_R2.fastq.gz
  * bbmap [directory]:
    * nextera.fa.gz
    * phix174_ill.ref.fa.gz
    * phix_adapters.fa.gz

Create additionally a directory called **R_objects**, which contains:
* full_phyloseq_object.RData
* rare8000_phyloseq_object.RData

## Install conda environment

You can install all required packages and tools with [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html).
Just install the environment with the following command: 
> conda env create --file kmc_16s_environment.yml --prefix kmc_workshop 
