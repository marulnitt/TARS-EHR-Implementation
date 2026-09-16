# TARS-EHR-Implementation
Proof-of-concept implementation accompanying the paper *"TARS-EHR: [full paper title]"*.

## Contents
- `tars_ehr.ipynb` — full implementation and benchmarking notebook (Google Colab / Jupyter compatible)
- `figures/` — performance charts included in the paper

## Components implemented
- Patient Ring signature (Stage I, anonymous submission)
- SKE/PKE encryption (AES-256-GCM + ECIES over secp256k1)
- Doctor Ring sequential threshold signing (Stage II, collaborative diagnosis)
- Shamir-based threshold identity recovery (Stage III, accountability)
- Simulated append-only ledger

## Requirements

## Running
Open `tars_ehr.ipynb` in Jupyter or Google Colab and run cells top to bottom.

## Note
This is a research prototype in Python for correctness validation and relative
performance trends, not an optimized production implementation. See the paper's
Implementation and Performance Evaluation section for details and caveats.
