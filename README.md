# nifH-ASV-workflow
This repository contains all post-pipeline software stages and data deliverables from the workflow described in Morando, Magasin et al. 2023.  The workflow was used to process nearly all nifH amplicon data sets (MiSeq) that existed at the time of publication.  DADA2 ASVs were created by the pipeline (green in the figure below; repository [here](https://github.com/jdmagasin/nifH_amplicons_DADA2)). Post-pipeline stages (orange), each executed by a Makefile, were used to gather the ASVs from all studies, filter them for quality, and annotate them.  The two main data resources generated by the workflow, the nifH ASV database and the nifH ASV catalog, will support future research in to nitrogen-fixing marine microbes.

[![Overview of the workflow](image path)](url)

This map shows all studies processed by the workflow. It links to an interactive Google map with study names, sample IDs, and collection information for each sample.
[![These are all the studies in our paper](Morando_Magasin_et_al_2023_studies_used.png)](https://www.google.com/maps/d/embed?mid=1M8ZCYmVIuLwEC-o1Ux_6m--uxgBIu_Q&ehbc=2E312F)
