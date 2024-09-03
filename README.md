# 🛠️ Network Optimization and Non-linear Models

In this project, we delve into two critical optimization problems: **Network Optimization** focusing on the Vehicle Routing Problem (VRP) and a **Non-linear Optimization** problem centered around the Wood Production industry. These problems represent real-world challenges in logistics and manufacturing, offering valuable insights into optimization techniques.

---

## 1. 🚚 Network Optimization: MULTIPLE VEHICLE ROUTING PROBLEM

The **Vehicle Routing Problem (VRP)** is a cornerstone in combinatorial optimization, widely used in logistics and transportation. The main objective is to plan optimal routes for a fleet of vehicles to efficiently serve a set of customers, each with specific demands. The goal is to minimize overall transportation costs, such as distance traveled or time spent, while adhering to constraints.

### 🧩 Key Components of the VRP:

- **Customers**: Each customer is located at a specific geographical point, with a known demand.
  
- **Vehicle Fleet**: A set of identical vehicles, each with a limited carrying capacity.

- **Customer Demand**: Each customer has a predetermined demand that needs to be fulfilled by the vehicles.

- **Vehicle Capacity**: Each vehicle has a maximum capacity that cannot be exceeded.

- **Routing Constraints**: Every customer must be visited exactly once by one vehicle. The fleet must collectively visit all customers.

### 🎯 Objective Function:
Minimize the total transportation cost, which may include distance, time, or other operational expenses.

To solve the VRP, we identify the optimal set of routes under the given constraints. Various algorithms, from heuristics to exact methods, can be applied depending on the problem's complexity. VRP is extensively used in sectors like transportation, distribution, and logistics, where efficient routing leads to significant cost savings and improved service quality.

### 🚀 Case Study:
Consider a delivery company aiming to strategically place depots to station vehicles. The goal is to deliver all packages while minimizing the total distance traveled, leveraging a fleet of 2 vehicles. Unlike traditional VRP, the return to the depot is not considered here, focusing solely on the optimal path to serve all customers as quickly as possible.

---

## 2. 🪵 Non-linear Optimization: WOOD PRODUCTION PROBLEM

Woodworking, a craft with ancient roots, has evolved into a sophisticated industry that blends tradition with modern technology. Today, woodworking faces the challenge of balancing artisanal quality with efficient mass production.

### 🌳 Project Overview:
In this project, we address contemporary challenges in woodworking by optimizing the dimensions of wooden pieces to maximize profit. This involves balancing the unique characteristics of different woods with production constraints, such as volume, surface area, and minimum output requirements.

### 🛠️ Optimization Approach:
Using **Pyomo**, we developed a model to optimize the non-linear cost functions associated with different wood types. The objective is to determine the most profitable dimensions, considering how size affects production costs and market demand. This project underscores the importance of dimension optimization to ensure both quality and profitability, bridging traditional woodworking techniques with modern optimization methods.

### 📈 Detailed Model:
The non-linear optimization model explores cost functions, constraints, and the mathematical framework guiding our approach. This project honors the rich heritage of woodworking while embracing technological advancements to enhance future practices.

---

By addressing these two distinct yet interconnected optimization challenges, this project provides a comprehensive look at how mathematical models can solve real-world problems in logistics and manufacturing.


