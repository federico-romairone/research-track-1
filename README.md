# Research Track I Assignment

Research Track I (Prof. Carmine Tommaso Recchiuto), Robotics Engineering, UniGe.

## Deliverables

- `paper/` — 5–6 page IEEE-style paper: Introduction & Research Question, Literature
  Analysis, Methodological Proposal, Experiment Design, Results & Visualization,
  Discussion & Limitations.
- `notebook/` — Jupyter notebook that simulates the experiment, runs multiple trials,
  collects/processes the data, and produces the plots used in the paper.

## LLM-use boundaries

- OK: polishing your own writing, outlines/summaries, understanding concepts.
- Not OK: writing whole sections, generating original ideas/methods/conclusions, or
  using text you don't fully understand yourself.

## Structure

```
paper/                  IEEE LaTeX source (main.tex, references.bib)
notebook/               Jupyter notebook(s) for the experiment
src/                    reusable Python code extracted from the notebook once it stabilizes
results/                generated figures/data (gitignored — regenerate from the notebook)
pyproject.toml          project metadata and dependencies (managed with uv)
uv.lock                 pinned, exact dependency versions — reproducible environment
.python-version         pins this project to Python 3.12
```
