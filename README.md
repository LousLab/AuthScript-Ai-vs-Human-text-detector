# AuthScript-Ai-vs-Human-text-detector

Fine-tuned transformer (DistilBERT/RoBERTa) to classify AI-generated vs human-written text, focused on cross-domain generalization.

## Motivation

First attempt (last semester, OutScript) failed because the human training data had poor grammar, so the model learned writing quality instead of AI-ness. This version uses clean data and tests on unseen datasets to avoid that.

## Status

- [ ] Data collection + cleaning
- [ ] Baseline
- [ ] Fine-tuning
- [ ] Cross-domain evaluation
- [ ] Improvement pass
- [ ] Deployed demo

*More details to come as the project progresses.*

## Setup

```bash
pip install -r requirements.txt
```
