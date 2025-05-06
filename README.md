# 💉 Liraglutide_QSP_Omics_Model

This project presents an **integrated quantitative systems pharmacology (QSP) model** to compare **native GLP-1 vs. palmitoylated GLP-1 (Liraglutide)**. It evaluates insulin and glucose dynamics using **SimBiology**, combines this with **RNA-seq expression data** (GSE163744), and visualizes structural impact via **PyMOL** modeling.

---

## 🧪 Objective

- Simulate insulin and glucose AUC in response to native vs. palmitoylated GLP-1.
- Analyze **DPP4 degradation resistance** and impact on insulin signaling.
- Integrate RNA-seq (GEO dataset) to evaluate gene regulation feedback.
- Model structural interaction with DPP4 via PyMOL-modified GLP-1 analogs.

---

## 🧰 Tools & Data Sources

| Component | Tool / Dataset |
|----------|-----------------|
| PK/PD Model | SimBiology (MATLAB) |
| Transcriptomics | GEO GSE163744 |
| Omics Analysis | R (`ggplot2`, `data.table`) |
| Structure Modeling | PyMOL |
| Target Genes | DPP4, GLP1R, INS, IRS1, PCSK1 |

---

## 📁 Project Structure


---

## 📊 Key Insights

| Feature | Native GLP-1 | Palmitoylated GLP-1 |
|--------|---------------|----------------------|
| DPP4 Degradation | Rapid | Sterically Hindered |
| GLP-1 AUC | 3.53 | 21.79 |
| Insulin/GLP1 AUC Ratio | 10.1 | 1.69 |
| Transcriptomic INS Expression | Baseline | -0.47 log₂FC |
| Structural Interaction | Exposed | Blocked at Lys26 |

- Palmitoylation prolongs GLP-1 presence but results in **feedback suppression** of insulin-related genes.
- Structural modeling confirms **DPP4 resistance** due to steric hindrance at Lys26.

---

## 📚 References

- GEO Dataset: [GSE163744](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE163744)
- PyMOL: GLP-1 PDB structures modified manually
- Clinical rationale based on liraglutide pharmacology

---

## 👨‍💻 Author

**Dr. Binil Benny**  
QSP | Translational Systems Biology | Omics Modeling  
GitHub: [@binilbenny1696](https://github.com/binilbenny1696)

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).
