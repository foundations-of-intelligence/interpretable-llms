# Interpretable LLMs: Mechanistic Understanding of Transformer Decision-Making

## Abstract
Large Language Models (LLMs) exhibit strong performance across reasoning and knowledge-intensive tasks, yet the internal mechanisms underlying their behavior remain poorly understood. This project investigates the internal representations and circuits within transformer-based language models that give rise to specific decisions, such as factual recall or multi-step reasoning. Using mechanistic interpretability techniques—including circuit discovery, sparse feature extraction, and causal interventions—we aim to move beyond correlational explanations and make precise, testable claims about how LLMs compute their outputs.

## Research Motivation
Despite widespread deployment of LLMs, their opacity poses risks for reliability, safety, and alignment. Interpretability is a prerequisite for:
- Diagnosing failure modes
- Improving robustness and alignment
- Building trustworthy AI systems

This project treats interpretability as a **scientific investigation**, not a visualization exercise.

## Core Research Questions
- Which internal circuits or features are responsible for specific behaviors (e.g., factual recall, indirect object identification)?
- Are these mechanisms consistent across model sizes and architectures?
- Can causal interventions reliably modify or suppress specific behaviors?

## Methodology Overview
We employ a combination of:
- Transformer circuit analysis (attention heads, MLPs)
- Sparse Autoencoders for feature discovery
- Activation patching and neuron ablation
- Cross-model and cross-layer comparisons

All claims are supported by controlled experiments and ablation studies.

## Experimental Philosophy
This project prioritizes:
- Causal evidence over correlation
- Reproducibility over novelty
- Insight over benchmark chasing

## Repository Structure
src/ # Core analysis and model interaction code
experiments/ # Experiment definitions and configs
analysis/ # Interpretability analyses and visualizations
results/ # Figures, tables, and logs
configs/ # Model and experiment configurations

## Status
This repository is under active research development.  
Results and conclusions may evolve as experiments progress.

## Ethical Considerations
Understanding internal mechanisms can inform safer model design, but interpretability tools can also be misused. All experiments are conducted on open models and focus on transparency, not exploitation.

## License
MIT License
