# ADNI MRI-Based Alzheimer's Disease Diagnosis Pipeline

## Overview

This repository contains a complete MRI-based Alzheimer's Disease diagnosis pipeline developed using the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset.

The project integrates MRI preprocessing, automated neuroanatomical segmentation using FastSurfer, volumetric feature extraction, clinical metadata processing, machine learning classification, and Alzheimer's disease prediction.

The pipeline is designed to support research in neuroimaging, early Alzheimer's detection, and MRI-based diagnostic modeling.

---

## Objectives

* Process structural MRI scans from the ADNI dataset.
* Perform automated brain segmentation using FastSurfer.
* Extract volumetric brain biomarkers.
* Integrate neuroimaging and clinical features.
* Train machine learning models for Alzheimer's disease classification.
* Support MCI conversion prediction and disease progression analysis.

---

## Dataset

This project utilizes data obtained from:

**Alzheimer's Disease Neuroimaging Initiative (ADNI)**

Website:
https://adni.loni.usc.edu

The dataset is not included in this repository due to ADNI data-sharing restrictions.

---

## Pipeline Workflow

### 1. MRI Data Acquisition

* ADNI T1-weighted MRI scans
* Subject metadata collection

### 2. MRI Segmentation

* FastSurfer-based brain segmentation
* Cortical and subcortical structure extraction

### 3. Feature Engineering

* Brain volumetric measurements
* Deep imaging features
* Clinical and demographic features

### 4. Data Processing

* Data cleaning
* Feature normalization
* Quality control procedures

### 5. Machine Learning Models

* XGBoost
* Hierarchical Classification Pipeline
* Binary CN vs AD Classification
* MCI Conversion Prediction Models

### 6. Evaluation

* Model performance analysis
* Classification metrics
* Disease progression assessment

---

## Repository Structure

```text
ADNI_Local/
│
├── ADNI_Pipeline.ipynb
├── outputs/
│   ├── fastsurfer_results/
│   └── processed_data/
├── FastSurfer/
└── README.md
```

---

## Generated Outputs

The repository contains:

* FastSurfer segmentation outputs
* Brain volumetric features
* Processed datasets
* Trained machine learning models
* Feature matrices
* Prediction outputs
* Pipeline session artifacts

---

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* FastSurfer
* Neuroimaging Processing Tools

---

## Installation

```bash
git clone https://github.com/abeerajaved1/adni-mri-diagnosis.git

cd adni-mri-diagnosis
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Launch the notebook:

```bash
jupyter notebook ADNI_Pipeline.ipynb
```

Execute the notebook sequentially to reproduce the complete workflow.

---

## Research Applications

* Alzheimer's Disease Classification
* Mild Cognitive Impairment (MCI) Analysis
* MRI Biomarker Discovery
* Neurodegenerative Disease Research
* Clinical Decision Support Research

---

## Disclaimer

This repository is intended for research and educational purposes only and is not designed for clinical diagnosis or medical decision-making.

---

## Author

**Abeera Javed**

LinkedIn:
https://www.linkedin.com/in/abeera-javed-2878b23b2/

GitHub:
https://github.com/abeerajaved1
