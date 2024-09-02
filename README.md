# Network Optimization and Non-linear Models
Formulate the network optimization problem as a discrete model, identifying mathematically the variables and constraints associated with the network. Formulate (mathematically) and solve a non-linear optimization problem based on real (or realistic) world data.

---

# 1. Network Optimization:MULTIPLE VEHICLE ROUTING PROBLEM

The Vehicle Routing Problem (VRP) is a classic combinatorial optimization issue prevalent in logistics and transportation. Its primary objective is to strategically plan routes for a fleet of vehicles to efficiently serve a specified set of customers, each with known demands for goods or services. The fundamental challenge revolves around minimizing the overall transportation cost, often measured in terms of distance traveled, time taken, or other pertinent metrics.

### Key Components of the VRP:

- Customers: The problem revolves around a group of customers, each situated at specific geographical points.

- Vehicle Fleet: A fleet of identical vehicles, each equipped with limited capacity for transporting goods or delivering services.

- Customer Demand: Each customer possesses a predetermined demand for goods or services, a requirement that the delivery vehicles must fulfill.

- Vehicle Capacity: Vehicles are constrained by a limited capacity for carrying goods, with the total demand served by a vehicle in a route not exceeding its designated capacity.

- Routing Constraints: The fleet of vehicles must visit all customers, but a customer can onl be visited by one vehicle only one time.

### ** Objective Function: ** 
The primary aim is to minimize the comprehensive transportation cost, incorporating factors such as the total distance covered, time taken, and other operational expenses.

Addressing the VRP entails determining an optimal or near-optimal set of routes that adhere to all specified constraints. A variety of optimization algorithms, including heuristics, metaheuristics, and exact methods, can be applied based on the complexity and scale of different VRP instances. The VRP finds extensive application in industries such as transportation, distribution, and logistics, where efficient route planning contributes to substantial cost savings and enhanced service quality.

In this case, assume a delivery company which objective is to study where to place the deposits to station the vehicles and the main purpose is to try to hand in all the packages traveling the lowest distance as possible. In this case, we will work with a fleet of 2 vehicles that will need to deliver all the packages travelling the minimum distance as possible taking advantage that there are 2 vehicles instead of only 1. For our project, we will not take into consideration the return to the deposit because we want to focus on optimizing the most optimal path to serve all the customers as fast as possible.

---

# 2. Non-linear optimization: WOOD PRODUCTION PROBLEM

The roots of woodworking trace back to prehistoric times when early humans fashioned tools and implements from wood to meet their basic needs. As civilizations emerged, woodworking advanced, giving rise to intricate woodcarvings, architectural marvels, and finely crafted furniture. Throughout the centuries, woodworking has remained a fundamental skill, transitioning from artisanal workshops to industrialized processes.

In the modern era, the woodworking industry faces a myriad of challenges and opportunities. Advancements in technology have introduced efficiency to production processes, enabling mass production and customization. Simultaneously, there is a growing appreciation for handmade, artisanal woodwork, emphasizing the uniqueness and craftsmanship of each piece.

Wood selection plays a pivotal role in woodworking, with different types of wood offering distinct characteristics in terms of durability, grain pattern, color, and workability. The choice of wood significantly influences the final product's quality and aesthetic appeal.

Our project delves into the contemporary challenges faced by woodworking enterprises, where the balance between tradition and innovation is crucial. The optimization problem at hand involves determining the optimal dimensions for wooden pieces, considering the intricacies of various wood types. Each wood type possesses unique attributes and, correspondingly, is associated with specific cost functions.

The goal is to maximize profit while navigating constraints related to total wood volume, surface area, and minimum production requirements. By leveraging optimization techniques and Pyomo, we aim to provide woodworkers with a data-driven approach to decision-making. This empowers them to make informed choices about the dimensions of wooden pieces, aligning with market demands, production capabilities, and the inherent characteristics of each wood type.

It is essential to mention that the production of different types of wood involves an important aspect about dimensions of the wood that must be produced in order to be transported and the needs and treat that each type of wood must have in order to ensure its quality, it is for all these reasons that producing pieces of wood of specific dimensions is important in order to sell it to carpenters or other business that works with wood in the most optimal conditions. For all these aspects, we computed individual cost functions for each of the woods, where in some of them it is a better to produce large lengths instead of heights, among other possible scenarios, that is why in this work we are going to analyze the most optimal dimensions that must be done in order to maximize profit and taking as the most important factor the non linear cost functions where depending on the size of the producition for each type of wood, can affect in a positive or negative way the profits, that after all, is the main objective of any business.

In the pages that follow, we will delve into the specifics of the optimization model, exploring the intricacies of cost functions, constraints, and the mathematical framework used to find the optimal solution. This project not only embraces the heritage of woodworking but also propels it into the future, where tradition and technology converge to shape the wooden creations of tomorrow.

