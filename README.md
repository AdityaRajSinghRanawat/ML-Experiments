# Machine Learning Lab — Current status & visual guide ✅

This repository contains hands‑on ML experiments from coursework, with notebooks, data and visual outputs. The READMEs for each experiment now include step‑by‑step guides and embedded screenshots (see `screenshot/` folders).

---

## Quick status (what's available now) 🔎

| Experiment | Notebook / Code | Screenshots | README status |
|---|:---:|:---:|:---:|
| `01-Find-S-Algorithm` | `code/` (notebook) | — (no screenshots) | README present |
| `02-Candidate-Elimination Algorithm` | `code/` + notebooks | `screenshots/` (data, output) ✅ | README present |
| `03-Naive-Bayes (In-Built)` | `code/code.ipynb` | `screenshot/` (output, use-case, logo) ✅ | README updated (image‑rich) |
| `03-Naive-Bayes (Manual)` | `code/code.ipynb` | `screenshot/` (formula, graph, output) ✅ | README updated (image‑rich) |
| `04-Decision-Tree` | `code/code.ipynb` | `screenshot/` (tree, output, working) ✅ | README updated (image‑rich) |
| `05-K-Nearest-Neighbour` | `code/code.ipynb` | `screenshot/` (plots, output, working) ✅ | README updated (image‑rich) |
| `06-K-Means-Clustering` | `code/code.ipynb` | `screenshot/` (centroids, assignments, working) ✅ | README updated (image‑rich) |

---

## How screenshots were used 📸
- Each experiment's `README.md` now embeds images from its `screenshot/` folder to explain outputs and guide interpretation.  
- Use the images to quickly identify expected notebook outputs before running code.

---

## How to run the notebooks ▶️
1. Open the experiment folder (for example `06-K-Means-Clustering/code/code.ipynb`).
2. Start Jupyter / VS Code Notebook and run cells top‑to‑bottom.
3. If a README mentions hyperparameters (e.g. `n_clusters`, `n_neighbors`), change them and re‑run to observe effects.

Quick install for dependencies:

```
pip install numpy pandas matplotlib scikit-learn jupyter
```

---

## Suggested next steps (priority) 🛠️
1. Add screenshots for `01-Find-S-Algorithm` to match the others. ✅
2. Add small code snippets to READMEs where missing (Elbow method for K‑Means, CV snippet for K‑NN).  
3. Add a CONTRIBUTING section and a short script to regenerate screenshots automatically (notebooks → images).

---

## Contribution / Editing workflow ✍️
- Update notebook → run cells → export key plots to `screenshot/` → update README with embedded images.
- Prefer PNG/JPEG for screenshots and keep filenames short (used in current READMEs).

---

## Contact / Credits
- Created as course lab experiments — feel free to fork and adapt for study.

---

*"In God we trust. All others must bring data." — W. Edwards Deming*