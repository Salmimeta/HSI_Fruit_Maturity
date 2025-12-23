# Dataset

This repository does not store large hyperspectral data files.

## Ground Truth (included)
- `SpectroFood_dataset.csv`  
  Contains dry matter (%) labels for apples.

## External Hyperspectral Datasets (Zenodo)
Download the raw data from the official Zenodo records:

- Apple: https://zenodo.org/records/10301753
- Broccoli: https://zenodo.org/records/10302386
- Leek: https://zenodo.org/records/10302426
- Mushroom: https://zenodo.org/records/10302438

## Expected Local Structure
After downloading and extracting, place data like this:

dataset/raw/
├── apple/
├── broccoli/
├── leek/
└── mushroom/

These files are ignored by Git and used locally for preprocessing.
