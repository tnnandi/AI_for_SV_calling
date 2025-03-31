# AI_for_SV_calling
Repository for  AI-based tools developed for structural variant (SV) calling in human genomes. Tools are grouped by their primary function.

# AI for Structural Variant Calling in Humans

This repository curates AI-based tools developed for structural variant (SV) calling in human genomes. Tools are grouped by their primary function:

- **Simple SV Callers** – Designed to detect individual SV types (e.g., deletions, insertions).
- **Complex SV Callers** – Capable of identifying and reconstructing compound or multi-breakpoint SVs.
- **Post-calling Filters** – Improve precision of SV calls from existing tools.

---

## 🧬 AI-based Callers for **Simple SVs**

| Caller / Tool Name | Scope | AI Method | Publication / GitHub Link |
|--------------------|--------|-----------|----------------------------|
| DeepSV | Deletions (≥50 bp) | CNN on alignment images | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2923-z) / No official repo |
| SVcnn | Deletions, Insertions | Deep CNN (long-read alignments) | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05256-3) / [GitHub](https://github.com/nwpuzhengyan/SVcnn) |
| Cue | All major SV types | Stacked Hourglass CNN | [Paper](https://www.nature.com/articles/s41592-023-02025-2) / [GitHub](https://github.com/PopicLab/cue) |
| cnnLSV | DEL, INS, INV, DUP | CNN + PCA-based filtering | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05241-w) / [GitHub](https://github.com/mhuidong/cnnLSV) |
| NPSV-deep | SV Genotyping | Image similarity + CNN | [Paper](https://academic.oup.com/bioinformatics/article/40/1/btae029/7512217) / [GitHub](https://github.com/mlinderm/npsv2) |

---

## 🔁 AI-based Callers for **Complex SVs**

| Caller / Tool Name | Scope | AI Method | Publication / GitHub Link |
|--------------------|--------|-----------|----------------------------|
| SVision | Complex SVs (multi-breakpoint) | CNN with multi-object recognition | [Paper](https://www.nature.com/articles/s41592-022-01619-1) / [GitHub](https://github.com/xjtu-omics/SVision) |
| ARC-SV | Complex SVs from short reads | Probabilistic ML + SV graph modeling | [Paper](https://www.cell.com/cell/fulltext/S0092-8674(24)00174-0) / [GitHub](https://github.com/jgarthur/arcsv) |

---

## 🧹 AI-based **Post-calling Filtering & Refinement** Tools

| Tool Name | Scope | AI Method | Publication / GitHub Link |
|-----------|--------|-----------|----------------------------|
| DeepSVFilter | Short-read SV filtering | Inception-ResNet CNN | [Paper](https://academic.oup.com/bib/article/22/6/bbab248/6334653) / [GitHub](https://github.com/yongzhuang/DeepSVFilter) |
| CSV-Filter | Illumina & long-read SVs | Self-supervised CNN + CIGAR image encoding | [Paper](https://academic.oup.com/bioinformatics/article/40/2/btaa032/7414467) / [GitHub](https://github.com/xzyschumacher/CSV-Filter) |
| sv-channels | Deletions (short-read) | 1D-CNN on signal channels | [Preprint](https://www.biorxiv.org/content/10.1101/2024.02.20.581323v1) / [GitHub](https://github.com/GooglingTheCancerGenome/sv-channels) |

---

## 📌 How to Contribute

Want to add a new tool or update an entry? Open a pull request or create an issue. This repository will be updated regularly to track the latest developments in AI-based SV calling.

---

## 📖 License

This repository is publicly available under the MIT License.

