# UV-Vis-based absorbance assay analysis 

The assay is performed on a 96-well microplate, using a plate reader (Synergy H4, BioTek Instruments, Inc., Santa Clara, CA, USA) and Gen5 software (BioTek Instruments, Inc., Santa Clara, CA, USA).

This project contains a data analysis pipeline written in Python. The pipeline processes and analyzes data from an Excel file (raw_data.xlsx) and outputs the results to a new Excel file (output_YYYYMMDD.xlsx).

The script utilizes the following libraries:
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scipy
- Datetime
- Openpyxl

## Usage
1. Install the required dependencies
2. Place the Excel file containing the data in the project directory or use the default 'raw_data.xlsx'
3. Open Jupyter Notebook 'UV-Vis_analysis.ipynb' 
4. Update the Input parameters
5. Run the Jupyter Notebook 'UV-Vis_analysis.ipynb'
6. The results will be saved to a new Excel file named 'output_YYYYMMDD.xlsx' in the project directory.

## Citation
If you use this script as part of a scholarly publication, please consider citing the method paper.

Tunable Heteroaromatic Nitriles for Selective Bioorthogonal Click Reaction with Cysteine
Matic Proj, Nika Strašek, Stane Pajk, Damijan Knez, and Izidor Sosič
https://doi.org/10.1021/acs.bioconjchem.3c00163
