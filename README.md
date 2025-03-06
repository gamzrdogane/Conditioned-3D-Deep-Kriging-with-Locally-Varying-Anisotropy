## Conditioned 3D DeepKriging with Locally Varying Anisotropy

This repository provides the implementation for Conditioned DeepKriging (C-DK) and Conditioned DeepKriging with Locally Varying Anisotropy (C-DK+LVA) applied to a 3D copper (Cu) modeling example.

### Overview of DeepKriging (DK) Structure in This Study
![Figure7](https://github.com/user-attachments/assets/15386a99-327f-45c5-9869-e93e7632f673)

## Comparative Framework
Conceptual diagram illustrating the comparative framework between Euclidean and HFM-based SPD. This framework modifies the kernel basis functions traditionally used in DK to include them in the embedding layer. In the diagram:
- S denotes the source location.
- D indicates the destination point.
- V_i represents an intermediate vertex.
![Figure3](https://github.com/user-attachments/assets/b39c7a13-32ce-45d4-b516-6e0860a3d504)

### Getting Started with 3D Estimation Using C-DK and C-DK+LVA

**Folder C-DK 3D-Nested CV:** This folder contains necessary datasets and demonstrates how DK is expanded into 3D, integrating Locally Dependent Moments (LDM) to accurately reproduce observed values at sampled locations, enhancing computational efficiency. Run `C-DK 3D-Nested CV.ipynb` to start.

**Folder C-DK+LVA 3D-Nested:** This folder includes datasets essential for implementing Locally Varying Anisotropy (LVA), which improves the model's ability to depict complex geological features. Run `C-DK+LVA 3D-Nested CV.ipynb` to proceed.

### Development and Testing Environment
The project was developed and tested with the following software and library versions:

| **Library**         | **Version**                                        |
|---------------------|----------------------------------------------------|
| **System platform** | Windows-10-10.0.22631-SP0                          |
| **Python**          | 3.10.16 (packaged by Anaconda, Inc.)               |
| **NumPy**           | 2.0.1                                              |
| **Pandas**          | 2.2.3                                              |
| **Matplotlib**      | 3.10.0                                             |
| **Seaborn**         | 0.13.2                                             |
| **pygeostat**       | 1.1.1                                              |
| **tqdm**            | 4.67.1                                             |
| **SciPy**           | 1.14.1                                             |
| **statsmodels**     | 0.14.4                                             |
| **scikit-learn**    | 1.6.0                                              |
| **TensorFlow**      | 2.18.0                                             |
| **hyperopt**        | 0.2.7                                              |
