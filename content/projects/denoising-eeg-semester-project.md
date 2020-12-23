+++
title = "Denoising EEG Signals"
date = "2020-12-08"
daterange = "Sep 2020 - Dec 2020"
author = "Machine Learning for Signal Processing Semester Project (CMU 18-797)"
cover = ""
tags = ["python", "machine learning", "signal processing", "eeg", "ica"]
keywords = ["mne", "denoising", "independent component analysis", "mlsp"]
description = "EEGs are extremely interesting to the signal processing world as the signals from them are high dimensional and localized spatially, spectrally, and temporally. These signals are extremely low amplitude and artifacts appear in the measured signal due to normal human processes like blinking, breathing, and moving; or noise can appear due to the external factors such as line noise or sound in the room. My peers and I implement Viola's ICA CorrMap procedure to denoise EEGs, but rather than retreiving EEG artifacts in-situ, we use Cho's EEG dataset which separately records subjects in both rest states and performing various 'noisy' actions prior to a motor imagery trial. We use this data to try and denoise signals and try to devise a way to create a generalized artifact template that can be transferred from user to user."
showFullContent = false
+++

[Github](https://github.com/justinnuwin/Denoising-EEG-Signals)

EEGs are extremely interesting to the signal processing world as the signals from them are high dimensional and localized spatially, spectrally, and temporally.
These signals are extremely low amplitude and artifacts appear in the measured signal due to normal human processes like blinking, breathing, and moving; or noise can appear due to the external factors such as line noise or sound in the room.
My peers and I implement Viola's ICA CorrMap procedure to denoise EEGs, but rather than retreiving EEG artifacts in-situ, we use Cho's EEG dataset which separately records subjects in both rest states and performing various 'noisy' actions prior to a motor imagery trial.
We use this data to try and denoise signals and try to devise a way to create a generalized artifact template that can be transferred from user to user.

#### Links:

- [Paper](https://github.com/justinnuwin/Denoising-EEG-Signals/blob/master/18-797_Project_Report.pdf)
- [Github](https://github.com/justinnuwin/Denoising-EEG-Signals)
