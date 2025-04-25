# mouse_data_analysis

##  Data Description

The dataset is stored in **long format**, where each row represents a single trial for a mouse. It includes the following columns:

- **`Id`**: Unique identifier for each mouse. Mice with `Id ≤ 100` were prepared by Reuben, and mice with `Id > 100` were prepared by Mimi.
- **`Expiriment`**: The experiment session number. Reuben’s mice each participated in 2 experiments, and Mimi’s mice each participated in 3 experiments.
- **`Sex`**: Biological sex of the mouse (`M` for male, `F` for female).
- **`Drug`**: Drug condition administered during the trial (`Saline` or `SKF`).
- **`Genotype`**: Genetic type of the mouse (`KI` for Knock-In or `WT` for Wild-Type).
- **`Trial`**: Trial number within the experiment session (1 through 4).
- **`Outcome`**: Path efficiency score for that trial (numeric).

##  Mouse Preparation

Reuben prepared mice with IDs from 1 to 100. These mice completed **2 experiments** each, with **4 trials per experiment**.

Mimi prepared mice with IDs from 101 to 137. These mice completed **3 experiments** each, also with **4 trials per experiment**.

## ‍ Mouse Counts by Group

The dataset includes a total of **54 mice**:

- Reuben contributed 24 mice evenly split across genotype and sex: 7 Female KI, 7 Female WT, 5 Male KI, and 5 Male WT.
- Mimi contributed 30 mice: 11 Female KI, 12 Female WT, 7 Male KI, and 7 Male WT.

