# Psychopy Setup

This repository contains experiment with dynamic language control functionality. The experiment supports both German and English, and has been tested on Ubuntu systems using Python 3.8.18.

Setup Instructions
1. Clone the Repository
```bash
git clone https://github.com/HPI-CH/EPIStress.git
cd EPIStress
```
📌 Note: Update the base_path in the code to the path where the repository is saved on your system. 

2. Create and Activate Conda Environment (Make sure you have conda installed in your system)
 ```bash
conda env create -f environment.yml
conda activate psychopy
```


3. Run the Experiment:
Execute the following script to start the experiment:
```bash
cd Psychopy
python main_study_full.py
```
4. Language Selection
At the beginning of the experiment, you will be prompted to select your preferred language: English or German.

5. Complete the Questionnaire
Follow the instructions and answer all the questions presented during the experiment.


# Data Setup
Download the data using the link here #ToDo

# Data Loader:

Use Data Loader.ipynb to download Raw, Labelled, Preprocesses, Features data. Raw contains all unprocessed sensor streams (Muse EEG, Empatica ACC/BVP/EDA/TEMP, PsychoPy logs & questionnaires, stretched data); Labeled contains synchronized, segmented raw data per task; Preprocessed contains cleaned & preprocessed labeled data; Features contains features extracted from the preprocessed data.

How to use:
1. Set your base_path on the Main function.
2. Run all cells.
3. Execute the notebook cells to display the output you need.. 








