
## Main Notebook Files
### MNIST1D.ipynb

### HMT.ipynb


## Supplementary files Required:
- mnist1d_utils.py is a python file to re-create the MNIST-1D dataset. (Based on: https://github.com/greydanus/mnist1d)

- MNIST1D.pkl is a “pickle file” containing all data in the MNIST-1D dataset. The data in this file is save as a dictionary that can be also created using the function make_dataset() in the library mnist1d_utils.py. More information to read the dictionary is provided in the notebook MNIST1D.ipynb.
 
- hmt_dataset is a folder containing two subfolders, including the train and test set for the HMT dataset.

- xai_utils.py is a Python file including utility functions needed for three state-of-the-art solutions in the field of visual XAI, Grad-CAM, RISE (Randomized Input Sampling for Explanation), and SISE (Semantic Input Sampling for Explanation). 

- models is a folder containing the pre-trained VGG7 model for HMT dataset.

- Project A_FAQs: A list of Frequently Asked Questions which try to throw light on (almost) all of your questions and concerns which you may have during the course of Project A.

## Python Libraries Required:

- Ensure you have all the python libraries for running both Jupyter Notebooks
- pip install lime to run parts of the LIME attribution method

