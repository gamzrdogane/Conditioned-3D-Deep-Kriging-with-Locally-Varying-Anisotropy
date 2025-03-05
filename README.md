## Conditioned 3D Deep Kriging with Locally Varying Anisotropy
This repository contains Jupyter notebooks for performing both Conditioned 3D DeepKriging (C-DK) and C-DK with Locally Varying Anisotropy (LVA) on a 3D copper (Cu) example.

C-DK 3D-Nested CV.ipynb: This notebook demonstrates the expansion of DK into 3D and the integration of Locally Dependent Moments (LDM) to accurately reproduce observed values at sampled locations without increasing the computational burden. 

C-DK+LVA 3D-Nested CV.ipynb introduces the addition of locally varying anisotropy (LVA), enhancing the model’s ability to represent complex geological features by incorporating LVA.

This project was developed and tested with the following environment and library versions:

| **Library**           | **Version**                                              |
|:----------------------|:---------------------------------------------------------|
| **System platform**   | Windows-10-10.0.22631-SP0                                |
| **Python**            | 3.10.16 (packaged by Anaconda, Inc.)                     |
| **NumPy**             | 2.0.1                                                    |
| **Pandas**            | 2.2.3                                                    |
| **Matplotlib**        | 3.10.0                                                   |
| **Seaborn**           | 0.13.2                                                   |
| **pygeostat**         | 1.1.1                                                    |
| **tqdm**              | 4.67.1                                                   |
| **SciPy**             | 1.14.1                                                   |
| **statsmodels**       | 0.14.4                                                   |
| **scikit-learn**      | 1.6.0                                                    |
| **TensorFlow**        | 2.18.0                                                   |
| **hyperopt**          | 0.2.7                                                    |


