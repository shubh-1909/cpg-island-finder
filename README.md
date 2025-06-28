# 🧬 CpG Island Finder & GC/CpG Ratio Plotter

This project reads a **DNA FASTA sequence**, scans it in sliding windows, computes **GC content** and **CpG observed/expected ratio**, and identifies regions that qualify as **CpG islands**.

It also generates clean plots and outputs a table listing all detected CpG islands with their statistics.

---

## 🚀 Run on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubh-1909/cpg-island-finder/blob/main/notebooks/CpG_Island_Finder.ipynb)

---

## 🔬 Features

✅ Upload a DNA `.fasta` file (single sequence)  
✅ Computes:
- **GC content** in sliding windows
- **CpG observed/expected ratio**

✅ Identifies CpG islands meeting typical criteria:
- GC content > **50%**
- CpG ratio > **0.6**
- Length >= **200 bp**

✅ Outputs:
- 📊 Line plots of GC content & CpG ratio
- 📝 Table of detected islands with positions, GC %, CpG ratio
- 💾 Downloadable CSV report

---

## 🛠 Tools Used

- Python
- BioPython for sequence parsing
- Pandas for data analysis
- Matplotlib & Seaborn for visualization
- Google Colab for an installation-free, reproducible workflow

---

## 🧬 Example Data Included

Sample FASTA under `examples/`:
- `example_sequence.fasta` — a small DNA sequence to quickly test CpG island detection.

---

## 👨‍💻 Author

**Shubkarandeep Singh Judge**  
🎓 M.Sc. Biotechnology | 💻 Minor in Computer Science  
🌐 [GitHub: shubh-1909](https://github.com/shubh-1909)

---

## 📜 License

This project is licensed under the **MIT License** — freely available for research, education, and portfolio use.
