# Machine Unlearning with Data Augmentation

## 📄 Paper  
**Audio Augmentation Meets Audio Unlearning: Help or Hinder?**  
*Moulik Gupta, Achyut Mani Tripathi, 2025 (Under Review at ICASSP 2026)*  

[![Paper](https://img.shields.io/badge/Paper-PDF-red)](Machine_Unlearning_Using_Data_Augmentation.pdf) [![Conference](https://img.shields.io/badge/ICASSP-2026-grey)]()


This repository contains **extended results tables** from the paper:  
**_Audio Augmentation Meets Audio Unlearning: Help or Hinder?_**

Due to ICASSP page constraints, the full experimental results (large tables with detailed metrics) could not be included in the main paper. This repo serves as a companion resource where the complete tables are made available in a clean, citable format.

---

## 📊 Tables

Each table reports detailed evaluation metrics for machine unlearning experiments across different **audio classification datasets**.  
The metrics include average accuracy, forgetting gap, membership inference attack (MIA) resistance, and more.

---

### 🎵 Table 1: ESC-10

Results on the **ESC-10 dataset** (environmental sound classification).  
Click to view the full PDF with all metrics.

[![ESC-10 Results](assets/esc10.png?raw=true)](esc10.pdf)

---

### 🗣️ Table 2: SpeechCommands

Results on the **Google SpeechCommands dataset** (keyword spotting).  
Click to view the full PDF with all metrics.

[![SpeechCommands Results](assets/speechcommands.png?raw=true)](speechcommands.pdf)

---

### 🌆 Table 3: UrbanSound8K

Results on the **UrbanSound8K dataset** (urban audio classification).  
Click to view the full PDF with all metrics.

[![UrbanSound8K Results](assets/urbansound8k.png?raw=true)](urbansound8k.pdf)

---

## 📊 Results Summary

The following table highlights the **best and worst augmentations** for each unlearning method across datasets, evaluated on **Membership Inference Attack (MIA)**, **Average Gap (AGP)**, and **Unlearning Accuracy (UNA)**.

[![Summary Results](assets/summary.png?raw=true)](summary.pdf)

---

## 🔍 Why This Repo?

Machine unlearning is the process of selectively removing the influence of specific data points (or subsets) from a trained model, **without retraining from scratch**.

In this project, we study how **audio data augmentations**—which are common in training pipelines—interact with unlearning algorithms.

- Do augmentations **help models forget faster**?
- Or do they **leave residual traces**, making forgetting harder?

This repo hosts the **supplementary tables** that provide detailed insights into these questions.

---

## 📦 What’s Next?

The full experimental **codebase** (training, unlearning routines, and augmentation setups) will be made available here in due time. Stay tuned.

---
