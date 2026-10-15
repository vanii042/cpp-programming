# C++ Programming: Beginner to Advanced

A collection of standalone C++ programs organized by topic for learning, college practice, and GitHub portfolio building.

## Contents

| Folder | Topics |
|---|---|
| `01-Basics` | Input/output, arithmetic, calculator, area, temperature |
| `02-Conditions-Loops` | Conditions, loops, factorial, Fibonacci, prime, palindrome, Armstrong |
| `03-Patterns` | Star and number patterns |
| `04-Functions-Recursion` | GCD/LCM, recursion, Tower of Hanoi |
| `05-Arrays` | Array operations, searching, rotation, matrices |
| `06-Strings` | Palindromes, anagrams, character and word counting |
| `07-Searching-Sorting` | Binary search, bubble/selection/insertion/merge/quick sort |
| `08-OOP` | Classes, objects, constructors, inheritance, polymorphism, encapsulation |
| `09-STL` | Vector, map, set, stack, queue |
| `10-Data-Structures` | Linked list, stack, circular queue, trees |
| `11-Algorithms` | BFS, DFS, Dijkstra, 0/1 knapsack, LIS, Kadane's algorithm |
| `12-File-Handling` | Reading and writing files |

## Requirements

- A C++ compiler such as GCC or Clang
- C++17 or later

## Compile and run

Open a terminal in the repository root. Compile any program by giving its path:

```bash
g++ -std=c++17 -Wall -Wextra -pedantic 01-Basics/hello_world.cpp -o hello_world
```

Run on Windows:

```powershell
.\hello_world.exe
```

Run on Linux/macOS:

```bash
./hello_world
```

Each `.cpp` file has its own `main()` function, so compile **one program at a time**. Do not compile all `.cpp` files into one executable.

## Input conventions

- Unless a program displays prompts, enter the input in the order expected by the code.
- `binary_search.cpp` expects a sorted array.
- `merge_two_sorted_arrays.cpp` expects both arrays to already be sorted.
- `graph_bfs.cpp`, `graph_dfs.cpp`, and `dijkstra_shortest_path.cpp` use zero-based vertex labels (`0` through `n-1`).
- `knapsack_01.cpp` expects `n capacity`, then `n` weights, then `n` values.
- Some examples intentionally limit input sizes to avoid overflow or excessive recursion.

## Suggested learning order

1. Basics and conditions/loops
2. Patterns, functions, and recursion
3. Arrays and strings
4. Searching and sorting
5. OOP and STL
6. Data structures
7. Graphs and dynamic programming

## Contributing

Add new problems to the relevant topic folder. Use descriptive filenames, keep each example standalone, and document any special input format in a comment or in this README.

## Disclaimer

This is a learning repository, not an exhaustive list of every possible C++ problem. Review and test code before using it in assignments or production systems.
