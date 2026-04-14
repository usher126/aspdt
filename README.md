# ASP-DT
ASP-DT, a declarative decision tree induction framework that encodes the entire learning problem—including tree structure, split selection, sample routing, leaf labeling, and optimization—within Answer Set Programming (ASP)

# Minimal Reproducible Package

This repository provides a minimal reproducible implementation of the ASP-DT framework described in the paper.

## Contents
- ASP encoding for decision tree induction
- Python preprocessing and tree extraction scripts
- A representative benchmark dataset
- A runnable end-to-end demo

## Requirements
- Python 3.10+
- clingo 5.6.2 or later

## Installation
pip install -r requirements.txt

## Run
python src/run_demo.py

## Output
The script will:
1. preprocess the dataset,
2. generate ASP facts,
3. call clingo,
4. extract the learned tree,
5. report accuracy and tree structure.

## Reproducibility note
This package is intended to reproduce the core experimental workflow and a representative result from the paper, rather than the full experimental batch pipeline.
