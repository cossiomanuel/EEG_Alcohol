# EEG Data Analysis Project

## About the Dataset

This dataset arises from a study examining EEG correlates of genetic predisposition to alcoholism. It contains measurements from 64 electrodes placed on subjects' scalps, sampled at 256 Hz with a 3.9-millisecond epoch duration for 1 second. The subjects were divided into alcoholic and control groups. Each subject was exposed to either a single stimulus (S1) or two stimuli (S1 and S2) chosen from the 1980 Snodgrass and Vanderwart picture set. In dual-stimulus trials, S1 and S2 were either identical (matched condition) or different (non-matched condition).

## Attribute Information

Each trial is stored in its own file and follows this format:

- Trial Number
- Sensor Position
- Sample Number (0-255)
- Sensor Value (microvolts)
- Subject Identifier (Alcoholic: `a` or Control: `c`)
- Matching Condition (S1 object, S2 matched, S2 non-matched)
- Channel Number (0-63)
- Subject Name (serial code)
- Time (inverse of sample number in seconds)

## Dataset Source

This dataset is publicly available without any usage restrictions. Acknowledgments for this data should be made to Henri Begleiter at the Neurodynamics Laboratory, State University of New York Health Center at Brooklyn.

**Dataset Link:** [EEG Database](https://archive.ics.uci.edu/ml/datasets/eeg+database)

## Project Overview

This repository contains code and analysis for studying the correlation between sensor values in EEG data. The analysis focuses on exploring patterns and relationships within the dataset to gain insights into the EEG.

## File Descriptions

- `data/`: Contains the raw EEG data files.
- `analysis.ipynb`: Jupyter Notebook file containing the data analysis code.
- `results/`: Folder for storing analysis results, visualizations, and intermediate data.
- `LICENSE`: License information for the project.
- `README.md`: Project overview, dataset information, and instructions.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/eeg-data-analysis.git
   cd eeg-data-analysis
