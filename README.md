# EPIStress

This repository contains experiment with dynamic language control functionality. The experiment supports both German and English, and has been tested on Ubuntu systems using Python 3.8.18.

Setup Instructions
1. Clone the Repository
```bash
git clone https://github.com/HPI-CH/EPIStress.git
cd EPIStress
```
📌 Note: Update the base_path in the code to the path where the repository is saved on your system.

2. Create and Activate Conda Environment
 ```bash
Option A:
conda env create -f environment.yml
conda activate psychopy
```

```bash
Option B:
python3.8 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

3. Run the Experiment:
Execute the following script to start the experiment:
```bash
python main_study_full.py
```
4. Language Selection
At the beginning of the experiment, you will be prompted to select your preferred language: English or German.

5. Complete the Questionnaire
Follow the instructions and answer all the questions presented during the experiment.










