 🚀 Travelling Salesman Problem Solver (Simulated Annealing)

This project solves the **Travelling Salesman Problem (TSP)** using the **Simulated Annealing (SA)** metaheuristic with a **2-opt neighborhood search**.  
The goal is to find the shortest possible route visiting all cities exactly once and returning to the start.

---

## 📌 Features
- Implements **Simulated Annealing** for optimization.  
- Uses **2-opt algorithm** to generate neighbor solutions.  
- Reads city coordinates from a file (`x y` format).  
- Outputs the **best tour and total cost**.  

---

## 🛠️ Technologies
- **C++** (STL, Random library)  
- Algorithm: **Simulated Annealing + 2-opt**  

---

## 📂 File Format
Your input file (`cities.txt`) should contain city coordinates in the following format:

10 20
30 40
50 60
70 80

yaml
Copy code

Each line = `x y` coordinates of a city.

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YASH-AI6/TSP-SimulatedAnnealing.git
   cd TSP-SimulatedAnnealing
Compile the code:

bash
Copy code
g++ tsp_sa.cpp -o tsp_sa
Run the executable:

bash
Copy code
./tsp_sa
📊 Example Output
rust
Copy code
Best Tour: 0 -> 3 -> 1 -> 2 -> 0
Total Cost: 129.53
🚀 Future Improvements
Add TSPLIB format parser.

Compare results with Genetic Algorithm / Ant Colony Optimization.

Visualize the tours using Python/Matplotlib.

👨‍💻 Author
Yash Saini
https://github.com/YASH-AI6
