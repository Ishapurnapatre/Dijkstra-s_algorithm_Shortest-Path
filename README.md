# Dijkstra's Algorithm: For calculating Shortest Path
JAVA code for truck drivers that specifies the shortest route distance between cities and gives a count of petrol pumps and rest locations on the route.

It is a small sample space-based application specifically made for truck drivers. The project displays a specific set of cities and the routes connecting them with petrol pumps and rest locations along the routes. The project also displays the shortest route distance between the desired source and the destination city. The truck driver needs the account for rest locations and petrol pumps on the way from one city to another. We have used an adjacency list to create the graph and Dijkstra’s algorithm to determine the shortest route.
 
 
 Graph as a data structure is used. The cities represent nodes of the graph and the routes connecting the cities represent the edges of the graph. This is an undirected weighted graph. The graph data structure is mostly used for network applications and since the cities are connected, the graph is preferred over data structures.
C: represents Cities.
P: represents the Petrol Pump.
R: represents the Rest Locations.

GRAPH:  

C1 -> P1 (500)
P1 -> R1 (700)
R1 -> C5 (100) -> C3 (200)
C5 -> P4 (740)
P4 -> R4 (315) -> C2 (570)
C2 -> P3 (650)
P3 -> C4 (725)
C4 -> R3 (475)
R3 -> R2 (800)
R2 -> P2 (150)
P2 -> C3 (600)
