# Geographically and Temporally Convolutional Neural Network Weighted Regression (GTCNNWR)

An advanced spatiotemporal regression model that integrates convolutional neural networks with geographically and temporally weighted regression framework.

## Abstract

Modelling non-stationary relationships in space and time remains a central challenge in geographical analysis. While geographically and temporally weighted regression (GTWR) and its neural extension (GTNNWR) have advanced the representation of spatiotemporal non-stationarities, they face challenges in capturing global spatiotemporal effects, particularly under uneven data distributions.

GTCNNWR introduces:
- A uniform spatiotemporal division framework (GSPG for spatial, GTPA for temporal)
- Specialized CNNs for spatial and temporal feature extraction
- Spatiotemporally weighted neural network (STWNN) for feature fusion
- Significant computational efficiency improvements (75% fewer parameters than GTNNWR)

The model demonstrates at least 21% improvement in prediction accuracy on environmental datasets while maintaining greater stability with unevenly distributed samples.

## Key Features

- **Global Spatial Proximity Grid (GSPG)**: Uniform spatial division capturing global spatial relationships
- **Global Temporal Proximity Axis (GTPA)**: Uniform temporal division capturing global temporal patterns
- **CNN-based Feature Extraction**: Specialized spatial and temporal CNNs for robust feature learning
- **Spatiotemporal Feature Fusion**: STWNN effectively combines spatial and temporal features
- **Computational Efficiency**: Modular design decouples model complexity from dataset size
- **Robust Performance**: Superior accuracy and stability, especially with uneven data distributions

## Installation

pass
