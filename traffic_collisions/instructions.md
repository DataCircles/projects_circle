# EDA Workshop
---------------

In this workshop we will show an example of Exploratory Data analysis. We will go through the collisions dataset and we will make use of a popular tool for this purpose, the __awsome__ jupyter notebook (or its derivatives).

## Requirements

The materials we will be using today require the following libraries for `python 3.7`:

* `pandas`
* `matplotlib`
* `seaborn`
* `jupyter lab` or `jupyter notebook`

## Running this workshop locally

If you want to run all the code in your local machine, you are welcome to do so by using anaconda which has all the libraries we need or by creating a local environment in python and manually installing all the libraries required.

To access the Notebook just clone this repository or download a zip file on the `Clone or download` button. If your download a zip file click on `Download ZIP`

<p align="center">
  <img src="https://hostadvice.com/wp-content/uploads/2019/01/how-to-download-install-plugins-and-themes-from-github-1.png" width="650" title="hover text">
</p>

Once you have downloaded the notebook, unzip it and open it with jupyter lab.

If you want to know more about installing jupyter lab, keep reading. Otherwise you're good to go!

## Running this workshop on colab

If you don't want to install anything in your machine or you don't want to use your personal computer for this workshop there is this great tool called colab. You will need a gmail account for this.

Colab is an online tool very similar to the jupyter notebook where you can run analysis and experiments in the cloud in an environment already set up by Google. This is a free tool and you only need to click on [this link](http://colab.research.google.com/github/orbitse/traffic_collisions/blob/master/EDA_traffic_collision_workshop.ipynb) to have your own version of the workshop.

This is possible to do with any jupyter notebook (files endind in `.ipynb`) that is hosted in any public repository. If you want to learn more about this integration of colab and github visit [this](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb#scrollTo=Rmai0dD30XzL)

## If you are going for the 'local' option here are some tips to install


#### Using Anaconda (preferred method)

Anaconda is a very comprehensive and free package manager, environment manager and Python distribution. That means that if you install it you will have a reliable way (for the most part) to have access to more than 1500 python libraries, ability to have different versions of Python via environments and ease in creating and working with said environments.  

To install anaconda in your computer you need to follow the instructions in their official website. There are specific instructions depending on the operative system you have here are the instructions for [windows](https://docs.anaconda.com/anaconda/install/windows/), [macOS](https://docs.anaconda.com/anaconda/install/mac-os/) and [linux](https://docs.anaconda.com/anaconda/install/linux/).

Because Anaconda has so many libraries that you may or may not end up using in the future, perhaps you would like to install [miniconda](https://docs.conda.io/en/latest/miniconda.html) instead, which is a very light version of anaconda, provided only with the essential components for it to work. This has the disadvantage that you may have to manually install packages and change environments for specific uses. 

After you install anaconda (or miniconda manually installing jupyter lab) you can access jupyter lab by doing the following:

__Using graphical interface in anaconda__

1. Open Anaconda Navigator
2. Click on the jupyter lab icon
3. Navigate to the directory with the notebook (it will most likely be in the Downloads folder). Navigation is done in the left panel on the folder icon
4. Click on the EDA notebook
5. Run cells by clickin the 'play' icon or by hitting CTRL + Enter (CMD + Enter in Mac)

__Using command line in miniconda__

1. Open the comand line (or anaconda prompt)
2. Type pip install jupyterlab and hit enter
3. Type jupyter lab and hit enter
4. Navigate to the directory with the notebook (it will most likely be in the Downloads folder). Navigation is done in the left panel on the folder icon
5. Click on the EDA notebook
6. Run cells by clickin the 'play' icon or by hitting CTRL + Enter (CMD + Enter in Mac)

