Heart Rate Analysis and Prediction
📌 Overview
This Jupyter notebook demonstrates a machine learning pipeline for analyzing and predicting heart rate using time-series data and image processing. The project leverages PyTorch for model training, custom dataset handling, and evaluation, with a focus on healthcare applications such as wearable device data analysis.

🚀 Key Features
Data Processing:

Load JSON/CSV datasets and image metadata.

Timestamp alignment for synchronizing sensor data and images.

Train/validation/test splits using scikit-learn.

Visualization:

Plot heart rate and SpO2 values alongside corresponding images.

Custom functions for displaying annotated medical data.

Deep Learning:

Custom PyTorch Dataset class for handling image and sensor data.

Integration with pre-trained models (e.g., ResNet via torchvision).

GPU acceleration support for faster training.

Reproducibility:

Predefined random splits for consistent experimentation.

Export/import of processed data and model checkpoints.

note the modle can predict for a singel image or a time series images
