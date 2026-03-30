# GENERATION OF STANDARD DISCRETE-TIME SIGNALS
# AIM:
To generate and plot standard discrete-time signals using MATLAB.
# APPARATUS REQUIRED:
•	Computer / Laptop
•	MATLAB software
# THEORY:
Discrete-time signals are signals defined only at integer values of time (n).
These signals are basic building blocks in Digital Signal Processing (DSP) and are used for system analysis, filtering, and signal modeling.
Standard discrete-time signals include:
	Unit Impulse
	Unit Step
	Ramp
	Exponential
	Sinusoidal
	Damped Sinusoidal
In MATLAB, discrete-time signals are represented using vectors and plotted using the stem() command.
 Standard Discrete-Time Signals
 
🔹 1. Unit Impulse Signal
δ(n)={■(1,&n=0@0,&n≠0)┤

🔹 2. Unit Step Signal
u(n)={■(1,&n≥0@0,&n<0)┤

🔹 3. Ramp Signal
r(n)=n⋅u(n)

🔹 4. Exponential Signal
x(n)=a^n

🔹 5. Sinusoidal Signal
x(n)=sin⁡(ωn)

🔹 6. Damped Sinusoidal Signal
x(n)=a^n sin⁡(ωn)

# ALGORITHM:
1.	Start the program
2.	Define the sample index n
3.	Generate each standard discrete-time signal
4.	Plot the signal using stem()
5.	Label the axes and title
6.	Stop the program

# MATLAB CODE:
![WhatsApp Image 2026-03-30 at 2 36 36 PM](https://github.com/user-attachments/assets/40c14d88-3614-46ab-b2aa-da08e9162504)
![WhatsApp Image 2026-03-30 at 2 36 51 PM](https://github.com/user-attachments/assets/c441a37d-8ea8-469d-be65-626dd0865fd8)


# OUTPUT GRAPH:
<img width="821" height="1452" alt="image" src="https://github.com/user-attachments/assets/2e5afdfd-e8aa-4738-b456-14f894b8d1bb" />
<img width="919" height="1600" alt="image" src="https://github.com/user-attachments/assets/6bab64d4-d9fd-469c-bae0-b10a32b0fc13" />

# Result :
Thus, standard discrete-time signals were successfully generated and plotted using MATLAB.



