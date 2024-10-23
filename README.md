# Shalu-kumari2003--Fine-tuning-TTS-for-English-with-a-Focus-on-Technical-Vocabulary-Steps-
If you want to use this on your own computer, you must have an NVIDIA GPU.

On Windows, I highly recommend using the Conda installation method. I have been told that if you do not do this, you will spend a lot of time chasing dependency problems.

First, install miniconda: https://docs.conda.io/en/latest/miniconda.html

Then run the following commands, using anaconda prompt as the terminal (or any other terminal configured to work with conda)

This will:

create conda environment with minimal dependencies specified
activate the environment
install pytorch with the command provided here: https://pytorch.org/get-started/locally/
clone tortoise-tts
change the current directory to tortoise-tts
run tortoise python setup install script

Optionally, pytorch can be installed in the base environment, so that other conda environments can use it too. To do this, simply send the conda install pytorch... line before activating the tortoise environment.
