# Reusable Prompt Template & Complete AI Practicals Guide (Practicals 1–9, 12 & 13)

## Part 1: Reusable AI Practicals Prompt Template

Copy and paste the prompt below into any future chat whenever you want an AI or Machine Learning practical explained in your preferred beginner-friendly layout:

```text
Please format all your future answers regarding Artificial Intelligence and Machine Learning practicals (in Python) using the following structured layout:

1. Practical Aim & Topic Breakdown:
   - State the exact Aim of the practical clearly.
   - Explain the core AI/ML topic and theory in plain, everyday language so I understand what the algorithm or technique actually does and why we use it.
2. Direct & Encouraging Overview:
   - A quick, clear summary of what our Python program is doing and how the workflow fits together.
3. Step-by-Step Instructions:
   - Bulleted, numbered steps for installing required libraries (via Command Prompt/Terminal), preparing datasets (if needed), and setting up the script in Python IDLE or VS Code.
4. File Paths Included:
   - Explicitly state the exact file path where the Python script and any dataset files (`.csv`) should be saved or loaded from (e.g., `Desktop > AI > Practical_12 > pract12_1.py`).
5. Fully Written Code Blocks:
   - Clean, formatted, heavily commented Python code explaining every import, function call, and variable.
   - Expected Output block showing what the program prints when run.
6. Next Steps / Follow-up:
   - End with a clear next action, experiment, or question to guide my learning step-by-step.

Target Audience: Absolute beginner. Keep explanations concise, scannable, visually clean, and avoid unnecessary jargon without context.
```

---

## Part 2: Master Index & Checklist of Your AI Practicals

Here is the complete index of all **18 practicals** now included in this guide (covering **Practicals 1 to 9**, **Practical 12 Parts 1–8**, and **Practical 13**), plus the only remaining missing practicals (**10 and 11**):

| Practical No. | PDF Filename | Status | Core AI / ML Topic | Dataset / Problem Used | Algorithm / Library |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Practical 1** | `AI Practicals 1-2.pdf` | ✅ Added | Rational Agents, PEAS Framework, Environment Classification & Table-Driven Agent | Vacuum Cleaner (Rooms A & B) & Autonomous Taxi | Pure Python (`dict`, `if/else` Table-Driven Agent) |
| **Practical 2** | `AI Practicals 1-2.pdf` | ✅ Added | 8-Puzzle Problem using Breadth-First Search (BFS) | 3×3 Sliding Tile Puzzle (`0` = Blank Space) | `collections.deque` (BFS Queue & Visited Set) |
| **Practical 3** | `Practical No 3.docx.pdf` | ✅ Added | Two Water Jug Problem using Depth-First Search (DFS) | 4L Jug & 3L Jug $\rightarrow$ Measure 2L | Recursive DFS (`dfs(x, y)`) & Backtracking |
| **Practical 4** | `Practical 4.pdf` | ✅ Added | Uniform Cost Search (UCS) for Least-Cost Path | Weighted Romania Road Map (`ARAD` to `BUCHAREST`) | `heapq` (Priority Queue with $g(n)$) |
| **Practical 5** | `Pract5.pdf` | ✅ Added | Greedy Best-First Search (GBFS) for 8-Puzzle | 3×3 Sliding Tile Puzzle (`0` = Blank Space) | `heapq` + Manhattan Distance Heuristic $h(n)$ |
| **Practical 6** | `Practical 6.docx.pdf` | ✅ Added | A* Search Algorithm for 8-Puzzle | 3×3 Sliding Tile Puzzle (`0` = Blank Space) | `heapq` + $f(n) = g(n) + h(n)$ (Manhattan Distance) |
| **Practical 7** | `Practical 7.docx.pdf` | ✅ Added | A* Search Algorithm for Shortest Path on Romania Map | Weighted Romania Road Map (`Arad` to `Bucharest`) | `heapq` + $f(n) = g(n) + h(n)$ (Straight-Line Distance) |
| **Practical 8** *(Header says 9, code is `Pract8.py`)* | `Practical No 8.pdf` | ✅ Added | Bayes' Rule for Medical Disease Probability | Medical Test Scenario ($1\%$ Disease Prevalence, $99\%$ Sensitivity, $5\%$ False Positive) | Pure Python Probability Formula |
| **Practical 9** *(File named `Practical No 11.pdf`)* | `Practical No 11.pdf` | ✅ Added | Bayesian Network & Posterior Probability Inference | Burglary, Earthquake & Alarm Network | `pgmpy` (`DiscreteBayesianNetwork`, `VariableElimination`) |
| **Practical 10** | *Not uploaded yet* | ❌ Missing | — | — | — |
| **Practical 11** | *Not uploaded yet* | ❌ Missing | — | — | — |
| **Practical 12 (1)** | `Practical No 12(1).pdf` | ✅ Added | End-to-End Machine Learning Workflow (Preprocessing, Scaling, Split, Train, Evaluate) | `student.csv` (Hours Studied, Attendance, Result) | `pandas`, `LabelEncoder`, `StandardScaler`, `KNeighborsClassifier` |
| **Practical 12 (2)** | `Practical No 12(2).pdf` | ✅ Added | Simple Linear Regression (Continuous Value Prediction) | `student_marks.csv` (Hours, Marks) | `pandas`, `LinearRegression` |
| **Practical 12 (3)** | `Practical No 12(3).pdf` | ✅ Added | Binary Classification (Digit 5 vs. Not Digit 5) | `sklearn` Digits (MNIST-like handwritten digits) | `LogisticRegression` |
| **Practical 12 (4)** | `Practical No 12(4).pdf` | ✅ Added | K-Fold Cross-Validation (5-Fold Model Evaluation) | `sklearn` Iris dataset | `KNeighborsClassifier`, `cross_val_score` (`cv=5`) |
| **Practical 12 (5)** | `Practical No 12(5).pdf` | ✅ Added | Decision Tree Classification | `sklearn` Iris dataset | `DecisionTreeClassifier` |
| **Practical 12 (6)** | `Practical No 12(6).pdf` | ✅ Added | Decision Tree Regression (Continuous Value Prediction) | `student_marks.csv` (Hours, Marks) | `pandas`, `DecisionTreeRegressor` |
| **Practical 12 (7)** | `Practical No 12(7).pdf` | ✅ Added | K-Nearest Neighbors (KNN) Classification (`k=3`) | `sklearn` Iris dataset | `KNeighborsClassifier(n_neighbors=3)` |
| **Practical 12 (8)** | `Practical No 12(8).pdf` | ✅ Added | Multiclass Classification (3 Flower Species) | `sklearn` Iris dataset | `DecisionTreeClassifier` |
| **Practical 13** | `Practical No 13.pdf` | ✅ Added | Dataset Bias & Class Imbalance Analysis | `sklearn` Iris dataset (`pandas` DataFrame) | `pandas` (`value_counts()`, `isnull().sum()`) |

---

## Part 3: All Uploaded AI Practicals Formatted in Your Custom Layout

### 1. Practical No. 1 (from `AI Practicals 1-2.pdf`): Rational Agents, PEAS & Table-Driven Vacuum Agent

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Design a simple rational agent by defining PEAS for a vacuum cleaner environment and an autonomous taxi. Classify environments (fully/partially observable, deterministic/stochastic, episodic/sequential). Implement a simple table-driven agent in Python.
* **What Topic Is This Practical?** This practical introduces the foundation of Artificial Intelligence: **Intelligent & Rational Agents**.
  * A **Rational Agent** is an AI system that perceives its surroundings through **sensors** and takes actions using **actuators** to achieve the best possible outcome.
  * Before building an agent, we define its task environment using the **PEAS Framework**:
    * **P — Performance Measure:** How do we score the agent's success?
    * **E — Environment:** Where does the agent operate?
    * **A — Actuators:** What physical/digital parts let it take action?
    * **S — Sensors:** What devices let it sense the world?

**PEAS Comparison Table:**

| Agent | Performance Measure (P) | Environment (E) | Actuators (A) | Sensors (S) |
| :--- | :--- | :--- | :--- | :--- |
| **Vacuum Cleaner Agent** | Clean rooms, less time, minimum power | Rooms / Floor with dirt | Move Left, Move Right, Suck | Location sensor, Dirt sensor |
| **Autonomous Taxi Agent** | Safe driving, minimum fuel, passenger satisfaction | Roads, traffic, pedestrians | Steering, accelerator, brake | Cameras, GPS, radar, lidar |

**Environment Classification Table:**

