# KMC 2024 Microbiome Workshop

This repository contains all jupyter notebooks of the two day workshop held in September 2024.

## Input files
To run the tutorials, you will need files from the GMbC 16S dataset, which have been reduced in size and randomly shuffled compared to the original dataset.

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

## Option 1: Using Jupyter Notebooks with the R Kernel

## Install conda environment

First, make sure you have Conda installed. 
You can install all required packages and tools with [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html).
Just install the environment with the following command: 
> conda env create --file kmc_16s_environment.yml --prefix kmc_workshop
> Once the environment is created, activate it
> `conda activate kmc_workshop`

## Launch Jupyter Notebook
If Jupyter is not already installed, you can install it within the environment:
`conda install jupyter`
Start Jupyter with the R kernel
`jupyter notebook`

## Option 2: Using RStudio

Ensure that Conda is installed and active (same as step 1 above).

## Link Conda Environment with RStudio:

In RStudio, go to Tools > Global Options > R and select the R Version associated with the Conda environment. 

## Run Your R Code
You can now open your R scripts or RMarkdown notebooks in RStudio and run the code, just as we did in the Jupyter environment.

# The Importance of FAIR Principles in Microbiome Research
The **FAIR Principles (Findability, Accessibility, Interoperability, and Reusability)** are essential for ensuring that scientific data can be effectively shared, reused, and integrated across different research projects. These principles enhance transparency, reproducibility, and long-term usability in microbiome research.

The data used in this workshop were generated and collected in accordance with FAIR principles, ensuring standardized, well-documented, and reusable datasets. While the content of this GitHub repository does not explicitly focus on implementing FAIR principles, they are at the core of [NFDI4Microbiota's mission](https://nfdi4microbiota.de/). We strongly encourage participants to integrate these principles into their individual research projects to improve data quality and foster collaboration.

# Questions & Discussion 💬
If you have any questions about the workshop materials or need further clarification, please use the "Issues" tab on this GitHub repository. This is the easiest and most efficient way to facilitate Q&A between instructors and participants after the workshop.

By posting your questions in the Issues section, you allow others to see previously asked questions, share insights, and contribute to discussions. Instructors will also monitor the issues and provide answers as needed.

## 📌 How to Ask a Question:
- Go to the **"Issues"** tab at the top of this repository.  
- Click on **"New Issue"**.  
- Provide a clear title and description of your question.  
- Submit the issue, and an instructor will respond.  


We encourage you to use this space to discuss topics from the workshop, troubleshoot code, and collaborate with others! 🚀

