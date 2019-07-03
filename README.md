# satellitedeorbitcalculator
# ------------------------------------------------------
# Name: Alina Siminiouk and Hannah Durkee
# Filename: README.txt
# Section: L04 and L01
# Date: 04.21.19
# References: None
# ------------------------------------------------------

The Satellite Deorbit Calculator 
Our project aims to create a calculator that given a set of parameters, 
will calculate how fast a satellite would deorbit from Low Earth Orbit (LEO) 
and other orbital outputs such as mean motion or orbital decay per iteration.
Our intended audience is people that are comfortable with science and technology, 
but don't know how orbital mechanics or other things about space. Generally, we 
made the project for ourselves and our own purposes within predicting the re-entry 
date of our Thermosphere Test Probe after launch. 

Files required to run the project:
-Final_Satellite_Calculator

How to run the project:
Open the file and select from the available options: feel free to explore the FAQ, test out the ISS, 
the experimental Smith-NASA Thermosphere Test Probe, or try out your own satellite! 

Architecture:
We heavily depended on functions, loops, and lists to structure the code. 
Our main() function first calls on our intro() function, then takes user input to start the FAQ_fx() function or sat_calc() function.
It also includes the ask_again_fx() function.
The intro() function prints an ASCII picture that we modified, demonstrating your satellite faling from the sky
The sat_calc() function offers the user three options between two presets and a build-your-own satellite (this dictates initial values for mass, area, etc)
It then performs a series of operations using list indexing to run all of the iterative calculations, then prints the results.
The FAQ_fx() function allows users to choose between preset questions that correspond to printing different answers.
The ask_again_fx() function allows users to run the calculator, access the FAQ, or end the program after each function's run. 

Challenge:
Our biggest challenge was moving from our working matlab code to the sat_calc() function. The syntax and overall engine functioned differently so we had to
implement lists in our calculations. We debugged for many hours, passed the laptop back and forth many times, and had to consider many approaches before 
deciding that this was the path we wanted to follow. We also formatted the results to make it easier to digest. 

