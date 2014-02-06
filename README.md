ECE281_CE2
==========

CE2 Repo

**I made a 2-4 memory address decoder with STRUCTURAL and BEHAVIORAL programming**


#Structural

First I made the decoder using structural programming

This means I used different components and connected them
together to get a functioning decoder.

The two components in the decoder was a inverter and a three way and gate

The code for the **inverter** and **and3** is above in the repo

Then I created a test bench for the structural decoder

The results are below:

![alt text](https://raw2.github.com/JarrodWooden/ECE281_CE2/master/DecoderTestPic.PNG "Structural Testbench Simulation")



#Behavioral

Next I made the decoder again with the same functionality
except using Behavioral programming

The test bench used was the same as the structural test bench
except a different VHDL testbench of course...

The simulation for the Behavioral Decoder is below:

![alt text](https://raw2.github.com/JarrodWooden/ECE281_CE2/master/Decoder_BehavioralTestPic.PNG "Behavioral Testbench Simulation")

As you can see both the simulation were exactly the same

This tells is the first check for consistency and accuracy;

The next test is that it follows the truth table below:

| I0 | I1 | EN | Y0 | Y1 | Y2 | Y3 |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|  0 |  0 |  0 |  0 |  0 |  0 |  0 |
|  0 |  0 |  1 |  1 |  0 |  0 |  0 |
|  0 |  1 |  0 |  0 |  0 |  0 |  0 |
|  0 |  1 |  1 |  0 |  0 |  1 |  0 |
|  1 |  0 |  0 |  0 |  0 |  0 |  0 |
|  1 |  0 |  1 |  0 |  1 |  0 |  0 |
|  1 |  1 |  0 |  0 |  0 |  0 |  0 |
|  1 |  1 |  1 |  0 |  0 |  0 |  1 |


If you compare the truth table with every line of each simulation
you can see that the results match up with the truth table
proving that our simulations worked properly 
Yayyy

Answer to step 15: What the adress decoder does, that we created, is based on some
adress input. The decoder will be able to select one "memory" location. Which also 
somewhat answers the next question, the decoder is used for computer memory! Like I 
said before each input adress would be used to access a tiny location in the CPU's 
memory to store that tid bit of informaiton.

#This is the end of my README!!!

##Thanks for Reading!
