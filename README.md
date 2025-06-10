# Single-cell RNA-seq Trachea vs Tongue

This repository contains code and data to compare single-cell RNA-seq profiles from mouse trachea and tongue using the [`scprep`](https://github.com/KrishnaswamyLab/scprep) package.

## Files

- `Final project supporting code_ChengHungTu.ipynb` – Jupyter notebook that loads the count tables, performs preprocessing, principal component analysis (PCA), UMAP, and clustering of the cells.
- `Final project write up.docx` – Written report with background, methods, and results.
- `Tongue-counts.csv` and `Trachea-counts.csv` – Count matrices (subset of the Figshare dataset ["Single-cell RNA-seq data from Smart-seq2 sequencing of FACS sorted cells v2"](https://figshare.com/articles/dataset/Single-cell_RNA-seq_data_from_Smart-seq2_sequencing_of_FACS_sorted_cells_v2_/5829687) ).
- `metadata_FACS.csv` – Metadata file referenced in the notebook but not included in this repository.

## Usage

1. Install the [`scprep`](https://github.com/KrishnaswamyLab/scprep) package (e.g., with `pip install scprep`).
2. Open `Final project supporting code_ChengHungTu.ipynb` in Jupyter.
3. Run the notebook cells to reproduce the analysis.
