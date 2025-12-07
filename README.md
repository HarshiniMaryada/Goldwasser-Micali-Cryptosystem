# Goldwasser–Micali Cryptosystem (GM)

This project contains a simple implementation and study of the **Goldwasser–Micali (GM)** cryptosystem and its **Generalized GM** variant.
GM is one of the first probabilistic public-key encryption schemes and works using quadratic residues modulo a composite number.

## Files
- **generalized_gm_code.ipynb** - Jupyter Notebook with the full code  
- **BTP_report.pdf** - Main project report  
- **BTP_presentation.pptx** - Summary presentation  
- **requirements.txt** - Python package list.

## How to Run the Code

### 1.Google Colab(Recommended)
- Simply upload `generalized_gm_code.ipynb` to **Google Colab**
- Run all cells directly in the browser  
- No installations needed

### 2.Local System
1. Install Python 3  
2. Install Jupyter Notebook  
3. Install required packages:
   ```bash
   pip install sympy gmpy2 numpy matplotlib
4. Run the notebook:
   jupyter notebook generalized_gm_code.ipynb

## What This Project Covers

- Basics of the Goldwasser–Micali encryption scheme
- Quadratic residues & non-residues
- Bit-wise probabilistic encryption
- Generalized GM for multi-bit encryption
- Small experiments and observations

## Purpose

This project explores GM encryption, implements the generalized version, and studies ciphertext expansion and behavior.

## Authors

- Harshini Maryada
- Devyani Remulkar

