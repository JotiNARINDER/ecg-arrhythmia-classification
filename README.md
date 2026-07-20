# ECG Arrhythmia Classification 🫀

Automated detection of cardiac arrhythmias from ECG signals.

## Results
- **Accuracy: 99.2%**
- 21,561 heartbeats analyzed
- 10 recordings (MIT-BIH PhysioNet)

## Methodology
1. Loading ECG signals (wfdb)
2. 0.5–50 Hz bandpass filtering (scipy)
3. Heartbeat segmentation around the R-peak
4. Extraction of 8 statistical features per heartbeat
5. Random Forest Classification (scikit-learn)

## Dataset
MIT-BIH Arrhythmia Database — PhysioNet

## Tech Stack
Python · wfdb · scikit-learn · scipy · matplotlib · seaborn

## Visual results
![Results](results.png)
