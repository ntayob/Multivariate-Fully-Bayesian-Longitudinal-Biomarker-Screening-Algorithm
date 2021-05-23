# Multivariate-Fully-Bayesian-Longitudinal-Biomarker-Screening-Algorithm

We have provided an example set of code to implement the multivariate fully Bayesian (mFB) proposed in "A Bayesian Screening Approach for Hepatocellular Carcinoma Using Multiple Longitudinal Biomarkers" by Tayob et al (Biometrics, 2017). 

We propose a robust computationally efficient screening algorithm that exploits all the available biomarker information. The fully Bayesian hierarchical joint model for the trajectory of multiple biomarkers in patients with and without the disease extends the work of Skates et al. (2001) beyond a single marker. For each biomarker, we assume the marker levels randomly vary around a constant mean in the absence of disease. After disease onset, each biomarker may or may not change over time.

The example datasets are generated based on Simulation Scenario A in the manuscript. We provide a training dataset (Training_data.csv) to estimate parameters of the mFB algorithm and a validation dataset (Validation_data.csv) to evaluate the performance of the algorithm.

To implement the multivariate fully Bayesian algorithm, a user can run the code "mFB_code.R". We have also provided code to run the algorithm for a single biomarker proposed by Skates et al. (2001) in "uFB_code.R".
