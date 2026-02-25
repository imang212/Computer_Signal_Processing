# Computer Signal Processing
## Processing ECG and Audio Signals in Python
This repository contains signal processing analyses implemented in
**Python using Jupyter Notebook**.
The project focuses on **electrocardiogram (ECG) signal processing** and
**audio/sound signal analysis**, applying fundamental Digital Signal
Processing (DSP) techniques.

## Project Overview
This project demonstrates practical applications of digital signal
processing, including:
-   Signal visualization in the time domain
-   Frequency domain analysis using Fourier Transform
-   Signal filtering and noise reduction
-   Spectrogram generation
-   Processing biomedical signals (ECG)
-   Audio signal analysis and transformation

The goal is to understand how raw signals can be transformed into
meaningful information using computational methods.

## Technologies Used
-   Python 3
-   Jupyter Notebook / JupyterLab
-   NumPy
-   SciPy
-   Pandas
-   Matplotlib
-   Seaborn

## Repository Structure
Computer_Signal_Processing/ ├── semnarni_prace_1.ipynb \# EKG signal
processing ├── semnarni_prace_2.ipynb \# Audio signal processing ├──
data/ \# Input datasets (EKG / audio files) ├── requirements.txt \#
Python dependencies (if included) ├── README.md \# Project documentation
├── LICENSE \# MIT License

## ECG Signal Processing
The ECG notebook includes:
-   Loading and visualizing ECG recordings
-   Noise filtering using digital filters
-   Peak detection
-   Heart rate calculation
-   Signal smoothing and analysis

This part focuses on biomedical signal interpretation and practical
filtering techniques.

## Audio Signal Processing
The audio notebook demonstrates:
-   Loading audio files (e.g., WAV format)
-   Waveform visualization
-   Spectrogram generation
-   Fourier Transform (FFT)
-   Frequency spectrum analysis
-   Time-frequency signal analysis

## How to Run the Project
1.  Clone the repository:

git clone https://github.com/imang212/Computer_Signal_Processing.git
cd Computer_Signal_Processing
3.  Install required libraries:
pip install numpy scipy pandas matplotlib seaborn jupyter
4.  Start Jupyter:
jupyter lab
5.  Open the notebooks and run the cells.

## Learning Objectives
By working with this repository, you will:
-   Understand core DSP concepts
-   Work with real-world biomedical and audio data
-   Apply filtering and spectral analysis
-   Visualize signals effectively
-   Gain hands-on experience with scientific Python tools
