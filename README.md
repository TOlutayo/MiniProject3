# MiniProject3
Demonstrating Python visualization tools (mainly spectrum, matplotlib and pylab) using Spectograms and Periodograms.

# PROJECT DESCRIPTION
The goal of this project is to demonstarte the visualization capabilities of python libraries in the field of Digital Signal Processing. Examples using spectograms and periodograms were chosen as they integrate various aspects of DSP as such providing ample opportunity to showcase the visualization tools available to us from the python libraries.

![Screenshot](Screenshot.png)
Fig 1: Spectrum Analyzer Using Spectrum Library (SciPy)

# SPECTOGRAMS
Spectograms are an incredibly useful tool for visualizing the time variation of frequency components of a signal. First some background information. In signal processing, fourier transforms are used to decompose a signal into its frequency components. For a more low level explanation: Every signal can be represented as a sum of complex exponentials of different frequencies. The fourier transform tells you how much (magnitude and phase) of each complex exponential is present in the given signal. However, this is only useful for stationary signals i.e. signals whose characteristics do not change with time - signals with a fixed impulse response function. Simple Fourier transforms are not helpful when dealing with signals with varying impulse response. As such a new method for tackiling this issue was devised. The short time fourier transform.

### The Short time fourier transform (STFT) ###
