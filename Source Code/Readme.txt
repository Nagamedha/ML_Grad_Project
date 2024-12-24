# README for Running Code in Jupyter Notebook

This README provides step-by-step instructions to run the code for the three parts: Classification, Multi-Label Classification, and Missing Value Estimation in a Jupyter Notebook environment.

---

Prerequisites:

Before running the code, ensure you have the following:

1. Python Environment: Python 3.8 or later.
2. Libraries Installed:
    - `numpy`
    - `pandas`
    - `scikit-learn`
    - `matplotlib`

You can install the libraries using the following command:
bash
pip install numpy pandas scikit-learn matplotlib


3. Dataset Files: Ensure the following datasets are available in the working directory:
   - For Classification:
     - `TrainData1.txt`, `TrainLabel1.txt`, `TestData1.txt`
   - For Multi-Label Classification:
     - `MultLabelTrainData.txt`, `MultLabelTrainLabel.txt`, `MultLabelTestData.txt`
   - For Missing Value Estimation:
     - `MissingData1.txt`, `MissingData2.txt`, `MissingData3.txt`

---

## Steps to Run

1. Classification (Dataset #)
        
        1. Open the `Classification` code in a Jupyter Notebook cell.
        2. Update the file paths if needed:
           - `TrainData#.txt`
           - `TrainLabel#.txt`
           - `TestData#.txt`
           - Output file: `SakhamuriClassification#.txt`
        3. Run the code.
        4. The output will include:
           - Predictions saved to `SakhamuriClassification1.txt`.
           - Predictions saved to `SakhamuriClassification2.txt`.
           - Predictions saved to `SakhamuriClassification3.txt`.
           - Predictions saved to `SakhamuriClassification4.txt`.
           - Predictions saved to `SakhamuriClassification5.txt`.
           - Predictions saved to `SakhamuriClassification6_RF_GBR.txt`.

     

2. Missing Value Estimation

        1. Open the `Missing Value Estimation` code in a new Jupyter Notebook cell.
        2. Update the file paths if needed for each dataset:
           - Input files:
             - `MissingData1.txt`
             - `MissingData2.txt`
             - `MissingData3.txt`
           - Output files:
             - `SakhamuriMissingData1.txt`
             - `SakhamuriMissingData2.txt`
             - `SakhamuriMissingData3.txt`
        3. Run the code for each dataset.
        4. The output will include:
           - Imputed Data saved to the output files.


3. Multi-Label Classification

        1. Open the `Multi-Label Classification` code in a new Jupyter Notebook cell.
        2. Update the file paths if needed:
           - `MultLabelTrainData.txt`
           - `MultLabelTrainLabel.txt`
           - `MultLabelTestData.txt`
           - Output files:
             - `SakhamuriMultiLabelTestPredLR.txt`
             - `SakhamuriMultiLabelTestPredMLP.txt`
             - `SakhamuriMultiLabelTestPredRF.txt`
        3. Run the code.
        4. The output will include:
           - Predictions saved to the output files.
---

## Notes

- Ensure all dataset files are in the same directory as the Jupyter Notebook, or provide absolute file paths.
- If encountering issues, verify dataset formatting and ensure no missing files.
- Modify the file paths in the code to match your directory structure.

---
