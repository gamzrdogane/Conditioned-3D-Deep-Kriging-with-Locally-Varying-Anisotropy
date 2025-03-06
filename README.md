## Conditioned 3D Deep Kriging with Locally Varying Anisotropy
This repository contains Jupyter notebooks for performing both Conditioned 3D DeepKriging (C-DK) and C-DK with Locally Varying Anisotropy (LVA) (i.e. C-DK+LVA) on a 3D copper (Cu) example.

### The structure of our DK in this study: 
![Figure7](https://github.com/user-attachments/assets/15386a99-327f-45c5-9869-e93e7632f673)



## Conceptual diagram illustrating the comparative framework between Euclidean and HFM-based SPD (integrated into the embedding layer, (modified from (Bogrash et al., 2023))). S denotes the source location, D indicates the destination point, and V_i represents an intermediate vertex.
![Figure3](https://github.com/user-attachments/assets/b39c7a13-32ce-45d4-b516-6e0860a3d504)



### Getting Start for the 3D estimation

Folder C-DK 3D-Nested CV: This folder contains necessary datasets and demonstrates the expansion of DK into 3D and the integration of Locally Dependent Moments (LDM) to accurately reproduce observed values at sampled locations without increasing the computational burden. run C-DK 3D-Nested CV.ipynb in the folder.  


Folder C-DK+LVA 3D-Nested:  This folder contains necessary datasets and introduces the addition of locally varying anisotropy (LVA), enhancing the model’s ability to represent complex geological features by incorporating LVA.run C-DK 3D-Nested CV.ipynb in the folder. Run C-DK+LVA 3D-Nested CV.ipyb in the folder.


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


