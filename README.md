# 🌟 Genomic Computation Final Project 🌟

Welcome to my **Genomic Computation Final Project** repository! This project leverages computational techniques to analyze genomic data from eukaryotic cells. The program calculates open reading frames (ORFs) from FASTA files, outputs genomic data, sequences, statistics, and includes a Hidden Markov Model (HMM) with an interactive GUI built using `ipywidgets`.

## 🧬 Introduction 🧬 

Genomic computation combines biology and computational methods to provide deep insights into genomic data. This project aims to:

- Calculate open reading frames (ORFs) from eukaryotic cell genomic data.
- Output comprehensive genomic data, sequences, and statistics.
- Utilize a Hidden Markov Model (HMM) for detailed DNA sequence analysis.
- Provide an intuitive GUI with `ipywidgets` for user interaction.

## ✨ Features

- **Open Reading Frame Calculation**: Identify and extract ORFs from eukaryotic cell genomic data.
- **Hidden Markov Model (HMM)**: Advanced DNA sequence analysis using HMM.
- **Interactive GUI**: User-friendly interface powered by `ipywidgets`.
- **Detailed Reports**: Generate and view genomic data, sequences, and statistical analysis.

## 🎉 Example

1. **Upload a FASTA file**:
   - Click on the "Upload" button in the GUI and select your FASTA file.

2. **Calculate ORFs**:
   - Click on the "Calculate ORFs" button to process the uploaded file.

3. **Analyze with HMM**:
   - Click on the "Run HMM Analysis" button to analyze the sequences.

4. **View Results**:
   - Results, including genomic data, sequences, and statistics, will be displayed in the GUI.

## 🗂️ Project Structure

```plaintext
genom-comp-fp/
│
├── data/                   # Sample data files
├── src/                    # Source code
│   ├── orf_calculation.py  # ORF calculation module
│   ├── hmm_analysis.py     # HMM analysis module
│   ├── gui.py              # GUI module using ipywidgets
│   └── main.py             # Main script
├── tests/                  # Test files
├── README.md               # This README file
├── requirements.txt        # Python dependencies

```
