# Master's Thesis Report

LaTeX source of the written report for the Master's thesis **Multimodal EHR-based Diagnosis Prediction via Knowledge Graph & Neuro-Symbolic Reasoning**, TU Dresden, submitted January 2026.

The code behind the thesis lives in [MasterThesis](https://github.com/Arjun-Sivasankar/MasterThesis).

## Layout

| Path | Contents |
|---|---|
| `0_frontmatter/` | Title page, abstract, declarations |
| `1_mainmatter/` | The chapters |
| `2_bib/` | Bibliography |
| `3_appendix/` | Appendix material |
| `fig/`, `Images/`, `logo/` | Figures and assets |
| `main.tex` | Root document |

## Building

```bash
latexmk -pdf main.tex
```

Or compile `main.tex` directly with any TeX distribution that has the required packages.

## Note on the build artefacts

The generated files (`main.aux`, `main.log`, `main.toc`, `main.synctex.gz` and friends) are committed alongside the source, because the repository doubles as a snapshot of exactly what was submitted. They are not needed to rebuild the document, and `main.pdf` is the compiled report.
