# Maze Generater and Solver in JAVA

# Introduction 
This is a Java program that generates and solves mazes using recursive backtracking algorithm. The program creates a maze of a specified size and then solves it by finding the shortest path from the starting point to the ending point.

# Features
* Generates a random maze using depth-first search algorithm.
* Solves the maze by finding a path from the start to the end using recursive backtracking algorithm.
* The maze is displayed graphically on a JPanel.
* The maze can be customized by changing various parameters, such as the number of rows and columns, the size of each cell, and the minimum number of pixels between the maze and the edge of the panel.

# Prerequisities
* Java Development Kit (JDK) version 8 or higher.
* An integrated development environment (IDE) that supports Java, such as Eclipse or IntelliJ IDEA.

# Installing
Clone : ```git clone https://github.com/OpenGenus/maze-generator-solver-in-java.git```

or download the repository (zip file) to your local machine.

# Running
* Compile the Maze.java file using the Java compiler.  
```javac Maze.java```
* Run the Maze class using the Java Virtual Machine.  
```java Maze```

# Customization
You can customize various aspects of the maze by changing the following variables in the **Maze** class:

* **rows**: number of rows of cells in the maze, including a wall around edges.
* **columns**: number of columns of cells in the maze, including a wall around edges.
* **blockSize**: size of each cell in pixels.
* **border**: minimum number of pixels between the maze and the edge of the panel.
* **sleepTime**: wait time after solving one maze before making another.
* **speedSleep**: short delay between steps in making and solving maze.