# GEG3460 Exercises

## 1. Getting started

To get started with the exercises, you'll need to create a `conda` environment containing the packages needed. On your M: drive, create a folder called ".conda" if it does not already exist. Next, open up __Anaconda Prompt__, and type the following commands:

'''

C:\> conda create --prefix M:\\.conda\geg3460 python=3.7

C:\> activate M:\\.conda\geg3460

C:\> conda install -c conda-forge cartopy geopandas

'''

This will probably take some time, but fortunately we only have to do this once (though you will have to do this again if you want to work on your personal computer). In the future, when you want to open the labs on a computer on the University network, you can just type `activate M:\.conda\geg3460` at the Anaconda command prompt, then navigate to the folder where you have your labs and open jupyter-notebook, without having to re-install the conda environment each time.

A handy cheat sheet of the most useful conda commands can be found [here](https://conda.io/docs/user-guide/cheatsheet.html).

## 2. Download/clone this repository

Now that you have a `conda` environment created with all of the python packages we'll need, you can __clone__ this repository to either your course folder on __lagringshotell__,
or your M: drive. You can do this in one of two ways:

1. Above this message, click the green "clone or download" button, and select "download ZIP" at the bottom of the menu. Once it's downloaded, unzip the file and move on to the next step.
2. __On a computer where you have administrative access__: Instead of downloading a zip, you can use __git__ to clone the repository. If you haven't already installed __git__, you should do so now - instructions can be found [here](https://www.atlassian.com/git/tutorials/install-git). On Windows, be sure to choose the option to use __git bash__ during setup. Using a terminal (or __git bash__ on Windows), navigate to the folder where you want to clone the repository. Create a new folder called "python\_labs" (`mkdir -p python_labs`), and navigate to that folder (`cd python_labs`). Now, execute the following command: `git clone https://github.com/iamdonovan/geg2250-exercises.git`. You should see some messages about downloading/unpacking files, and the repository should be set up.

## 3. Start jupyter-notebook

On the lab computers, open the __Anaconda Prompt__ (if it isn't already) . Make sure that __geg3460__ is selected ("Applications on ..."), and launch __jupyter-notebook__. Navigate to the folder where you've saved the tutorials, and activate your newly created environment (`activate M:\.conda\geg3460`). Launch jupyter-notebook (`jupyter-notebook.exe`), which should launch a web browser window. If you haven't had any experience with programming before, it's a good idea to go through the Intro2Python lab first, so you have som familiarity with python and basic programming structures. Otherwise, to get started with Lab1b, click on the __Lab1__ folder and open the notebook file (`Lab1b.ipynb`). That's it!
