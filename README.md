# Note

This is made for linux based operating systems only.
Calculating ANYTHING that involves round brackets requires the expression to be in double quotes. For more info see usage examples.

# GeeksForGeeks link

https://www.geeksforgeeks.org/how-to-parse-mathematical-expressions-in-cpp/

# What I added

- the % mathematical operator
- adaptation to take terminal arguments

# Building the program and making it a bash command

To build the program use g++: 
g++ -o calculate main.cpp

To make it a bash command: 
sudo mv calculate /usr/local/bin/

# Usage examples

calculate 2.4+5.4 (output = 7.8)
calculate "(23%2+5*4)^2" (output = 441)
calculate "2^0.5" (output = 1.41421)
calculate "(2+6)/(4\*3)" (output = 0.66667)

# Customising program to your liking

You may change the output text colours, on how to check out: 
https://stackoverflow.com/questions/2616906/how-do-i-output-coloured-text-to-a-linux-terminal
You may also freely add your own features.

# Planned features to come

- ANS varialbe to be used in calculating using preceding answers (ex: calculate 2+2 ANS+2 (output = 6))
- sin cos and tan functions
