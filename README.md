# Experimental Characterization of a Low-Cost Signal Generator

This repository contains the project and results for my Final Examination in **Cybernetic Engineering** at the University of Palermo. The study focuses on the performance analysis and experimental validation of an affordable DIY signal generator.

## 🎯 Project Overview
The primary goal of this research is the experimental characterization of a DIY function generator kit based on the **XR-2206** monolithic function generator IC. The project evaluates whether a low-cost device (approx. €4-5) can serve as a reliable tool for educational or hobbyist purposes by comparing its output against professional laboratory standards.

## 🔬 Experimental Setup
The Device Under Test (DUT) was analyzed using a professional-grade measurement chain:
* **Digital Oscilloscope**: Used for waveform acquisition, timing analysis, and FFT (Fast Fourier Transform).
* **Digital Multimeter**: Employed for precise voltage calibration and RMS measurements.
* **Data Processing**: Custom analysis to calculate linearity, uncertainty, and harmonic distortion.

## 📊 Key Analysis & Methodology
The characterization was divided into three main experimental phases:
* **Frequency Characterization**: Testing the accuracy and stability of the output frequency across the device's operational range.
* **Amplitude Characterization**: Measuring the output voltage consistency and evaluating the device's linearity.
* **Total Harmonic Distortion (THD) Analysis**: Quantifying the spectral purity of the sine wave produced by the XR-2206 chip to identify signal degradation.

## 📈 Summary of Results
* **Linearity**: The device demonstrated remarkably high linearity in amplitude, with R² coefficients exceeding 99% in several test conditions.
* **Total Harmonic Distortion**: THD values were monitored to define the "cleanliness" of the signal, revealing the inherent limitations of the low-cost circuitry compared to professional equipment.
* **Conclusions**: While the XR-2206 kit has clear limitations in high-precision scenarios, it proves to be a cost-effective and valid solution for basic electronics education and general hobbyist applications.

---
**Candidate**: Salvatore Zuccaro  
**Supervisor**: Prof. Valentina Cosentino  
**Co-supervisor**: Prof. Giovanni Artale  
**University of Palermo** | *Department of Engineering*
