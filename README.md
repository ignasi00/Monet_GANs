# Monet GANs (Generative Adversarial Neworks)

## Introduction

Kaggle link: https://www.kaggle.com/c/gan-getting-started/overview/description

“Every artist dips his brush in his own soul, and paints his own nature into his pictures” - Henry Ward Beecher

## Structure

- **data_lists:** lists which contain the pathes of the images we will use. This directory will be empty, because the lists will be personal of each member (each member will have his own file structure). In root directory it will be an script to generate lists (to genereate each member lists). It will contain the lists that will be loadeded by the datasets.
- **dataloaders:** custom dataloaders with elaborated collate_fn, batch_samplers, etc if needed. We wish we will leave this folder empty.
- **datasets:** dataset objects will be defined.
  - **wrappingdatasets:** modules to transformate all data included in a dataset.
    - **custom_transforms:** modules defining custom data transformations if needed. We think we will leave this folder empty.
- **docopts:** parameters manager to the training scripts (parser).
- **extern:** to import and test external tools (the idea is use them to implement our own solution).
- **list_utils:** scripts to davide lists in train, test, validation.. Or useful functions to manage lists.
- **loggers:** 
- **losses:** losses function classes (metrics we use to optimize, they have to be differentiable).
- **metrics:** evalutation classes (they are only to evaluate and not to optimize, it is not necessary to be differentiable).
- **model_parameters:** training results (the parameters of the trainned models) (maybe better locally).
- **models:** algorithms and useful tools to define the model.
- **optims:** if we want to use our own optimizer.
- **train_utils:** useful items to the training (stopers for example).

## First Steps

- Talk to Ignasi to join the Kaggle (os tiene que invitar al team)
- Download Images: https://www.kaggle.com/c/gan-getting-started/data?select=photo_jpg
- Analize Kaggle datasets
- Embrance the structure of the project

