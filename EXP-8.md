# HAMMING WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Hamming Window and study its frequency characteristics.
# THEORY:

Hamming window is defined as:

w(n)=0.54-0.46cos⁡(2πn/N)

Characteristics:
Reduced side lobes

Better stopband attenuation (~41 dB)

Slightly wider main lobe than rectangular

Reduced ripple

Design Equation:

h(n)=h_d (n)⋅w(n)

Where hd(n) is ideal impulse response.

# ALGORITHM:
1.	Choose N and ωc
2.	Compute ideal impulse response
3.	Generate Hamming window
4.	Multiply and obtain h(n)
5.	Plot magnitude & phase

# MATLAB CODE :
<img width="1079" height="965" alt="image" src="https://github.com/user-attachments/assets/5b5bbb21-eaa7-475a-9d31-d526625b5c6c" />

# OUTPUT GRAPH :
![WhatsApp Image 2026-03-30 at 2 55 15 PM](https://github.com/user-attachments/assets/64370a8f-2e29-4434-8ff5-a2b71617829d)

# RESULT :
The FIR filter was designed using Hamming window .

