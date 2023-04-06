# Read Me

## Sorry for Late

Sorry for the late upload of my sources code due to my very busy shedule. Unofortuanately, it still needs to costs me extra time to clean the original project to make this project more readable. I will upload the codes and datasets in serveral times. And finally, I will make this repository an out of box version.


## Introduction

The codes for Johannes's MATT Paper.


## Usage 
### Requirements
pip install torch==1.9.1 torchvision==0.10.1 torchaudio==0.9.1
pip install nni==1.9.1
pip install librosa==0.8.0

### Execution Steps

## 0. Process Data
Split the original complex dsv file to multi datasets with different sizes.

## 1. Sort Data
Construct the Bag-Level Data Structure.

## 2. Build Representation
Build the Mel-spectrogram Representation.
1. Run "2. Build Representation_medium.ipynb.ipynb".


## 3. Re-sort Data.
Construct the Bag-Level Data Structure with clean Data.
1. Delete the unavailable audio index in the sort files.
2.. Run "3. Re_init_Clean_Data.ipynb".

## 4. Build Representation with Clean Audio
Build the Mel-spectrogram Representation.
1. Run "2. Build Representation_medium.ipynb.ipynb".

## 5. Train Models
1. Train statistica models,
2. Train Neural Networks.

## 6. Evaluation
1. Evaluate Statistica Models.
2. Evaluate Neural Networks.