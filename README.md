# Game Directory Manager: Automated Game Compilation and Execution

# Overview
The Game Directory Manager script is a Python tool designed to automate the process of managing, compiling, and executing Go-based games stored in specific directories. This script searches for game directories, compiles the Go code files, and runs the games, while also generating metadata in the form of a JSON file. The script allows users to quickly and efficiently handle multiple games from a large directory.  

🚀 **Features**  
- Game Discovery: Automatically searches for directories containing the word "game."
- Directory Organization: Moves and renames game directories into a centralized /games directory.
- Go Compilation: Compiles Go source files (.go) for each game found in the directories.
- Execution: Runs the compiled Go games and logs the results.
- Metadata Generation: Creates a metadata.json file that contains details about the games, such as the number of games and their names.

🚀 **Assumptions**  
- The data directory contains various files and subdirectories.
-Game directories are identified by the word "game" in their names.
-Each game directory contains a single .go file that must be compiled and run.
-A new games directory will be created to store the renamed games without the "game" suffix.
-No experience needed—just your determination. Future-proof your career and unlock six-figure potential like many of our students have!

# Usage
#1. Install Required Packages
Make sure you have the necessary tools installed:
Python 3.x
Go Compiler

# 2. Run the Script
To run the script, use the following command in your terminal or command prompt:
python3 get_game_data.py <source_directory> <target_directory>

For example:
python3 get_game_data.py data games
This will search for all game directories in the /data directory, copy and rename them into the /games directory, compile the .go files, run them, and generate a metadata.json file in the /games directory.

# 3. Output
The compiled games will be stored in the /games directory.
The metadata.json file will contain information about the processed games.
The output of the compilation and execution will be printed to the console.
