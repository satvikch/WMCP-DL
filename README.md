# WMCP-DL : Denoising of Brain MR Images

Adaptive Weighted Minimax-Concave Penalty-Based Dictionary Learning for Brain MR Images

This repository contains the implementation of the Adaptive Weighted Minimax-Concave Penalty (WMC) based Dictionary Learning for Brain MR Images, as described in our paper published at the 2020 IEEE 17th International Symposium on Biomedical Imaging (ISBI). The approach uses a weighted ℓ1-minimization technique under tight frames, leveraging an adaptive threshold for enhancing dictionary learning and image denoising performance.

# Introduction

The code implements a novel sparse recovery algorithm using a weighted minimax-concave penalty, which adapts weights iteratively to improve the representation capability of dictionary learning algorithms. This results in superior denoising performance in brain MR images compared to state-of-the-art techniques.

# Features

- Implement the Weighted Minimax Concave Penalty optimization algorithm for Sparse Coding (WMCPSC).
- Demonstrates superior denoising performance using learned dictionaries.
- Utilizes FISTA for efficient optimization.

# Requirements

- Python 3.6 or above
- NumPy
- SciPy
- Matplotlib (for visualization)
- open-cv


## Files in Final Codes:

- IRLI_Dictionary_Learning.ipynb - IRL1 based dictionary Learning.
- K-SVD.ipynb - KSVD-based dictionary learning.
- K-SVD_dict_initialize_final.ipynb - KSVD-based dictionary learning with custom dictionary initialization.
- L_1_Dictionary_Learning.ipynb - ℓ1-minimization dictionary learning.
- MCP_Dictionary_Learning_Final.ipynb - MCP-based dictionary learning.
- WMCP_Dictionary_Learning_Final.ipynb - Weighted ℓ1-minimization dictionary learning.

- For the dictionary initialized, the dicitonary_initiliaze.mat file is used. The input MRI (input.png) is used, and (15% noise.png) is generated as the noisy image.

# If you find this work useful for your research, please cite:

@inproceedings{pokala2020adaptive,
  title={Adaptive Weighted Minimax-Concave Penalty Based Dictionary Learning for Brain MR Images},
  author={Pokala, Praveen Kumar and Chemudupati, Satvik and Seelamantula, Chandra Sekhar},
  booktitle={IEEE 17th International Symposium on Biomedical Imaging (ISBI)},
  year={2020},
  organization={IEEE}
}

# This project is licensed under the MIT License - see the LICENSE file for details.

This README provides a comprehensive overview of the project, including how to set up and run the code, visualize results, cite the work, and contact the authors. It also addresses installation requirements and acknowledges support and contributions.
