# Network Optimization and Non-linear Models
Formulate the network optimization problem as a discrete model, identifying mathematically the variables and constraints associated with the network. Formulate (mathematically) and solve a non-linear optimization problem based on real (or realistic) world data.

---

# 1. Network Optimization: MULTIPLE VEHICLE ROUTING PROBLEM

The Vehicle Routing Problem (VRP) is a classic combinatorial optimization issue prevalent in logistics and transportation. Its primary objective is to strategically plan routes for a fleet of vehicles to efficiently serve a specified set of customers, each with known demands for goods or services. The fundamental challenge revolves around minimizing the overall transportation cost, often measured in terms of distance traveled, time taken, or other pertinent metrics.

### Key Components of the VRP:

- Customers: The problem revolves around a group of customers, each situated at specific geographical points.

- Vehicle Fleet: A fleet of identical vehicles, each equipped with limited capacity for transporting goods or delivering services.

- Customer Demand: Each customer possesses a predetermined demand for goods or services, a requirement that the delivery vehicles must fulfill.

- Vehicle Capacity: Vehicles are constrained by a limited capacity for carrying goods, with the total demand served by a vehicle in a route not exceeding its designated capacity.

- Routing Constraints: The fleet of vehicles must visit all customers, but a customer can onl be visited by one vehicle only one time.

### Objective Function: 
The primary aim is to minimize the comprehensive transportation cost, incorporating factors such as the total distance covered, time taken, and other operational expenses.

Addressing the VRP entails determining an optimal or near-optimal set of routes that adhere to all specified constraints. A variety of optimization algorithms, including heuristics, metaheuristics, and exact methods, can be applied based on the complexity and scale of different VRP instances. The VRP finds extensive application in industries such as transportation, distribution, and logistics, where efficient route planning contributes to substantial cost savings and enhanced service quality.

In this case, assume a delivery company which objective is to study where to place the deposits to station the vehicles and the main purpose is to try to hand in all the packages traveling the lowest distance as possible. In this case, we will work with a fleet of 2 vehicles that will need to deliver all the packages travelling the minimum distance as possible taking advantage that there are 2 vehicles instead of only 1. For our project, we will not take into consideration the return to the deposit because we want to focus on optimizing the most optimal path to serve all the customers as fast as possible.

---

# 2. Non-linear optimization: WOOD PRODUCTION PROBLEM

Woodworking has deep roots in history, evolving from primitive tool-making to the creation of intricate carvings, architecture, and furniture. Today, the woodworking industry balances tradition with modern technology, facing both challenges and opportunities. While technological advancements have enabled mass production, there is still a strong appreciation for artisanal craftsmanship.

Wood selection is crucial, as different woods offer unique qualities that affect durability, aesthetics, and workability. Our project addresses contemporary challenges in woodworking, focusing on optimizing the dimensions of wooden pieces to maximize profit. This involves balancing wood characteristics with production constraints, such as volume, surface area, and minimum output requirements.

Using Pyomo, we developed a model that incorporates the non-linear cost functions associated with different wood types. The aim is to determine the most profitable dimensions, considering how size impacts production costs and market demands. The project highlights the importance of optimizing wood dimensions to ensure quality and profitability, bridging the gap between traditional woodworking practices and modern optimization techniques.

In the Non-linear model file, we will detail the optimization model, exploring the cost functions, constraints, and mathematical framework that guide our approach. This project honors the heritage of woodworking while embracing technology to enhance future practices.

