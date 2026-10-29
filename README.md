# Iraaj Gangavaram

**Bioinformatics and computational biology** · Microbiology undergraduate, University of East Anglia

I use computational methods to answer biological questions about gene expression, genomic variation, horizontal gene transfer and bioactivity. I build analysis pipelines and models in Python, R and Bash, and test them on public datasets.

---

## Projects

| # | Project | Area | What it does | Technologies |
|:-:|---|---|---|---|
| 1 | [**Count-DE Benchmark**](https://github.com/iraajgangavaram/count-de-benchmark) | Transcriptomics, statistics | Implements median-of-ratios normalisation, limma-style empirical Bayes variance moderation, Welch t and Mann-Whitney tests with Benjamini-Hochberg correction. Benchmarks them on negative-binomial simulations (power, observed FDR, AUC, null calibration across replicate numbers) and re-analyses a public GEO dataset. | Python, NumPy, SciPy, pandas, Matplotlib, GitHub Actions |
| 2 | [**VCF QC Toolkit**](https://github.com/iraajgangavaram/vcf-qc-toolkit) | Population genomics, variant QC | Quality control for variant call sets: Ti/Tv, exact Hardy-Weinberg test, allele-frequency spectra, missingness and robust per-sample outlier detection. Validated on simulated cohorts with planted artefacts and problem samples. | Python (standard library), Matplotlib, VCF, GitHub Actions |
| 3 | [**ORF Codon Toolkit**](https://github.com/iraajgangavaram/orf-codon-toolkit) | Prokaryotic genomics | ORF finding on both strands, codon usage (RSCU) and GC skew. Checked against an analytic null model, planted genes and a planted skew switch. | Python (standard library), Matplotlib, GitHub Actions |
| 4 | [**Predict-HGT**](https://github.com/iraajgangavaram/Predict-HGT) | Comparative genomics, machine learning | Investigates potential horizontal gene transfer between bacterial species using genomic features, machine learning and network analysis. | Python, pandas, scikit-learn, NetworkX, Biopython |
| 5 | [**Transcriptomic Biomarker Analysis**](https://github.com/iraajgangavaram/transcriptomic-biomarker-analysis) | Transcriptomics, networks | Pipeline for public Alzheimer's disease brain RNA-seq data (GSE163877): differential expression, pathway enrichment and protein-interaction network analysis. Exploratory only, as the dataset has 7 samples. | Python, pandas, NumPy, SciPy, Matplotlib, gseapy, STRING, Streamlit |
| 6 | [**Exploratory Bioactivity Analysis**](https://github.com/iraajgangavaram/Exploratory-analysis-on-Bioactivity-Data) | Cheminformatics | Exploratory analysis of ChEMBL bioactivity data for acetylcholinesterase, following the Data Professor drug-discovery tutorial: IC50 curation, Lipinski descriptors and active vs inactive comparisons. | Python, pandas, NumPy, Matplotlib, Seaborn, RDKit, Jupyter |
| 7 | **Mutation Imbalance Analysis** (private, HPC research data) | Population genomics, HPC | Investigates mutation patterns around genetic variants in large population genomic datasets on high-performance computing infrastructure. | Linux, Bash, Python, SLURM, bcftools |


## Open-source contributions

| Project | Contribution | Status |
|---|---|---|
| [nf-core/modules](https://github.com/nf-core/modules) | New module for [CellTypist](https://www.celltypist.org) automated cell-type annotation of single-cell RNA-seq data, with nf-test tests ([branch](https://github.com/iraajgangavaram/modules/tree/add-celltypist-module)) | In progress |
| [nf-core/modules](https://github.com/nf-core/modules) | New module for [scDblFinder](https://github.com/plger/scDblFinder) doublet detection in single-cell RNA-seq data, with nf-test tests ([branch](https://github.com/iraajgangavaram/modules/tree/add-scdblfinder-module)) | Merged |
| [nf-core/test-datasets](https://github.com/nf-core/test-datasets) | Test data for the CellTypist module: a 300-cell PBMC query file and a CellTypist model trained on 600 cells ([pull request](https://github.com/nf-core/test-datasets/pull/2350)) | Merged |

---

## Skills and tools

| Area | Tools and methods |
|---|---|
| Languages | Python, Bash |
| Data analysis | pandas, NumPy, SciPy, scikit-learn, Matplotlib, Seaborn |
| Statistics | Differential expression, empirical Bayes variance moderation, multiple-testing correction (Benjamini-Hochberg), exact tests, simulation-based benchmarking |
| Genomics | Variant call (VCF) QC, bcftools, Biopython, ORF and codon analysis, GC skew |
| Networks and enrichment | NetworkX, STRING, gseapy |
| Cheminformatics | RDKit, ChEMBL |
| Infrastructure | Linux, SLURM, Nextflow and nf-test, Git and GitHub Actions, Jupyter, Streamlit |

---

## Research interests

Genomics · Population genomics · Transcriptomics · Machine learning in biology ·
Biological networks · Computational drug discovery · Biotechnology

## Current focus

Building reproducible computational biology projects on real biological
datasets, and benchmarking analysis methods against simulations where the true
answer is known.
