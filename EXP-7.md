# RECTANGULAR WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Rectangular Window and analyze its magnitude and phase response using MATLAB.
# Theory :
Rectangular Window
The Rectangular window is defined as:
        w(n)=1≤n≤N
Characteristics:
Narrowest main lobe

Highest side lobes

High ripple (Gibbs phenomenon)

Sharp transition width

It simply truncates the ideal impulse response.

Design Equations
Ideal Low Pass Impulse Response:

h_d (n)=(sin⁡ω_c (n-α))/(π(n-α))

Where:

α=N/2

Actual filter:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Choose filter order N
2.	Choose cutoff frequency ωc
3.	Generate ideal impulse response
4.	Generate rectangular window
5.	Multiply both
6.	Plot frequency response

# MATLAB CODE :
![WhatsApp Image 2026-03-30 at 2 54 24 PM](https://github.com/user-attachments/assets/08d111b6-72b6-4b7a-834c-6d71de253482)

# OUTPUT GRAPH :
![WhatsApp Image 2026-03-30 at 2 54 24 PM (1)](https://github.com/user-attachments/assets/7d26a94c-8224-4a1e-8967-b8b9082b8c01)

# RESULT :
The FIR filter was designed using Rectangular window.
