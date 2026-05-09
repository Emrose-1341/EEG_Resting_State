# EEG_Resting_State
A class project processing resting state EEG data to determine if there was a difference between those with and without Adverse Childhood Experiences


# Project includes: 
1. Linear Model	0.5	
2. Feature Selection / Engineering	0.5 (alpha-band frequencies)
3. Error Analysis - Confidence Intervals	0.5 
4. Combining Datasets	0.5	
5. ROC / AUC Curves	1
6. IRB Approved Study	1


# EEG Alpha Power Analysis
Overview

This project analyzes resting-state EEG data to compare alpha-band brain activity between participants with and without Adverse Childhood Experiences (ACEs) during:

Eyes Closed (EC) & 
Eyes Open (EO)

The script computes Power Spectral Density (PSD) using Welch’s method, normalizes the data, visualizes group differences, and performs basic statistical analysis.
What the Code Does

# The workflow:
1. Load processed EEG .txt files
2. Compute PSD for each electrode
3. Average PSD across electrodes and subjects
4. Extract alpha-band activity

# Statistics Run
1. Welch Power Spectral Density (PSD)
2. Log transformation
3. Baseline correction
4. Z-scoring normalization
5. Mean-centering
6. Peak alpha frequency extraction
7. Area Under the Curve (AUC) calculation
8. Welch’s independent samples t-test

# Visualizations Created
1. Group alpha power spectra
2. Baseline-corrected PSD plots
3. Z-scored PSD plots
4. Mean-centered alpha power plots
5. Eyes Closed vs Eyes Open comparisons
6. ACEs vs No ACEs comparisons
7. Combined group comparison plots
8. Peak alpha activation plots
9. Highlighted alpha-band region (8–12 Hz)
10. Overlaid spectral comparison graphs
