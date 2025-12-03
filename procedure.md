### Procedure

1. **Input Signal Sequence**
   - Enter the discrete signal values x[n] into the text fields provided.
   - Use the **Add Input** button to increase the number of samples.
   - Use the **Remove Input** button if any input needs to be deleted.

2. **Select Transform Method**
   - Choose either:
     - **Discrete Fourier Transform (DFT)** panel for manual DFT computation
     - **Fast Fourier Transform (FFT)** panel for efficient transformation

3. **Simulate the Transformation**
   - After entering the complete sequence, click the **Simulate** button.
   - The system will compute:
     - Real part of the frequency components
     - Imaginary part of the frequency components
     - Complete DFT/FFT result representation

4. **Observe Output Results**
   - Check the results displayed in the tabular format under the “RESULTS” section.
   - Each frequency index k will show its corresponding:
     - Real component
     - Imaginary component
     - Magnitude and/or combined frequency-domain value depending on implementation

5. **Analyze Frequency Characteristics**
   - Compare DFT and FFT results to verify that both produce identical frequency-domain results.
   - Notice how FFT performs the same operation more efficiently for larger data sequences.

6. **Repeat for Different Signals (Optional)**
   - Modify input data values to study the effect of different time-domain signals on frequency components.
   - Try sequences like sinusoidal waves, impulses, and step functions for better understanding.

