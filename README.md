# Planta Física · Monthly challenge · MA2015.202

We use the supplied genetic algorithm to study four buildings using March 2025 demands. We keep formulation, manual calculation, code, results and interpretation in one cumulative notebook.

## Start from the common base

1. Extract all five files into the same folder.
2. Read the [challenge guide](challenge_guide_planta_fisica.pdf) to identify criteria, deadlines and evidence.
3. Prepare Python 3.12-3.14 and run `uv sync --locked`.
4. Run `uv run jupyter lab` and open [the notebook](planta_fisica_minimum_solution.ipynb).
5. Restart the kernel and run every cell in order. Compare the manual calculation with the outputs.
6. Integrate your team's explanation, identify changes and record role rotation in the same notebook.
7. Retain the outputs and submit the cumulative notebook with both environment files at each deadline.

Data and code are embedded. The 1410 m³ capacity and building limits are teaching assumptions.

| Milestone | Criteria and maximum points | Deadline, Mexico City time | Course weight |
|---|---|---|---|
| Research | A1 formulation and assumptions (60); A2 hand calculation and verification (40) | October 13, 2026, 23:59 | 15% |
| Development | B1 justified operator modification (70); B2 reproduction and controlled comparison (30) | October 16, 2026, 23:59 | 15% |
| Final | C1 generation explanation (40); C2 same-code mutation comparison (35); C3 physical interpretation (25) | October 20, 2026, 16:10 | 30% |

For Development, preserve the baseline and make a substantive change to one selection, crossover or mutation operator. Compare both versions with mutation probability 0.25 and the same conditions and seed 42.

For Final, analyze one identified code version and compare mutation probabilities 0.25 and 0.50 in that same code. If only the baseline is available, identify it as unmodified and complete all three Final evidence items; the Development penalty will not be applied again.

Each assignment will be graded out of 100, with the same team grade assigned to every member. Consult the detailed Research, Development and Final instructions and rubrics in Canvas; their specific requirements govern each milestone.
