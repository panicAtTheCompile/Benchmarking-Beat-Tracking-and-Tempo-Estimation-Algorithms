# 🎵 Music Information Retrieval Benchmarking Study
Associated with Research Internship at the University of Victoria under the guidance of Prof.Geroge Tzanetakis

## Overview

This repository presents a comparative benchmarking study of popular Music Information Retrieval (MIR) frameworks for beat tracking and tempo estimation tasks.

The project evaluates algorithmic performance across two widely used benchmark datasets:

* GTZAN Genre Collection
* GiantSteps Tempo Dataset

Using standardized evaluation metrics and statistical analysis, the study investigates the strengths, limitations, and dataset-dependent behavior of MIR algorithms under diverse musical conditions.

---

## Research Objectives

* Evaluate beat tracking performance across multiple datasets.
* Compare tempo estimation accuracy using established MIR frameworks.
* Analyze model behavior across different musical genres and styles.
* Perform statistical evaluation using standard MIR metrics.
* Assess the generalizability of algorithm performance across datasets.

---

## Datasets

### 1. GTZAN Genre Collection

A benchmark dataset containing audio recordings from ten music genres.

Genres include:

* Blues
* Classical
* Country
* Disco
* Hip-Hop
* Jazz
* Metal
* Pop
* Reggae
* Rock

Used for:

* Beat tracking evaluation
* Tempo estimation benchmarking
* Genre-wise analysis

---

### 2. GiantSteps Dataset

A large-scale electronic dance music dataset with high-quality tempo annotations.

Used for:

* Tempo estimation benchmarking
* Cross-dataset generalization analysis
* Performance validation on modern electronic music

---

## Methodology

### Literature Review

Existing research in Music Information Retrieval was reviewed to identify widely adopted beat tracking and tempo estimation approaches.

### Benchmarking

Algorithms were evaluated under identical experimental conditions and compared using standard MIR metrics.

### Statistical Evaluation

Results were aggregated and analyzed using descriptive statistics and visualization techniques.

### Comparative Analysis

Performance was analyzed:

* Across datasets
* Across genres
* Across evaluation metrics
* Across algorithm implementations

---

## Evaluation Metrics

The following metrics are used throughout the study:

| Metric           | Purpose                      |
| ---------------- | ---------------------------- |
| F-measure        | Beat tracking accuracy       |
| Cemgil Score     | Temporal precision           |
| P-score          | Beat sequence consistency    |
| Information Gain | Beat prediction quality      |
| Tempo Accuracy   | Tempo estimation performance |

---

## Repository Structure

```text
.
├── notebooks/
│   ├── GTZAN_Benchmark.ipynb
│   └── GiantSteps_Benchmark.ipynb
│
├── figures/
│   ├── gtzan/
│   └── giantsteps/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* librosa
* madmom
* mir_eval

---

## Key Contributions

* Comparative benchmarking across multiple MIR datasets.
* Reproducible evaluation pipeline.
* Statistical analysis of beat tracking and tempo estimation performance.
* Cross-dataset assessment of algorithm robustness.
* Research-oriented workflow suitable for future MIR studies.

---

## Future Work

* Downbeat tracking evaluation.
* Additional MIR datasets.
* Deep learning-based beat tracking models.
* Real-time tempo estimation systems.
* Cross-cultural music benchmarking.

---

## References

* GTZAN Genre Collection
* GiantSteps Dataset
* librosa Documentation
* madmom Documentation
* mir_eval Evaluation Framework

---

## Author

Harshita Pulavarti

Research project exploring benchmarking methodologies for Music Information Retrieval systems, with a focus on beat tracking and tempo estimation.
