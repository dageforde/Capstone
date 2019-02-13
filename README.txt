### Goals

The goal of this project is twofold:

1. Use the Python library, Librosa, to extract spectral features from audio files in a way that they can be used in a machine learning model
2. Build a model that can accurately predict the musical genre of an audio signal, given a set of spectral features as a Numpy array

### Data
1. 'genres'
    This folder contains 1,000 audio files, each of which is 30 seconds long. The audio files represent ten distinct genres, with 100 files per genre. All tracks are 22040 Mono 16-bit audio files in .wav format.
2. 'gtazan.csv'
    This file contains our extracted audio features in Numpy array format
3. 'gtzan_clean'
    Cleaned, labeled dataset

### Notebooks

1. capstone_final
    This notebook contains the code for extracting audio features and storing to .csv along with code for predictive models
