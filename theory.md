## Theory

### Introduction to Fourier Transform
The Fourier Transform is a mathematical technique used to represent a signal in terms of its frequency components. While a signal in the time domain shows how it varies over time, its frequency-domain representation reveals the presence of different frequency components, their strengths, and their phases. Many real-world signals contain periodic or oscillatory behavior that is not easily visible in the time domain but becomes clear after frequency-domain analysis.

#### Discrete Fourier Transform (DFT)

In digital signal processing, signals are available as discrete samples rather than continuous functions. The Discrete Fourier Transform (DFT) is used to analyze such discrete signals by decomposing them into a finite set of sinusoidal components.

<img width="964" height="618" alt="image" src="https://github.com/user-attachments/assets/96d3892d-2148-489f-b34b-ae886bb0d1e6" />

#### Interpretation of DFT Output (Conceptual Schematic Description)
<img width="953" height="136" alt="image" src="https://github.com/user-attachments/assets/4dc8e6a6-433c-48da-bc10-c063938ea224" />

#### Computational Limitation of DFT
<img width="964" height="104" alt="image" src="https://github.com/user-attachments/assets/cc020079-38cf-4101-9b2e-a275386fe475" />

### Fast Fourier Transform (FFT)
The Fast Fourier Transform (FFT) is an efficient algorithm used to compute the DFT. FFT does not change the mathematical result of the DFT; instead, it reduces the number of computations by exploiting symmetry and periodicity properties of the complex exponentials.

The computational complexity of FFT is reduced to:
<img width="133" height="40" alt="image" src="https://github.com/user-attachments/assets/9cc0f91f-76c0-4270-a71d-4eb4dc3fc4e3" />

This significant reduction makes FFT the preferred technique in modern signal processing applications.

#### Difference Between DFT and FFT (Conceptual Comparison)
The DFT defines the mathematical transformation from time domain to frequency domain, while FFT is an algorithm used to compute the same transformation efficiently. In practice, FFT is always used to compute the DFT for digital signals due to its speed and computational efficiency.

#### Applications of Fourier Transform
Fourier Transform techniques are fundamental in many engineering and scientific applications, including:

- Digital communication and modulation

- Audio and speech signal analysis

- Biomedical signal processing (ECG, EEG)

- Image processing and filtering

- Vibration analysis and fault detection

- Spectrum estimation
