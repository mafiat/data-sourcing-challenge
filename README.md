# Module 6 Challenge: Data Sourcing for Geomagnetic Storm Prediction

## Background
This project consists in preparing a dataset for a prediction system to assist the NOAA Space Weather Prediction Center in predicting Geomagnetic Storms (GSTs).

These storms are caused by Coronal Mass Ejections (CMEs), which are massive bursts of plasma emitted from the Sun at irregular intervals. Earth's magnetic shield protects us from CMEs, but they can still cause Geomagnetic Storms that may damage electronic devices such as satellites, GPS systems, and essential parts of our power grids.

NASA and the Space Weather Prediction Center operate satellites that collect data on CMEs, which is then used to warn operators of power grids and GPS systems, allowing them to make necessary adjustments.

For more information, check out these videos from the Space Weather Prediction Center:
- [An Introduction to Space Weather and the Space Weather Prediction Center](#)
- [Space Weather Impact on the Power Grid](#)

Although these predictions are important, they are not always accurate, as indicated by this [NOAA Space Weather Prediction Accuracy Table](#).

## Objective
Extract data from the NASA API, specifically from two sources—GST data and CME data. You will merge these datasets and compute the average time it takes for a CME to cause a GST. This prepared dataset can later be used with Machine Learning models for predictions.

## Scope
This Challenge has three parts and must be completed in order:
1. **Request CME data from the NASA API.**
2. **Request GST data from the NASA API.**
3. **Merge and Clean the Data for Export.**


