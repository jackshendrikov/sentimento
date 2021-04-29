<h1 align="center">Sentimento English</h1>

<div align="center"> 
This repository contains 3 parts of iPython notebooks, which reveal the whole process of model development for the sentiment analysis from data processing to comparative analysis of different LSTM models. Visualization is accompanied throughout the journey. The model was created for the analysis of the English text.
</div>

## 📥 &nbsp;Downloading Data

Before running notebooks, we first need to download all the data we will be using. 

As always, the first step is to clone the repository:

```shell
>> git clone https://github.com/JackShen1/sentimento-en.git
```

Learning datasets include large dataset with a review from Amazon, you can download it [here](http://www.cs.jhu.edu/~mdredze/datasets/sentiment/unprocessed.tar.gz).

## 📝 &nbsp;Requirements

In order to run the iPython notebook, you'll need **Python** (`v3.6+`) and the following libraries:

- **Keras** (`v2.4+`)
- **Gensim** (`v3.8+`)
- **Pandas** (`v1.2+`)
- **NumPy** (`v1.19.5+`)
- **NLTK** (`v3.5+`)
- **python-decouple** (`v3.4+`)
- **scikit-learn** (`v0.24.1`)
- **SciPy** (`v0.19.1+`)
- **Matplotlib** (`v2.1.1+`)
- **Jupyter**

The commands for installing these libraries will follow. First, let's create a virtual environment.

## 🐍 &nbsp;Creating a Virtual Environment

The easiest way to install `Keras`, `Gensim`, `NumPy`, `Jupyter`, `matplotlib` and our other libraries is to start with the Anaconda Python distribution.

1. Select your OS and follow the [installation instructions](https://docs.anaconda.com/anaconda/install/) for Anaconda Python. We recommend using Python 3.6+ (64-bit).

2. Install the Python development environment on your system:

	```shell
    >> pip install -U pip virtualenv
    ```
    
3. If you haven't done so already, download and unzip this entire repository from GitHub:
	
    ```shell
    >> git clone https://github.com/JackShen1/sentimento-en.git
    ```

4. Use `cd` to navigate into the top directory of the repo on your machine.

5. Open Anaconda Promt and install JupyterLab, also enter the following commands:

	```shell
    >> conda install -c conda-forge jupyterlab    # install JupyterLab
    >> conda create -n sentimento pip python=3.7  # choose the Python version
    >> source activate sentimento                 # activate the virtual environment
    ```
	
    Alternatively, you can install Jupyter with pip: `pip install jupyterlab`


6. Now we can install all the libraries we need:

	```shell
    >> pip install Keras gensim pandas numpy nltk python-decouple scikit-learn scipy matplotlib 
    ```
   
7. Launch Jupyter by entering:
	
    ```shell
	>> jupyter notebook
	```
Once you have everything installed, the next time to activate everything, do the following:

1. Open Anaconda Prompt and enter the project folder with the `cd` command. Now enter the following commands:
   
    ```shell
    >> conda activate sentimento
    >> jupyter notebook
    ```

## 📋 &nbsp;Overview

In this project in 3 parts the whole process of data preparation and training of our model was described, the comparative analysis of classifiers and various models is carried out. Each stage is accompanied by data visualization.


## 📫 &nbsp;Get in touch

<p align="center">
<a href="https://www.linkedin.com/in/yevhenii-shendrikov-6795291b8/"><img src="https://img.shields.io/badge/-Jack%20Shendrikov-0077B5?style=flat&logo=Linkedin&logoColor=white"/></a>
<a href="mailto:jackshendrikov@gmail.com"><img src="https://img.shields.io/badge/-Jack%20Shendrikov-D14836?style=flat&logo=Gmail&logoColor=white"/></a>
<a href="https://www.facebook.com/jack.shendrikov"><img src="https://img.shields.io/badge/-Jack%20Shendrikov-1877F2?style=flat&logo=Facebook&logoColor=white"/></a>
<a href=""><img src="https://img.shields.io/badge/-@jackshen-0088cc?style=flat&logo=Telegram&logoColor=white"/></a>
</p>
