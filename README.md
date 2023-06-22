# pathfinding-algorithms-Visualizer
Welcome to Pathfinding Visualizer
Hey! Shiba (Creator) here. This is short Tutorial/Info-thingy on how this works. Don't worry I've got you. 
btw if you go fullscreen (by pressing f11) I'll be happy.

What is a pathfinding algorithm? At its core, a pathfinding algorithm seeks to find the shortest path between two points that is from the Starting Node (Green) to the Destination Node (Red). 
Both of them can be dragged across anywhere in the grid. This application visualizes various pathfinding algorithms in action, and more!

All of the algorithms on this application are adapted for a 2D grid of 25x25 nodes, where 90 degree turns have a "cost" of 1 and movements from a node to another have a "cost" of 1. Alright Now you can see some button at the bottom with

Dijkstra's Algorithm: the father of pathfinding algorithms; guarantees the shortest path

A* Search: arguably the best pathfinding algorithm; uses heuristics to guarantee the shortest path much faster than Dijkstra's Algorithm.

Breath-first Search: a great algorithm; guarantees the shortest path.

Depth-first Search: a very bad algorithm for pathfinding; does not guarantee the shortest path.

You can also make walls on the grid by just clicking and dragging your cursor, to give those algorithms some challenge as these Walls are impenetrable, meaning that a path cannot cross through them meaning that the algorithms would explore more paths, hence more exciting visualisation process.

And the maze function was added much later so its not implemented as best it can be but it works by first clicking on the maze button and the moving you cursor to any of the nodes on the grid and hold the click till you start seeing the maze appearing and hold until the maze is generated that is the longer you have it clicked, the maze gets more complex. And if the maze stops appearing or you think its not complex enough, then just repeat the whole steps again but this time choose some other node on the grid.

This is how the Application looks or you can also check it out here - https://shibaperu.github.io/pathfinding-algorithms-Visualizer/

![Screenshot 2023-05-01 194004](https://github.com/Shibaperu/pathfinding-algorithms-Visualizer/assets/97682691/76a11704-69de-4840-b682-9362df95060b)

This how you can create custom walls by holding click and dragging it across the grid.

![Screenshot 2023-05-01 212838](https://github.com/Shibaperu/pathfinding-algorithms-Visualizer/assets/97682691/52e42452-68c8-49d9-9d36-8feef8cd32cc)

This how a generated maze looks like from the maze button down below the grid.

![Screenshot 2023-05-01 203818](https://github.com/Shibaperu/pathfinding-algorithms-Visualizer/assets/97682691/ffe88dca-67fa-4204-bc59-f898db285bdb)

And this how an Algorithm running on the maze looks like.

![Screenshot 2023-05-01 210652](https://github.com/Shibaperu/pathfinding-algorithms-Visualizer/assets/97682691/046ab43a-15d4-4c46-a97d-ff76b387248e)
