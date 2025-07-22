# 🧬 Zebrafish Variant Calling Training Project

This project explores a basic variant calling workflow using zebrafish whole genome sequencing data. It was built as a personal training project to better understand common genomics tools and steps involved in identifying genetic variants from raw sequencing reads.

> ⚠️ Due to bandwidth and file size constraints, output files (e.g. BAM/VCF) are **not included** in this repository. All code and pipeline steps are available in the GitHub Repository.

---

## 📚 Project Overview

The pipeline was implemented in a Jupyter Notebook and run primarily on [Galaxy](https://usegalaxy.org) and [Galaxy EU](https://usegalaxy.eu), combining both graphical workflows and command-line tools.

### 🛠️ Tools & Steps
- 📥 **Data download** from ENA (zebrafish)
- 🔬 **Quality check** with FastQC
- ✂️ **Read trimming** using Fastp
- 🎯 **Alignment** with Minimap2
- 🧹 **SAM/BAM processing** using SAMtools
- 🧬 **Variant calling** with FreeBayes
- 🧪 **VCF filtering** with vcffilter
- 🧠 **Annotation**: VEP on Galaxy EU
