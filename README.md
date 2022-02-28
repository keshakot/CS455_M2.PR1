# CS455 Module 2 PR1: Dijkstra++   
Author: Georgiy Antonovich Bondar  

Go to https://keshakot.github.io/CS455_M2.PR1/ to play the game :)

# Behaviors
Dijkstra Path Follower: Assets/Scripts/PathFollower_Dijkstra.cs   
Dijkstra's Algorithm: Assets/Scripts/Dijkstra/Dijkstra.cs   
Dijkstra Graph Nodes: Assets/Scripts/Dijkstra/Node.cs   
Modified Game Manager: Assets/Scripts/GameManager.cs   

# Changes
1. At the start of the game, the GameManager places an obstacle randomly in one of the paths.  
2. Connection.getCost() in Dijkstra.cs will check for any obstacles in the connection - if any exist, the cost is increased (to infinity) and the path will be avoided.   
3. The red box will then take different paths depending on where the box is spawned.   

