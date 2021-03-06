## Introduction

In this notebook, I used the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). 
Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora.
Hidden Markov models have also been used for speech recognition and speech generation, machine translation, 
gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

## Getting Started

Alternatively, you can download a copy of the project from GitHub [here](https://github.com/MarwaMohammad/HMM-Tagger) and then run a Jupyter server locally with [Anaconda](https://www.anaconda.com/download/).

1. Open a terminal and clone the project repository:
```
$ git clone https://github.com/MarwaMohammad/HMM-Tagger
```

3. Switch to the project folder and create a conda environment (note: you must already have Anaconda installed):
```
$ cd hmm-tagger
hmm-tagger/ $ conda env create -f hmm-tagger.yaml
```

4. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
hmm-tagger/ $ source activate hmm-tagger
(hmm-tagger) hmm-tagger/ $ jupyter notebook
```

Depending on your system settings, Jupyter will either open a browser window, or the terminal will print a URL with a security token. 
If the terminal prints a URL, simply copy the URL and paste it into a browser window to load the Jupyter browser. 
Once you load the Jupyter browser, select the project notebook (HMM tagger.ipynb) and follow the instructions inside to complete the project.

See below for project submission instructions.


