# BIOC3301 project
This repository contains scripts (PBS and Python) and part of the data analysis for the UCL BIOC3301 project.

## pbs_scripts
Scripts that were submitted to the Cirrus HPC via the portable batch system. Contains the basic QIIME pipeline (OTU assigning, 
filtering, and demultiplexing) as well as scripts used for further analysis (e.g. beta-diversity or construction of OTU table for specific taxonomy level). This foler does not contain scripts used on a local machine, however, the full list of available scripts can be found at [http://qiime.org/scripts/index.html](http://qiime.org/scripts/index.html). 

## metadata 
This foler stores tsv files that contain external data both for our project and the [Earth Microbiome Project](http://www.earthmicrobiome.org/data-and-code/) (EMP). They include physicochemical properties of the soil, location, temperature, etc. Note that the EMP dataset was filtered to contain only soil samples (i.e. the marine sediments, etc. were excluded).

## jupyter_scripts 
ipynb scripts for  analysis and manipulation of our and EMP data.

## beta_div
This folder contains data required to construct the phylogenetic tree (representative sequences were picked and aligned) and
the tree file itself. The [Phylo.io](http://phylo.io/) resouce is convenient for tree visualisation. 

## Other folders 
**correlations** contains txt files which are output of various correlation analyses applied to our project and EMP data.
**figures** stores images, some of which were used in the report. 
**taxa_summary** stores OTU tables for specific taxonomy levels (L1-L6) rarefied at a depth of 600 reads. 
 
