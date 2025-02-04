# 🎯 100 Code in 100 Days – Challenge 

This is *project no.1* in my **100 Code in 100 Days challenge!** 🚀 I’m committing to coding a new project every day and sharing my progress on GitHub.

📌 ***Follow my journey here***: [www.linkedin.com/in/rawan-ashry-621b10343
](https://www.linkedin.com/in/rawan-ashry-621b10343?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
# 🎭 Degrees of Separation 🎬

This project is part of Harvard's CS50 AI course and is inspired by the "Degrees" problem. The goal is to find the shortest path between two actors based on their co-starring in movies, using data from IMDb.

## 📌 Project Overview

The program loads a dataset containing information about actors, movies, and their relationships. Given two actor names, it determines the shortest path between them using the **Depth-First Search (DFS) 🔍** and **Breadth-First Search (BFS) 🔎** algorithms.

## 🚀 Features
- 📂 Loads data from CSV files containing actors, movies, and their connections.
- 🔄 Implements search algorithms to find the shortest path between two actors.
- 🔍 Handles multiple actors with the same name.
- 🖥️ Provides an interactive command-line interface for user input.

## ⚙️ Installation & Usage
### 📌 Prerequisites
- 🐍 Python 3.x
- 📄 Required CSV dataset (provided in the project directory in a zip file)

### ▶️ Running the Program
1. 📥 Clone the repository or download the project files.
2. ✅ Ensure the required CSV files (`people.csv`, `movies.csv`, `stars.csv`) are in the correct directory.
3. 🔗 Open a terminal and navigate to the project folder.
4. 🏃 Run the program with:
   ```sh
   python degrees.py [directory]
   ```
   If no directory is specified, the program defaults to the `large` dataset.
5. 🎤 Enter the names of two actors when prompted to find their shortest connection path.

## 📁 File Structure
- `degrees.py` 📝: Main script for loading data and finding shortest paths.
- `util.py` ⚙️: Contains helper classes such as `Node`, `StackFrontier`, and `QueueFrontier` for search algorithms.
- `people.csv` 🧑‍🎭: List of actors with their IDs and birth years.
- `movies.csv` 🎞️: List of movies with their IDs, titles, and release years.
- `stars.csv` 🌟: Relationships between actors and movies.

## 🧠 Algorithms Used
The program uses **Depth-First Search (DFS) 🔍** and **Breadth-First Search (BFS) 🔎** to explore actor connections and find the shortest path. The search is implemented using both stack-based (`StackFrontier`) and queue-based (`QueueFrontier`) approaches.

## 💡 Example Usage
```
Loading data...
Data loaded.
Name: Tom Hanks
Name: Kevin Bacon
2 degrees of separation.
1: Tom Hanks and Bill Paxton starred in Apollo 13
2: Bill Paxton and Kevin Bacon starred in Apollo 13
```

## 🔧 Potential Enhancements
- 🚀 Implementing a heuristic-based search like A* for performance optimization.
- 🎥 Expanding the dataset for a more comprehensive search.
- 🖥️ Creating a graphical user interface for better user interaction.

## 📜 Credits
This project is part of **CS50 AI** offered by Harvard University.

## 📝 License
This project is for educational purposes and follows the guidelines of Harvard's CS50 course.

