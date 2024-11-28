# CSC-333-OR-Linear-Programming-Solutions

Overview
This repository contains solutions for the linear programming (LP) problems assigned in CSC 333 Lab Assignment 1. The solutions include:
1.	Hand-Solved Solutions: Graphical methods showing constraints, feasible regions, and optimal solutions.
2.	Python Solutions: Programmatic and graphical solutions using Python libraries such as matplotlib, NumPy, and SciPy.
Each problem focuses on optimization (maximization or minimization) under given constraints, representing real-world scenarios like profit maximization, cost minimization, and resource allocation.
________________________________________
Instructions for Submission
Requirements
1.	Hand-Solved Solutions:
o	Graphical solution by hand for each LP problem, including constraints and feasible regions.
o	Clearly mark the feasible region and identify the optimal solution.
2.	Python Graphical Solution:
o	Use Python libraries (matplotlib, NumPy, SciPy) to:
	Plot constraints.
	Shade the feasible region.
	Identify corner points of the feasible region.
	Calculate the optimal solution programmatically.
o	Provide Python code as .py files.
3.	GitHub Repository:
o	Store and share all files in a GitHub repository. Include:
	A detailed README file (this document).
	Python scripts for graphical solutions.
	Hand-solved solutions (scanned images or PDFs).
4.	Submission Link:
o	Submit the GitHub repository link via the provided form.
________________________________________
Setup Instructions
Dependencies
Ensure the following Python libraries are installed:
•	matplotlib for plotting.
•	NumPy for numerical operations.
•	SciPy for solving LP problems programmatically.
Install them using:
bash
Copy code
pip install matplotlib numpy scipy
Running the Python Scripts
1.	Clone this repository:
bash
Copy code
git clone https://github.com/<your-username>/CSC-333-OR-Linear-Programming-Solutions.git
cd CSC-333-OR-Linear-Programming-Solutions
2.	Run any of the Python scripts (e.g., problem_1_solution.py) in a code editor or terminal:
bash
Copy code
python problem_1_solution.py
________________________________________
Problem Descriptions
Below are the 10 problems included in the assignment, their objectives, constraints, and expected solutions.
Problem 1: Maximizing Profit for a Factory
Objective: Maximize profit from two products (A and B) under constraints on machine time and raw materials.
Objective Function:
Z=3x+4y(maximize profit)Z = 3x + 4y \quad \text{(maximize profit)}Z=3x+4y(maximize profit)
Constraints:
2x+3y≤12(machine time)x+2y≤8(raw material)x,y≥0(non-negativity).\begin{aligned} 2x + 3y & \leq 12 \quad \text{(machine time)} \\ x + 2y & \leq 8 \quad \text{(raw material)} \\ x, y & \geq 0 \quad \text{(non-negativity)}. \end{aligned}2x+3yx+2yx,y≤12(machine time)≤8(raw material)≥0(non-negativity).
________________________________________
Problem 2: Minimizing Cost for a Manufacturer
Objective: Minimize the production cost of two products (X and Y) under labor and material constraints.
Objective Function:
Z=2x+5y(minimize cost)Z = 2x + 5y \quad \text{(minimize cost)}Z=2x+5y(minimize cost)
Constraints:
x+2y≤6(labor)2x+y≤5(material)x,y≥0.\begin{aligned} x + 2y & \leq 6 \quad \text{(labor)} \\ 2x + y & \leq 5 \quad \text{(material)} \\ x, y & \geq 0. \end{aligned}x+2y2x+yx,y≤6(labor)≤5(material)≥0.
________________________________________
Problem 3: Maximizing Production with Multiple Resources
Objective: Maximize profit by determining optimal production of products A and B under labor, material, and machine time constraints.
Objective Function:
Z=5x+4y(maximize profit)Z = 5x + 4y \quad \text{(maximize profit)}Z=5x+4y(maximize profit)
Constraints:
2x+y≤20(labor)3x+2y≤30(material)x+2y≤18(machine time)x,y≥0.\begin{aligned} 2x + y & \leq 20 \quad \text{(labor)} \\ 3x + 2y & \leq 30 \quad \text{(material)} \\ x + 2y & \leq 18 \quad \text{(machine time)} \\ x, y & \geq 0. \end{aligned}2x+y3x+2yx+2yx,y≤20(labor)≤30(material)≤18(machine time)≥0.
________________________________________
Problem 4: Maximizing Revenue from Sales
Objective: Maximize revenue from two products (A and B) under constraints on advertising budget and production capacity.
Objective Function:
Z=4x+5y(maximize revenue)Z = 4x + 5y \quad \text{(maximize revenue)}Z=4x+5y(maximize revenue)
Constraints:
x+2y≤20(advertising budget)x+2y≤15(production capacity)x,y≥0.\begin{aligned} x + 2y & \leq 20 \quad \text{(advertising budget)} \\ x + 2y & \leq 15 \quad \text{(production capacity)} \\ x, y & \geq 0. \end{aligned}x+2yx+2yx,y≤20(advertising budget)≤15(production capacity)≥0.
________________________________________
Problem 5: Resource Allocation for Two Projects
Objective: Maximize profit from two projects (P1 and P2) under labor hours and capital investment constraints.
Objective Function:
Z=8x+7y(maximize profit)Z = 8x + 7y \quad \text{(maximize profit)}Z=8x+7y(maximize profit)
Constraints:
3x+4y≤12(labor hours)2x+y≤6(capital investment)x,y≥0.\begin{aligned} 3x + 4y & \leq 12 \quad \text{(labor hours)} \\ 2x + y & \leq 6 \quad \text{(capital investment)} \\ x, y & \geq 0. \end{aligned}3x+4y2x+yx,y≤12(labor hours)≤6(capital investment)≥0.
________________________________________
Problem 6: Production Planning for a Bakery
Objective: Maximize profit by determining the optimal number of chocolate and vanilla cakes to produce under baking time and flour constraints.
Objective Function:
Z=5x+3y(maximize profit)Z = 5x + 3y \quad \text{(maximize profit)}Z=5x+3y(maximize profit)
Constraints:
x+2y≤8(baking time)3x+2y≤12(flour)x,y≥0.\begin{aligned} x + 2y & \leq 8 \quad \text{(baking time)} \\ 3x + 2y & \leq 12 \quad \text{(flour)} \\ x, y & \geq 0. \end{aligned}x+2y3x+2yx,y≤8(baking time)≤12(flour)≥0.
________________________________________
Problem 7: Minimizing Cost for a Transport Company
Objective: Minimize the total cost of operating two vehicle types under fuel and driver time constraints.
Objective Function:
Z=6x+7y(minimize cost)Z = 6x + 7y \quad \text{(minimize cost)}Z=6x+7y(minimize cost)
Constraints:
3x+4y≤18(fuel)2x+y≤10(driver time)x,y≥0.\begin{aligned} 3x + 4y & \leq 18 \quad \text{(fuel)} \\ 2x + y & \leq 10 \quad \text{(driver time)} \\ x, y & \geq 0. \end{aligned}3x+4y2x+yx,y≤18(fuel)≤10(driver time)≥0.
________________________________________
Problem 8: Maximizing Revenue from Two Products
Objective: Maximize revenue from two products (P1 and P2) under labor, raw material, and machine time constraints.
Objective Function:
Z=10x+12y(maximize revenue)Z = 10x + 12y \quad \text{(maximize revenue)}Z=10x+12y(maximize revenue)
Constraints:
4x+3y≤30(labor)x+2y≤18(raw material)3x+2y≤24(machine time)x,y≥0.\begin{aligned} 4x + 3y & \leq 30 \quad \text{(labor)} \\ x + 2y & \leq 18 \quad \text{(raw material)} \\ 3x + 2y & \leq 24 \quad \text{(machine time)} \\ x, y & \geq 0. \end{aligned}4x+3yx+2y3x+2yx,y≤30(labor)≤18(raw material)≤24(machine time)≥0.
________________________________________
Problem 9: Advertising Campaign Budget Allocation
Objective: Maximize reach by allocating a budget across two advertising campaigns (A and B) under constraints on spending across various media.
Objective Function:
Z=500000x+400000y(maximize reach)Z = 500000x + 400000y \quad \text{(maximize reach)}Z=500000x+400000y(maximize reach)
Constraints:
4x+3y≤5000(television)2x+2.5y≤4500(print media)x+1.5y≤3000(social media)x,y≥0.\begin{aligned} 4x + 3y & \leq 5000 \quad \text{(television)} \\ 2x + 2.5y & \leq 4500 \quad \text{(print media)} \\ x + 1.5y & \leq 3000 \quad \text{(social media)} \\ x, y & \geq 0. \end{aligned}4x+3y2x+2.5yx+1.5yx,y≤5000(television)≤4500(print media)≤3000(social media)≥0.
________________________________________
Problem 10: Meal Planning for a School Cafeteria
Objective: Maximize revenue by planning the number of two types of meals (A and B) under constraints on ingredients.
Objective Function:
Z=6x+5y(maximize revenue)Z = 6x + 5y \quad \text{(maximize revenue)}Z=6x+5y(maximize revenue)
Constraints:
2x+4y≤30(meat)3x+2y≤24(vegetables)x+2y≤20(rice)x,y≥0.\begin{aligned} 2x + 4y & \leq 30 \quad \text{(meat)} \\ 3x + 2y & \leq 24 \quad \text{(vegetables)} \\ x + 2y & \leq 20 \quad \text{(rice)} \\ x, y & \geq 0. \end{aligned}2x+4y3x+2yx+2yx,y≤30(meat)≤24(vegetables)≤20(rice)≥0.
Results
Each problem's solution includes the optimal values for decision variables and the maximum or minimum value of the objective function, depending on the problem's focus.
Problem 1: Maximizing Profit for a Factory
•	Optimal Solution:
x=6x = 6x=6 (units of Product A)
y=0y = 0y=0 (units of Product B)
•	Maximum Profit: Z=18Z = 18Z=18
Problem 2: Minimizing Cost for a Manufacturer
•	Optimal Solution:
x=0x = 0x=0 (units of Product X)
y=2.5y = 2.5y=2.5 (units of Product Y)
•	Minimum Cost: Z=12.5Z = 12.5Z=12.5
Problem 3: Maximizing Production with Multiple Resources
•	Optimal Solution:
x=5x = 5x=5 (units of Product A)
y=5y = 5y=5 (units of Product B)
•	Maximum Profit: Z=45Z = 45Z=45
Problem 4: Maximizing Revenue from Sales
•	Optimal Solution:
x=5x = 5x=5 (units of Product A)
y=5y = 5y=5 (units of Product B)
•	Maximum Revenue: Z=45Z = 45Z=45
Problem 5: Resource Allocation for Two Projects
•	Optimal Solution:
x=2x = 2x=2 (Project P1 units)
y=0y = 0y=0 (Project P2 units)
•	Maximum Profit: Z=16Z = 16Z=16
Problem 6: Production Planning for a Bakery
•	Optimal Solution:
x=4x = 4x=4 (Chocolate cakes)
y=0y = 0y=0 (Vanilla cakes)
•	Maximum Profit: Z=20Z = 20Z=20
Problem 7: Minimizing Cost for a Transport Company
•	Optimal Solution:
x=0x = 0x=0 (Trips by Vehicle X)
y=4.5y = 4.5y=4.5 (Trips by Vehicle Y)
•	Minimum Cost: Z=31.5Z = 31.5Z=31.5
Problem 8: Maximizing Revenue from Two Products
•	Optimal Solution:
x=0x = 0x=0 (Units of P1)
y=12y = 12y=12 (Units of P2)
•	Maximum Revenue: Z=144Z = 144Z=144
Problem 9: Advertising Campaign Budget Allocation
•	Optimal Solution:
x=0x = 0x=0 (Campaign A units)
y=2y = 2y=2 (Campaign B units)
•	Maximum Reach: Z=800,000Z = 800,000Z=800,000
Problem 10: Meal Planning for a School Cafeteria
•	Optimal Solution:
x=5x = 5x=5 (Units of Meal A)
y=0y = 0y=0 (Units of Meal B)
•	Maximum Revenue: Z=30Z = 30Z=30

