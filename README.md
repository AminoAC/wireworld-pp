# wireworld-pp
The Wireworld++ rule file for the Golly software

It should be saved with the file extension .rule and put into the “Rules” subdirectory of the Golly directory.

Transition rules are set as follows:

1. Strong Conductor becomes Strong Head if neighbors contain either 1,2 Strong Heads or exactly 2 Weak Heads.
2. Strong Head becomes Strong Tail
3. Strong Tail becomes Strong Conductor.
4. Weak Conductor becomes Weak Head if neighbors contain either 1 Strong Head or 1,2 Weak Heads
5. Weak Head becomes Weak Tail
6. Weak Tail becomes Weak Conductor.
