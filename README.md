# AI_for_SV_calling
Repository for  AI-based tools developed for structural variant (SV) calling in human genomes. Tools are grouped by their primary function.

# AI for Structural Variant Calling in Humans

This repository curates AI-based tools developed for structural variant (SV) calling in human genomes. Tools are grouped by their primary function:

- **Simple SV Callers** – Designed to detect individual SV types (e.g., deletions, insertions).
- **Complex SV Callers** – Capable of identifying and reconstructing compound or multi-breakpoint SVs.


---

## AI-based Callers for **Simple SVs**

| Caller / Tool Name | Scope | AI Method | Publication / GitHub Link |
|--------------------|--------|-----------|----------------------------|
| DeepSV | DEL from short reads | CNN on pileup images | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3299-y) / [GitHub](https://github.com/CSuperlei/DeepSV) |
| SVcnn | DEL from long reads | Time-distributed CNN + Bidirectional LSTM | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05324-x) / [GitHub](https://github.com/nwpuzhengyan/SVcnn) |
| cnnLSV | DEL, INS, INV, DUP | CNN + PCA-based filtering | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05243-x) / [GitHub](https://github.com/mhuidong/cnnLSV) |
|Breaknet|Deletions using long-read data|Time-distributed CNN, Bidirectional LSTM|[Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04499-5) / [GitHub](https://github.com/luojunwei/BreakNet) |
|MAMnet|DEl, INS from long reads|Time-distributed CNN + LSTM|[Paper](https://academic.oup.com/bib/article/23/5/bbac195/6587170) / [GitHub](https://github.com/micahvista/MAMnet)|

---

## AI-based Callers for **Complex SVs**

| Caller / Tool Name | Scope | AI Method | Publication / GitHub Link |
|--------------------|--------|-----------|----------------------------|
| SVision | Complex SVs (multi-breakpoint) | CNN with multi-object recognition | [Paper](https://www.nature.com/articles/s41592-022-01609-w) / [GitHub](https://github.com/xjtu-omics/SVision) |
| ARC-SV | Complex SVs from short reads | Probabilistic ML + SV graph modeling | [Paper](https://www.cell.com/cell/fulltext/S0092-8674(24)00174-0) / [GitHub](https://github.com/jgarthur/arcsv) |
| Cue | DEL, INS, INVDUP from short reads | Stacked Hourglass CNN | [Paper](https://www.nature.com/articles/s41592-023-01799-x) / [GitHub](https://github.com/PopicLab/cue) |
---
<!--
## AI-based **Post-calling Filtering & Refinement** Tools

| Tool Name | Scope | AI Method | Publication / GitHub Link |
|-----------|--------|-----------|----------------------------|
| DeepSVFilter | Short-read SV filtering | Inception-ResNet CNN | [Paper](https://academic.oup.com/bib/article/22/6/bbab248/6334653) / [GitHub](https://github.com/yongzhuang/DeepSVFilter) |
| CSV-Filter | Illumina & long-read SVs | Self-supervised CNN + CIGAR image encoding | [Paper](https://academic.oup.com/bioinformatics/article/40/2/btaa032/7414467) / [GitHub](https://github.com/xzyschumacher/CSV-Filter) |
| sv-channels | Deletions (short-read) | 1D-CNN on signal channels | [Preprint](https://www.biorxiv.org/content/10.1101/2024.02.20.581323v1) / [GitHub](https://github.com/GooglingTheCancerGenome/sv-channels) |

---
-->

## 📌 How to Contribute

Want to add a new tool or update an entry? Open a pull request or create an issue. This repository will be updated regularly to track the latest developments in AI-based SV calling.

---

## 📖 License

This repository is publicly available under the MIT License.

