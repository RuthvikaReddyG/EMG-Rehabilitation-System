# Dataset

This project uses a publicly available surface electromyography (sEMG) dataset recorded during squatting.

**Original dataset:** [Data for: Intermuscular Coherence between Surface EMG Signals recorded with Monopolar and Bipolar EMG Systems during Squatting](https://data.mendeley.com/datasets/37wyv32y8j/1)

**Citation:** Mohr et al. (2018). *Data for: Intermuscular Coherence between Surface EMG Signals recorded with Monopolar and Bipolar EMG Systems during Squatting*. Mendeley Data. https://doi.org/10.17632/37wyv32y8j.1

**License:** CC BY 4.0, as listed for the dataset.

The original dataset is hosted by Mendeley Data and is not stored in this repository. Download it from the source above and follow the project notebooks for the processing workflow.

**Scientific note:** The original dataset describes vastus medialis (VM) and vastus lateralis (VL) recordings. The mapping of channels to VMO/VL terminology in this project should be interpreted in light of the available acquisition metadata and the limitations documented in the manuscript.
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

