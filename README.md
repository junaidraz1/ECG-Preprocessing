# ECG & PPG Signal Preprocessing  

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/Library-NumPy-orange.svg)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/Library-SciPy-lightgrey.svg)](https://scipy.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📌 Project Description  
This project focuses on preprocessing and analyzing simultaneously measured **ECG (Electrocardiogram)** and **PPG (Photoplethysmogram)** signals. The primary objectives include **resampling, frequency domain analysis, and filtering** to enhance signal quality for further processing.

## 📂 Features  
✅ **Load and visualize** raw ECG and PPG signals  
✅ **Resample signals** to a common sampling frequency of 200 Hz  
✅ **Analyze frequency components** using FFT and Welch’s method  
✅ **Apply filtering** using Butterworth and moving average filters  
✅ **Preserve essential signal information** while removing out-of-band noise  

## 📝 Methodology  
1️⃣ **Data Loading & Visualization:** Reads ECG and PPG data files and plots signals.  
2️⃣ **Resampling:** Converts ECG (128 Hz) and PPG (100 Hz) signals to a unified **200 Hz**.  
3️⃣ **Frequency Domain Analysis:** Computes **FFT and Welch’s Power Spectral Density (PSD)**.  
4️⃣ **Filtering:** Uses **Butterworth and moving average filters** to clean signals.  

## 📊 Visualization  
- **Time-domain plots** of raw and filtered signals  
- **Frequency-domain analysis** to identify dominant frequency components  
- **Comparison of resampled and original signals**  
