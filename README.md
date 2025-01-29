# ACO with Levy Flight for PTSPD

🚀 **A Combined Ant Colony Optimization with Levy Flight for the Probabilistic Traveling Salesman Problem with Deadlines (PTSPD)**

This repository contains an implementation of the Ant Colony Optimization (ACO) algorithm enhanced with the **Levy Flight Mechanism** for solving the **Probabilistic Traveling Salesman Problem with Deadlines (PTSPD)**.

---

## 📌 About the Project
The **PTSPD** is a challenging combinatorial optimization problem where a salesman must visit customers who have:
- **Probabilistic availability** (each customer may or may not be available at the time of visit).
- **Deadlines** that must be met to avoid penalties.

To tackle this problem, **Ant Colony Optimization (ACO)** is combined with **Levy Flight**, which helps ants explore the solution space more effectively, avoiding local optima and enhancing performance.

This implementation is based on the research paper "A Combined Ant Colony Optimization with Levy Flight for the Probabilistic Traveling Salesman Problem with Deadlines". The original paper can be accessed [here](https://www.researchgate.net/publication/379629696_A_combined_ant_colony_optimization_with_Levy_flight_mechanism_for_the_probabilistic_traveling_salesman_problem_with_deadlines).

---

## ⚙️ Features
- ✅ **Implementation of ACO with Levy Flight**
- ✅ **Optimized for handling probabilistic constraints**
- ✅ **Comparison between ACO and LFACO**
- ✅ **Python-based simulation and results analysis**

---

## 📖 Methodology
1. **Ant Colony Optimization (ACO)**: Simulates a colony of ants exploring different routes to find the optimal solution.
2. **Levy Flight Mechanism**: Introduces a probabilistic jump behavior to prevent premature convergence.
3. **Performance Evaluation**: The algorithm is tested on different datasets to compare its efficiency against standard ACO.

---

## 📊 Results
The experiment compares **ACO** and **Levy Flight-ACO (LFACO)** based on:
- **Expected travel cost**
- **Quality of solutions in different scenarios (Range & Mixed datasets)**
