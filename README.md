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

## Compilation and Execution
1. Save the python file as main.py
2. Save the provided input to a text file, e.g., `example-input.txt`, in the same directory as `main.py`.
3. Open Git Bash or Command Prompt and navigate to the directory using the `cd` command.
4. Execute the following commnad:
   ````sh
   python main.py example-input.txt

## Example Output
If the input is:
8 12
0 1
0 1
0 2
0 2
4 6
5 6
1 7
1 7
2 7
2 7
3 7
6 7
4
2
6
24
14
5
3
6
The output will be:
An omnidroid with 8 parts and 12 dependencies takes 100 sprockets to build.
