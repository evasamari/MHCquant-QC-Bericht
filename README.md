# MHCquant QC Report Enviroment Setup
This **README** provides the instructions for setting up the enviroment needed to run the MHCquant QC Report using MultiQC in a Python 3.9.19 enviroment. It includes steps to install the necessary tools and dependencies, as well as how to change the paths to load your Data

# Setting Up the Enviroment
**1. Create Conda Enviroment**\
Run the following command to create a new conda enviroment with Python 3.9.19: \
**Bash:**
conda create -n mhcquant_qc python=3.9.19

**2. Activate the Enviroment**\
conda activate mhcquant_qc

**3. Install Required Packages** \
pip install multiqc==1.12\
pip install notebook matplotlib numpy

# Change Paths to your TSV-Files
Please ensure that you update the Paths to TSV files and the Paths for saving the MultiQC reports based on your local setup in each Module

# Example for adjusting Paths
...
#Define paths for the input and output \
#Adjust to your local setup \
tsv_folder_path = "path/to/tsv/folder" \
report_path = "path/to/reports" \
...
