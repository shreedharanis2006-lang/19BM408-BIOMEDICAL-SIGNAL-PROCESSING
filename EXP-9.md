# HANNING WINDOW BASED FIR FILTER DESIGN

# AIM:

To design a Low Pass FIR filter using Hanning (Hann) Window and analyze its response.
# THEORY :

Hanning window is defined as:

w(n)=0.5-0.5cos⁡(2πn/N)

Characteristics:

1)Smooth tapering at ends

2)Reduced spectral leakage

3)Moderate stopband attenuation (~31 dB)

4)Wider main lobe than Hamming

Design Equation:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Select N and ωc
2.	Compute ideal response
3.	Generate Hanning window
4.	Multiply and obtain FIR coefficients
5.	Plot response

# MATLAB CODE :
![WhatsApp Image 2026-03-30 at 2 56 18 PM](https://github.com/user-attachments/assets/f0b450f9-6f9a-483c-85d7-9fe4e4a7dcca)

# OUTPUT GRAPH :
![WhatsApp Image 2026-03-30 at 2 56 18 PM (1)](https://github.com/user-attachments/assets/14851070-7ad3-4501-a976-7625111dd5e8)

# RESULT :
The FIR filter was designed using Hanning window.
