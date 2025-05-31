# Exoplanet Detection Using Machine Learning

This project focuses on detecting exoplanets from Kepler light curve data by leveraging machine learning techniques. By analyzing the brightness variations in stellar light curves, we identify potential exoplanet transits and classify them accordingly.

## Overview

Using data from the Kepler space telescope, this project explores both deep learning and traditional machine learning approaches:
1. **CNN-LSTM**: For direct time series modeling of light curve data.
2. **Feature Engineering with MLP and XGBoost**: Using custom temporal and spectral features for enhanced classification.

## Data

- **Source**: Kepler light curve dataset.
- **Preprocessing**: Segmenting light curves, handling missing data, and applying normalization.
- **Features**: Includes flux statistics, spectral analysis, distances between transit dips, and more.

## Results

The model achieved high accuracy in distinguishing exoplanet transits, highlighting the potential of AI in exoplanet discovery within large astronomical datasets.
