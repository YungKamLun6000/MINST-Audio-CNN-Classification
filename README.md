This project implements a Convolutional Neural Network (CNN) to classify spoken digits (0–9) using spectrograms generated from audio samples. 
The model was trained and validated on a dataset of 2,000 audio samples, achieving a validation accuracy of 99.25%.
Audio Preprocessing:

Audio samples are converted to spectrograms using the Short-Time Fourier Transform (STFT).
The spectrograms are saved as PNG images categorized by their respective digit labels.

Model Training:

A CNN model is trained on the spectrogram dataset.

Evaluation:

The model is validated on a separate validation set.

