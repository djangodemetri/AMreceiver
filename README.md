Over four months, my team is tasked to create a heterodyne AM receiver using discrete components. The AM receiver should be able to demodulate
a square wave with a frequency of 1kHz and 50% AWGN. The receiver consists of four main parts:

1 LNA (2N3904 with a BS170 for a buffer)

2 Lowpass and bandpass filters, active (u741) and passive

3 Colpitts Oscillator (2N3904)

4 AB Amplifier (2N3906) 

5 Single Diode Mixer (1N4148)

What I learned:

1 Understand the IV curve of a component. The IV curve will allow an engineer to choose a Q point and obtain the desired results such as, linearity or non-linearity, maximum gain, energy efficient gain, avoid triode 
and saturation stages

2 There is a design process: use theoretical analysis to understand the component and get ballpark numbers. Simulate the circuit and identify ideal and unideal behavior for later troubleshooting. 
When building and testing the circuit, be very clear about what the desired outcome is and, if that desired outcome is not achieved, troubleshoot basic behavior and work up from there, (don't start with the most complicated idea).


