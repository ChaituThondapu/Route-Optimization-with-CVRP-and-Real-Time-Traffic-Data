# Route-Optimization-with-CVRP-and-Real-Time-Traffic-Data
This project aims to optimize delivery routes for a local grocery store using the Capacitated Vehicle Routing Problem (CVRP) model and real-time distance data from the Google Maps API.

The project reads delivery data from a dataset containing order information such as order IDs, customer details, addresses, and order sizes. It then formulates the CVRP model using the Gurobi optimization library in Python, considering constraints such as vehicle capacity, visitation constraints, and minimizing the total distance traveled.
The Google Maps API is utilized to calculate the distances between delivery locations and the depot, enabling real-time distance matrix computation. This distance matrix is essential for formulating the objective function and constraints in the CVRP model.
Upon solving the CVRP model, optimal routes for each vehicle are extracted and visualized using the Google Maps Routes API, providing insights into the most efficient delivery routes.
