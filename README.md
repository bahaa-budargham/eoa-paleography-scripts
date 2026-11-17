# Engineering of Alphabets (EOA): Computational Paleography Series

Deterministic sequence dynamics, algebraic invariants, and collapse profiles across five historical writing systems (**186 letters total**):
* **Caucasian Albanian** (52 letters)
* **Georgian Mkhedruli** (33 letters)
* **Classical Armenian** (38 letters)
* **Old South Arabian / Proto-Ge'ez** (29 letters)
* **Ethiopic Ge'ez** (26-letter classical core / 34-letter expanded base)

This research serves as a discrete dynamical sequence companion to computational neural paleography models (Zemene et al., 2026).

---

## Publications & Technical Notes

1. **Part I: Form and Function in Ancient Writing Systems (178-Letter Baseline)**
   * Focus: The 26-letter Ge'ez $\phi^2$ core, Caucasus bimodal split, and atomic OSA control.
   * Permanent Zenodo DOI: [10.5281/zenodo.24115627](https://doi.org/10.5281/zenodo.24115627)
   * File: `papers/EOA_Part_I_Ancient_Writing_Systems.pdf`

2. **Part II: Updated Sequence Census (186 Letters)**
   * Focus: Activating Old South Arabian epigraphic names ($\phi^2$), Ge'ez 34-character base ($1+\sqrt{2}$ Pell collapse), and Georgian 15-group partition.
   * Permanent Zenodo DOI: [10.5281/zenodo.24115627](https://doi.org/10.5281/zenodo.24309286)
   * File: `papers/EOA_Part_II_Updated_Census.pdf`

4. **Summary Report: Comparison Across Three Iterations**
   * Focus: Systematic sensitivity analysis (atomic vs. native syllabic vs. standardized Latin transliteration).
   * Permanent Zenodo DOI: [10.5281/zenodo.24115627](https://doi.org/10.5281/zenodo.24310519)
   * File: `papers/EOA_Ancient_Writing_Systems_Summary_Report.pdf`

---

## Summary of Findings

| Script | Letters ($N$) | Part I Baseline | Part II Syllabic | Transliterated Run | Primary Invariant / Growth ($\lambda$) |
| :--- | :---: | :---- | :--- | :--- | :--- |
| **Caucasian Albanian** | 52 | 49 groups | 49 groups | 49 groups | Invariant web ($\lambda \approx 2.956080$) |
| **Georgian (Mkhedruli)** | 33 | 11 groups | 15 groups | 15 groups | Unified cubic core ($\lambda \approx 2.521380$) |
| **Old South Arabian** | 29 | Flatline ($1, 1, 1$) | 26 groups | 26 groups | Epigraphic awakening ($\lambda = 1, 2, \approx \phi^2$) |
| **Classical Armenian** | 38 | 25 groups* + 2 | 24 groups* + 5 | 24 groups* + 5 | Bimodal ($\lambda = 1.000$ and $2.000$) |
| **Ge'ez (Classical Core)** | 26 | 16 groups ($\phi^2$) | — | — | Golden Ratio core ($\phi^2 \approx 2.618034$) |
| **Ge'ez (Expanded Base)** | 34 | — | 2 groups | 4 groups | Quadratic phase shift ($1 + \sqrt{2} \approx 2.414214$) |
| **Total** | **186** | **102 rows** | **116 rows** | **118 rows** | **69–89 OEIS-matched letters** |

---

## Data Availability & Staged Disclosure

* **Input Nomenclature:** All 186 symbols and exact input strings are documented in `data/5_scripts_letter_names.csv` (and Appendix A of Part II).
* **Extended Sequence Audits:** The full 500-term integer sequences, exact polynomial factorizations, and pairwise distance matrices (`EOA_Distance_Matrix_186.csv`) are managed under staged disclosure and provided upon academic request.

### Contact
Bahaa BuDargham  
Neurolabs R&D, Montréal, Canada  
Research Portal: [https://research.neurolabs.space](https://research.neurolabs.space)  
Email: `bdarghamneurolabs@gmail.com`
