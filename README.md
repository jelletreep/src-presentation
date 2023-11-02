# Presentation SRC Whisper

This repository contains the presentation for workshop Whisper on Research Cloud

[Presentation](https://jelletreep.github.io/src-presentation/src-whisper.html)

## Getting Started: Surf Research Cloud

[Request an account](https://www.uu.nl/en/research/research-data-management/tools-services/software-and-computing/virtual-research-environments)

[Instructions](https://utrechtuniversity.github.io/vre-docs/docs/workspaces/whisper.html)

[Template notebook](notebooks/whisper_template.ipynb)



## Self installation

- Follow installation instructions [WhisperX](https://github.com/m-bain/whisperX):

### 1. Create Python3.10 environment

`conda create --name whisperx python=3.10`

`conda activate whisperx`

### 2. Install PyTorch, e.g. for Linux and Windows CUDA11.8:

`conda install pytorch==2.0.0 torchaudio==2.0.0 pytorch-cuda=11.8 -c pytorch -c nvidia`

See other methods [here.](https://pytorch.org/get-started/previous-versions/#v200)

### 3. Install WhisperX from repo

`pip install git+https://github.com/m-bain/whisperx.git`

### 4. Install Whisper from repo

`pip install git+https://github.com/openai/whisper.git`

### 5. Use the template Jupyter notebook to run Whisper
Download the notebook and run it using the whisperx conda environment

[Template notebook](notebooks/whisper_template.ipynb)