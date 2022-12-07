#!/bin/bash

# Define some variables
G=6.67408e-11 # gravitational constant
M=5.972e24 # mass of Earth
R=6371e3 # radius of Earth

# Ask the user for the initial altitude of the spacecraft
echo "Enter the initial altitude of the spacecraft (in meters):"
read alt

# Calculate the initial velocity needed to achieve a circular orbit
v=$(echo "sqrt($G*$M/($R+$alt))" | bc -l)

# Print the results to the user
echo "The initial velocity needed to achieve a circular orbit at an altitude of $alt meters is $v m/s."
