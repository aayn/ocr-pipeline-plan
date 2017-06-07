# Technical Walkthrough of the OCR Pipeline

## Goal

To have an end-to-end system that can find and extract from images.

## Pipeline Overview

![Dropbox Pipeline image](pipeline.png)

## Pipeline Modules

### Word Deep Net

![Dropbox Pipeline image](wdn.png)

- [ ] Single Word Accuracy
  - [x] Large dataset - 9M images Oxford MJSynth dataset
  - [x] Code to generate synthetic images
  - [ ] Experiments on the WDN (using Jupyter Notebooks)
    - [x] Regular architecture, based on the Keras example.
      - Trained on ~20% of the samples, performance plateaus at ~7% accuracy.
    - [x] Batch normalization added to above architecture.
      - Considerable performance improvement, accuracy ~35% by training after training on 10% of the samples.
    - [ ] Dropout
    -


