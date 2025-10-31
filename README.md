# Regional Supply Chain Optimization (Bay Area Model)

A Python + Gurobi project modeling a **supply chain in Silicon Valley**.  
Products are shipped from factories through local depots to customers while **minimizing total logistics costs** and satisfying all demand.  
Example output shows a **minimum total shipping cost of $260,040**.  

This project demonstrates **linear programming, data modeling, and automated optimization** in a real-world supply chain context.

---

### Project Overview

This notebook builds and solves a realistic supply chain optimization problem for a tech manufacturer operating in **Silicon Valley**.  
Products are shipped from factories (**San Jose** and **Oakland**) through local depots (**Palo Alto, Fremont, San Francisco, Santa Cruz**) to major customers — minimizing total logistics cost by balancing **supply, demand, and throughput constraints**.

---

### Tech
- Python (Jupyter Notebook)  
- Gurobi Optimizer    

---

### What You'll See
- End-to-end supply chain **data modeling**, **LP formulation**, and **automated solution**  
- Clear constraints for factories, depots, and customer demand  
- Example output: all customer demands satisfied with **minimum total shipping cost of $260,040**

---

### How to Run
1. **Clone the repository**
    ```bash
    git clone https://github.com/guroflux/supply-chain-optimization.git
    cd regional-supply-chain
    ```

2. **Install dependencies**  
   Make sure you have Python 3.10+ installed, then run:
    ```bash
    pip install -r requirements.txt
    ```

3. **Ensure Gurobi is installed and licensed**  
   Gurobi requires either a free academic license or a commercial license.

4. **Open the Jupyter Notebook**
    ```bash
    jupyter notebook Minimizing_Costs_in_a_Regional_Supply_Chain.ipynb 
    ```

5. **Run the notebook cells in order** to see the full model, data, and results.
