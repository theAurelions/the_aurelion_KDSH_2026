# THE_AURELION_KDSH_2026

This repository contains our Track A submission focused on classifying global narrative consistency in long-form texts. Using Pathway for long-context ingestion and retrieval, the system determines whether a hypothetical backstory is logically and causally consistent with a complete narrative, emphasizing robustness and reproducibility.

# Problem Overview

Large language models often perform well on local text understanding but struggle with global consistency and causal reasoning over long narratives.

This challenge focuses on evaluating whether a hypothetical backstory for a character is logically and causally consistent with an entire long-form narrative (100k+ words).
The task is framed as a binary classification problem:

1 (Consistent): The backstory can plausibly produce the observed future.

0 (Contradict): The backstory violates narrative constraints or causal logic.

## Solution Approach
Our solution is designed as a modular reasoning pipeline that evaluates global narrative consistency rather than surface-level plausibility.

### Key Ideas
Treat the problem as long-context classification, not text generation

Aggregate evidence from multiple parts of the narrative

Preserve global constraints across time, events, and character evolution

## Reproducibility
All code is designed to run end-to-end in a clean environment.

No manual intervention is required once inputs are provided.

# Team: The Aurelion
Bhavya – Exploratory Data Analysis & Model Development

Rutvi – Frontend & UI Design

Kena – Repository Management, Documentation & Presentation

Digvijay – Backend, APIs & Project Management


## Final Note
Our approach focuses on clear reasoning, long-context handling, and reproducibility, aligning closely with the goals of Track A. The system is designed to be extensible and serves as a strong foundation for further improvements in narrative consistency reasoning.
