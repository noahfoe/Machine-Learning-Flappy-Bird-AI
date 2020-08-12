# Machine-Learning-Flappy-Bird-AI
Starts with a population size of 50, then uses NEAT framework inside of Python to create a neural network (3 inputs: the birds y position, the top pipes position, and the bottom pipes position. 1 output: jump/dont jump.) that takes the best birds of each generation, and breeds them to create 50 new, smarter, birds. usually after 2 or 3 generations, the program will run infinity because the bird has mastered when to jump and when not to jump.

However, since the first generation is purely random, sometimes there will be a bird or two from the first generation that will be able to get pretty far into the game. I believe you could tweek a few of the numbers to get it running more smoothly
