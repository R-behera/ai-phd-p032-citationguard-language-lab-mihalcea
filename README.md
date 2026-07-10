# CitationGuard Language Lab: NLP for Mihalcea-Aligned Research

A research-grade AI/ML PhD preparation project aligned with **Rada Mihalcea** at **University of Michigan**.

## Research Question

Can a citation-faithful agent answer ambiguous scientific questions without inventing unsupported claims?

## Advisor Fit

- **Professor:** Rada Mihalcea
- **University:** University of Michigan
- **Program:** Computer Science & Engineering
- **CSV research area:** NLP, computational social science, multimodal
- **Representative paper:** TextRank: Bringing Order into Texts; 2004; EMNLP
- **Scholar link:** https://scholar.google.com/scholar?q=TextRank%3A+Bringing+Order+into+Texts

## Research-Grade Deliverable

This repo is scaffolded to become a serious research artifact, not a demo-only project. The finished version should include:

- Reproducible dataset pipeline with raw-data provenance.
- Strong baselines and locked experiment configs.
- Original method or evaluation contribution.
- Ablation studies that isolate what changed.
- Failure analysis with concrete examples.
- Paper-style report, limitations, and reproducibility notes.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/experiment_plan.md` - concrete baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `src/` - implementation package placeholder.
- `tests/` - smoke and metric tests placeholder.
- `reports/` - figures, tables, and final writeup.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Scaffolded from the Fall 2027 AI PhD programs CSV. Before external use, re-verify professor interests, application dates, and paper/citation metadata.
