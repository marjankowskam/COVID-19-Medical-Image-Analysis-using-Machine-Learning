# Cellular Image Classification for Drug Discovery

An  [Engineers Without Borders]([url](https://www.ewb-uk.org/)) 
 Oxford project exploring machine learning
for identifying genetic perturbations in cellular microscopy images.

Using the RxRx1 dataset from Recursion, we investigated how image
classification could help distinguish biological changes from
experimental variation.

## Approach

- Preprocessed six-channel fluorescence microscopy images.
- Merged pairs of channels into three-channel inputs for a pretrained ResNet-18.
- Trained the final classification layer to predict siRNA perturbations.
- Achieved 90.4% validation accuracy in experiments using a subset of approximately 4,000 images.

## Repository contents

Image preprocessing scripts and ResNet-18 training and evaluation code.

## Context

This repository preserves an early undergraduate team project.
The accompanying presentation discusses the motivation, experiments,
limitations and potential extensions.

<img width="570" height="210" alt="ewbo" src="https://github.com/user-attachments/assets/78f07af4-4c21-42c8-9ad5-0c3f7893988d" />
