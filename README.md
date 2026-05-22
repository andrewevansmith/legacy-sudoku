# Legacy Sudoku Research

Archived Python Sudoku modeling and solving research project, developed around March to July 2010 for SciPy 2010 work.

## What this shows

- Sudoku modeling in Python using graph, constraint, and optimization approaches.
- Puzzle representation helpers, solver experiments, random puzzle investigations, and test assertions.
- Research artifacts including Sphinx docs, LaTeX article material, talk slides, puzzle datasets, and graph exports.

## Archive Status

This repository is preserved as a public reference snapshot. It targets an older Python/scientific-computing environment and is not maintained as a modern package.

## Project Layout

- `src/`: core Sudoku modeling code.
- `tests/`: assertion-based tests from the original project.
- `scripts/`: command-line solving helper.
- `puzzles/`: benchmark and example puzzle datasets.
- `investigations/` and `demos/`: exploratory scripts.
- `doc/`, `article/`, and `talk/`: documentation, paper, and presentation sources.

## Cleanup Notes

- Recovered the working tree from an archived Mercurial store.
- Removed Mercurial metadata before publishing.
- Converted `.hgignore` to `.gitignore`.
- Replaced a machine-specific SCons build path with a repository-local build path.

