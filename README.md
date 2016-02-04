# Phylogeny_model_papillomavirus
This repository is used to store instructions for running MrBayes to examine virus data on a computing cluster running LSF.
To run this code please run the following command:
bsub -W 168:00 -q long -N -o log.txt mb helper.nexus

This is for a single cpu where mb is MrBayes and helper.neux links to your nexus data.  
To make a nexus file from a fasta file please see:
http://sequenceconversion.bugaco.com/converter/biology/sequences/fasta_to_nexus.php

The nexus file included is expected to take days to run, depending on your computing environment.  This was tested using CentOS.

