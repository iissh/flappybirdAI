# Flappy Bird AI
AI plays Flappy Bird.


The program starts off random and has no idea how game operates. After many generations of slowing learning and getting better, the neural network picks up on patterns on what it can do to get further in the level. After a few generations it starts getting exponentially better until it reaches a point that it cannot be beat (the algorithm never loses and passes infinite levels).

I used the NeuroEvolution of Augmenting Topologies (NEAT) algorithm as a base to program this project.


<!--
The neural networks come in layers:
The first layer is input layer. It essentially tells the program what it knows and what it can see (the eyes of the AI).
position of bird from bottom and top piepe and bird y direction
ned to use this input info to get output output in this case is decision... jump?pass values from input to ouput depending on those values we jump or not jump
connections and weights tweak these weights to make AI better
-->
