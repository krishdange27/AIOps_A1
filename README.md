## Q1 — Technical Debt Diagnosis

The `Q1/` folder contains my submission for the technical debt diagnosis question.

It includes:

- Identification of the hidden technical-debt category for each of the three given scenarios.
- Explanation of the identified categories.
- A proposed mitigation for one of the scenarios using a relevant tool or practice from the lectures.

**Submission:** `Q1/AiOps_Q1.pdf`

---

## Q2 — MLflow Experiment Comparison

The `Q2/` folder contains my implementation and results for the MLflow experiment comparison.

The work includes:

- Changing the predictor from RandomForest to **MLP**.
- Changing the dataset from IRIS to **MNIST**.
- Running at least **six experiments**.
- Varying at least **two hyperparameters**.
- Tracking the experiments using **MLflow**.
- Comparing the runs and identifying the best-performing run.
- Analysis of overfitting using training loss and validation accuracy.
- Analysis of the effect of the varied hyperparameters.
- The exact MLflow parameter and metric logging code.

### Files

- `Q2.ipynb` — Notebook containing the implementation.
- `AiOps_Q2.pdf` — Written submission.
- `part1.png` — MLflow experiment results.
- `part2.png` — Supporting results/evidence.

---

## Q3 — DVC Data Versioning & Rollback

The `Q3_DVC/` folder contains my implementation for dataset versioning and rollback using **DVC** and **Git**.

The work includes:

- Creating the initial dataset version.
- Tracking the dataset using DVC.
- Configuring the DVC remote.
- Creating a second dataset version using the provided `new-labels.zip`.
- Tracking the updated dataset using DVC.
- Committing the different dataset versions using Git.
- Rolling back to the earlier dataset version using Git and DVC.
- Verifying the restored dataset.

### Important Files

- `data.csv`
- `data.csv.dvc`
- `.dvc/`
- `.dvcignore`

The Git history can be checked to verify the different dataset versions, commits, and rollback process.

---

# Q4 — End-to-End Reproducibility

**Q4 was completed as a collaboration between Partner A and Partner B.**

- **Partner A:** Madhav AK — DA24B012
- **Partner B:** Krish Dange — DA24B011 (me)

All Q4 work was carried out in the following repository:

[**AIOps_A1_Q4**](https://github.com/Madhav-AK/AIOps_A1_Q4)

Please refer to this repository for the complete Q4 implementation, Git history, MLflow results, DVC setup, and proof of reproducibility.

## Q4 Collaboration Process

- The repository was created by **Partner A (Madhav AK)** with the required `environment.yml`, `requirements.txt`, DVC configuration, and training code.
- **Backblaze** was used as the remote DVC storage.
- Partner A ran the code using MLflow and recorded the results in `partnerA_proof/`.
- **Partner B (Krish Dange)** pulled the repository and independently reproduced the results using the permitted commands.
- Partner B's results are available in `partnerB_proof/`.
- Partner B verified that the results and environment were reproduced correctly.
- The repository history can be checked to verify the complete process.


## Repository Structure

```text
AIOps_A1/
│
├── Q1/
│   └── AiOps_Q1.pdf
│
├── Q2/
│   ├── Q2.ipynb
│   ├── AiOps_Q2.pdf
│   ├── part1.png
│   └── part2.png
│
├── Q3_DVC/
│   ├── data.csv
│   ├── data.csv.dvc
│   ├── .dvc/
│   ├── .dvcignore
│   └── ...
│
├── Q4/
│   └── ...
│
└── README.md
