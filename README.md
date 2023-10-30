# GEO Accession with GEOquery Package

Welcome to the GEO Accession repository! This README provides an overview of how to access gene expression data from the Gene Expression Omnibus (GEO) using the GEOquery package in R.

![geo](https://github.com/Moha-cm/GEO_accession/assets/118077473/3298d386-775b-4d54-9b44-b00f87a51290=250x250)

## Introduction

The GEOquery package is a valuable tool for extracting high-throughput experimental data from the National Center for Biotechnology Information (NCBI) GEO. It allows you to access a wide range of data, including samples, series, and platforms, which are submitted to the GEO Datasets database by data owners.

## Getting Started

- To access the metadata associated with GSM (GSMxxx) sample IDs, follow our tutorial on [Accessing Metadata with GSM Sample IDs](https://moha-cm.github.io/GEO_accession/).

- To access metadata by GSE (GSExxx) IDs, refer to the documentation within the repository.

## Overview of GEO

The Gene Expression Omnibus (GEO) is a public repository [GEO Link](https://www.ncbi.nlm.nih.gov/geo/) that hosts data submitted by various array-based applications and high-throughput sequencing experiments. It includes raw and processed data, covering a wide range of experimental types, such as microarrays, RNA sequencing, ChIP experiments, and DNA sequencing. GEO classifies data into four main categories: platforms, samples, series, and datasets.

- **Platforms (GPLxxx):** These identify the experimental platforms and the elements used in experiments.

- **Samples (GSMxxx):** Each sample record provides information about the sample conditions used in experiments.

- **Series (GSExxx):** Series records group samples and provide details about the experimental design, including the array platform used.

- **Datasets:** Datasets contain curated sets of sample data for data display and analysis. They often share a common probe design.

  



![GEO 2](https://github.com/Moha-cm/GEO_accession/assets/118077473/449b2424-75e1-4fac-9ac9-f90d4d4d1449=250x250)


![GEO 3 1](https://github.com/Moha-cm/GEO_accession/assets/118077473/bff98815-976a-4fa3-a8da-c46f4f028952=250x250)

## GEOquery Package

The GEOquery package is an R tool that simplifies interactions with the NCBI GEO database, making it easy to access gene expression data. You can download data as a list of experiments, including platform information.

## Accessing Data

- To check the list of experiments associated with the data, use the following code:
  ```R
  gsm_list <- getGEO(x)
  total_platform <- length(gsm_list)




























    
  
  
  

  
        

  
