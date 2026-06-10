# WiC Ablation Study

This repository contains the final code and research paper for my ablation study on the Word‑in‑Context (WiC) task, which investigates how different input representations affect performance. The notebook implements the entire training pipeline, including ablation runs with multiple Transformer backbones, and the paper presents results and analysis.

## Files

- `wic_holm_perseed.ipynb` – Jupyter notebook implementing the pipeline, ablation runs, and submission generation. It's designed to be resumable; it saves intermediate results to Google Drive, allowing runs to resume after interruptions.
- `paper_wic_en_anon.pdf` – Anonymous research paper detailing the ablation study, including methodology, metrics, and results.

## Project Overview

The WiC task requires determining whether a target word has the same meaning in two sentences. This ablation study explores the impact of explicit span highlighting and lexical prefix encoding on model performance, using DeBERTa‑large and RoBERTa‑large as base models, and evaluates results with cross‑validation and statistical tests (McNemar, Holm–Bonferroni).

Feel free to explore the notebook and read the paper for details. Feedback is welcome!
