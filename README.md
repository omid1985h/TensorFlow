# ECG Heartbeat Categorization Dataset

## Overview

This repository contains a comprehensive dataset for classifying heartbeat signals, sourced from two renowned datasets: the **MIT-BIH Arrhythmia Dataset** and the **PTB Diagnostic ECG Database**. It is suitable for training deep neural networks due to its substantial sample size. Electrocardiography (ECG) is a critical tool for diagnosing heart diseases, as it records the heart's electrical activity over time.

Abnormalities in the ECG can indicate various cardiac issues, including:
- **Rhythm disturbances** (e.g., atrial fibrillation)
- **Inadequate blood flow** (e.g., myocardial ischemia)
- **Electrolyte imbalances** (e.g., hypokalemia)

This project aims to classify different types of arrhythmias using neural network techniques. The MIT-BIH dataset features 48 half-hour segments of two-channel ECG recordings from 47 subjects studied between 1975 and 1979. It includes both common and rare arrhythmias to enhance the model's learning potential. The dataset includes preprocessed and segmented heartbeat signals representing normal and abnormal cases, including myocardial infarction.

## Dataset Details

### Arrhythmia Dataset
- **Total Samples:** 109,446
- **Categories:** 5
- **Sampling Frequency:** 125 Hz
- **Source:** [PhysioNet's MIT-BIH Arrhythmia Dataset](https://physionet.org/physiobank/database/mitdb/)
- **Classes:** 
  - **N:** Normal (0)
  - **S:** Supraventricular (1)
  - **V:** Ventricular (2)
  - **F:** Fibrillation (3)
  - **Q:** Unclassified (4)

### PTB Diagnostic ECG Database
- **Total Samples:** 14,552
- **Categories:** 2
- **Sampling Frequency:** 125 Hz
- **Source:** [PhysioNet's PTB Diagnostic Database](https://physionet.org/physiobank/database/ptbdb/)

This dataset is instrumental for researchers and developers focusing on ECG classification and analysis, leveraging advanced machine learning techniques.
