# Traffic-Light-FSM
ELE432_Homework 1 Traffic Light Code and Results
This code is a modified version of the code studied in the class, 
even though the code has still clk_100MHz written in it, the clock is modified through the testbench so that is possesses a 100kHz speed instead,
making also modifications to the repetions before the "modified clock of 1hz", now the everything is scaled down by 10 so to make the simulation easy to run as large sim times also create compile exceptions.
So the light that is required to stay still for 5 seconds is now reduced to 0.5 as mentioned above, all of the phases in the testbench waveform output can be seen, and it can be noticed that the light at non-timer states still take little delay to change, this is not an error and is done to again, speed up the simulations.
Note: All of the light numbers are converted into decimals in the .png file, so keeping this mind will prevent potential confusing situations.
