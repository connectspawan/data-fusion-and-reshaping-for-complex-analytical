# Data Fusion and Reshaping Project

## BrainyBeam Internship Submission

**Author**: \Pawan Kumar Barnawal\
**Date**: August 24, 2025

## Project Overview

This project fulfills the BrainyBeam internship task: "Merge and reshape data from multiple DataFrames to create complex analytical datasets." It uses synthetic data (`data1.csv`, `data2.csv`, `data3.csv`) representing customer information, transaction records, and engagement metrics. The workflow includes:

- Loading and cleaning data (handling duplicates, missing values).
- Merging DataFrames on `customer_id`.
- Reshaping data via pivoting, aggregating, and melting.
- Saving the analytical dataset as `analytical_dataset.csv`.

## Project Structure

```
data-fusion-and-reshaping-for-complex-analytical/
├── main.ipynb              # Main Python script for Data Fusion and Reshaping
├── environment.yml     # Conda environment configuration file
├── data/
│   ├── data1.csv       # input CSV file 1
│   ├── data2.csv       # input CSV file 2
│   └── data2.csv       # input CSV file 3
│ 
├── README.md        # Project documentation
├── report/
│     └── Task_4_Report.docx       # Report of the project
└── output/
      └── analytical_dataset.csv       # Contains the final `analytical_dataset.csv`.

```

## How to Run

1. Install Conda (Miniconda/Anaconda).
2. Create the Conda environment:

   ```bash
   conda env create -f environment.yml
   conda activate data_fusion
   ```
3. Install additional packages (if needed):

   ```bash
   pip install fuzzywuzzy python-Levenshtein
   ```
4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook src/main.ipynb
   ```
5. Run all cells to reproduce the results.

## Notes

- The synthetic data mimics real-world scenarios with missing values, duplicates, and mismatched keys.
- The notebook is designed to be adaptable to BrainyBeam’s actual data.

### Contact
For questions or issues, contact at connecspawan@gmail.com.
