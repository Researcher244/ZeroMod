# Reproducibility Code for: "ZeroMod: Optimizing Neural Network Training Dynamics through Targeted Activation Function Modification"  
This repository contains the implementation and source code for the experiments presented in the paper as is.  
This codebase allows the exact reproduction of the experimental results reported in the paper. The provided scripts were run without modification on the environments described below. Simply run the scripts as-is after setting the desired function and random seed.  

- The code does not require any modification beyond selecting the desired function and seed.  
- All dependencies are standard and are automatically available on Google Colab / Kaggle by default.  
- For GPU acceleration, ensure that your runtime is configured to use a **Tesla T4** or equivalent CUDA 12.4 compatible GPU.  

***
### Environment and Hyperparameters  
For Cifar100 experiment  
Enviornment 1: Google Colab  
Torch Version: 2.6.0+cu124  
CUDA Version: 12.4  
cuDNN Version: 90300  
NumPy Version: 2.0.2  
Python Version: 3.11.11  
Number of GPUs: 1  
Current GPU Name: Tesla T4  
GPU Name: Tesla T4  
Total Memory: 15.828320256 GB  
CUDA Capability: 7.5  
***
### For Other experiments  
Enviornment 2: Kaggle  
Torch Version: 2.5.1+cu121  
CUDA Version: 12.1  
cuDNN Version: 90100  
NumPy Version: 1.26.4  
Python Version: 3.10.12  
Number of GPUs: 2  
Current GPU Name: Tesla T4  
GPU Name: Tesla T4  
Total Memory: 15.828320256 GB  
CUDA Capability: 7.5  

***
### Hyperparameters  
To satisfy (14) the parameters are set as such:  

PMish : beta= 0.9454113159514  
MishPlus: alpha = 0.025 and beta= 0.5  
SwishPlus: alpha = 0.125 and beta=0.5  
ESwish: alpha = 1.25  

To satisfy (15) the parameters are set as such:  

PMish : beta= 1.34198859922  
MishPlus: alpha = -0.125 and beta= 0.5  
SwishPlus: alpha = -0.025 and beta=0.5  
ESwish: alpha = 0.95
