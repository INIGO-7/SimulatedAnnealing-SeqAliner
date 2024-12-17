# 🧬 Simulated Annealing for Biological Sequence Alignment

This repository contains Python code to explore the application of the **Simulated Annealing (SA)** algorithm for **biological sequence alignment**. The aim of this project is to analyze how different **objective functions** affect the quality of alignments and the computational efficiency of SA-based methods. This work is inspired by the paper: [**SANA - Simulated Annealing Far Outperforms Many Other Search Algorithms for Biological Network Alignment**](https://academic.oup.com/bioinformatics/article/33/14/2156/2996219).

---

## 📌 **Project Overview**

In biological research, sequence alignment is fundamental for understanding evolutionary relationships, functional similarities, and structural conservation. While Simulated Annealing has shown remarkable performance in **network alignment**, its potential for **sequence alignment** remains underexplored.

This project aims to:

1. **Implement Simulated Annealing** for pairwise biological sequence alignment.
2. **Compare multiple objective functions** to measure their impact on alignment quality and runtime.
3. **Investigate whether insights from SA-based network alignment** can be extrapolated to sequence alignment.
4. **Benchmark different scoring and evaluation functions** to identify optimal strategies for improving SA performance.

---

## 🚀 **Features**

- **Flexible SA Implementation**: Customize key parameters (temperature schedules, perturbations, cooling rates) for Simulated Annealing.
- **Multiple Objective Functions**:
  - Classic scoring with substitution matrices (e.g., BLOSUM, PAM).
  - Gap penalties (fixed and affine).
  - Hybrid and dynamic scoring functions.
- **Alignment Quality Metrics**:
  - Alignment score
  - Percent identity and similarity
  - Gap proportion
  - Statistical significance (bit score, E-value)
- **Benchmarking Tools**: Compare SA results against reference alignments for accuracy and efficiency.

---

## 📊 **Motivation**

The SANA paper demonstrated the power of Simulated Annealing in aligning biological networks, outperforming other algorithms. This project seeks to understand:

1. Can the principles of SA for **network alignment** apply to **sequence alignment**?
2. How do different **objective functions** influence SA's performance in sequence alignment?
3. Can better-designed objective functions improve the efficiency and quality of SA alignments?

This study aims to highlight the importance of well-chosen evaluation functions and how they can significantly impact optimization performance.

---

## 🛠️ **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sa-sequence-alignment.git
   cd sa-sequence-alignment
