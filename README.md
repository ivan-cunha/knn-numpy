# KNN using NumPy

This is an implementation and test of the KNN (K nearest neighbors) clustering algorithm using only the NumPy library in Python. I created this project while learning about the KNN algorithm and wanted to better understand the math behind it. It looked like a simple and fun implementation to work on.

# Dataset

For this project, I used a wine quality dataset as a test subject for the KNN functions. Although not very relevant to this project, it was a good dataset to work with. The first implementation was straightforward, following the description of the algorithm closely. The second implementation used some optimizations after exploring interesting functions in NumPy.

# Results

The optimizations worked, but the improvement wasn't spectacular. The first implementation took 0.319 seconds, while the second implementation took 0.241 seconds, which is approximately a 22% improvement. However, when compared to the scikit-learn library, the difference was much bigger. The scikit-learn implementation took only 0.07 seconds for the same dataset, which is orders of magnitude faster. This shows that there is still much more optimization that can be done in standard libraries used for machine learning.

# How to Run

The easiest way to run the code is to create a Conda environment using the requirements file and then run the code in Jupyter Notebook. Alternatively, you can upload the notebook to Google Colab.

```bash
conda create --name knn-numpy --file requirements.txt
conda activate knn-numpy
```
