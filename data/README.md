# Data

This project uses a publicly available surface electromyography
dataset released by Mohr through Mendeley Data in 2018.

The dataset contains two-channel EMG recordings associated
with squatting.

No new human-subject data were collected for this project.

The dataset was processed into 998 window-level observations:
- 157 VMO-dominant
- 841 VL-dominant

The processed dataset used for model development is described
in the project notebooks.

Source:
[https://data.mendeley.com/datasets/37wyv32y8j/1]


## Dataset Structure

The analysis uses two EMG channels corresponding to the muscles investigated in the study.

The raw signals were processed using overlapping windows before feature extraction.

## Processing

The feature-extraction notebook generates seven candidate features. Two ratio-based features were subsequently excluded from the final machine-learning models.

The five retained features are:

- VMO activation (RMS)
- VL activation (RMS)
- Peak activation delay
- Muscle onset delay
- Muscle synchronization

## Data Availability

The original dataset is not redistributed in this repository.

