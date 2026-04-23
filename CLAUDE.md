# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is a teaching repository for **Computational Data Analysis with Python**, a course aimed at engineering students (civil engineering focus) with beginner to intermediate Python skills. Content is delivered as Jupyter notebooks designed to run in **Google Colab**, with each notebook covering a 90-minute tutorial session.

## Running notebooks

Notebooks are designed for Google Colab. To run locally:

```bash
jupyter notebook notebooks/T3_from_missing_data_to_insights_solution.ipynb
# or
jupyter lab
```

Each notebook is self-contained: it imports its own libraries and generates synthetic datasets inline. No external data files are required.

## Repository structure

```
notebooks/   Tutorial notebooks (T1–T4)
project/     Course project guidelines and suggested tracks
```

### Notebook progression

| File | Topic | Key libraries |
|------|-------|---------------|
| `T1_intro_to_Python.ipynb` | Python basics (variables, loops, conditionals) | stdlib only |
| `T2_from_scripts_to_structured_code.ipynb` | Python continuation | stdlib only |
| `T3_from_missing_data_to_insights_solution.ipynb` | NumPy, Pandas, time series, missing data | `numpy`, `pandas` |
| `T4_from_data_points_to_visualization_solution.ipynb` | Matplotlib, SciPy curve fitting, hypothesis testing | `numpy`, `pandas`, `matplotlib`, `scipy` |

## Notebook format conventions

Every tutorial notebook follows this structure:

1. **Header cell** — Colab badge, title, duration, prerequisites
2. **Overview** — learning objectives, new Python concepts introduced
3. **Self-study resources** — links students read before the tutorial (30 min)
4. **Quick reference cheat sheet** — copy-paste commands in a fenced code block
5. **Hackathon** — numbered tasks graded Easy / Medium / Hard, each with a `# YOUR CODE HERE` scaffold cell followed by a `# ✅ SOLUTION` cell.
6. **Summary table** — recap of skills practised

Use `notebooks/T3_from_missing_data_to_insights_solution.ipynb` as the starting point for new tutorial notebooks.

When editing notebooks use the `NotebookEdit` tool rather than editing raw JSON.

## Project context

The course project (`project/`) uses a shared climate/heat dataset. Four pre-defined tracks are available (heat-risk screening, alert system, driver analysis, monitoring representativeness), or students may propose their own. The project follows a fixed 7-stage workflow: problem framing → data audit → cleaning → EDA → baseline model → validation → interpretation.

## Key conventions

- **Synthetic datasets are generated inline** — each notebook seeds `np.random` and builds its own dataset so notebooks are fully self-contained.
- **Solution cells are present but not hidden** — `# ✅ SOLUTION` cells appear directly after scaffold cells.
- **Scaffold cells use `# YOUR CODE HERE`** comments as placeholders.
