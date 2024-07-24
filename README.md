# Portfolio

### 1. Wavelet Packet Transform Analysis of NMR Spectroscopy Signals in Classifying Rheumatoid Arthritis and Osteoarthritis
This project aimed to determine the effectiveness of Wavelet Packet Transform (WPT) in extracting features that can distinguish between Rheumatoid Arthritis (RA) and Osteoarthritis (OA).

- **Wavelet Packet Transform (WPT):** Decomposed NMR signals into subfrequency bands for detailed analysis and feature extraction. Employed three mother wavelets.
- **Statistical Tests:** Performed Shapiro-Wilk test for normality and statistical comparisons (Mann-Whitney U test and Independent t-test) between groups.
- **Python and MATLAB:** Accessed and visualized data, implemented WPT and statistical feature calculations.
- **Machine Learning Classifiers:** Used Support Vector Machine (SVM) and Logistic Regression (LR) to evaluate classification accuracy.
- **Cross-Validation:** Applied 4-fold cross-validation to validate the model's performance.

**Visualization of the Shannon entropy features of patients with RA and OA using Coiflet 1 mother wavelet:**
<img src="WPT_DB2_SHANNON_FEATURES.png" alt="WPT_DB2_SHANNON_FEATURES" width="500">

**Classification scores of SVM and LR using different power as statistical feature:**
<img src="https://github.com/user-attachments/assets/e52fc8e0-9590-45c3-8993-3ee0d1bafd73" alt="DWT Power SVM and LR" width="500">

### 2. Analysis of Deforestation and Flight Tracks of Lesser Spotted Eagles (Clanga pomarina) in Latvia using Computational Methods in MATLAB
This project aimed to correlate deforestation and changes in flight tracks of vulnerable lesser spotted eagles in Latvia using MATLAB.

- **Geospatial Mapping:** Used MATLAB's geoplot function to map and visualize flight tracks.
- **Flight Trajectory Interpolation:** Applied Rhumb-line interpolation in MATLAB to create continuous flight trajectories.
- **Machine Learning and Statistical Analysis:** Implemented logistic regression using scikit-learn and performed statistical tests using statsmodels.
- **Data Visualization:** Visualized geospatial data and flight trajectories in MATLAB.

**Trajectory of Lesser Spotted Eagles visualized using Geoplot**
<img src="https://github.com/user-attachments/assets/82ddf615-8e02-4ad5-8ebd-ef43e3a39642" alt="LATVIA MAP" width="500">

**Logistic regression plot for probability of deflection versus tree cover percent changes in Latvian regions**
<img src="https://github.com/user-attachments/assets/f32a2f63-b70d-4cf2-bafa-229c36398078" alt="SIGMOID FUNCTION" width="500">

### 3. SIR MODEL: A Theoretical Measles Outbreak with and without Vaccine Intervention
This project utilizes the SIR model to analyze a theoretical measles outbreak with and without vaccine intervention. Furthermore, the effect of vaccination rate and vaccination at different time points on the three compartments (Susceptible, Affected, Recovered) were analyzed.

- **Differential Equations:** Solved a differential equation in the simulation of ordinary SIR model and SIR model with vaccination.
- **Simulation and Modeling:** Utilized numpy, scipy, and matplotlib for simulating and modeling differential equations.

**Measles outbreak analysis with 25%, 50%, 75% and 100 % vaccination rate**
<img src="SIR.PNG" alt="SIR" width="500">

**Measles outbreak analysis with delayed vaccination at fixed 25% vaccination rate**
<img src="https://github.com/user-attachments/assets/881b5011-6179-437a-9dc9-a2a3cfd6ae4f" alt="SIR2" width="500">
