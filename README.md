# Heart-Rate Variability: A Potential Marker of Anesthetic Depth

## Description
This project investigates the feasibility of using heart-rate variability (HRV) parameters derived from electrocardiogram (ECG) to assess the anesthetic depth in patients undergoing surgery. In this project, intraoperative vital signs data are selected from surgical cases in the Vital Signs Database (VitalDB) (Lee et al., 2022). The ECG track data is then pre-processed, and HRV parameters are extracted to develop machine learning models to classify the DoA. 

This is part of the final project for EGBE 601: Medical Signal Processing and Instrumentation. 

## Structure
- `ECG_Pipeline.ipynb`: Jupyter Notebook containing the pipeline for pre-processing ECG track data, extracting HRV features, and labeling Depth of Anesthesia (DoA).
- `DT_and_KNN.ipynb`: Jupyter Notebook that loads the data from the ECG Pipeline, balances and scales the features, and constructs, trains/tests, and optimizes Decision Tree (DT) and K-Nearest Neighbors (KNN) models.
- `Case_3.csv`: CSV file containing the data generated from the ECG pipeline.
- `Project_Report.docx`: Word document containing the detailed report of the project.

## Results and Interpretation
The optimized DT model achieved an accuracy of 95.83%, while the KNN model achieved 86.67% accuracy, with the light class exhibiting the highest accuracy in both models. The study suggests HRV as a promising marker for assessing anesthesia depth, advocating for further validation through larger and more diverse datasets, exploration of alternative machine learning architectures, and consideration of broader surgical contexts beyond the light, moderate, and deep classification.

## References
Lee, H.-C., et al., VitalDB, a high-fidelity multi-parameter vital signs database in surgical patients. Scientific Data, 2022. 9(1): p. 279.