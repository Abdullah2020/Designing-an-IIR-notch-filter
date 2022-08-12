# Implementation of IIR-Notch-Filter

The aim of this project is to design and implement an Infinite Impulse Response (IIR) filter on `Don_Giovanni_1.wav` audio signal so as to cancel the unwanted signal associated with the audio. The project uses Matlab R2022a version to develop the filter.

The major requirement in this project is to design an Infinite Impulse Response (IIR) Filter to cancel the noising frequencies in the given audio file. The type of IIR filter required to be used is the IIR Notch filter.

An IIR Notch filter is a band stop filter with a very narrow stop band and two pass bands. It removes a particular frequency component from the input signal while leaving the amplitude of the other frequencies more or less unchanged.

## Result

At the final output, we check the validity of our signal processing by playing the file before and after filtering. We also plotting the spectrum on a logarithmic scale before and after filtering. The figure shown below are the Original audio signal and Spectrum of Filtered Signal 

![Time domain waveform of original audio signal](https://user-images.githubusercontent.com/16369782/184449228-17338185-532f-470d-b6f6-aaf2aed6be16.jpg)



![Spectrum of Filtered Signal](https://user-images.githubusercontent.com/16369782/184449363-e0de8bb7-b527-49ca-95e3-7c32449d3ca2.jpg)

