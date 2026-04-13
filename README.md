# Qiskit Security Lab

Introductory Qiskit projects demonstrating quantum computing concepts relevant to future security and cryptography.

## Overview

This repository contains simple quantum computing demos built with Qiskit.

It covers:

- quantum randomness
- superposition
- entanglement
- probabilistic measurement outcomes

These examples are intended as a beginner portfolio project and a practical first step toward understanding concepts related to future cryptography and quantum security.

## Files

### `random_generator.py`
Creates a 1-qubit quantum circuit, applies a Hadamard gate to place the qubit in superposition, and measures the result to generate random outcomes.

### `bell_state_demo.py`
Creates a 2-qubit Bell state to demonstrate entanglement and saves a histogram of measurement results.

## Installation

Create and activate a virtual environment, then install dependencies:

```bash
python3 -m venv qiskit-env
source qiskit-env/bin/activate
pip install -r requirements.tx
