
**Luminal B Breast Cancer RNA-Seq Analysis**

## 📂 Project Overview
This project uses RNA-Seq data (PRJNA680808) to explore gene expression changes in drug-resistant vs sensitive breast cancer samples.

## 🛠 Tools Used
- Galaxy (Europe Server)
- FastQC
- Trimmomatic
- HISAT2 (aligner)
- samtoos flagstat
- samtools sort
- featureCounts
- DESeq2 (differential expression)

## 🧬 Pipeline Summary
1. Quality check using FastQC
2. Trimming with Trimmomatic
3. Alignment using HISAT2
4. Post-Alignment QC using Samtools flagstat
5. Sorting BAM Files using Samtools sort
6. Counting reads with featureCounts
7. DE analysis using DESeq2

## 🧾 Data
- **6 samples total**: 3 Resistant, 3 Sensitive
- Source: [SRA PRJNA680808](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA680808)

## 📈 Key Results
- PCA shows a clear separation of groups
- Significant DEGs identified (padj < 0.1)
- See `results/.gitkeep` for visualizations

## 🧠 Skills Demonstrated
- RNA-seq pipeline execution
- Data normalization, statistical testing
- Galaxy workflow automation
- Reproducible research practices

