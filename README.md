# mouse_data_analysis

##  Data Description

The dataset is stored in **long format**, where each row represents a single trial for a mouse. It includes the following columns:

- **`Id`**: Unique identifier for each mouse. Mice with `Id ≤ 100` were prepared by Reuben, and mice with `Id > 100` were prepared by Mimi.
- **`Experiment`**: The experiment session number. Reuben’s mice each participated in 2 experiments, and Mimi’s mice each participated in 3 experiments.
- **`Sex`**: Biological sex of the mouse (`M` for male, `F` for female).
- **`Drug`**: Drug condition administered during the trial (`Saline` or `SKF`(at dosage of 3.0 mg/kg) ).
- **`Genotype`**: Genetic type of the mouse (`KI` for Knock-In or `WT` for Wild-Type).
- **`Trial`**: Trial number within the experiment session (1 through 4).
- **`Outcome`**: Path efficiency, Mean Speed, or Escape Latency for that trial (numeric).

## ‍ Mouse Counts by Group

The dataset includes a total of **61 mice**:

- Reuben contributed 24 mice evenly split across genotype and sex: 7 Female KI, 7 Female WT, 5 Male KI, and 5 Male WT.
- Mimi contributed 37 mice: 11 Female KI, 12 Female WT, 7 Male KI, and 7 Male WT.

