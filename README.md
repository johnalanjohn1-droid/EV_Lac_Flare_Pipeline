# EV_Lac_Flare_Pipeline
Flare detection and energy analysis pipeline for EV Lac using TESS data.
This repository contains the Python notebook used for the project:
**Detecting and Characterising Stellar Flare Statistics and Energy Distributions of EV Lac**
The pipeline uses 20-second cadence TESS Sector 56 data for EV Lac (TIC 154101678).
The notebook includes:
- TESS light-curve retrieval
- quality filtering
- Savitzky-Golay detrending
- flare detection using AltaiPony
- flare candidate validation
- flare amplitude and duration analysis
- equivalent duration calculation
- flare-energy estimation

The finalised version of the detection pipeline can be viewed under the Markdown section named "Final Pipeline" towards the end of the .ipynb file.
