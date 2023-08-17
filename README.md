# recursive-resolver-functions
This is an implementation of fibonnacci generator with 3 different implementations
# Recurrence Relation Solver func

This repository contains C implementations for solving the recurrence relation F(n) = F(n-3) + F(n-2) using three different approaches: recursive, memoization, and iterative.

## Usage

1. Make sure you have GCC (GNU Compiler Collection) installed.

2. Clone this repository and navigate to the project directory:
git clone https://github.com/brianckiptoo/recurrence-relation-solver.git
cd recurrence-relation-solver


3. Compile the source code for the desired approach:

- Recursive:
  ```
  gcc recursive.c -o recursive
  ```

- Memoization:
  ```
  gcc memoization.c -o memoization
  ```

- Iterative:
  ```
  gcc iterative.c -o iterative
  ```

4. Run the compiled executable:
./recursive
./memoization
./iterative


5. Follow the prompts to input `n` and see the result of F(n) = F(n-3) + F(n-2).

## Contributing

Feel free to fork and submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

