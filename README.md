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

Eyes Closed (EC)
Eyes Open (EO)

The script computes Power Spectral Density (PSD) using Welch’s method, normalizes the data, visualizes group differences, and performs basic statistical analysis.
What the Code Does

The workflow:

Loads processed EEG .txt files
Computes PSD for each electrode
Averages PSD across electrodes and subjects
Extracts alpha-band activity
Applies:
log normalization
z-scoring
baseline correction
Creates comparison plots
Finds peak alpha frequencies
Runs statistical testing between groups

# Statistics Run
Welch Power Spectral Density (PSD)
Log transformation
Baseline correction
Z-scoring normalization
Mean-centering
Peak alpha frequency extraction
Area Under the Curve (AUC) calculation
Welch’s independent samples t-test

# Visualizations Created
Group alpha power spectra
Baseline-corrected PSD plots
Z-scored PSD plots
Mean-centered alpha power plots
Eyes Closed vs Eyes Open comparisons
ACEs vs No ACEs comparisons
Combined group comparison plots
Peak alpha activation plots
Highlighted alpha-band region (8–12 Hz)
Overlaid spectral comparison graphs
