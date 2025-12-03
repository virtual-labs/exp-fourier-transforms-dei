### Theory

Fourier Transform is a mathematical tool used to convert a time-domain signal into its frequency-domain representation. Many real-world signals contain hidden frequency components that are not easily visible in the time domain. By transforming the signal to frequency domain, we can analyze periodic behavior, dominant frequencies, harmonics, and noise content.

For practical computation on digital systems, the **Discrete Fourier Transform (DFT)** is used. It operates on discrete sampled signals and decomposes them into sums of complex exponential basis functions. The output values of DFT represent the signal in frequency bins, each consisting of:

- **Real part**: Represents cosine component
- **Imaginary part**: Represents sine component
- **Magnitude and phase**: Indicate amplitude and angle of each frequency component

Although DFT provides accurate frequency analysis, it is computationally expensive with complexity **O(N²)** for N samples.

To overcome this limitation, the **Fast Fourier Transform (FFT)** algorithm is used. FFT computes the same DFT but in a much more efficient manner with reduced complexity **O(N log N)**. This makes FFT the preferred technique in all modern signal processing systems.

Fourier Transform techniques are widely applied in:

- Digital communication and modulation
- Audio and speech analysis
- Biomedical signals (ECG, EEG)
- Image processing and filtering
- Vibration and structural analysis
- Spectrum estimation and filtering

Thus, DFT and FFT together form the foundation of modern frequency-domain signal analysis.
