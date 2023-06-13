# Metro_data

**ABOUT**
This is application meant for windows, linux users.  It helps you find &amp; visualize the Shortest Path between Delhi Metro Stations, it uses Graph Data Structure &amp; Dijkstra's Algorithm.

**Implementation**

This app can directly show the distance and the number of stations from one source to destination. To use the app, you would create a class object, add the stations and connections using the addEdge function, specify the source and destination stations, and then call the dijkstra function to obtain the shortest path. Finally, the printPath function can be used to display the stations in the shortest path to the user.

-> Station Representation: The app represents each metro station using a name. This information is stored in the Station.txt file.

->Metro Network: The app models the metro network using a class, which maintains an adjacency list to store the connections between stations. The addEdge function allows you to add connections (edges) between stations, specifying the weight or distance associated with each connection.

->Dijkstra's Algorithm: The dijkstra function in the class implements Dijkstra's algorithm. It takes the name of the source station and the name of the destination station as input string and returns a vector path representing the shortest path between the two stations. This function uses a set to efficiently explore the stations based on their total distances from the source station.

->Printing the Path: The printPath function in the class takes the vector representing the shortest path as input and prints the sequence of stations from the source station to the destination station. 

