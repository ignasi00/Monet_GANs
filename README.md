# Monet GANs (Generative Adversarial Neworks)

## Introduction

Kaggle link: https://www.kaggle.com/c/gan-getting-started/overview/description

“Every artist dips his brush in his own soul, and paints his own nature into his pictures” - Henry Ward Beecher

## Structure

- data_lists: lists which contain the pathes of the images we will use. This directory will be empty, because the lists will be personal of each member (each member will have his own file structure). In root directory it will be an script to generate lists (to genereate each member lists). It will contain the lists that will be loadeded by the datasets.
- dataloaders: custom dataloaders with elaborated collate_fn, batch_samplers, etc if needed. We wish we will leave this folder empty.
- datasets: dataset objects will be defined.
  - wrappingdatasets: modules to transformate all data included in a dataset.
    - custom_transforms: modules defining custom data transformations if needed. We think we will leave this folder empty.
- docopts: 
- extern: 
- list_utils: 
- loggers: 
- losses: 
- metrics: 
- model_parameters: 
- models: 
- optims: 
- train_utils: 

## First Steps

- Download the
- Analize Kaggle datasets
- Embrance the structure of the project

