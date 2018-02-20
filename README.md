# ASE_analyses_pipeline
Pipeline for ASE (allele specific expression) using competitive alignment to diploid genome

Below are the steps by step guide to do ASE analyses using diploid genome

    Step 01: Alignment on haploid genome to preparation of VCF file
   
   This step can be done using GATK pipeline or any other pipelines of your interest. I am not going to talk about this in detail.
  
Step 02: Preparation of phased genotype/variants
  In this step we prepare the phased variants ; but in contrary to full genome wide phased genome which are prepared using GW/CW (genome wide, chromosome wide) phasing tool, we rather run a ReadBackPhasing using VCF and BAM files. My choice of RBphasing is phaser ... weblink ?? The detailed method to prepare extended haplotype block is detailed in `phase extender` link ?? and `phase stitcher` link?? . `phase stitcher` is exclusively for F1 hybrids, but can apply to other hybrids depending on the relationship between input sample and collection of samples.
  
Step 03: Preparation of full diploid genome


Step 04: Alignment to diploid genome and transcriptome using rnaSTAR


Step 05: quantification of reads


Step 06: ASE analyses


