
# Satellite Imagery Classification with Deep Learning
## Lisa Taylor
### Springboard Data Science Bootcamp - Capstone Project 2

Satellite imagery is crucial for many applications in agriculture, city planning, natural resource management, environmental monitoring, and disaster response.  Since satellite imagery can cover large areas, the labor costs to manually categorize land uses covered by imagery can be prohibitive.  Deep learning has emerged as an important approach for automating land use classification over extensive areas.

For this project, I have applied deep learning using convolutional neural networks (CNNs) to classify labelled satellite image tiles from the [DeepSat-6 dataset](https://www.kaggle.com/crawford/deepsat-sat6) into six land use classes.  Two approaches were implemented in Keras:  building a custom CNN from scratch and using a pre-trained CNN.  Both approaches achieved over 96% accuracy on held-out data.  
The custom CNN was also applied to classify new, contiguous satellite imagery not part of the original DeepSat-6 dataset.

This repository includes three final notebooks:<br>
* [Data Acquisition, Checking, and Preparation](SatelliteImagery_DataPreparation.ipynb)
* [Satellite Imagery Classification with a Simple CNN](SatelliteImageryClassification.ipynb)
* [Satellite Imagery Classification with Transfer Learning](SatelliteImageryClassification_Transfer.ipynb)

The results are documented in a [Final Report](Capstone%202%20Final%20Report.pdf) and 
[Final Presentation](Capstone%202%20Final%20Presentation.pdf)

![Tiles](examples.png)

