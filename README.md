# Exploring PyTorch’s Datasets
In this lab, you will explore PyTorch’s built-in datasets.  These datasets makes it extremely easy to get started with AI programming and provides plenty of data for your neural networks to learn from.  Let’s get started!
## Overview
PyTorch has a long list of included datasets.   Check here for the latest:
## Session Agenda
1.	Import PyTorch libraries
2.	Load a PyTorch’s dataset
3.	Explore the dataset

## Setting Up Your Environment
You have 3 options to follow along.  If you have a GPU on your laptop/desktop, you can load the libraries and dataset locally and run the notebook locally.   Otherwise, you can choose to run the notebook (free) in Google Colab.  Note, it is not required that you run the notebook to attend the session but it will help you understand the content.
### Option 1 - Setup your own laptop/PC with GPU for this workbook
If you have a GPU and want to work on your own laptop/PC:
1.  Download Anaconda  (https://www.anaconda.com/distribution/)
2.  Create a virtual environment using Anaconda on your local machine by following these commands:

```
conda create –name python3 python=3.8
conda activate python3
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch
conda install matplotlib jupyter
conda install -c intel scikit-learn
pip install efficientnet_pytorch
pip install torchsummary
python -m ipykernel install --user --name python3 --display-name "python3 "
git clone https://github.com/LeakyAI/ExplorePyTorchDatasets
jupyter notebook
```

4. Skip Option 2 below and deactivate the first code cell of the notebook by selecting it and typing "R" (intended for Colab only)
5. Specify the directory of your dataset in the 2nd cell below.

### Option 2 - Follow along in a Google Colab workbook

If you want to work in Google Colab, into Colab and pull the notebook file from GitHub:
1.  Go to colab.research.google.com
2.  Click **GitHub** and paste the address ** https://github.com/LeakyAI/ExplorePyTorchDatasets **
3.  Click **Search Icon**
4.  Click on ** ExplorePyTorchDatasets.ipynb **, notebook should now open
5.  Set the notebook settings to **Python** and **GPU** (**Edit -> Notebook Settings**) 
### Option 3 - Just follow along during the presentation
Running the notebook is not required to get something out of the session :)
