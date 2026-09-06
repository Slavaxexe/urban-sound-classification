# Urban Sound Classification

Deep-learning experiments for classifying environmental audio from the UrbanSound8K dataset into ten categories.

The project covers raw-waveform classification, a manual log-Mel spectrogram implementation, recurrent and convolutional classifiers, and SpecAugment. Validation accuracy improved from approximately **24.8%** for the raw-signal baseline to **81.6%** with a Mel-spectrogram LSTM and **93.6%** with the CNN.

## Stack

Python, PyTorch, TorchAudio, NumPy, pandas, scikit-learn, Matplotlib, and Seaborn.

## Data

The raw audio is not stored in this repository because it is approximately 1.86 GB. Download UrbanSound8K from the [official dataset page](https://urbansounddataset.weebly.com/urbansound8k.html) and prepare the WAV files referenced by `data/train_part.csv` and `data/val_part.csv` under `data/data/`.

Open `urban_sound_classification.ipynb` to review or reproduce the experiments.
