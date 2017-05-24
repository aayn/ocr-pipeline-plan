# 9.5-Week Plan for OCR Pipeline

## Main Objective
Creating an OCR pipeline to accurately and swiftly read text off from social
media images.

## Sub-Objectives

1. Get/generate synthetic dataset. [done].
  1. Refine this as required in the later stages.
2. Single Word Accuracy (SWA) experiments using Word Deep Net (WDN) to find a good
architecture. WDN has the following components that need to be tweaked:
  1. A stack of CNNs.
  2. A stack of LSTMs.
  3. [Connectionist Temporal Classification](http://www.cs.toronto.edu/~graves/icml_2006.pdf).
3. Text localisation (using MSER).
  1. Build Wordinator which puts bounding boxes around words.
  2. Figure out how to merge small words and cut log words into a single OCR
  reading.
4. Aggregate Word Deep Net and localisation into an end-to-end system.


## Week 1 (29 May - 4 June)
  * Start Word Deep Net experiments for SWA.


## Week 2 (5 June - 11 June)
  * Continue refining WDN.


## Week 3 (12 June - 18 June)
  * Buffer.
  * Can either continue refining WDN or start with text localisation.


## Week 4 (19 June - 25 June)
  * Start text localisation.

## Week 5 (26 June - 2 July)
  * Buffer.

## Week 6 (3 July - 9 July)
  * Integrate WDN and localisation.

## Week 7 (10 July - 16 July)
  * Tweak the system as a whole.
  * This would include adding real-world negative and postive examples.


## Week 8 (17 July - 23 July)
  * Optimise the system for better performance.

## Week 9 (24 July - 30 July)
  * Buffer.
