# Audio-Denoiser

Project Title: Deep Learning-Based Audio Denoising Using Spectrograms
Overview:
This project focuses on audio denoising using deep learning techniques. The core idea is to denoise noisy audio signals by transforming them into spectrograms, applying a neural network model to remove noise, and reconstructing the clean audio. The project uses convolutional layers and attention mechanisms to learn the features of clean audio and separate it from noise.

Key Features:
Spectrogram Conversion: Converts the audio waveform into a spectrogram (visual representation of frequencies over time).
Denoising Model: Utilizes a convolutional neural network (CNN) with attention mechanisms to denoise the audio.
Loss Function: The model is trained to minimize the mean squared error (MSE) between the predicted clean audio and the target clean audio.
Post-Processing: Converts the predicted spectrogram back into audio after denoising, ensuring minimal loss in audio quality.


[Audiodenoise.pptx](https://github.com/user-attachments/files/17165118/Audiodenoise.pptx)