| Property | Vacuum Cleaner | Autonomous Taxi | Plain-English Meaning |
| :--- | :--- | :--- | :--- |
| **Observable** | Fully Observable | Partially Observable | **Fully observable:** Agent sees the complete state of the world. **Partially observable:** Some info is hidden or uncertain (e.g., blind spots, other drivers' intentions). |
| **Nature** | Deterministic | Stochastic | **Deterministic:** An action always produces a guaranteed, predictable result. **Stochastic:** Outcomes involve randomness/uncertainty (traffic, weather). |
| **Task Type** | Sequential | Sequential | **Sequential:** Current actions affect future states and decisions. **Episodic:** Each action is totally independent of previous actions. |

#### 2. Direct & Encouraging Overview
In the coding part of Practical 1, we build a **Table-Driven Vacuum Cleaner Agent** in Python. The program asks you for the current status (`Clean` or `Dirty`) of **Room A** and **Room B**, checks if both rooms are already clean, and if not, visits each room in order—sucking up dirt whenever it finds a dirty room until the entire house is spotless!

#### 3. Step-by-Step Instructions
1. **No extra libraries needed:** This practical uses pure, built-in Python (`dict`, `input()`, and `if/else`).
2. **Open Python IDLE:** Launch IDLE and click **File > New File**.
3. **Create the Rooms Dictionary:** Initialize `rooms = {}` and use `input()` to ask the user whether Room `'A'` and Room `'B'` are `Clean` or `Dirty`.
4. **Implement Agent Decision Rules:** Check if both rooms are `"Clean"`. Otherwise, inspect Room A and Room B one by one, printing `"Action: Suck"` and updating their status to `"Clean"` whenever a room is `"Dirty"`.
5. **Run the Program:** Save as `Pract 1.py`, press **F5**, and type `Dirty` for both rooms when prompted.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Pratapgad\Desktop\Pract 1.py`

#### 5. Fully Written Code Blocks
```python
# Table-Driven Vacuum Cleaner Agent

# Step 1: Define rooms dictionary and ask user for their initial status
rooms = {}

rooms['A'] = input("Enter status of Room A (Clean/Dirty): ")
rooms['B'] = input("Enter status of Room B (Clean/Dirty): ")

# Step 2: Check whether all rooms are already clean
if rooms['A'] == "Clean" and rooms['B'] == "Clean":
    print("\nAll rooms are clean. Task completed.")

else:
    # Step 3: Visit Room A
    if rooms['A'] == "Dirty":
        print("\nRoom A is Dirty")
        print("Action: Suck")
        rooms['A'] = "Clean"
        print("Room A cleaned")
    else:
        print("\nRoom A is already Clean")

    # Step 4: Visit Room B
    if rooms['B'] == "Dirty":
        print("\nRoom B is Dirty")
        print("Action: Suck")
        rooms['B'] = "Clean"
        print("Room B cleaned")
    else:
        print("Room B is already Clean")

    # Step 5: Confirm completion
    print("\nAll rooms are clean. Task completed.")
```

**Expected Output:**
```text
Enter status of Room A (Clean/Dirty): Dirty
Enter status of Room B (Clean/Dirty): Dirty

Room A is Dirty
Action: Suck
Room A cleaned

Room B is Dirty
Action: Suck
Room B cleaned

All rooms are clean. Task completed.
```

#### 6. Next Steps / Follow-up
* **Try this next:** Run the program again and enter `Clean` for Room A and `Dirty` for Room B to see how the agent skips cleaning Room A and only cleans Room B!

---

### 2. Practical No. 2 (from `AI Practicals 1-2.pdf`): 8-Puzzle Problem using Breadth-First Search (BFS)

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Given an initial configuration of the 8-puzzle and a goal configuration, write a Python program to find the shortest sequence of moves to reach the goal state using Breadth-First Search (BFS).
* **What Topic Is This Practical?** This practical covers **State Space Search** and **Breadth-First Search (BFS)** on the classic **8-Puzzle Problem**:
  * **The 8-Puzzle:** A $3 \times 3$ board has 8 numbered tiles (`1` to `8`) and one blank space represented by `0`. You can slide any adjacent tile into the blank space (`0`).
  * **Breadth-First Search (BFS):** An uninformed search algorithm that explores states **level by level** (all 1-move boards first, then all 2-move boards, etc.) using a First-In, First-Out (FIFO) queue (`deque`).
  * **Why use BFS?** Because it explores level by level, BFS is **guaranteed to find the shortest sequence of moves** to reach the goal state (`1, 2, 3, 4, 5, 6, 7, 8, 0`).

#### 2. Direct & Encouraging Overview
We represent the $3 \times 3$ puzzle board as a 9-element Python tuple—for example, `(1, 2, 3, 4, 0, 6, 7, 5, 8)` where `0` is in the center (index `4`). We write a `neighbors(state)` function that lists every valid index the blank space `0` can swap with, and a `bfs(start, goal)` function that searches level-by-level until the board matches `(1, 2, 3, 4, 5, 6, 7, 8, 0)`, then prints every board step along the shortest path!

#### 3. Step-by-Step Instructions
1. **No external packages required:** We use `deque` from Python's built-in `collections` module.
2. **Open Python IDLE:** Create a new script named `pract2.py`.
3. **Define Valid Moves (`neighbors`):** Map each board position (`0` to `8`) to the adjacent indices that the blank tile `0` can swap with (e.g., index `0` top-left can swap with index `1` right or index `3` down).
4. **Implement BFS (`bfs`):** Use a `deque` initialized with `(start, [])` and a `visited` set so the algorithm never gets stuck in an infinite loop undoing its own moves.
5. **Print the Solution Steps:** Slice each 9-element tuple into 3 rows of 3 (`s[:3]`, `s[3:6]`, `s[6:]`) so it prints like a neat $3 \times 3$ grid.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Server\Desktop\pract2.py`

#### 5. Fully Written Code Blocks
```python
from collections import deque

# Step 1: Generate all possible next board states by sliding the blank tile (0)
def neighbors(state):
    i = state.index(0)  # Find current index (0 to 8) of the blank space
    
    # Dictionary showing which indices the blank tile can move to from each position
    moves = {
        0: [1, 3],       1: [0, 2, 4],    2: [1, 5],
        3: [0, 4, 6],    4: [1, 3, 5, 7], 5: [2, 4, 8],
        6: [3, 7],       7: [4, 6, 8],    8: [5, 7]
    }

    result = []
    for j in moves[i]:
        new = list(state)
        # Swap the blank tile (0) with the neighboring tile
        new[i], new[j] = new[j], new[i]
        result.append(tuple(new))
    return result

# Step 2: Breadth-First Search (BFS) to find the shortest sequence of moves
def bfs(start, goal):
    queue = deque([(start, [])])
    visited = set()

    while queue:
        state, path = queue.popleft()

        # If we reached the goal configuration, return the full sequence of states
        if state == goal:
            return path + [state]

        # Explore unvisited neighbor states
        if state not in visited:
            visited.add(state)
            for n in neighbors(state):
                queue.append((n, path + [state]))

# Step 3: Define Initial and Goal states (0 represents the blank space)
start = (1, 2, 3, 4, 0, 6, 7, 5, 8)
goal  = (1, 2, 3, 4, 5, 6, 7, 8, 0)

# Step 4: Display Initial State as a 3x3 grid
print("Initial State:")
print(start[:3])
print(start[3:6])
print(start[6:])
print()

# Step 5: Display Goal State as a 3x3 grid
print("Goal State:")
print(goal[:3])
print(goal[3:6])
print(goal[6:])
print()

# Step 6: Find and display the shortest solution steps
solution = bfs(start, goal)

print("Solution Steps:")
for s in solution:
    print(s[:3])
    print(s[3:6])
    print(s[6:])
    print()
```

**Expected Output:**
```text
Initial State:
(1, 2, 3)
(4, 0, 6)
(7, 5, 8)

Goal State:
(1, 2, 3)
(4, 5, 6)
(7, 8, 0)

Solution Steps:
(1, 2, 3)
(4, 0, 6)
(7, 5, 8)

(1, 2, 3)
(4, 5, 6)
(7, 0, 8)

(1, 2, 3)
(4, 5, 6)
(7, 8, 0)
```

#### 6. Next Steps / Follow-up
* **Try this next:** Try changing `start` to `(1, 2, 3, 0, 4, 6, 7, 5, 8)` (where the blank space starts on the middle-left) and re-run the program—you'll see BFS find a 4-state solution!

---

### 3. Practical No. 3 (from `Practical No 3.docx.pdf`): Two Water Jug Problem using Depth-First Search (DFS)

#### 1. Practical Aim & Topic Breakdown
* **Aim:** To implement the Two Water Jug Problem using Depth-First Search (DFS) in Python and find a sequence of operations to measure the required amount of water.
* **What Topic Is This Practical?** This practical covers **State-Space Search** using **Depth-First Search (DFS) and Backtracking** on the classic **Water Jug Problem**:
  * **The Problem:** You have two unmarked water jugs—**Jug 1** holds up to **4 liters** (`cap1 = 4`) and **Jug 2** holds up to **3 liters** (`cap2 = 3`)—and an unlimited water tap. How do you measure out exactly **2 liters** (`target = 2`)?
  * **State Representation:** At any moment, the state of both jugs is written as `(x, y)` where `x` = water in Jug 1 and `y` = water in Jug 2, starting from `(0, 0)` (both empty).
  * **6 Valid Operations:** (1) Fill Jug 1 completely, (2) Fill Jug 2 completely, (3) Empty Jug 1, (4) Empty Jug 2, (5) Pour Jug 1 into Jug 2 until Jug 1 is empty or Jug 2 is full, and (6) Pour Jug 2 into Jug 1 until Jug 2 is empty or Jug 1 is full.
  * **How DFS Works:** Unlike BFS (which checks states level-by-level), **Depth-First Search (DFS)** plunges as deeply as possible down one sequence of pours, marking each `(x, y)` state as `visited`, and **backtracks** (`path.pop()`) only if it hits a dead end where all possible pours lead to already-visited states.

#### 2. Direct & Encouraging Overview
We will write a recursive function `dfs(x, y)` inside `water_jug_dfs(cap1, cap2, target)`. Starting from `(0, 0)`, it checks if either `x` or `y` has reached `2` liters, generates all 6 possible next states from the current water levels, explores unvisited states deeply using recursion, and prints the exact step-by-step sequence of jug amounts from `(0, 0)` to `(4, 2)`!

#### 3. Step-by-Step Instructions
1. **No external packages required:** This practical uses pure Python recursion, lists (`path`), and sets (`visited`).
2. **Open Python IDLE:** Create a new script named `Pract 3.py`.
3. **Define the 6 Jug Operations:** Inside `dfs(x, y)`, build the `states` list for filling, emptying, and pouring between Jug 1 and Jug 2 (using `min(x, cap2 - y)` and `min(y, cap1 - x)` so neither jug ever overflows).
4. **Implement Recursive DFS & Backtracking:** Loop through `for new_x, new_y in states:` and call `dfs(new_x, new_y)`. If a branch fails to reach the goal, call `path.pop()` to backtrack cleanly.
5. **Run with `jug1 = 4`, `jug2 = 3`, `target = 2`:** Press **F5** to see the 7-step solution path!

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Administrator\AppData\Local\Programs\Python\Python313\Pract 3.py`

#### 5. Fully Written Code Blocks
```python
def water_jug_dfs(cap1, cap2, target):
    visited = set()
    path = []

    def dfs(x, y):
        # Goal state: check if either Jug 1 (x) or Jug 2 (y) has the target amount
        if x == target or y == target:
            path.append((x, y))
            return True

        # Avoid repeating states we have already explored
        if (x, y) in visited:
            return False

        visited.add((x, y))
        path.append((x, y))

        # Generate all 6 possible next states
        # 1. Fill Jug 1 completely
        states = [(cap1, y)]

        # 2. Fill Jug 2 completely
        states.append((x, cap2))

        # 3. Empty Jug 1
        states.append((0, y))

        # 4. Empty Jug 2
        states.append((x, 0))

        # 5. Pour Jug 1 into Jug 2 (until Jug 1 is empty or Jug 2 is full)
        amount = min(x, cap2 - y)
        states.append((x - amount, y + amount))

        # 6. Pour Jug 2 into Jug 1 (until Jug 2 is empty or Jug 1 is full)
        amount = min(y, cap1 - x)
        states.append((x + amount, y - amount))

        # Explore next states using DFS recursion
        for new_x, new_y in states:
            if dfs(new_x, new_y):
                return True

        # Backtracking: remove current state if no path was found from here
        path.pop()
        return False

    # Start DFS from initial state (0, 0) where both jugs are empty
    if dfs(0, 0):
        print("Solution Found:")
        for state in path:
            print(state)
    else:
        print("No solution exists.")


# Main Program
jug1 = 4
jug2 = 3
target = 2

water_jug_dfs(jug1, jug2, target)
```

**Expected Output:**
```text
Solution Found:
(0, 0)
(4, 0)
(4, 3)
(0, 3)
(3, 0)
(3, 3)
(4, 2)
```
*(How the final step `(4, 2)` works: From `(3, 3)`, we pour 1 liter from Jug 2 into Jug 1 to top off Jug 1 at 4L, leaving exactly **2 liters** inside Jug 2!)*

#### 6. Next Steps / Follow-up
* **Try this next:** What if you have a **5-liter jug** (`jug1 = 5`) and a **3-liter jug** (`jug2 = 3`), and you want to measure **4 liters** (`target = 4`)? Change those three numbers at the bottom of your script and run it to see DFS solve the 5L/3L puzzle!

---

### 4. Practical No. 4 (from `Practical 4.pdf`): Uniform Cost Search (UCS) on the Romania Map

#### 1. Practical Aim & Topic Breakdown
* **Aim:** To implement Uniform Cost Search (UCS) in Python to find the least-cost path from `ARAD` to `BUCHAREST` in a weighted graph.
* **What Topic Is This Practical?** This practical covers **Uniform Cost Search (UCS)**, an uninformed search algorithm designed for **weighted graphs** (where different roads have different kilometer distances):
  * While BFS (Practical 2) counts only the *number of steps*, **UCS** always expands the city with the **lowest cumulative distance (cost) traveled so far** from the starting city.
  * To do this efficiently, UCS uses a **Priority Queue (`heapq`)** that automatically pops the lowest-cost path first.
  * On the Romania road map, going `ARAD -> SIBIU -> FAGARAS -> BUCHAREST` takes only 3 hops, but costs $140 + 99 + 211 = 450\text{ km}$. UCS discovers a 4-hop route—`ARAD -> SIBIU -> RIMNICU VILCEA -> PITESTI -> BUCHAREST`—that costs only **$418\text{ km}$** ($140 + 80 + 97 + 101 = 418$)!

#### 2. Direct & Encouraging Overview
We will represent the Romania map as a nested dictionary of cities and road distances (`graph`), use Python's built-in `heapq` priority queue to always explore the cheapest cumulative route next, and print both the optimal route from `ARAD` to `BUCHAREST` and its exact total distance in kilometers.

#### 3. Step-by-Step Instructions
1. **No external packages required:** `heapq` is built right into Python's standard library.
2. **Open Python IDLE:** Create a new script named `Pract4.py`.
3. **Build the Weighted Graph:** Create a dictionary `graph` where each city maps to its neighboring cities and their road distances in kilometers.
4. **Write the `ucs(start, goal)` Function:** Store tuples of `(cost, city, path)` inside `queue`. Because `cost` is the first item in the tuple, `heapq.heappop(queue)` automatically selects the path with the smallest total kilometer cost!
5. **Run & Verify:** Press **F5** to see the shortest route and the `418 km` total cost.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\ictc\Desktop\AI Pract\Pract4.py`

#### 5. Fully Written Code Blocks
```python
import heapq

# Step 1: Represent the Romania road map as a weighted graph (distances in km)
graph = {
    'ARAD': {'ZERIND': 75, 'SIBIU': 140, 'TIMISOARA': 118},
    'ZERIND': {'ARAD': 75, 'ORADEA': 71},
    'ORADEA': {'ZERIND': 71, 'SIBIU': 151},
    'TIMISOARA': {'ARAD': 118, 'LUGOJ': 111},
    'LUGOJ': {'TIMISOARA': 111, 'MEHADIA': 70},
    'MEHADIA': {'LUGOJ': 70, 'DROBETA': 75},
    'DROBETA': {'MEHADIA': 75, 'CRAIOVA': 120},
    'CRAIOVA': {'DROBETA': 120, 'RIMNICU VILCEA': 146, 'PITESTI': 138},
    'SIBIU': {'ARAD': 140, 'ORADEA': 151,
              'FAGARAS': 99, 'RIMNICU VILCEA': 80},
    'RIMNICU VILCEA': {'SIBIU': 80, 'CRAIOVA': 146, 'PITESTI': 97},
    'FAGARAS': {'SIBIU': 99, 'BUCHAREST': 211},
    'PITESTI': {'RIMNICU VILCEA': 97,
                'CRAIOVA': 138, 'BUCHAREST': 101},
    'BUCHAREST': {'FAGARAS': 211, 'PITESTI': 101}
}

# Step 2: Implement Uniform Cost Search (UCS) using a Priority Queue
def ucs(start, goal):
    # Priority queue stores (cumulative_cost, current_city, path_list)
    queue = [(0, start, [start])]
    visited = set()

    while queue:
        # Pop the path with the lowest cumulative cost so far
        cost, city, path = heapq.heappop(queue)

        if city in visited:
            continue
        visited.add(city)

        # If we reached the destination city, return the optimal path and total cost
        if city == goal:
            return path, cost

        # Add all neighboring cities to the priority queue with updated cumulative cost
        for neighbor, distance in graph[city].items():
            heapq.heappush(
                queue,
                (cost + distance, neighbor, path + [neighbor])
            )

# Step 3: Find the least-cost path from ARAD to BUCHAREST
path, cost = ucs('ARAD', 'BUCHAREST')

print("Least Cost Path:", " -> ".join(path))
print("Total Cost:", cost, "km")
```

**Expected Output:**
```text
Least Cost Path: ARAD -> SIBIU -> RIMNICU VILCEA -> PITESTI -> BUCHAREST
Total Cost: 418 km
```

#### 6. Next Steps / Follow-up
* **Try this next:** Change `'ARAD'` in `ucs('ARAD', 'BUCHAREST')` to `'TIMISOARA'` or `'ORADEA'` to find the cheapest driving route to Bucharest from any other city on the Romania map!

---

### 5. Practical No. 5 (from `Pract5.pdf`): Greedy Best-First Search (GBFS) for the 8-Puzzle Problem

#### 1. Practical Aim & Topic Breakdown
* **Aim:** To implement Greedy Best-First Search for solving the 8-puzzle problem using the Manhattan Distance heuristic.
* **What Topic Is This Practical?** This practical introduces **Informed (Heuristic) Search** via **Greedy Best-First Search (GBFS)**:
  * Uninformed searches like BFS (Practical 2) and DFS (Practical 3) search "blindly" without knowing whether a move brings the puzzle closer to or further from the goal.
  * **Greedy Best-First Search (GBFS)** uses a **heuristic function $h(n)$**—an educated estimate of how close a board state $n$ is to the goal state—and **always expands the state with the smallest $h(n)$ first** ($f(n) = h(n)$).
  * **Manhattan Distance Heuristic:** For every numbered tile (`1` to `8`, ignoring the blank tile `0`), we count how many rows plus how many columns away it is from its goal position:
    $$\text{Manhattan Distance} = |\text{current row} - \text{goal row}| + |\text{current column} - \text{goal column}|$$
    Adding this up across all 8 tiles gives the total Manhattan Distance $h(n)$ for the board!

#### 2. Direct & Encouraging Overview
We will write a `manhattan(state, goal)` function using Python's handy `divmod(index, 3)` (which converts a 0–8 index directly into `(row, column)` coordinates on a $3 \times 3$ grid!), generate valid neighbor moves with `get_neighbors(state)`, and use `heapq` in `greedy_best_first(start, goal)` to always pick the board with the lowest Manhattan Distance $h(n)$.

#### 3. Step-by-Step Instructions
1. **No external packages required:** We use Python's built-in `heapq` module.
2. **Open Python IDLE:** Create a new script named `Pract5.py`.
3. **Write `manhattan(state, goal)`:** Loop through indices `0` to `8`. Whenever `state[i] != 0` (not the blank space), use `divmod(i, 3)` to get `(current_row, current_col)` and `divmod(goal_pos, 3)` to get `(goal_row, goal_col)`, then add their absolute row and column differences.
4. **Write `get_neighbors(state)`:** Find the `(row, col)` of `0` and slide it Up `(-1, 0)`, Down `(1, 0)`, Left `(0, -1)`, or Right `(0, 1)` whenever the new coordinates stay inside the $3 \times 3$ grid (`0 <= new_row < 3` and `0 <= new_col < 3`).
5. **Run GBFS:** Push `(h, start, [start])` into `priority_queue` and press **F5** to see the solution steps!

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\ictc\Desktop\AI Pract\Practical 5\Pract5.py`

#### 5. Fully Written Code Blocks
```python
import heapq

# Step 1: Calculate Manhattan Distance heuristic h(n)
def manhattan(state, goal):
    distance = 0

    for i in range(9):
        if state[i] != 0:  # Ignore the blank tile (0)
            current_row, current_col = divmod(i, 3)
            goal_pos = goal.index(state[i])
            goal_row, goal_col = divmod(goal_pos, 3)

            distance += abs(current_row - goal_row)
            distance += abs(current_col - goal_col)

    return distance

# Step 2: Generate all valid neighboring 8-puzzle states
def get_neighbors(state):
    neighbors = []
    zero = state.index(0)
    row, col = divmod(zero, 3)

    # Possible blank tile moves: Up, Down, Left, Right
    moves = [(-1, 0), (1, 0), (0, -1), (0, 1)]

    for dr, dc in moves:
        new_row = row + dr
        new_col = col + dc

        if 0 <= new_row < 3 and 0 <= new_col < 3:
            new_zero = new_row * 3 + new_col

            new_state = list(state)
            new_state[zero], new_state[new_zero] = \
                new_state[new_zero], new_state[zero]

            neighbors.append(tuple(new_state))

    return neighbors

# Step 3: Greedy Best-First Search (always expands smallest h(n) first)
def greedy_best_first(start, goal):
    priority_queue = []
    h = manhattan(start, goal)

    heapq.heappush(priority_queue, (h, start, [start]))
    visited = set()

    while priority_queue:
        h, state, path = heapq.heappop(priority_queue)

        if state in visited:
            continue

        visited.add(state)

        if state == goal:
            return path

        for neighbor in get_neighbors(state):
            if neighbor not in visited:
                h = manhattan(neighbor, goal)
                heapq.heappush(
                    priority_queue,
                    (h, neighbor, path + [neighbor])
                )

    return None

# Step 4: Define Initial and Goal configurations
start = (1, 2, 3,
         4, 0, 6,
         7, 5, 8)

goal = (1, 2, 3,
        4, 5, 6,
        7, 8, 0)

# Step 5: Solve and display the moves
solution = greedy_best_first(start, goal)

if solution:
    print("Solution found!")
    print("Number of moves:", len(solution) - 1)

    for state in solution:
        print()
        for i in range(0, 9, 3):
            print(state[i:i+3])
else:
    print("No solution found.")
```

**Expected Output:**
```text
Solution found!
Number of moves: 2

(1, 2, 3)
(4, 0, 6)
(7, 5, 8)

(1, 2, 3)
(4, 5, 6)
(7, 0, 8)

(1, 2, 3)
(4, 5, 6)
(7, 8, 0)
```

#### 6. Next Steps / Follow-up
* **Compare with Practical 6 (A* Search):** Greedy Best-First Search only looks at the estimated distance ahead ($h(n)$) and ignores how many moves it has already taken ($g(n)$). Next, in Practical 6, we combine both ($f(n) = g(n) + h(n)$) to build **A* Search**!

---

### 6. Practical No. 6 (from `Practical 6.docx.pdf`): A* Search for the 8-Puzzle Problem

#### 1. Practical Aim & Topic Breakdown
* **Aim:** To write and implement a Python program to find the shortest path for the 8-puzzle problem using the A* search algorithm with Manhattan Distance as the heuristic function.
* **What Topic Is This Practical?** This practical covers the **A* (A-Star) Search Algorithm** on the 8-Puzzle Problem:
  * While Uniform Cost Search (Practical 4) only looks at past cost $g(n)$ and Greedy Best-First Search (Practical 5) only looks at estimated future cost $h(n)$, **A* Search combines both**:
    $$f(n) = g(n) + h(n)$$
    * **$g(n)$:** Actual number of moves taken from the initial board to the current board.
    * **$h(n)$:** Estimated moves remaining to reach the goal (using **Manhattan Distance**).
    * **$f(n)$:** Total estimated cost of the cheapest solution passing through state $n$.
  * Because Manhattan Distance never overestimates the true number of moves required (it is *admissible*), **A* is guaranteed to find the shortest possible path** while exploring far fewer states than BFS!

#### 2. Direct & Encouraging Overview
Building directly on Practical 5, we store `(f, g, current, path)` inside our `priority_queue`. Each time we slide a tile to a neighbor, the actual step count increases by 1 (`new_g = g + 1`), we compute `new_h = manhattan_distance(neighbor, goal)`, and we prioritize states by `new_f = new_g + new_h`.

#### 3. Step-by-Step Instructions
1. **No external packages required:** Uses Python's standard `heapq` library.
2. **Open Python IDLE:** Create a new script named `Pract6.py`.
3. **Define `manhattan_distance` and `get_neighbors`:** Same clean `divmod(index, 3)` grid math as Practical 5.
4. **Implement `a_star(start, goal)`:** Push `(h, 0, start, [start])` into `priority_queue` (where `f = h + 0` and `g = 0`). When expanding neighbors, set `new_g = g + 1`, `new_h = manhattan_distance(neighbor, goal)`, and `new_f = new_g + new_h`.
5. **Run & Inspect Steps:** Press **F5** to see Step 0 through Step 3 printed neatly!

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Rajgad\Desktop\AI\Practical 6\Pract6.py`

#### 5. Fully Written Code Blocks
```python
import heapq

# Step 1: Manhattan Distance Heuristic h(n)
def manhattan_distance(state, goal):
    distance = 0

    for i in range(9):
        if state[i] != 0:
            current_row, current_col = divmod(i, 3)
            goal_index = goal.index(state[i])
            goal_row, goal_col = divmod(goal_index, 3)

            distance += abs(current_row - goal_row) + abs(current_col - goal_col)

    return distance


# Step 2: Generate possible moves of the blank space (0)
def get_neighbors(state):
    neighbors = []
    zero_index = state.index(0)
    row, col = divmod(zero_index, 3)

    moves = [
        (-1, 0),  # Up
        (1, 0),   # Down
        (0, -1),  # Left
        (0, 1)    # Right
    ]

    for dr, dc in moves:
        new_row = row + dr
        new_col = col + dc

        if 0 <= new_row < 3 and 0 <= new_col < 3:
            new_index = new_row * 3 + new_col

            new_state = list(state)
            new_state[zero_index], new_state[new_index] = \
                new_state[new_index], new_state[zero_index]

            neighbors.append(tuple(new_state))

    return neighbors


# Step 3: A* Search Algorithm using f(n) = g(n) + h(n)
def a_star(start, goal):
    priority_queue = []

    # Tuple format in priority queue: (f, g, state, path)
    h = manhattan_distance(start, goal)
    heapq.heappush(priority_queue, (h, 0, start, [start]))

    visited = set()

    while priority_queue:
        f, g, current, path = heapq.heappop(priority_queue)

        if current in visited:
            continue

        visited.add(current)

        # Goal reached
        if current == goal:
            return path

        for neighbor in get_neighbors(current):
            if neighbor not in visited:
                new_g = g + 1
                new_h = manhattan_distance(neighbor, goal)
                new_f = new_g + new_h

                heapq.heappush(
                    priority_queue,
                    (new_f, new_g, neighbor, path + [neighbor])
                )

    return None


# Step 4: Helper function to print the 3x3 puzzle board
def print_puzzle(state):
    for i in range(0, 9, 3):
        print(state[i:i+3])
    print()


# Step 5: Initial and goal configurations
start = (1, 2, 3,
         0, 4, 6,
         7, 5, 8)

goal = (1, 2, 3,
        4, 5, 6,
        7, 8, 0)

# Step 6: Find shortest path using A*
path = a_star(start, goal)

if path:
    print("Shortest path found!")
    print("Number of moves:", len(path) - 1)
    print("\nSteps:")

    for step, state in enumerate(path):
        print("Step", step)
        print_puzzle(state)
else:
    print("No solution exists.")
```

**Expected Output:**
```text
Shortest path found!
Number of moves: 3

Steps:
Step 0
(1, 2, 3)
(0, 4, 6)
(7, 5, 8)

Step 1
(1, 2, 3)
(4, 0, 6)
(7, 5, 8)

Step 2
(1, 2, 3)
(4, 5, 6)
(7, 0, 8)

Step 3
(1, 2, 3)
(4, 5, 6)
(7, 8, 0)
```

#### 6. Next Steps / Follow-up
* **Try this next:** Want to see why A* is smarter than Greedy Best-First Search? Try giving both `Pract5.py` and `Pract6.py` a harder starting board like `(8, 1, 2, 0, 4, 3, 7, 6, 5)` or `(1, 2, 3, 7, 4, 6, 0, 5, 8)` and compare the number of moves they find!

---

### 7. Practical No. 7 (from `Practical 7.docx.pdf`): A* Search on the Romania Map (Straight-Line Distance Heuristic)

#### 1. Practical Aim & Topic Breakdown
* **Aim:** To write and implement a Python program to find the shortest path from `Arad` to `Bucharest` using the A* search algorithm, where the straight-line distance to Bucharest is used as the heuristic function.
* **What Topic Is This Practical?** In Practical 4, we solved the Romania map with **Uniform Cost Search (UCS)** using only road distances traveled so far ($g(n)$). Here in **Practical 7**, we upgrade to **A* Search** by adding a geographic heuristic $h(n)$: the **Straight-Line Distance (SLD)** ("as the crow flies") from each city directly to Bucharest!
  * **Evaluation Function:** $f(n) = g(n) + h(n)$
    * **$g(n)$:** Actual road distance driven from `Arad` to the current city.
    * **$h(n)$:** Straight-line distance from the current city to `Bucharest` (e.g., `Arad` = $366\text{ km}$, `Sibiu` = $253\text{ km}$, `Rimnicu Vilcea` = $193\text{ km}$, `Pitesti` = $100\text{ km}$, `Bucharest` = $0\text{ km}$).
  * Because a straight line is the shortest possible distance between any two points on a map, $h(n)$ never overestimates the true driving distance—so A* heads straight toward Bucharest and finds the optimal **$418\text{ km}$** route (`Arad -> Sibiu -> Rimnicu Vilcea -> Pitesti -> Bucharest`) without wasting time exploring cities in the wrong direction!

#### 2. Direct & Encouraging Overview
We will define two dictionaries: `graph` (storing each city's road connections and kilometer distances) and `heuristic` (storing each city's straight-line distance to Bucharest). Then our `a_star(start, goal)` function uses `heapq` and a `cost_so_far` dictionary to track the best $g(n)$ distance to each city, prioritizing cities with the lowest total estimated distance `new_f = new_g + heuristic[neighbor]`.

#### 3. Step-by-Step Instructions
1. **No external packages required:** Uses Python's standard `heapq` module.
2. **Open Python IDLE:** Create a new script named `Pract7.py`.
3. **Define `graph` and `heuristic`:** Enter the Romania road network in `graph` and the 20 city straight-line distances to Bucharest in `heuristic`.
4. **Implement `a_star(start, goal)`:** Initialize `queue = [(heuristic[start], 0, start, [start])]` and `cost_so_far = {start: 0}`. Whenever a neighbor has a cheaper `new_g` than seen before, update `cost_so_far[neighbor] = new_g`, compute `new_f = new_g + heuristic[neighbor]`, and push to the priority queue.
5. **Run & Verify:** Press **F5** to see the optimal path and `418 km` total distance.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Rajgad\Desktop\AI\Practical 7\Pract7.py`

#### 5. Fully Written Code Blocks
```python
import heapq

# Step 1: Weighted Romania road map (city: [(neighbor, road_distance_km), ...])
graph = {
    'Arad': [('Zerind', 75), ('Sibiu', 140), ('Timisoara', 118)],
    'Zerind': [('Arad', 75), ('Oradea', 71)],
    'Oradea': [('Zerind', 71), ('Sibiu', 151)],
    'Sibiu': [('Arad', 140), ('Oradea', 151), ('Fagaras', 99),
              ('Rimnicu Vilcea', 80)],
    'Timisoara': [('Arad', 118), ('Lugoj', 111)],
    'Lugoj': [('Timisoara', 111), ('Mehadia', 70)],
    'Mehadia': [('Lugoj', 70), ('Dobreta', 75)],
    'Dobreta': [('Mehadia', 75), ('Craiova', 120)],
    'Craiova': [('Dobreta', 120), ('Rimnicu Vilcea', 146),
                ('Pitesti', 138)],
    'Rimnicu Vilcea': [('Sibiu', 80), ('Craiova', 146),
                       ('Pitesti', 97)],
    'Fagaras': [('Sibiu', 99), ('Bucharest', 211)],
    'Pitesti': [('Rimnicu Vilcea', 97), ('Craiova', 138),
                ('Bucharest', 101)],
    'Bucharest': [('Fagaras', 211), ('Pitesti', 101),
                  ('Giurgiu', 90), ('Urziceni', 85)],
    'Giurgiu': [('Bucharest', 90)],
    'Urziceni': [('Bucharest', 85), ('Hirsova', 98),
                 ('Vaslui', 142)],
    'Hirsova': [('Urziceni', 98), ('Eforie', 86)],
    'Eforie': [('Hirsova', 86)],
    'Vaslui': [('Urziceni', 142), ('Iasi', 92)],
    'Iasi': [('Vaslui', 92), ('Neamt', 87)],
    'Neamt': [('Iasi', 87)]
}

# Step 2: Straight-Line Distance (SLD) heuristic h(n) to Bucharest (in km)
heuristic = {
    'Arad': 366,
    'Zerind': 374,
    'Oradea': 380,
    'Sibiu': 253,
    'Timisoara': 329,
    'Lugoj': 244,
    'Mehadia': 241,
    'Dobreta': 242,
    'Craiova': 160,
    'Rimnicu Vilcea': 193,
    'Fagaras': 176,
    'Pitesti': 100,
    'Bucharest': 0,
    'Giurgiu': 77,
    'Urziceni': 80,
    'Hirsova': 151,
    'Eforie': 161,
    'Vaslui': 199,
    'Iasi': 226,
    'Neamt': 234
}

# Step 3: Implement A* Search Algorithm using f(n) = g(n) + h(n)
def a_star(start, goal):
    # Queue stores tuples of (f, g, current_city, path_list)
    queue = [(heuristic[start], 0, start, [start])]
    cost_so_far = {start: 0}

    while queue:
        f, g, current, path = heapq.heappop(queue)

        if current == goal:
            return path, g

        for neighbor, distance in graph[current]:
            new_g = g + distance

            if neighbor not in cost_so_far or new_g < cost_so_far[neighbor]:
                cost_so_far[neighbor] = new_g
                new_f = new_g + heuristic[neighbor]

                heapq.heappush(
                    queue,
                    (new_f, new_g, neighbor, path + [neighbor])
                )

    return None, None

# Step 4: Find the shortest path from Arad to Bucharest
start = 'Arad'
goal = 'Bucharest'

path, distance = a_star(start, goal)

if path:
    print("Shortest path:")
    print(" -> ".join(path))
    print("Total distance:", distance, "km")
else:
    print("No path exists.")
```

**Expected Output:**
```text
Shortest path:
Arad -> Sibiu -> Rimnicu Vilcea -> Pitesti -> Bucharest
Total distance: 418 km
```

#### 6. Next Steps / Follow-up
* **Compare Practical 4 (UCS) vs. Practical 7 (A*):** Both found the exact same `418 km` route (`Arad -> Sibiu -> Rimnicu Vilcea -> Pitesti -> Bucharest`), but A* used the `heuristic` dictionary to steer directly toward Bucharest instead of expanding side cities like `Timisoara` or `Zerind`!

---

### 8. Practical No. 8 (from `Practical No 8.pdf`): Bayes' Rule for Medical Diagnosis

*(Note: The PDF heading says "Practical No. 9", while the code and filename are `Pract8.py` — "# Practical 8: Bayes' Rule Application".)*

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Write a Python program to calculate the probability that a person actually has a disease given that the medical test result is positive using Bayes' Rule.
* **What Topic Is This Practical?** This practical teaches **Bayes' Theorem (Bayes' Rule)**, one of the most important probability formulas in AI and medical diagnosis:
  $$P(D \mid +) = \frac{P(+ \mid D) \times P(D)}{P(+)}$$
  * **Why is this surprising?** Suppose a disease is rare: only **$1\%$ ($0.01$)** of people have it ($P(D) = 0.01$). The test is **$99\%$ ($0.99$)** accurate when someone has the disease ($P(+ \mid D) = 0.99$), and has a **$5\%$ ($0.05$)** false-positive rate on healthy people ($P(+ \mid \neg D) = 0.05$).
  * If you test positive, do you have a $99\%$ chance of having the disease? **No!** Because $99\%$ of the population is healthy, the $5\%$ false positives ($0.05 \times 0.99 = 0.0495$) outnumber the true positives ($0.99 \times 0.01 = 0.0099$). Bayes' Rule shows your actual probability of having the disease is only **$16.67\%$**!

#### 2. Direct & Encouraging Overview
We will write a clean, super-readable Python script that stores the three given probabilities (`P_D`, `P_positive_D`, and `P_positive_not_D`), calculates the total probability of testing positive (`P_positive`), and applies Bayes' Rule to print both the raw probability (`0.1666...`) and the percentage (`16.67%`).

#### 3. Step-by-Step Instructions
1. **No external libraries needed:** This practical uses pure Python arithmetic.
2. **Open Python IDLE:** Create a new script named `Pract8.py`.
3. **Define Given Probabilities:** Set `P_D = 0.01` ($1\%$ disease rate), `P_positive_D = 0.99` ($99\%$ true positive rate), and `P_positive_not_D = 0.05` ($5\%$ false positive rate).
4. **Calculate Total Positive Rate `P(+)`:** First find `P_not_D = 1 - P_D` ($0.99$), then combine true positives and false positives: `P_positive = (P_positive_D * P_D) + (P_positive_not_D * P_not_D)`.
5. **Apply Bayes' Rule:** Divide `(P_positive_D * P_D)` by `P_positive` and press **F5** to run.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Administrator\Desktop\AI\Pract8.py`

#### 5. Fully Written Code Blocks
```python
# Practical 8: Bayes' Rule Application

# Step 1: Given probabilities from the medical scenario
P_D = 0.01               # P(D): Probability a person has the disease (1%)
P_positive_D = 0.99      # P(+|D): Probability of positive test given disease (99%)
P_positive_not_D = 0.05  # P(+|not D): False positive rate when healthy (5%)

# Step 2: Probability of NOT having the disease P(not D) = 1 - 0.01 = 0.99
P_not_D = 1 - P_D

# Step 3: Total probability of getting a positive test result P(+)
# P(+) = [P(+|D) * P(D)] + [P(+|not D) * P(not D)]
P_positive = (P_positive_D * P_D) + (P_positive_not_D * P_not_D)

# Step 4: Apply Bayes' Rule: P(D|+) = [P(+|D) * P(D)] / P(+)
P_D_positive = (P_positive_D * P_D) / P_positive

# Step 5: Display the result as a decimal and percentage
print("Probability that the person actually has the disease:")
print(P_D_positive)

print("Percentage:", P_D_positive * 100, "%")
```

**Expected Output:**
```text
Probability that the person actually has the disease:
0.16666666666666669
Percentage: 16.666666666666668 %
```

#### 6. Next Steps / Follow-up
* **Try this next:** What if the false positive rate of the lab test is improved from $5\%$ (`0.05`) down to $1\%$ (`0.01`)? Change `P_positive_not_D = 0.01` and run the code—you'll see the probability jump from $16.67\%$ to $50\%$!

---

### 9. Practical No. 9 (from `Practical No 11.pdf`): Bayesian Network Inference

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Write a Python program to calculate the posterior probability of burglary using a Bayesian Network and the `pgmpy` library in Python.
* **What Topic Is This Practical?** This practical covers **Bayesian Networks (Probabilistic Graphical Models)**. In real life, multiple events are connected by cause and effect. Here, two independent events—a **Burglary** or an **Earthquake**—can both trigger a house **Alarm** to ring. If your alarm goes off (`Alarm = True`), how likely is it that a burglary actually happened? Finding the probability of a hidden cause after observing evidence is called calculating the **posterior probability**, written mathematically as $P(\text{Burglary} \mid \text{Alarm} = \text{True})$.

#### 2. Direct & Encouraging Overview
We are building a cause-and-effect probability model in Python using `pgmpy`. We will connect `Burglary` and `Earthquake` as causes of `Alarm`, feed in their probability tables (Conditional Probability Distributions or CPDs), verify that our network is mathematically valid, and ask Python to calculate the exact chance of a burglary given that the alarm rang.

#### 3. Step-by-Step Instructions
1. **Install the required library:** Open Command Prompt (Windows) or Terminal and install `pgmpy` by running:
   `py -3.13 -m pip install pgmpy`
2. **Open Python IDLE:** Launch IDLE (Python 3.13) and click **File > New File** to open a blank script editor.
3. **Define the Network Structure:** Create a `DiscreteBayesianNetwork` linking `("Burglary", "Alarm")` and `("Earthquake", "Alarm")`.
4. **Add Probability Tables (`TabularCPD`):** Define the base probability of a Burglary (`0.001`), an Earthquake (`0.002`), and the conditional probabilities of the Alarm ringing for every combination of Burglary and Earthquake.
5. **Run Inference:** Use `VariableElimination` to query `"Burglary"` with `evidence={"Alarm": 1}` and press **F5** to run your script.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Administrator\Desktop\AI\AI.py`

#### 5. Fully Written Code Blocks
```python
import warnings
# Hide future warning messages to keep our output clean
warnings.filterwarnings("ignore", category=FutureWarning)

from pgmpy.models import DiscreteBayesianNetwork
from pgmpy.factors.discrete import TabularCPD
from pgmpy.inference import VariableElimination

# Step 1: Create the Bayesian Network structure (Cause -> Effect)
# Both Burglary and Earthquake can cause the Alarm to go off
model = DiscreteBayesianNetwork([
    ("Burglary", "Alarm"),
    ("Earthquake", "Alarm")
])

# Step 2: Define Probability Table for Burglary (0 = False: 99.9%, 1 = True: 0.1%)
burglary = TabularCPD(
    variable="Burglary",
    variable_card=2,
    values=[[0.999], [0.001]]
)

# Step 3: Define Probability Table for Earthquake (0 = False: 99.8%, 1 = True: 0.2%)
earthquake = TabularCPD(
    variable="Earthquake",
    variable_card=2,
    values=[[0.998], [0.002]]
)

# Step 4: Define Conditional Probability Table for Alarm given Burglary and Earthquake
# Columns correspond to (Burglary, Earthquake): (0,0), (0,1), (1,0), (1,1)
alarm = TabularCPD(
    variable="Alarm",
    variable_card=2,
    values=[
        [0.999, 0.71, 0.06, 0.05],  # Probability Alarm = 0 (Off)
        [0.001, 0.29, 0.94, 0.95]   # Probability Alarm = 1 (On)
    ],
    evidence=["Burglary", "Earthquake"],
    evidence_card=[2, 2]
)

# Step 5: Attach all probability tables to our model and validate
model.add_cpds(burglary, earthquake, alarm)
print("Model valid:", model.check_model())

# Step 6: Calculate Posterior Probability P(Burglary | Alarm = 1)
inference = VariableElimination(model)
result = inference.query(
    variables=["Burglary"],
    evidence={"Alarm": 1}
)

print(result)
```

**Expected Output:**
```text
Model valid: True
+-------------+-----------------+
| Burglary    |   phi(Burglary) |
+=============+=================+
| Burglary(0) |          0.6264 |
+-------------+-----------------+
| Burglary(1) |          0.3736 |
+-------------+-----------------+
```
*(Interpretation: When the alarm rings, there is a **37.36%** chance of a burglary (`Burglary(1)`) and a **62.64%** chance of no burglary (`Burglary(0)`).)*

#### 6. Next Steps / Follow-up
* **Try this next:** What happens to the probability of a burglary if the alarm rings **and** you also feel an earthquake (`evidence={"Alarm": 1, "Earthquake": 1}`)? Try adding `"Earthquake": 1` to the `evidence` dictionary to see how the probability shifts!

---

### 10. Practical No. 12 (1) (from `Practical No 12(1).pdf`): Basic Machine Learning Workflow

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Using any small dataset, write a Python program to demonstrate the basic Machine Learning workflow.
* **What Topic Is This Practical?** This practical teaches the **Standard 8-Step Machine Learning Pipeline**. Before a computer can learn from raw spreadsheet data, we have to prepare the data properly:
  1. **Load Data:** Read a CSV file (`student.csv`) using `pandas`.
  2. **Label Encoding (`LabelEncoder`):** Machine learning models only understand numbers, not words. We convert text labels (`"Pass"` / `"Fail"`) into numbers (`1` and `0`).
  3. **Feature Scaling (`StandardScaler`):** Since `"Attendance"` (60–95) has much bigger numbers than `"Hours_Studied"` (1–10), we standardize both columns onto a balanced scale so neither column unfairly dominates the model.
  4. **Train/Test Split, Training & Evaluation:** We hold back 30% of the data for testing, train a **K-Nearest Neighbors (`KNeighborsClassifier`)** model on the remaining 70%, and check its accuracy score.

#### 2. Direct & Encouraging Overview
You are building a complete end-to-end ML pipeline from scratch! We will load a small student dataset containing study hours and attendance, clean and scale the data, train a classifier to predict whether a student passes or fails, and measure how accurate our model is on both training and test data.

#### 3. Step-by-Step Instructions
1. **Install Required Packages:** Open Command Prompt and run:
   * `py -3.13 -m pip install pandas`
   * `py -3.13 -m pip install scikit-learn`
2. **Create the Dataset (`student.csv`):** Open Notepad, paste the CSV data below, and save it as `student.csv` in your `Downloads` folder:
   ```csv
   Hours_Studied,Attendance,Result
   1,60,Fail
   2,65,Fail
   3,70,Fail
   4,72,Pass
   5,75,Pass
   6,80,Pass
   7,82,Pass
   8,85,Pass
   9,90,Pass
   10,95,Pass
   ```
3. **Write and Run the Script:** Open Python IDLE, create `Pract12(1).py`, paste the Python code below, and press **F5**.

#### 4. File Paths Included
* **Dataset File Path:** `C:\Users\Student 048\Downloads\student.csv`
* **Python Script Path:** `C:\Users\Student 048\Desktop\AI\Practical 12\12.1\Pract12(1).py`

#### 5. Fully Written Code Blocks
```python
import pandas as pd
from sklearn.preprocessing import LabelEncoder, StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import accuracy_score

# Step 1: Load dataset from CSV
data = pd.read_csv("C:\\Users\\Student 048\\Downloads\\student.csv")

print("Dataset:")
print(data)

# Step 2: Convert text labels ("Pass"/"Fail") into numbers (1/0)
le = LabelEncoder()
data["Result"] = le.fit_transform(data["Result"])

# Step 3: Separate Input features (X) and Output target (y)
X = data[["Hours_Studied", "Attendance"]]
y = data["Result"]

# Step 4: Preprocess inputs by scaling them to a standard range
scaler = StandardScaler()
X = scaler.fit_transform(X)

# Step 5: Split data into 70% training and 30% testing sets
X_train, X_test, y_train, y_test = train_test_split(
    X, y,
    test_size=0.3,
    random_state=1
)

# Step 6: Create and train the KNN classifier model
model = KNeighborsClassifier()
model.fit(X_train, y_train)

# Step 7: Make predictions on both training and test sets
train_pred = model.predict(X_train)
test_pred = model.predict(X_test)

# Step 8: Calculate and display accuracy percentages
print("\nTraining Accuracy:",
      accuracy_score(y_train, train_pred) * 100)

print("Testing Accuracy:",
      accuracy_score(y_test, test_pred) * 100)
```

**Expected Output:**
```text
Dataset:
   Hours_Studied  Attendance Result
0              1          60   Fail
1              2          65   Fail
2              3          70   Fail
3              4          72   Pass
4              5          75   Pass
5              6          80   Pass
6              7          82   Pass
7              8          85   Pass
8              9          90   Pass
9             10          95   Pass

Training Accuracy: 71.42857142857143
Testing Accuracy: 66.66666666666666
```

#### 6. Next Steps / Follow-up
* **Try this next:** Notice how `KNeighborsClassifier()` defaults to looking at 5 neighbors (`n_neighbors=5`), which is quite large for a tiny 7-row training set! Try changing `KNeighborsClassifier()` to `KNeighborsClassifier(n_neighbors=3)` and see how much your training and testing accuracy improve.

---

### 11. Practical No. 12 (2) (from `Practical No 12(2).pdf`): Linear Regression

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Using a suitable regression dataset, implement Linear Regression using Scikit-Learn.
* **What Topic Is This Practical?** This practical covers **Linear Regression**, a supervised learning algorithm used to predict a **continuous numerical value** (like exam marks, house prices, or temperature) rather than a category. It works by drawing the best-fitting straight line ($y = mx + c$) through your data points to capture the relationship between **Hours Studied** (input $X$) and **Marks Scored** (output $y$).

#### 2. Direct & Encouraging Overview
We will load a CSV file of student study hours and exam marks (`student_marks.csv`), train a `LinearRegression` model to learn the trend between hours studied and marks earned, evaluate its accuracy score ($R^2$ score), and predict the exact marks for a student who studies for **11 hours**.

#### 3. Step-by-Step Instructions
1. **Prepare `student_marks.csv`:** Save a CSV file named `student_marks.csv` in your `Downloads` folder with columns `Hours` and `Marks`.
2. **Open Python IDLE:** Create a new script file named `Pract12(2).py`.
3. **Load & Split Data:** Use `pd.read_csv()` to load the file, assign `X = data[["Hours"]]` and `y = data["Marks"]`, and split into 70% training and 30% testing sets.
4. **Train & Predict:** Fit `LinearRegression()` on the training data, print the training/testing scores, and predict the score for `[[11]]` hours.

#### 4. File Paths Included
* **Dataset File Path:** `C:\Users\Student 048\Downloads\student_marks.csv`
* **Python Script Path:** `C:\Users\Student 048\Desktop\AI\Practical 12\12.2\Pract12(2).py`

#### 5. Fully Written Code Blocks
```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression

# Step 1: Load dataset
data = pd.read_csv("C:\\Users\\Student 048\\Downloads\\student_marks.csv")

# Step 2: Select Input feature (Hours) and Output target (Marks)
X = data[["Hours"]]
y = data["Marks"]

# Step 3: Split dataset into 70% training and 30% testing
X_train, X_test, y_train, y_test = train_test_split(
    X, y,
    test_size=0.3,
    random_state=1
)

# Step 4: Create and train the Linear Regression model
model = LinearRegression()
model.fit(X_train, y_train)

# Step 5: Display R^2 accuracy scores on training and testing sets
print(
    "Training Accuracy:",
    model.score(X_train, y_train) * 100
)

print(
    "Testing Accuracy:",
    model.score(X_test, y_test) * 100
)

# Step 6: Predict marks for a student who studies for 11 hours
new_data = pd.DataFrame(
    [[11]],
    columns=["Hours"]
)

prediction = model.predict(new_data)

print(
    "Predicted Marks for 11 Hours:",
    prediction[0]
)
```

**Expected Output:**
```text
Training Accuracy: 100.0
Testing Accuracy: 100.0
Predicted Marks for 11 Hours: 85.0
```

#### 6. Next Steps / Follow-up
* **Try this next:** Want to see the exact mathematical formula your Linear Regression model learned? Add `print("Slope (m):", model.coef_[0])` and `print("Intercept (c):", model.intercept_)` at the end of your script!

---

### 12. Practical No. 12 (3) (from `Practical No 12(3).pdf`): Binary Classification on Handwritten Digits (MNIST)

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Using the MNIST dataset (Digit vs. Not Digit), implement a binary classifier.
* **What Topic Is This Practical?** This practical introduces **Binary Classification** using **Logistic Regression**. While the handwritten digits dataset (`load_digits`) contains 10 classes (digits `0` through `9`), a binary classifier only makes a **Yes/No (True/False)** decision between **two** classes. We convert the 10-digit problem into a binary "5-detector" using `y = (y == 5)`:
  * **Digit is 5** $\rightarrow$ `True`
  * **Digit is NOT 5** (0, 1, 2, 3, 4, 6, 7, 8, 9) $\rightarrow$ `False`

#### 2. Direct & Encouraging Overview
No external CSV file is needed here! We will load Scikit-Learn's built-in handwritten digits dataset, transform the target labels into `True`/`False` for whether the image is the number `5`, train a `LogisticRegression` model, check its accuracy, and test it on the first sample in our test set.

#### 3. Step-by-Step Instructions
1. **Open Python IDLE:** Create a new script named `Pract12(3).py`.
2. **Load Built-In Digits Data:** Import `load_digits` from `sklearn.datasets` and load the pixel data (`digits.data`) and labels (`digits.target`).
3. **Convert to Binary Target:** Write `y = (y == 5)` so `y` becomes `True` only when the digit is `5`.
4. **Train Logistic Regression:** Initialize `LogisticRegression(max_iter=1000)` (giving the solver up to 1,000 iterations to converge cleanly) and call `model.fit(X_train, y_train)`.
5. **Test a Sample:** Predict on `[X_test[0]]` and use an `if/else` block to print `"Digit is 5"` or `"Digit is not 5"`.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Student 048\Desktop\AI\Practical 12\12.3\Pract12(3).py`

#### 5. Fully Written Code Blocks
```python
from sklearn.datasets import load_digits
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression

# Step 1: Load MNIST-like handwritten digits dataset (built into sklearn)
digits = load_digits()

X = digits.data    # Flattened 8x8 pixel values (64 features per image)
y = digits.target  # Actual digit labels (0 to 9)

# Step 2: Convert into Binary Classification
# True if digit is 5, otherwise False
y = (y == 5)

# Step 3: Split dataset into 70% training and 30% testing sets
X_train, X_test, y_train, y_test = train_test_split(
    X, y,
    test_size=0.3,
    random_state=1
)

# Step 4: Create and train the Logistic Regression binary classifier
model = LogisticRegression(max_iter=1000)
model.fit(X_train, y_train)

# Step 5: Display training and testing accuracy
print(
    "Training Accuracy:",
    model.score(X_train, y_train) * 100
)

print(
    "Testing Accuracy:",
    model.score(X_test, y_test) * 100
)

# Step 6: Predict whether the first test image is a 5 or not
prediction = model.predict([X_test[0]])

if prediction[0]:
    print("Digit is 5")
else:
    print("Digit is not 5")
```

**Expected Output:**
```text
Training Accuracy: 100.0
Testing Accuracy: 98.88888888888889
Digit is not 5
```

#### 6. Next Steps / Follow-up
* **Try this next:** Curious what digit `X_test[0]` actually was? Print `digits.target` before overwriting `y`, or change `y = (y == 5)` to `y = (y == 8)` to build an "8-detector" instead!

---

### 13. Practical No. 12 (4) (from `Practical No 12(4).pdf`): K-Fold Cross-Validation

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Implement K-Fold Cross-Validation on a classification model.
* **What Topic Is This Practical?** This practical covers **K-Fold Cross-Validation**. When you split data only once into training and testing sets, your accuracy score might get lucky (or unlucky) depending on which rows landed in the test set. **K-Fold Cross-Validation** solves this by splitting the dataset into **K equal parts (folds)**—here, $K = 5$:
  * In Round 1, Folds 1–4 train the model and Fold 5 tests it.
  * In Round 2, Folds 1, 2, 3, and 5 train the model and Fold 4 tests it.
  * This repeats **5 times** so every single fold gets a turn as the test set, and we average all 5 scores for a rock-solid, trustworthy performance score.

#### 2. Direct & Encouraging Overview
We will load the classic **Iris flower dataset**, create a **K-Nearest Neighbors (`KNeighborsClassifier`)** model, and use Scikit-Learn's `cross_val_score` with `cv=5` to automatically run 5-fold cross-validation and print both the individual fold scores and their overall average.

#### 3. Step-by-Step Instructions
1. **Open Python IDLE:** Create a new script file named `pract12(4).py`.
2. **Import Tools:** Import `load_iris`, `cross_val_score` from `sklearn.model_selection`, and `KNeighborsClassifier` from `sklearn.neighbors`.
3. **Run 5-Fold Cross-Validation:** Call `cross_val_score(model, X, y, cv=5)`—notice you don't even need `train_test_split` because `cross_val_score` splits the data 5 times automatically!
4. **Calculate the Mean:** Use `round(scores.mean() * 100, 2)` to print the average percentage across all 5 folds.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Student 048\Desktop\AI\Practical 12\12.4\pract12(4).py`

#### 5. Fully Written Code Blocks
```python
from sklearn.datasets import load_iris
from sklearn.model_selection import cross_val_score
from sklearn.neighbors import KNeighborsClassifier

# Step 1: Load the built-in Iris flower dataset
iris = load_iris()

X = iris.data    # Flower measurements (sepal & petal length/width)
y = iris.target  # Flower species (0, 1, or 2)

# Step 2: Create the K-Nearest Neighbors classification model
model = KNeighborsClassifier()

# Step 3: Apply 5-Fold Cross-Validation (splits data into 5 equal folds)
scores = cross_val_score(model, X, y, cv=5)

# Step 4: Print accuracy for each of the 5 folds and the overall average
print("Accuracy scores for each fold:")
print(scores)

print("Average Accuracy:", round(scores.mean() * 100, 2), "%")
```

**Expected Output:**
```text
Accuracy scores for each fold:
[0.96666667 1.         0.93333333 0.96666667 1.        ]
Average Accuracy: 97.33 %
```

#### 6. Next Steps / Follow-up
* **Try this next:** What happens if you use 10 folds instead of 5? Change `cv=5` to `cv=10` and run the script again to see 10 individual fold scores and compare the new average accuracy!

---

### 14. Practical No. 12 (5) (from `Practical No 12(5).pdf`): Decision Tree Classifier

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Implement a Decision Tree Classifier using the Iris or any relevant dataset.
* **What Topic Is This Practical?** This practical covers **Decision Tree Classification**. A Decision Tree works just like a game of "20 Questions" or a flowchart:
  * **Internal Nodes** ask yes/no questions about features (e.g., *"Is petal length < 2.45 cm?"*).
  * **Branches** represent the outcome (`True` or `False`) of each condition.
  * **Leaf Nodes** at the bottom give the final predicted class (which species of Iris flower it is: `0` = Setosa, `1` = Versicolor, `2` = Virginica).

#### 2. Direct & Encouraging Overview
We will load the built-in Iris dataset, split it into training and testing sets, train a `DecisionTreeClassifier`, evaluate how well it learned on both sets, and predict the species class of the first flower in our test set.

#### 3. Step-by-Step Instructions
1. **Open Python IDLE:** Create a new script named `pract12(5).py`.
2. **Import Modules:** Import `load_iris`, `train_test_split`, and `DecisionTreeClassifier` from `sklearn.tree`.
3. **Split & Train:** Split the Iris dataset (`test_size=0.3, random_state=1`), initialize `DecisionTreeClassifier()`, and fit it on `X_train, y_train`.
4. **Evaluate & Predict:** Print the training and testing accuracy percentages and predict the class for `[X_test[0]]`.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Student 048\Desktop\AI\Practical 12\12.5\pract12(5).py`

#### 5. Fully Written Code Blocks
```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier

# Step 1: Load the built-in Iris dataset
iris = load_iris()
X = iris.data
y = iris.target

# Step 2: Split dataset into 70% training and 30% testing sets
X_train, X_test, y_train, y_test = train_test_split(
    X,
    y,
    test_size=0.3,
    random_state=1
)

# Step 3: Create the Decision Tree Classifier model
model = DecisionTreeClassifier()

# Step 4: Train the model using training data
model.fit(X_train, y_train)

# Step 5: Display training and testing accuracy
print("Training Accuracy:", model.score(X_train, y_train) * 100)
print("Testing Accuracy:", model.score(X_test, y_test) * 100)

# Step 6: Predict the flower species class for one test sample
prediction = model.predict([X_test[0]])
print("Predicted Class:", prediction[0])
```

**Expected Output:**
```text
Training Accuracy: 100.0
Testing Accuracy: 95.55555555555556
Predicted Class: 0
```

#### 6. Next Steps / Follow-up
* **Try this next:** Want to print the actual flower name (`"setosa"`) instead of the number `0`? Add `print("Flower Species Name:", iris.target_names[prediction[0]])` right after the last line!

---

### 15. Practical No. 12 (6) (from `Practical No 12(6).pdf`): Decision Tree Regression

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Implement Decision Tree Regression on a regression dataset.
* **What Topic Is This Practical?** In Practical 12(5), we used a Decision Tree to predict *categories* (flower species). In **Decision Tree Regression (`DecisionTreeRegressor`)**, we use that same flowchart tree structure to predict a **continuous numerical value** (student exam marks based on hours studied). Instead of voting on a class label at the leaf nodes, the tree splits the data into groups and predicts the numerical value at the leaf node!

#### 2. Direct & Encouraging Overview
We will load `student_marks.csv` using `pandas`, train a `DecisionTreeRegressor` on `Hours` vs. `Marks`, check its training and testing accuracy scores, and predict the marks for a student who studies for **11 hours**.

#### 3. Step-by-Step Instructions
1. **Verify Dataset Path:** Make sure `student_marks.csv` is saved in your practical folder (`C:\Users\Student 048\Desktop\AI\Practical 12\12.6\student_marks.csv`).
2. **Open Python IDLE:** Create `pract12(6).py` in the same folder.
3. **Load & Split:** Read the CSV with `pd.read_csv(r"...")` (using `r""` raw string so Windows backslashes don't cause escape errors), and split into training and test sets.
4. **Train & Predict:** Fit `DecisionTreeRegressor()` on the training data, print accuracy scores, and predict on `pd.DataFrame([[11]], columns=["Hours"])`.

#### 4. File Paths Included
* **Dataset File Path:** `C:\Users\Student 048\Desktop\AI\Practical 12\12.6\student_marks.csv`
* **Python Script Path:** `C:\Users\Student 048\Desktop\AI\Practical 12\12.6\pract12(6).py`

#### 5. Fully Written Code Blocks
```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor

# Step 1: Load dataset using a raw string path (r"...")
data = pd.read_csv(
    r"C:\Users\Student 048\Desktop\AI\Practical 12\12.6\student_marks.csv"
)

# Step 2: Define Input feature (Hours) and Output target (Marks)
X = data[["Hours"]]
y = data["Marks"]

# Step 3: Split dataset into 70% training and 30% testing sets
X_train, X_test, y_train, y_test = train_test_split(
    X,
    y,
    test_size=0.3,
    random_state=1
)

# Step 4: Create and train the Decision Tree Regressor model
model = DecisionTreeRegressor()
model.fit(X_train, y_train)

# Step 5: Display training and testing accuracy scores
print("Training Accuracy:", model.score(X_train, y_train) * 100)
print("Testing Accuracy:", model.score(X_test, y_test) * 100)

# Step 6: Predict marks for 11 hours of study
new_data = pd.DataFrame([[11]], columns=["Hours"])
prediction = model.predict(new_data)

print("Predicted Marks for 11 Hours:", prediction[0])
```

**Expected Output:**
```text
Training Accuracy: 100.0
Testing Accuracy: 87.83783783783784
Predicted Marks for 11 Hours: 75.0
```

#### 6. Next Steps / Follow-up
* **Compare & Contrast:** Notice how **Linear Regression** in Practical 12(2) predicted `85.0` marks for 11 hours (by extending a straight line upward), whereas **Decision Tree Regression** here predicted `75.0` (because a Decision Tree caps predictions at the highest training leaf value it has seen!).

---

### 16. Practical No. 12 (7) (from `Practical No 12(7).pdf`): K-Nearest Neighbors (KNN) Classifier

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Implement K-Nearest Neighbors (KNN) Classifier.
* **What Topic Is This Practical?** This practical focuses on the **K-Nearest Neighbors (KNN)** algorithm. Think of KNN as "tell me who your closest friends are, and I'll tell you who you are." When given a new, mystery flower, KNN measures the distance between its petal/sepal measurements and all flowers in the training set, picks the **3 closest flowers (`n_neighbors=3`)**, and takes a majority vote among those 3 neighbors to decide the species!

#### 2. Direct & Encouraging Overview
We will load the built-in Iris dataset, split it into 70% training and 30% testing data, initialize a `KNeighborsClassifier(n_neighbors=3)` model, train it, check its accuracy, and classify a test sample.

#### 3. Step-by-Step Instructions
1. **Open Python IDLE:** Create a new script named `Pract12(7).py`.
2. **Import Modules:** Import `load_iris`, `train_test_split`, and `KNeighborsClassifier` from `sklearn.neighbors`.
3. **Set `n_neighbors=3`:** Create the model with `model = KNeighborsClassifier(n_neighbors=3)` and fit it on `X_train, y_train`.
4. **Run & Verify:** Press **F5** to see the training accuracy, testing accuracy, and single sample prediction.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Administrator\Desktop\AI\12.7\Pract12(7).py`

#### 5. Fully Written Code Blocks
```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier

# Step 1: Load the built-in Iris dataset
iris = load_iris()

X = iris.data
y = iris.target

# Step 2: Split dataset into 70% training and 30% testing sets
X_train, X_test, y_train, y_test = train_test_split(
    X,
    y,
    test_size=0.3,
    random_state=1
)

# Step 3: Create KNN model looking at the 3 closest neighbors
model = KNeighborsClassifier(n_neighbors=3)

# Step 4: Train the model
model.fit(X_train, y_train)

# Step 5: Display training and testing accuracy percentages
print("Training Accuracy:", model.score(X_train, y_train) * 100)
print("Testing Accuracy:", model.score(X_test, y_test) * 100)

# Step 6: Predict the class of the first test sample
prediction = model.predict([X_test[0]])
print("Predicted Class:", prediction[0])
```

**Expected Output:**
```text
Training Accuracy: 95.23809523809523
Testing Accuracy: 97.77777777777777
Predicted Class: 0
```

#### 6. Next Steps / Follow-up
* **Try this next:** What happens if you change `n_neighbors=3` to `n_neighbors=1` or `n_neighbors=7`? Try testing different odd numbers for `n_neighbors` to see how the training and testing accuracy change!

---

### 17. Practical No. 12 (8) (from `Practical No 12(8).pdf`): Multiclass Classification

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Implement Multiclass Classification using Logistic Regression or Decision Tree.
* **What Topic Is This Practical?** This practical demonstrates **Multiclass Classification**. Unlike Binary Classification (which chooses between only 2 categories, like `Digit 5` vs. `Not Digit 5` in Practical 12(3)), **Multiclass Classification** classifies data into **three or more categories**. Because the Iris dataset has **3 distinct flower species** (`0` = Setosa, `1` = Versicolor, `2` = Virginica), training a `DecisionTreeClassifier` on all three target classes is a direct implementation of multiclass classification.

#### 2. Direct & Encouraging Overview
We will use the Iris dataset (with all 3 flower classes intact), split the data into training and testing sets, train a `DecisionTreeClassifier` to distinguish between all three classes simultaneously, and verify its accuracy and sample prediction.

#### 3. Step-by-Step Instructions
1. **Open Python IDLE:** Create a new script named `Pract 12(8).py`.
2. **Load All 3 Classes:** Load `iris = load_iris()` where `iris.target` contains classes `0`, `1`, and `2`.
3. **Split, Train & Evaluate:** Split the dataset (`test_size=0.3, random_state=1`), train `DecisionTreeClassifier()`, and print training accuracy, testing accuracy, and the predicted class for `[X_test[0]]`.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Administrator\Desktop\AI\12.8\Pract 12(8).py`

#### 5. Fully Written Code Blocks
```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier

# Step 1: Load Iris dataset (contains 3 classes: 0, 1, and 2)
iris = load_iris()
X = iris.data
y = iris.target

# Step 2: Split dataset into 70% training and 30% testing sets
X_train, X_test, y_train, y_test = train_test_split(
    X,
    y,
    test_size=0.3,
    random_state=1
)

# Step 3: Create Decision Tree model for multiclass classification
model = DecisionTreeClassifier()

# Step 4: Train model
model.fit(X_train, y_train)

# Step 5: Display accuracy
print("Training Accuracy:", model.score(X_train, y_train) * 100)
print("Testing Accuracy:", model.score(X_test, y_test) * 100)

# Step 6: Predict one sample across the 3 possible classes
prediction = model.predict([X_test[0]])
print("Predicted Class:", prediction[0])
```

**Expected Output:**
```text
Training Accuracy: 100.0
Testing Accuracy: 95.55555555555556
Predicted Class: 0
```

#### 6. Next Steps / Follow-up
* **Try this next:** Since the Aim says *"using Logistic Regression or Decision Tree"*, you can also swap `from sklearn.tree import DecisionTreeClassifier` with `from sklearn.linear_model import LogisticRegression` and set `model = LogisticRegression(max_iter=200)` to see how Logistic Regression handles multiclass classification!

---

### 18. Practical No. 13 (from `Practical No 13.pdf`): Dataset Bias & Class Imbalance Analysis

#### 1. Practical Aim & Topic Breakdown
* **Aim:** Select any publicly available dataset (for example, Iris, Adult Income, or a classification dataset of your choice) and analyse it for possible bias and class imbalance.
* **What Topic Is This Practical?** This practical covers **AI Ethics & Data Quality: Dataset Bias and Class Imbalance**:
  * **Dataset Bias** happens when collected data doesn't represent all groups fairly or contains missing/skewed records.
  * **Class Imbalance** happens when one category has way more examples than another (e.g., 950 examples of Class 0 and only 50 examples of Class 1), which tricks a model into ignoring the minority class.
  * Here, we load the Iris dataset into a `pandas` table (`DataFrame`), inspect its first 5 rows, check for any missing (`null`) values, count how many flowers belong to each class (`0`, `1`, and `2`), and programmatically check if the minimum class count equals the maximum class count (`50 == 50`) to confirm whether the dataset is **balanced** or **imbalanced**.

#### 2. Direct & Encouraging Overview
Before training any AI model, a good developer inspects the data for fairness and completeness! We will convert the Iris dataset into a `pandas` DataFrame, check its first 5 rows (`head()`), count the exact number of samples per class (`value_counts()`), verify there are zero missing values (`isnull().sum()`), and run an `if/else` check to prove the dataset is balanced.

#### 3. Step-by-Step Instructions
1. **Open Python IDLE:** Create a new script named `pract13.py`.
2. **Convert to DataFrame:** Load `load_iris()`, put `iris.data` into `pd.DataFrame(..., columns=iris.feature_names)`, and add the `"Class"` column (`data["Class"] = iris.target`).
3. **Inspect Records & Missing Values:** Print `data.head()`, `data["Class"].value_counts()`, and `data.isnull().sum()`.
4. **Check Class Balance:** Compare `data["Class"].value_counts().min() == data["Class"].value_counts().max()` to print whether the dataset is balanced or imbalanced.

#### 4. File Paths Included
* **Python Script Path:** `C:\Users\Administrator\Desktop\AI\13\pract13.py`

#### 5. Fully Written Code Blocks
```python
import pandas as pd
from sklearn.datasets import load_iris

# Step 1: Load the built-in Iris dataset
iris = load_iris()

# Step 2: Convert raw data into a structured Pandas DataFrame table
data = pd.DataFrame(
    iris.data,
    columns=iris.feature_names
)

# Add the target species column (0, 1, 2) as "Class"
data["Class"] = iris.target

# Step 3: Inspect the first 5 rows of the dataset
print("First 5 records:")
print(data.head())

# Step 4: Count how many samples belong to each class
print("Class Distribution:")
print(data["Class"].value_counts())

# Step 5: Check if any column has missing (null/empty) values
print("Missing Values:")
print(data.isnull().sum())

# Step 6: Bias & Class Imbalance Analysis
# If the smallest class count equals the largest class count, all classes are equally represented
print("Bias Analysis:")

if data["Class"].value_counts().min() == data["Class"].value_counts().max():
    print("Dataset is balanced.")
else:
    print("Dataset is imbalanced.")
```

**Expected Output:**
```text
First 5 records:
   sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)  Class
0                5.1               3.5                1.4               0.2      0
1                4.9               3.0                1.4               0.2      0
2                4.7               3.2                1.3               0.2      0
3                4.6               3.1                1.5               0.2      0
4                5.0               3.6                1.4               0.2      0
Class Distribution:
Class
0    50
1    50
2    50
Name: count, dtype: int64
Missing Values:
sepal length (cm)    0
sepal width (cm)     0
petal length (cm)    0
petal width (cm)     0
Class                0
dtype: int64
Bias Analysis:
Dataset is balanced.
```

#### 6. Next Steps / Follow-up
* **Try this next:** Want to see what happens when a dataset **is** imbalanced? Add `data = data.iloc[10:]` right before Step 4 (which drops the first 10 rows of Class 0, leaving 40 rows of Class 0 and 50 rows each of Classes 1 and 2) and re-run the script to see it detect the imbalance!
