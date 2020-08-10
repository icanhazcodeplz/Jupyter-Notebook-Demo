# Jupyter-Notebook-Demo

Here are the minimum steps required to get this Jupyter Notebook running from scratch:

 1. [Install Python 3 using Anaconda](https://www.continuum.io/downloads)
    * Make sure it is working by typing the command `conda` in a terminal.
    * If you get a reponse of `command not found`, you may need to add anaconda to your environment path.
      * One way to do this is to add the line `export PATH="$PATH:/Users/bmagnusson/anaconda/bin"` to your .bashrc or .profile file. Replace `/Users/bmagnusson` with the location of your anaconda installation.
    * If you have already installed Anaconda, run the command `conda update anaconda` to make sure you have the latest and greatest.
 1. [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
 1. [Make a github account](https://github.com/join)
 1. [Fork this repo](https://github.com/bmagnusson/Jupyter-Notebook-Demo) by clicking the "Fork" button at the top right of the page
 1. [Clone this repo](https://help.github.com/articles/cloning-a-repository/) locally in the directory of your choice
    * For example, my commands from terminal (mac OSX) were:
      * `cd /Users/bmagnusson`
      * `git clone https://github.com/bmagnusson/Jupyter-Notebook-Demo.git`
 1. Navigate to the directory that you cloned the repo and run the command `jupyter notebook`
     * For me: 
       * `cd /Users/bmagnusson/Jupyter-Notebook-Demo`
       * `jupyter notebook`
 1. This (should) open up the Jupyter directory browser at [http://localhost:8888/tree](http://localhost:8888/tree) in your default web browser.
 1. Navigate to [http://localhost:8888/nbextensions/](http://localhost:8888/nbextensions/)
 1. Under Configurable extensions click the check box for **Nbextensions dashboard tab**
 1. Go back to the tree directory by clicking the **Files** tab
 1. Click **Jupyter Notebook Intro.ipynb**
 1. [Congrats](https://i.imgflip.com/sd946.jpg) you're ready to roll. Happy notebooking! 
  