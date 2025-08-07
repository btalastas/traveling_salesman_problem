# traveling_salesman_problem

## ***Description***

Java Program that solves the classic NP-hard problem the Traveling Salesman Problem. Compares the brute-force solution which tries all valid permutations (n!), to the approximation solution which implements Prim's Minimum Spanning Tree (MST) Algorithm to get a MST, to perform a pre-order Depth-First Traversal of that MST.

## ***How to Run***

Navigate to a directory and run the following command in your terminal

```sh
git clone https://github.com/btalastas/traveling_salesman_problem.git
```

Compile and run using the following commands

### ***Windows***

```sh
javac -cp .;483libs.jar *.java
java -cp .;483libs.jar SIMGUI
```

### ***MacOS/Linux***

```sh
javac -cp .:483libs.jar *.java
java -cp .:483libs.jar SimGUI
```

There are three additional commands that can be used to run the program.

```sh
java -cp .;483libs.jar SimGUI [number-of-cities]
java -cp .;483libs.jar SimGUI [number-of-cities] [rng-seed]
java -cp .;483libs.jar SimGUI [number-of-cities] [rng-seed] [ms-delay]
```

## ***Example***

![example run][example]

## ***Acknowledgements***

Professor Katherine Russell

[example]: ./pics/output.gif
