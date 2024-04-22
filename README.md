# BatchGer

Just to give some directions to the most important directories of this project:
- The front end is located at `batchger/tree-sitter-batch`
  - The main part of the frontend (the **tree-sitter grammar** for the parser) is located at `batchger/tree-sitter-batch/grammar.js`
  - For the **corpus** (test-driven-development), see `batchger/tree-sitter-batch/corpus`
  - For the other half of the parser correctness evaluation, the batch files located at `batchger/tree-sitter-batch/test-scripts` have been used
- The backend (the **extensible toolkit for deobfuscation**) is located at `batchger/src`
  - For **sphinx documentation** of the backend, open up `batchger/docs/_build/html/index.html` in your favorite browser

## Requirements (in general)

- `python3`
- `python3-pip` for `pip install tree-sitter`
- `node.js`
- `cargo`, `npm` or download the `tree-sitter binary` from its GitHub and put it into `PATH`
- C compiler

## Requirements (for setup via make)

- `python3-pip`
- `python3-venv`
- `node`
- `cargo`
- C compiler

## Setup

Running `make setup` will create a virtual python environment, install the dependencies and set up sane defaults for code formatting and linting.

Activate the virtual environment by running `source ./venv/bin/activate`

---

# Notes

- The obfuscated test files are around 250MB, so we didn't push them to GitLab and didn't include them in the submission. If desired, we can send them later on.
