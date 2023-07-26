# Identifying Biomarkers for Autism Spectrum Disorder with ROI Parcellation and Graph Neural Network 
Graph Convolutional Network on ASD Clasification

This repo is a graph convolutional network classifier of autism with functions of selecting salient biomarkers trained on ABIDE I Preprocessed Dataset. 

## Requirements
torch

torch-geometric

torch-sparse

sklearn

deepdish

## Dataset
Dataset is downloaded and preprocessed through ABIDE I Preprocessed. The preprocessed data is stored here: (https://drive.google.com/drive/folders/1QS71Ks4Vjbs4DQRkNDoz5zz4GVipV_GX?usp=drive_link). Data is processed through the pipeline provided in "BrainGNN: Interpretable Brain Graph Neural Network for fMRI Analysis" [1].

## Model Training




## Reference
[1] Li, XiaoXiao, et al., “BrainGNN: Interpretable Brain Graph Neural Network for fMRI Analysis.” ScienceDirect, 12 September 2021.

[2] Pan, Li, et al. "Identifying autism spectrum disorder based on individual-aware down-sampling and multi-modal learning." arXiv preprint arXiv:2109.09129 (2021).

[3] ElGazzar, Ahmed, Rajat Thomas, and Guido Van Wingen. "Benchmarking Graph Neural Networks for FMRI analysis." arXiv preprint arXiv:2211.08927 (2022).
