Intent Preservation Benchmark

Building open-source evaluation infrastructure that helps researchers determine when AI systems faithfully preserve human intent before deployment in high-stakes environments.

 Overview

As large language models become integrated into healthcare, government, finance, and other critical systems, evaluating reliability has become just as important as improving capability. While many existing benchmarks measure whether a model produces the correct answer, fewer evaluate whether it faithfully preserves the original intent behind human instructions.

This project explores a different question:

How do we know when an AI system has preserved what a human actually meant?

The Intent Preservation Benchmark is an open-source research initiative focused on developing practical methods for identifying where large language models introduce omissions, unsupported assumptions, hallucinations, or subtle changes in meaning during complex information transfer.

Healthcare serves as the initial validation domain because it provides clear, measurable examples of high-stakes communication where preserving human intent is essential. The long-term goal is to develop evaluation methods that can be adapted to other safety-critical domains.



Research Objective

The objective of this project is to develop an open-source benchmark and evaluation framework capable of measuring whether large language models faithfully preserve human intent when transforming complex information.

Rather than asking whether an AI response sounds reasonable, this project asks a different question:

Did the model preserve the meaning the human originally intended to communicate?


Current Project Status

Completed

Independent 20-case pilot using Gemini 1.5 Flash
Initial evaluation rubric
Documentation of recurring failure patterns
Interactive Figma prototype
Initial project architecture

In Progress

Intent Preservation Benchmark v0.1
Public GitHub documentation
Benchmark methodology
Open-source repository
Platform planning and execution strategy

Planned

Automated evaluation pipeline
Reliability scorecards
Expanded benchmark dataset
Public web platform
Open-source platform release


 
Repository Structure

README.md

benchmark/
── Benchmark_v0.1.md
── Evaluation_Rubric.md

methodology/
── Methodology.md

results/
── Benchmark_Results.xlsx
── Findings.md

prototype/
- Figma_Prototype.md

 docs/
  ─ Execution_Strategy.md
  ─ Project_Status.md


Initial Benchmark

The project currently includes Intent Preservation Benchmark v0.1, an initial benchmark consisting of twenty complex clinical discharge planning scenarios designed to evaluate how well large language models preserve clinician intent during complex information transformation.

The complete benchmark documentation, evaluation methodology, scoring framework, and benchmark structure are available within the **benchmark** directory.

 
Why This Matters

As AI systems become increasingly involved in real-world workflows, preserving human intent becomes a critical component of reliability. Small changes in meaning can accumulate into significant downstream failures, particularly in environments where information must be transferred accurately between people and systems.

By developing standardized methods for measuring intent preservation, this project aims to contribute practical evaluation infrastructure that researchers can use to identify alignment failures before deployment rather than after real-world harm occurs.


Roadmap

Phase 1 — Research Foundation

Initial pilot study
Evaluation rubric
Initial benchmark design
Platform prototype

Phase 2 — Benchmark Development

Intent Preservation Benchmark v0.1
Public documentation
GitHub repository
Benchmark refinement

Phase 3 — Platform MVP

Automated evaluation pipeline
Reliability score generation
Interactive research interface

Phase 4 — Open-Source Release

Public platform
Expanded benchmark
Community collaboration
Continuous benchmark development

Contributing

This project is currently under active development.

Technical feedback, research collaboration, benchmark improvements, and discussions surrounding AI evaluation, benchmark design, and intent preservation are welcome.

License

This repository is being developed as an open-source research initiative to encourage collaboration and continued advancement in AI safety evaluation.
