# Optimization Algorithms Coursework

Academic optimization project from Instituto Superior Tecnico, 2023/2024.

The project solves a sequence of optimization tasks in MATLAB, including cost-function visualization,
trajectory selection, and iterative parameter experiments.

## Repository Contents

- `TasksScripts.m`: MATLAB script with the project task solutions.
- `proj_oa2324p1.pdf`: original project statement.

## How To Run

Open `TasksScripts.m` in MATLAB and run the script from the beginning.

The script executes tasks sequentially and writes plots using names like:

```text
Task1.png
Task2.png
...
```

Some tasks require manual interaction:

- Task 9 asks the user to select reference trajectory points on a graph.
- Task 13 uses a similar interaction with a maximum of two points.
- Tasks 10, 11, and 12 iterate over multiple `mu` values and may take longer to finish.

## Notes

This repository is kept as a compact coursework archive. It is not a packaged MATLAB toolbox, and the
main value is in the implemented optimization exercises rather than reusable project infrastructure.
