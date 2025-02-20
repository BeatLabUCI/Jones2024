# Synergistic biophysics and machine learning modeling to rapidly predict cardiac growth probability
#### Clara E. Jones and Pim J. A. Oomen

This repo can be utilized to recreate the results from Jones and Oomen 2024. The preprint of this paper can be found here: https://www.biorxiv.org/content/10.1101/2024.07.17.603959v1 
Before running these notebooks, please download and install MONARCH and CHAMELEON from the BEAT Lab GitHub page: https://github.com/BeatLabUCI/ You should use monarch as the environment for this repository. 

MONARCH is an open-source Python package to rapidly model cardiac physiology and remodeling. It is developed by the BEAT Lab at UCI directed by Pim Oomen. MONARCH stands for Model for Open-source Numerical simulations of Arrhythmia, Remodeling, Cardiac mechanics, and Hypertrophy.
CHAMELEON is an open-source Python package to accommodate model calibration and Gaussian process emulation (GPE).

## Generation of results
The results in the paper were generated using the three notebooks in the `notebooks` directory. The notebooks should be run in the following order:
1. `synthetic.ipynb`
2. `calibration.ipynb`
3. `validation.ipynb`

The results will be saved in the `results` directory within the output directory specified in the notebooks.