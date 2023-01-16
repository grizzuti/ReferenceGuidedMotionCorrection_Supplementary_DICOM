# Reference-guided retrospective motion correction for MRI

3D results (DICOM) of the experiments detailed in the paper:

- [G. Rizzuti, T. Schakel, N. R. F. Huttinga, J. W. Dankbaar, T. van Leeuwen, and A. Sbrizzi, *Towards retrospective motion correction and reconstruction for clinical 3D brain MRI protocols with a reference contrast*, 2023](https://arxiv.org/abs/2301.01106)

The results are organized as follows:

- Experiment 1: robustness test
    - motion corruption level 1 (corrupted1.zip/corrected1.zip/ground_truth.zip)
    - motion corruption level 2 (corrupted2.zip/corrected2.zip/ground_truth.zip)
    - motion corruption level 3 (corrupted3.zip/corrected3.zip/ground_truth.zip)
- Experiment 2: Choice of the reference contrast
- Experiment 3: Scanner reconstruction vs raw *k*-space data
    - Input from raw *k*-space data
    - Input from scanner reconstruction

# Instructions

For each subfolder, unzip the motion *corrupted* scan, *corrected* scan (with the proposed methodology), and *ground-truth* scan, and compare with any DICOM viewer.