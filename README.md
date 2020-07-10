[![CC BY 4.0][cc-by-shield]][cc-by]

# music21playground

Some Jupyter notebooks (http://jupyter.org/) to test basic music21 functionalities.

## Usage

### Run notebook locally

Make sure you have installed the following:
1. Python (Version 3.6): https://www.python.org/downloads/
    follow the instructions of the installer

2. Jupyter Notebook (http://jupyter.org/install)
    
    After installation of Python, open terminal and type (if needed change „python3“ to „python“):
    ```
    python3 --version
    python3 -m pip install --upgrade pip
    python3 -m pip install jupyter
    ```

3. music21 (http://web.mit.edu/music21)
    
    Also in terminal type (if needed change „pip“ to „pip3“ :
    ```
    pip --version
    pip install music21
    ```

After installation, fork this repo and clone your fork to your local machine. 

To start the notebook server, change to the directory of your local clone in terminal and type:
    
```
jupyter notebook
```

The server should now be running and the jupyter dashboard should open in your browser.

To learn more about Jupyter notebooks, see this detailed tutorial: https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook#WhatIs


### Run notebook online
There are some possibilities to get an interactive online notebook running without the need to install the whole jNotebook environment (especially useful for classes, e-learning etc):

Google Notebooks (not used here):
https://colab.research.google.com

Binder:
https://mybinder.org/

To see this Repo running on Binder, click on the badge: 
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/musicEnfanthen/music21playground/master)

Use the `xxx_interactiveImage.ipynb`-Notebooks when you started this repo via Binder because of the following:

Basic functionalities are interactively working with the Binder image, but, using jupyter notebook inside a Binder image causes some issues with music21's ".show()"-method (see: https://github.com/cuthbertLab/music21/issues/260). Thanks to Tony Hirst ([@psychemedia](https://github.com/psychemedia)) there is a small workaround with a redefinition of the show()-method.

### License
The notebooks in this repo are licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
