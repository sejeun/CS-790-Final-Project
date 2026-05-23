Comp Sci 790 Final Project: Python-Embedded DSL for Optimized Biosignal Preprocessing Pipelines

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Author:
Devin SaJeun DuCharme

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Description:
This project implements a lightweight Python-embedded domain-specific
language (DSL) for biosignal preprocessing workflows.

The system represents preprocessing operations as nodes within a
directed acyclic graph (DAG) and applies common subexpression
elimination (CSE) to reuse shared preprocessing computations across
multiple feature extraction branches.

The project compares:
- Naive NumPy preprocessing
- DSL without optimization
- DSL with CSE optimization

Synthetic EMG-like signals are used to evaluate runtime performance,
memory usage, traversal reduction, and correctness.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Main Features:
- Python-embedded preprocessing DSL
- DAG-based preprocessing representation
- Shared preprocessing reuse through CSE
- Bandpass filtering
- Sliding window generation
- RMS feature extraction
- FFT-based feature extraction
- Mean absolute value feature extraction
- Runtime and traversal benchmarking
- Single-channel and multi-channel signal evaluation

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Requirements:
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- SciPy

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
IMPORTANT
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This project uses synthetic EMG-like signal generation and does
NOT require external datasets or online data sources.

The program will automatically generate benchmark signals during
execution.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To Run:

1. Open terminal
2. Install required libraries if necessary
3. Run the program

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Program Behavior:
- Executes preprocessing benchmark experiments
- Displays runtime and traversal comparison graphs
- Compares:
    • Naive NumPy
    • DSL no optimization
    • DSL + CSE
- Verifies numerical correctness across implementations

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
