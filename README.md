# Pybrain: Diffusion in python (Dipy)

In this two-days workshop, you will learn how to use different diffusion MRI (dMRI) techniques in an open-source environment. During the workshop, I will explain the theory behind different diffusion MRI techniques. This will be followed by practical tutorials based on the Diffusion in Python (Dipy) package ([dipy.org](https://dipy.org/)). 

# Preparations 

To participate in the workshop, you will need to install Dipy and Fury. To install the dependencies of these two packages, I suggested that you install [anaconda] (https://www.anaconda.com/products/individual) (in the anaconda website you will find the installers for different operative systems).

After installing anaconda, open an anaconda prompt terminal and type:

conda install -c conda-forge dipy

For some Dipy visualization tools you also need to have Fury installed. For this, in the anaconda prompt terminal, type:

pip install fury

More information on Dipy and Fury installation can be found in the following [page](https://dipy.org/documentation/1.3.0./installation/#installing-a-release)).


# Workshop summary

The workshop will start with a 30 min warm-up at 9:00 am UTC on both days. During this warm-up, we can resolve technical difficulties you might be experiencing. The actual workshop will start at 9:30. Lunch break is from 12 to 1, and we will continue until 3:30.

Below you can find the topics discussed on the two days:
** 23/11/2020 **
- Workshop introduction
- Diffusion MRI data as 4D images and simple Apparent Diffusion Coefficient calculation
- Diffusion Tensor Imaging (DTI)
- Introduction to DTI tractography
(Lunch)
- Exploration of different reconstruction techniques for tractography
- Probabilistic vs Deterministic Tractography
- High angular resolution diffusion imaging (DSI, Q-ball, CSA)
- Open questions and discussion

** 24/11/2020 **
- Diffusion MRI pre-processing
- Diffusion MRI signal representation techniques (DTI, DKI, MAP-MRI)
- Diffusion MRI microstructural models (WMTI, SMT, fw-DTI)
(Lunch)
- Combining advanced dMRI metrics and tractography
- Overview of other tools available in Dipy 
- Discussion of the future directions on Dipy development
- Open questions and discussion
