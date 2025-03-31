# Voice Recon Tasks

## Overview
This repository contains implementations of three computational tasks:

1. **Monte Carlo Simulation for Rain Probability** – Estimates the probability of more than `n` rainy days in a year.
2. **Phoneme Sequence to Word Combinations** – Finds word matches for a given phoneme sequence using a pronunciation dictionary.
3. **Connectionist Temporal Classification (CTC) Implementation** – Computes CTC loss and gradients for sequence alignment.

## Installation
Ensure Python is installed, then install dependencies:
```sh
pip install -r requirements.txt
```

## Usage
Run each task as follows:

- **Monte Carlo Rain Simulation:**
  ```sh
  python monte_carlo_rain.py --days 365 --rain_prob 0.3 --threshold 100
  ```

- **Phoneme to Word Matching:**
  ```sh
  python phoneme_to_words.py --sequence "T AH N"
  ```

- **CTC Loss Calculation:**
  ```sh
  python ctc_loss.py
  ```

## Structure
```
voice-recon-tasks/
│── src/                    # Source code
│   ├── monte_carlo_rain.py  # Monte Carlo simulation
│   ├── phoneme_to_words.py  # Phoneme matching
│   ├── ctc_loss.py          # CTC computation
│── requirements.txt         # Dependencies
│── README.md                # Documentation
```

## License
This project is licensed under the MIT License.

