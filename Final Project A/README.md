
## Main Notebook Files
### MNIST1D.ipynb
This notebook contains many sections that must be run from top to bottom to get proper outputs that are already visible. Note that the results you may receive might be slightly different due to the generation of random masks for the attribution methods. The following are the most relevant sections that were used to answer questions in the report:
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
This notebook contains many sections that must be run from top to bottom to get proper outputs that are already visible. Note that the results you may receive might be slightly different due to the generation of random masks for the attribution methods The following are the most relevant sections that were used to answer questions in the report:
#### TASK 3 Q1 - Load Model and Evaluate
- The HMT pretrained model was loaded and evaluated using the same performance metrics from the MNIST1D.ipynb
#### TASK 3 Q2
- This section applies LIME and RISE methodology to each unique class from Histopathological Test Set
#### TASK 4
- This sections computes the average drop and average increase rates for HMT model

## Supplementary files Required:
- mnist1d_utils.py is a python file to re-create the MNIST-1D dataset. (Based on: https://github.com/greydanus/mnist1d)

- MNIST1D.pkl is a “pickle file” containing all data in the MNIST-1D dataset. The data in this file is save as a dictionary that can be also created using the function make_dataset() in the library mnist1d_utils.py. More information to read the dictionary is provided in the notebook MNIST1D.ipynb.
 
- Obtain the hmt_dataset folder containing two subfolders, including the train and test set for the HMT dataset. This can be obtained from the paper: https://www.nature.com/articles/srep27988

- HMT.h5 model is also required to avoid having to train on the dataset

- xai_utils.py is a Python file including utility functions needed for three state-of-the-art solutions in the field of visual XAI, Grad-CAM, RISE (Randomized Input Sampling for Explanation), and SISE (Semantic Input Sampling for Explanation). This was obtained from Ahmad Sajedi from ECE1512 Course TA.

## Python Libraries Required:

- Ensure you are running Python 3
- Ensure you have all the python libraries for running both Jupyter Notebooks (Includes numpy, scipy, tensorflow, matplotlib, and sklearn)
- pip install lime to run parts of the LIME attribution method (Based on: https://github.com/marcotcr/lime)

## References to Open Source Libraries
- F. Pedregosa et al., “Scikit-learn: Machine Learning in Python,” J. Mach. Learn. Res., vol. 12, no. 85, pp. 2825–2830, 2011.
- J. D. Hunter, “Matplotlib: A 2D Graphics Environment,” Comput. Sci. Eng., vol. 9, no. 3, pp. 90–95, May 2007, doi: 10.1109/MCSE.2007.55.
- M. Abadi et al., “TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems,” ArXiv160304467 Cs, Mar. 2016, Accessed: Mar. 01, 2022. [Online]. Available: http://arxiv.org/abs/1603.04467
- M. T. Ribeiro, S. Singh, and C. Guestrin, “‘Why Should I Trust You?’: Explaining the Predictions of Any Classifier,” in Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, New York, NY, USA, Aug. 2016, pp. 1135–1144. doi: 10.1145/2939672.2939778.
- “Keras: the Python deep learning API.” https://keras.io/ (accessed Mar. 01, 2022).
- G. Bradski, “The OpenCV Library,” Dr Dobbs J. Softw. Tools, 2000.
- C. R. Harris et al., “Array programming with NumPy,” Nature, vol. 585, no. 7825, pp. 357–362, Sep. 2020, doi: 10.1038/s41586-020-2649-2.
