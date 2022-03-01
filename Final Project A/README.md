
## Main Notebook Files
### MNIST1D.ipynb
This notebook contains many sections that must be run from top to bottom to get proper outputs that are already visible. Note that the results you may receive might be slightly different due to the generation of random masks for the attribution methods
The following are the most relevant sections that were used to answer questions in the report:
#### TASK 1 Q1 - Model Creation
- This section outlines the creation of the CNN model for MNIST-1D
#### TASK 1 Q2 - Training the model
- This section outlines how the model was trained
#### TASK 1 Q3 - Evaluation Metrics
- This section outlines the performance metrics applied when the CNN model was tested
#### TASK 1 Q4
- This section shows some of the successful predictions and failed predictions made by the CNN model
#### TASK 2 Q2
- This section applies LIME and RISE attribution methods for each unique digits from 0-9
#### Task 4
- This sections computes the average drop and average increase rates for MNIST-1D CNN model

### HMT.ipynb
The following are the most relevant sections that were used to answer questions in the report:
#### TASK 3 Q1 - Load Model and Evaluate
- The HMT pretrained model was loaded and evaluated using the same performance metrics from the MNIST1D.ipynb
#### TASK 3 Q2
- This section applies LIME and RISE methodology to each unique class from Histopathological Test Set
#### TASK 4
- This sections computes the average drop and average increase rates for HMT model

## Supplementary files Required:
- mnist1d_utils.py is a python file to re-create the MNIST-1D dataset. (Based on: https://github.com/greydanus/mnist1d)

- MNIST1D.pkl is a “pickle file” containing all data in the MNIST-1D dataset. The data in this file is save as a dictionary that can be also created using the function make_dataset() in the library mnist1d_utils.py. More information to read the dictionary is provided in the notebook MNIST1D.ipynb.
 
- hmt_dataset is a folder containing two subfolders, including the train and test set for the HMT dataset.

- xai_utils.py is a Python file including utility functions needed for three state-of-the-art solutions in the field of visual XAI, Grad-CAM, RISE (Randomized Input Sampling for Explanation), and SISE (Semantic Input Sampling for Explanation). 

- models is a folder containing the pre-trained VGG7 model for HMT dataset.

- Project A_FAQs: A list of Frequently Asked Questions which try to throw light on (almost) all of your questions and concerns which you may have during the course of Project A.

## Python Libraries Required:

- Ensure you are running Python 3
- Ensure you have all the python libraries for running both Jupyter Notebooks (Includes numpy, scipy, tensorflow, matplotlib, and sklearn)
- pip install lime to run parts of the LIME attribution method (Based on: https://github.com/marcotcr/lime)

