# 📁 Data Directory

This folder contains all datasets used throughout the pipeline for COVID-19 gene classification and drug repurposing using machine learning and deep learning.

It includes sample versions of raw sequences, processed training data, and extracted feature matrices to ensure reproducibility without uploading full datasets.

---

## 📂 Subfolders

### `raw/`
- Sample FASTA files for:
  - SARS-CoV-2 proteins (`covid_proteins_sample.fasta`)
  - Human reviewed proteins (`uniprot_human_reviewed_sample.fasta`)
- Additional raw samples:
  - GO annotations (`go_annotations_sample.csv`)
  - Protein–protein interactions (`protein_interactions_sample.csv`)
- 🧬 All data originates from **[UniProt](https://www.uniprot.org/)**  
- 📄 See `raw/README.md` for full description and citation

---

### `processed/`
- Cleaned, labeled, and merged datasets ready for modeling
- Includes:
  - `merged_final_dataset.csv`: Combined positive and negative dataset with unified columns, used for training models

> These are small, representative samples for code testing.  
> Full datasets are not included in the repository.

---

### `features/`
- Engineered features extracted from sequences and annotations:
  - `aac_features_sample.csv` – Amino Acid Composition (AAC)
  - `pcp_features_sample.csv` – Physicochemical Properties (PCP)
  - `go_features_sample.csv` – GO term binary feature matrix (based on enriched terms)
  - `centrality_features_sample.csv` – Network centrality metrics derived from PPI data

> Features are aligned by protein ID and used for ML/DL model input after merging.

---

## Data Usage & Licensing

- All sequence and annotation data are samples derived from publicly available UniProt resources.
- Refer to `raw/README.md` for source citation and license (CC BY 4.0).
