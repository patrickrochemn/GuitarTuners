Pitch: the perceived frequency of a sound. Frequency is physical measure, pitch is a psychoacoustical measure. We can hear frequencies that are not there

Note: a pitch with a name

Tone: subjective and ambiguous term

Pure Tone: a sound with a sinusoidal waveform

Guitar standard tuning:
-E2: 82.41 Hz
-A2: 110 Hz
-D3: 146.83 Hz
-G3: 196 Hz
-B3: 246.94 Hz
-E4: 329.63 Hz

f(i) = f0 * 2 ^ (i / 12) where i is the number of half-steps from f0


DFT TUNER:

-only care about the last few seconds of input from microphone at any given time
-uses Short-Time Fourier Transform (STFT) which is effectively the DFT applied for the most recent sampels
-taking into account the Nyquist-Shannon sampling theorem, f_s / N ~ 1 / t_window [Hz] with N being window size in samples and t_window being the window size in seconds

HPS tuner:
-Harmonic Product Spectrum (HPS)
-multiplication of R magnitude spectrums with different frequency scalings