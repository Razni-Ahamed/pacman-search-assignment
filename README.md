# Pac-Man Search — SE3062 Intelligent Systems Group Assignment

Implementation of DFS, BFS, Uniform Cost Search and A*, plus heuristics for the
Corners and Food-search problems, in the UC Berkeley CS188 Pac-Man framework.

Starter code: UC Berkeley CS188 (http://ai.berkeley.edu), used for educational purposes.

## Files we edit
- `search.py` — Q1 DFS, Q2 BFS, Q3 UCS, Q4 A*
- `searchAgents.py` — Q5 `CornersProblem`, Q6 `cornersHeuristic`, Q7 `foodHeuristic`

Do NOT rename files, functions or classes.

## Setup
```bash
conda create -n cs188 python=3.11
conda activate cs188
pip install numpy matplotlib
python pacman.py        # sanity check
```

## Work split
| Branch | Questions | File |
|---|---|---|
| `q1-q2-dfs-bfs` | Q1 DFS, Q2 BFS | search.py |
| `q3-q4-ucs-astar` | Q3 UCS, Q4 A* | search.py |
| `q5-q6-corners` | Q5 CornersProblem, Q6 cornersHeuristic | searchAgents.py |
| `q7-food-heuristic` | Q7 foodHeuristic | searchAgents.py |

Merge order: Q1-Q2 -> Q3-Q4 -> Q5-Q6 -> Q7.

## Git workflow
1. `git pull origin main`
2. `git checkout -b <your-branch>`
3. Small commits with meaningful messages
4. `git push -u origin <your-branch>` and open a Pull Request; a teammate reviews and merges

## Testing
```bash
python autograder.py -q q1 --no-graphics
python autograder.py --no-graphics
```
