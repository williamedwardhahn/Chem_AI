# FAU Chemistry & Biochemistry with AI

An educational data science curriculum that teaches **Python, cheminformatics, and machine learning** through real molecular data. Designed for students with no programming experience.

A collaboration between **[Salvatore Lepore](https://chemistry.fau.edu/leporelab/leporelabhome.php)** (Chemistry & Biochemistry) and **[William Hahn](https://mpcrlab.com/)** (Mathematics & Statistics) at Florida Atlantic University.

---

## Why Computational Chemistry?

Understanding molecules computationally is transforming drug discovery, materials science, and biochemistry. This curriculum uses molecular data as a compelling context to teach data science — the same approach used in our companion projects for [Birdsong](https://github.com/wjhahn/fau-birdsong) (bioacoustics) and [Climate](https://github.com/wjhahn/fau-geo) (geoscience).

---

## Notebooks

| # | Notebook | Description |
|---|---------|-------------|
| 0 | **Python Basics** | Variables, lists, loops, and functions — using molecules and chemical properties as context |
| 1 | **Molecules as Data** | SMILES notation, RDKit visualization, molecular descriptors, Morgan fingerprints |
| 2 | **Molecule Explorer** | Compare 5 chemical families (alcohols, acids, aromatics, amines, drugs), fingerprint heatmaps |
| 3 | **Clustering** | Extract 26 molecular features, train a PyTorch autoencoder, 2D chemical space embedding |
| 4 | **3D Structure & Dynamics** | py3Dmol visualization, PubChem API, chemical kinetics ODEs (first-order, reversible, Michaelis-Menten) |
| 5 | **Your Own Molecules** | Choose compounds from PubChem, run the full pipeline, see where they cluster — capstone project |

All notebooks run in **Google Colab** — no installation required.

---

## Compound Library

30 compounds across 5 chemical families:

| Family | Examples | Count |
|--------|---------|-------|
| Alcohols | Methanol, Ethanol, 1-Butanol, Isopropanol | 7 |
| Carboxylic Acids | Formic Acid, Acetic Acid, Benzoic Acid | 6 |
| Aromatics | Benzene, Toluene, Naphthalene, Aniline | 7 |
| Amines | Methylamine, Dimethylamine, Diethylamine | 6 |
| Drug-like | Aspirin, Ibuprofen, Caffeine, Lidocaine | 6 |

---

## Dependencies

All installed automatically in Colab:

- `rdkit` — Molecular structure and descriptors
- `pubchempy` — PubChem database access
- `py3Dmol` — Interactive 3D molecular visualization
- `torch` (PyTorch) — Neural networks
- `scikit-learn` — Preprocessing and PCA
- `matplotlib` / `seaborn` — Plotting
- `numpy` / `pandas` — Data manipulation
- `scipy` — ODE integration for kinetics

---

## Getting Started

1. Click any notebook link on the [landing page](index.html)
2. Click **"Open in Colab"** at the top
3. Run cells from top to bottom — each notebook is self-contained

---

## Data Sources

- **RDKit** — Open-source cheminformatics (descriptor computation, fingerprints, 2D drawing)
- **PubChem** — NIH's open chemistry database (100M+ compounds)
- **MoleculeNet** — Benchmark datasets for molecular ML

---

## Collaborators

- **Salvatore Lepore** — Department of Chemistry & Biochemistry, FAU
- **[William Hahn](https://mpcrlab.com/)** — Department of Mathematics & Statistics, FAU

---

## License

Educational use. RDKit is BSD-licensed. PubChem data is public domain.
