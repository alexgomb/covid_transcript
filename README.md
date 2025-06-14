# Comparative Peripheral Blood Transcriptomics

This repository compares peripheral blood transcriptomic signatures between COVID-19, bacterial pneumonia, and healthy controls using public RNA-seq data (GEO GSE161731).

## Data Source

* **GEO Series**: GSE161731

## Prerequisites

* R (≥ 4.1)
* Bioconductor packages: `GEOquery`, `SummarizedExperiment`, `edgeR`, `limma`, `clusterProfiler`, `org.Hs.eg.db`, `GenomicRanges`, `EnsDb.Hsapiens.v86`

## Installation

Clone the repository:

```bash
git clone https://github.com/alexgomb/covid_transcript.git
```

## Biological Insights

* Cohort identity (COVID-19, bacterial pneumonia, healthy) is the primary determinant of peripheral-blood transcriptomic variation.
* Bacterial pneumonia samples exhibit robust activation of pro-inflammatory and coagulation/fibrinolysis pathways.
* COVID-19 samples display heterogeneous type I interferon and immunoglobulin signatures alongside a novel mitotic activation program (e.g., spindle assembly, nuclear division).
* GO-BP enrichment and REVIGO highlight three functional axes: mitosis, immune cytotoxicity, and tissue remodelling.

## License

This project is licensed under the MIT License.

## Contact

For questions or feedback, open an issue or email \[[your.email@example.com](mailto:your.email@example.com)].
