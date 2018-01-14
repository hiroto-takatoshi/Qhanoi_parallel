# Qhanoi_parallel
hanoi tower problem in Q learning (parallel version)

## Credits

Base code credit to : https://github.com/khpeek/Q-learning-Hanoi/blob/master/hanoi.py

Parallel version inspired by:

Kretchmar, R. Matthew. "Parallel reinforcement learning." The 6th World Conference on Systemics, Cybernetics, and Informatics. 2002.

The implemention is a dumb version, time complexity is somehow huge.

## Requirements

Python 3.6 since we are using asyncio

## Experimental Results

![alt text](https://github.com/hiroto-takatoshi/Qhanoi_parallel/blob/master/exp.PNG)

The right part is the original version, you can see the left desends 10 times faster when we have 10 agents working at the same time.
