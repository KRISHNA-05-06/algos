# Dynamic Programming Project

## Description
The project calculated the number of sprockets required to assembe an omnidroid. The solution uses a memorized dynamic programming approach to compute the cost effectively. The program reads input from a file, process the dependencies between parts and recursively calculates the toal sprocket cost.

## Requirements
- python 3.x
- Any text editor or IDE for editing the input file.

## Modules Used
- **`defaultdict` from `collections`**: simplifies handling of dependencies as adjacency lists.
- **`sys` module**: Handles command-line arguments.

## Input Format
The input file should follow this format:
1. The first line contains two integers `n` and `m`:
   - `n`: Number of parts.
   - `m`: Number of dependencies.
2. The next `m` lines list dependencies: `i j` means part `i` is used to build part `j`.
3. The final `n` lines list the sprocket cost for each part.

## Output Format
The program outputs the total number of sprockets required to build the omnidroid in the following format:
An omnidroid with parts and dependencies, takes <total_cost> sprockets to build.
