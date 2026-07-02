clinical-summary-hallucination-benchmark
Evaluation dataset and methodology for measuring hallucination, omission, and meaning drift in AI generated clinical discharge summaries. 
 Clinical AI Safety Evaluation

 Overview

This project evaluates whether AI-generated clinical discharge summaries preserve medical accuracy and avoid unsafe transformations.

Research Question

Do language models introduce clinically meaningful errors when converting medical records into patient-facing summaries?

Evaluation Categories

- Omission
- Hallucination
- Meaning Drift
- Critical Safety Failure

Preliminary Findings

The pilot evaluation identified recurring failure modes including:

- Historical medications incorrectly converted into active discharge medications
- Treatment responses incorrectly converted into patient instructions
- Missing clinical uncertainty replaced with confident recommendations

Dataset

The repository contains anonymized evaluation examples, scoring criteria, and analysis artifacts.

Goal

Develop a reproducible benchmark for evaluating clinical AI safety.
