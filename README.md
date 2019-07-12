# speech-utils
Utilities for modifying and analyzing speech waveforms (e.g., generate spectrograms, modify pitch, etc.). Originally used for MIT's 6.345 Automatic Speech Recognition final project.

## Pitch modification
The pitch modification tools use the Praat library for Python, [Parselmouth](https://github.com/YannickJadoul/Parselmouth).

## SPH conversion
For many Linguistic Data Consortium datasets, like the [TIDIGITS](https://catalog.ldc.upenn.edu/LDC93S10) dataset, the files need to be converted between `.sph` and `.wav` file formats. See `convert-all-to-sph.sh` for an example batch conversion using the [`sox` command line tool](http://sox.sourceforge.net/sox.html).

## Generate spectrograms
The `create_spectrogram.py` program shows how you may use [Parselmouth](https://github.com/YannickJadoul/Parselmouth) to create spectrograms, which is based on this [documentation from Parselmouth](https://parselmouth.readthedocs.io/en/stable/examples/plotting.html).
