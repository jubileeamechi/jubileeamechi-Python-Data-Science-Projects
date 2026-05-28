# Differential Gene Expression Analysis in Cancer Research


## 📖 Project Overview
In modern precision oncology, understanding the molecular drivers of disease is critical for targeted therapy. This project implements a robust bioinformatics pipeline written in Python to analyze high-throughput transcriptomic data (the classic **Golub Leukemia Dataset**). 

By transitioning traditional wet-lab biochemistry principles into a scalable data science workflow, this project processes thousands of gene expression profiles to isolate statistically significant biomarkers that distinguish Acute Lymphoblastic Leukemia (ALL) from Acute Myeloid Leukemia (AML).

## 🎯 Project Objectives & Aim
The overarching **aim** of this project is to leverage computational biology to uncover distinct genetic signatures that can aid in accurate cancer classification and diagnostic precision.

## 📊 Dataset Overview
The project utilizes the **Golub et al. (1999) Leukemia Dataset**.
* **Data Matrix:** Consists of expression levels of **7,129 genes** across **72 samples**.
* **Phenotypes:** Samples are derived from patients diagnosed with either **ALL** or **AML**.

## 💻 Pipeline Architecture
1. **Data Cleaning & Normalization:** Handled missing data via median imputation and applied $log_2$ transformations to stabilize variance.
2. **Variance Filtering:** Eliminated low-variance, uninformative genes by filtering for the top 10% most variable features.
3. **Statistical Testing:** Conducted independent two-sample $t$-tests to evaluate differential expression across phenotypes.
4. **Visual Analysis:** Constructed hierarchical clustered heatmaps using `Seaborn` to group similar genetic expressions.

## 📊 Core Visualization
![Gene Expression Heatmap](plots/gene_expression_heatmap.png)

## 💡 Future Extensions
* Implementation of Multiple Testing Correction (Benjamini-Hochberg FDR).
* Dimensionality reduction using PCA (Principal Component Analysis).
