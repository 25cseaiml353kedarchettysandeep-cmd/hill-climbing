# Hill Climbing

## Aim
To maximize an objective function by repeatedly moving to a better neighbouring state.

## Algorithm
1. Evaluate the objective function at the current position.
2. Evaluate the left and right neighbours.
3. Move to a neighbour if it has a higher value.
4. Stop when neither neighbour improves the value or the iteration limit is reached.

## How to run
Requires Python 3.10 or newer. No third-party packages are required.

```bash
python hill_climbing.py
```

## Sample output
```text
Enter starting value: 0
Enter step size: 1
Enter maximum iterations: 20
Best position = 5.0
Maximum value = 100.0
```

## Notes
Hill climbing is a local search technique and may get stuck at local optima for more complex functions.

## Repository structure
- `hill_climbing.py` — program source code
- `README.md` — aim, algorithm, run instructions, and sample output

> Before submission, run the program on your own computer and capture the actual output. Sample output may vary with user input.


## Captured sample output
See [`output.txt`](output.txt) for a sample console run produced from the included program.


## Output file
See [`OUTPUT.txt`](OUTPUT.txt) for a captured sample run. For interactive programs, output depends on the input entered.
