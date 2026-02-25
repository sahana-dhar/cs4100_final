# Disease Progression Modeling
Group 12: Anya Wild, Sahana Dhar, Pradnya Balamurugan, Shireen Kumar

# Project Proposal
https://docs.google.com/document/d/1KpmXgZfMOgtlGukHRuJy4pufTLLY-a1wsbrNoEKHMC8/edit?usp=sharing


CNN + HMM pipeline that predicts brain disease progression
from longitudinal MRI scans and clinical data.
Target: Clinical Dementia Rating

## Dataset
OASIS-2- Longitudinal MRI in Nondemented and Demented Older Adults
Download: https://www.oasis-brains.org

## Notebooks
Run in order in Google Colab:
- 01_eda.ipynb       → explore the data
- 02_hmm.ipynb       → train HMM on CSV features
- 03_cnn.ipynb       → train CNN on MRI images
- 04_pipeline.ipynb  → connect CNN + HMM end to end