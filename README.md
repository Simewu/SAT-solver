# Boolean Satisfiability Solver
 A web-based boolean satisfiability solver.
 Given a SAT instance, the program will determine whether or not it is satisfiable (i.e. has some variable assignment that evaluates the Boolean formula to true), if it is, it will provide the variable assignment that satisfies the formula.
 
![](/screenshots/1.png)

## Instructions
Each number represents a variable index (e.g., x_1, ..., x_n), where variables can be true (1) or false (0). Negative numbers indicate the use of the NOT operator. Variables combined with negative and positive signs are referred to as literals.

Each line of input is a clause, combining all literals with a logical OR. All clauses are combined with a logical AND. The goal is to determine whether any variable arrangement can satisfy the formula (SAT) or not (UNSAT).

- **Left box**: The editor for entering SAT instances.
- **Right box**: Displays the instance in mathematical notation.
- **Bottom box**: Shows the output from experiments run.
- **Benchmark button**: Generates random instances with varying numbers of literals and clauses, running ten samples per configuration to measure performance.

## Presets
The following instances are preloaded into the application.

- **Default [SAT]**: Variables = 5, Clauses = 6
- **Simple Test [SAT]**: Variables = 3, Clauses = 2
- **Sudoku Instance [SAT]**: Variables = 729, Clauses = 8850
- **Who Owns the Zebra Puzzle [SAT]**: Variables = 155, Clauses = 1135
- **Pigeon Hole Problem [UNSAT]**: Variables = 42, Clauses = 133
- **Parity Problem [SAT]**: Variables = 64, Clauses = 254
- **Factorize 139*227=31553 [SAT]**: Variables = 83, Clauses = 1468
- **Factorize 2711*2153=5836783 [SAT]**: Variables = 191, Clauses = 4679
- **Artificial Instances from Generator [UNSAT]**: Variables = 100, Clauses = 160
- **Artificial Instances from Generator [SAT]**: Variables = 50, Clauses = 80
- **Nemesis Formula [UNSAT]**: Variables = 1317, Clauses = 3668
- **Instance from Generator 20 [UNSAT]**: Variables = 60, Clauses = 160
- **Instance from Generator 21 [UNSAT]**: Variables = 63, Clauses = 168
- **Instance from Generator 22 [UNSAT]**: Variables = 66, Clauses = 176

---

The application is hosted at https://simewu.github.io/SAT-solver
