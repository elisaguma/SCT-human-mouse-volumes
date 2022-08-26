# SCT-human-mouse-volumes
Data and files used to generate analyses for the SCT human mouse paper
This repository contains data and code used to create the paper “A cross-species study of sex chromosome dosage effects on mammalian brain anatomy” by E. Guma et al, currently available as a preprint on BioRxiv.

Project overview

In this study, we use comparative neuroimaging in humans and mice with the same sex chromosome trisomy (SCT) variations (XXY, XYY, and XY controls) to assess the effect of an added X- or Y-chromosome on structural neuroimaging-derived total and regional brain volume. 

In this repository
Input human data
This contains a .csv file of regions brian volumes computed with Freesurfer v7.1 for both XXY and XYY individuals and XY controls. 

For the XXY data:
AGECALC = age
DX_GROUP = karyotype (XXY & NV=XY)
MASK_3TC = unique participant ID
SEX = M: males; F: females
AGE_cent = mean centered age
All other metrics are standard Freesurfer names.

For XYY data:
dx_group = karyotype (XYY & HV=XY)
MASK_3TC = unique participant ID
sex = M: males; F: females
AGE_cent = mean centered age
All other metrics are standard Freesurfer names.

Input human data
ID: unique mouse ID
Sex = M: males (testes); F: females (ovaries)
Shorthand = karyotype

Scripts
Here are the r markdown scripts used to generate the results and figures for this paper.
