# Analytical Solution Generating Script for Lin R13
A Python script that generated analytical solutions of the linearized R13 equations for problems defined in an annular domain.

## Requirements

- Conda

## Installation

Create the environment:

```bash
conda env create -p .conda-env -f environment.yml
```

Activate it:

```bash
conda activate ./.conda-env
```

Run with the default input file:

```bash
python exact_sol_gen_R13.py
```

Run with a custom input file:

```bash
python exact_sol_gen_R13.py path/to/input.yml
```

## Output

The script writes these files in the current directory:

- `Exact_Sol_Python.py`
- `Exact_Sol_Dolfin.cpp`
- `Exact_Sol_C++.h`
