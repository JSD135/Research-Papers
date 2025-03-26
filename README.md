Here's a polished **README.md** tailored to your project structure and research paper:

---

# **Autism Spectrum Disorder (ASD) Prediction in Adults**  
*A Machine Learning Framework for High-Accuracy Diagnosis*  

[![GitHub last commit](https://img.shields.io/github/last-commit/JSD135/Research-Papers)](https://github.com/JSD135/Research-Papers/commits/main)  
[![GitHub repo size](https://img.shields.io/github/repo-size/JSD135/Research-Papers)](https://github.com/JSD135/Research-Papers)  

---

## 📜 **Overview**  
This repository contains the complete research materials for the paper:  
**"Prediction of Autism Spectrum Disorder in Adults Using Feature-Specific Machine Learning Models"**  

**Key Contributions**:  
✅ **100% accuracy** with Random Forest/XGBoost ensembles  
✅ Comparative analysis of 26 ML models (CNNs, lazy classifiers)  
✅ Rigorous preprocessing (SMOTE, feature engineering)  
✅ Clinical-grade evaluation protocol  

---

## 🌐 **Project Structure**  
```bash
.
├── Media/                  # Research figures & visualizations
│   ├── ASD_Prevalence.png  # Demographic trends
│   ├── CNN.png             # CNN performance
│   └── XGB.png             # XGBoost results
│
├── src/                    # LaTeX manuscript source
│   ├── main.tex            # Main document
│   └── Bibliography/       # References (BibTeX)
│
├── Utilities/              # Supplementary files
│   └── Flow/chart.tex      # Methodology flowchart
│
├── docs/                   # Documentation
│   └── README.md           # You are here
│
└── resources/              # LaTeX templates & configs
    ├── jmlr2e.sty          # Journal style
    └── requirements.tex    # LaTeX dependencies
```

*(Run `tree -L 3 --dirsfirst` to regenerate this tree locally.)*  

---

## 🚀 **Quick Start**  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/JSD135/Research-Papers.git
   cd Research-Papers
   ```

2. **Compile the LaTeX manuscript** (requires TeX distribution):  
   ```bash
   pdflatex src/main.tex
   bibtex src/main.aux
   pdflatex src/main.tex  # Run twice for references
   ```

3. **Explore results**:  
   - View pre-generated figures in `Media/`  
   - See model metrics in the paper (`main.pdf`)

---

## 📊 **Key Results**  
| Model          | Accuracy | F1 Score | ROC AUC |  
|----------------|----------|----------|---------|  
| Random Forest  | 100%     | 1.0      | 1.0     |  
| XGBoost        | 100%     | 1.0      | 1.0     |  
| CNN            | 52.87%   | 0.5968   | 0.9665  |  

**Top Features**:  
- A1-A10 Screening Scores  
- Age at diagnosis  
- Jaundice history  

![ASD Prevalence by Age](Media/ASD_Prevalence.png)  

---

## 📑 **Citation**  
```bibtex
@article{mishra2024asd,
  title={Prediction of Autism Spectrum Disorder in Adults},
  author={Mishra, Khushi and Sharma, Jai},
  year={2024},
  url={https://github.com/JSD135/Research-Papers}
}
```

---

## 🤝 **Contribution Guidelines**  
1. **Report issues**: [New Issue](https://github.com/JSD135/Research-Papers/issues)  
2. **Suggest improvements**: Fork + Pull Request  
3. **Add datasets**: Place in `Media/` or `resources/` with clear naming  

---

## ❓ **FAQ**  
**Q**: How to regenerate figures?  
**A**: Run Python/Matplotlib scripts (to be added in `Utilities/`).  

**Q**: Where's the full paper PDF?  
**A**: Compile `src/main.tex` or check releases for pre-built PDF.  

---

*📌 Note: Add a LICENSE file later via GitHub UI if needed.*  

--- 

This README provides:  
- Clear navigation with emoji headers  
- Auto-generated badges for repo activity  
- Copy-paste commands for easy setup  
- Visual structure with ASCII tree  
- Mobile-responsive tables/images  
