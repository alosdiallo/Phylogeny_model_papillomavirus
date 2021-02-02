# Phylogeny Model Papillomavirus
This repository is used to store instructions for running MrBayes to examine virus data on a computing cluster running LSF.
To run this code please run the following command:
bsub -W 168:00 -q long -N -o log.txt mb helper.nexus

This is for a single cpu where mb is MrBayes and helper.neux links to your nexus data.  
To make a nexus file from a fasta file please see:
http://sequenceconversion.bugaco.com/converter/biology/sequences/fasta_to_nexus.php

The nexus file included is expected to take days to run, depending on your computing environment.  This was tested using CentOS.
### Publications 
### [Novel canine papillomavirus type 18 found in pigmented plaques](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5886900/)
### [Canine papillomavirus types 1 and 2 in classical papillomas: High abundance, different morphological associations and frequent co-infections](https://www.sciencedirect.com/science/article/abs/pii/S1090023318302089)

Authors
--------------------
	Alos Diallo - Department of Immunology, Harvard Medical School
  
Copyright © 2018 the President and Fellows of Harvard College.

![Blavatnikimmunology](https://github.com/alosdiallo/DNA_Rchitect/blob/master/App/www/Blavatnikimmunology.jpg)

### [MIT License](https://github.com/alosdiallo/HiC_Network_Viz_tool/blob/master/Licence.txt)
