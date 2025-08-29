# Pulse-Width-comparison-method-Matlab-
This program is the code for the paper "A Novel laser detection method against soot interference based on pulse-width comparison" (Remote Sensing). Readers can open the code using MATLAB and utilize this method to evaluate laser echo signals.

The specific functions and operation guidelines are as follows:

1. Identify the first column of the dataset as time and the second column as signal data.
2. Extract the wave crests from the signal data.
3. Determine the pulse width of the extracted wave crests. In this method, the number of data points can be used as a substitute for the actual pulse width value, which is denoted by the parameter "length" in the program.
4. For target identification results: the indicator light will turn red if a target is detected; otherwise, the light will remain in its original state.

It should be noted that objective factors such as sampling frequency and receiver parameters will affect the practical performance of this method. Therefore, the core parameters of the method need to be adjusted in a targeted manner based on the actual data obtained under specific test scenarios to ensure its adaptability and accuracy.

If you require technical support, personalized scheme recommendations, or assistance with parameter debugging, please feel free to contact us at any time. We will provide you with professional support.
