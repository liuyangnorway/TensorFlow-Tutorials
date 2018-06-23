TensorFlow TutorialsOriginal repository on GitHub

Original author is Magnus Erik Hvass Pedersen

IntroductionThese tutorials are intended for beginners in Deep Learning and TensorFlow.
Each tutorial covers a single topic.
The source-code is well-documented.
There is a YouTube video for each tutorial.
TutorialsSimple Linear Model (Notebook)

Convolutional Neural Network (Notebook)

Pretty Tensor (Notebook)

3-B. Layers API (Notebook)

3-C. Keras API (Notebook)

Save & Restore (Notebook)

Ensemble Learning (Notebook)

CIFAR-10 (Notebook)

Inception Model (Notebook)

Transfer Learning (Notebook)

Video Data (Notebook)

Fine-Tuning (Notebook)

Adversarial Examples (Notebook)

Adversarial Noise for MNIST (Notebook)

Visual Analysis (Notebook)

13-B. Visual Analysis for MNIST (Notebook)

DeepDream (Notebook)

Style Transfer (Notebook)

Reinforcement Learning (Notebook)

Estimator API (Notebook)

TFRecords & Dataset API (Notebook)

Hyper-Parameter Optimization (Notebook)

Natural Language Processing (Notebook)

Machine Translation (Notebook)

Image Captioning (Notebook)

Time-Series Prediction (Notebook)

VideosThese tutorials are also available as YouTube videos.

TranslationsThese tutorials have been translated to the following languages:

Chinese
You can help by translating the remaining tutorials or reviewing the ones that have already been translated. You can also help by translating to other languages.

ForksSee the selected list of forks for community modifications to these tutorials.

DownloadingSome of the Python Notebooks use source-code located in different files to allow for easy re-use across multiple tutorials. It is therefore recommended that you download the whole repository from GitHub, instead of just downloading the individual Python Notebooks.

GitThe easiest way to download and install these tutorials is by using git from the command-line:

git clone https://github.com/Hvass-Labs/TensorFlow-Tutorials.git


This will create the directory TensorFlow-Tutorials and download all the files to it.

This also makes it easy to update the tutorials, simply by executing this command inside that directory:

git pull


Zip-FileYou can also download the contents of the GitHub repository as a Zip-file and extract it manually.

InstallationThere are different ways of installing and running TensorFlow. This section describes how I did it for these tutorials. You may want to do it differently and you can search the internet for instructions.

If you are new to using Python and Linux, etc. then this may be challenging to get working and you may need to do internet searches for error-messages, etc. It will get easier with practice.

Python Version 3.5 or LaterThese tutorials were developed on Linux using Python 3.5 / 3.6 (the Anaconda distribution) and PyCharm.

There are reports that Python 2.7 gives error messages with these tutorials. Please make sure you are using Python 3.5 or later!

EnvironmentAfter installing Anaconda, you should create a conda environment so you do not destroy your main installation in case you make a mistake somewhere:

conda create --name tf python=3


Now you can switch to the new environment by running the following (on Linux):

source activate tf


Required PackagesThe tutorials require several Python packages to be installed. The packages are listed in requirements.txt First you need to edit this file and select whether you want to install the CPU or GPU version of TensorFlow.

To install the required Python packages and dependencies you first have to activate the conda-environment as described above, and then you run the following command in a terminal:

pip install -r requirements.txt


Note that the GPU-version of TensorFlow also requires the installation of various NVIDIA drivers, which is not described here.

TestingYou should now be able to run the tutorials in the Python Notebooks:

cd ~/development/TensorFlow-Tutorials/  # Your installation directory.
jupyter notebook


This should start a web-browser that shows the list of tutorials. Click on a tutorial to load it.

Older VersionsSometimes the source-code has changed from that shown in the YouTube videos. This may be due to bug-fixes, improvements, or because code-sections are moved to separate files for easy re-use.

If you want to see the exact versions of the source-code that were used in the YouTube videos, then you can browse the history of commits to the GitHub repository.

License (MIT)These tutorials and source-code are published under the MIT License which allows very broad use for both academic and commercial purposes.

A few of the images used for demonstration purposes may be under copyright. These images are included under the "fair usage" laws.

You are very welcome to modify these tutorials and use them in your own projects. Please keep a link to the original repository.
