# AVCO

Power supply:29mA

knob1: fundamental frequency
knob2: harmonics gain
knob3: harmonics spectrum
CV1: harmonics gain
CV2: harmonics spectrum
V / oct (10bit, 5Vp-p)
Output is 4Vp-p.

Outputs the fundamental tone and seven overtones. Both waveforms are sine waves.
The fundamental tone is controlled by V / oct.
The spectrum, that is, how many harmonics to add, is controlled by "harmonics spectrum". Since the added overtones are integral multiples of the fundamental tone, it becomes a musical tone.
The fundamental and harmonic gains are controlled by "harmonics gain".

"harmonics spectrum" and "harmonics gain" cannot be set to arbitrary values. It has a wave table-like format that refers to the values ​​stored in the table in advance.
With a combination of 256 types of spectra and 256 types of gain, you can create an infinite number of tones.
