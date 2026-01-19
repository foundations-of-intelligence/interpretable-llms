# Research Questions & Hypotheses

## Primary Research Questions

1. Can specific transformer circuits be causally linked to factual recall or reasoning behaviors?
2. Do similar behaviors rely on shared internal mechanisms across different model sizes?
3. Are discovered features localized, distributed, or hierarchical in nature?
4. How stable are these mechanisms under intervention or distribution shift?

## Hypotheses

- H1: Certain attention heads and MLP neurons form task-specific circuits responsible for factual recall.
- H2: These circuits exhibit partial invariance across model scales but differ in redundancy.
- H3: Sparse Autoencoders can recover human-interpretable features aligned with semantic concepts.
- H4: Targeted causal interventions can selectively suppress behaviors without degrading unrelated capabilities.

## Falsification Criteria

- Failure to observe behavior change after targeted ablations
- Inability to reproduce findings across random seeds or model variants
- Features that correlate with behavior but fail under causal testing

## Evaluation Principles

- Causal impact over correlation strength
- Cross-checking results with multiple intervention methods
- Reporting negative results where hypotheses fail
