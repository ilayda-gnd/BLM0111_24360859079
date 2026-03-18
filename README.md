# BLM0111_24360859079
İLAYDA GÜNDOĞDU  
24360859079  
Code link: https://1drv.ms/f/c/13e97621a3309053/IgA5gk9zoeOlSI6PoAomDlK7AVvZlQcVMB5_lJBk4Svs430?e=yPoVaO

# Physics Experiments Simulation (C Programming)

This project was developed in C to simulate various physics experiments conducted on the planets of the Solar System. Based on user input, the program performs calculations for the selected experiment on each planet and displays the results with units on the console.

The project aims to apply basic physics formulas programmatically and reinforce concepts such as arrays, pointers, functions, and user input validation in C.

---

## Program Features

- Planetary gravitational accelerations are stored in an array.  
- Each experiment is implemented as a separate function.  
- All operations on arrays are performed using pointers.  
- Negative user input for physical quantities is converted to absolute values using the ternary operator.  
- After completing an experiment, the user can select another experiment.  
- Entering `-1` in the menu safely terminates the program.  
- Non-numeric or invalid menu inputs are checked, and the user is notified.  
- Experiment results are displayed with units.

---

## Included Experiments

The following physics experiments are implemented:

1. Free Fall  
2. Vertical Throw  
3. Weight Calculation  
4. Potential Energy  
5. Hydrostatic Pressure  
6. Archimedes’ Force  
7. Pendulum Period  
8. Rope Tension  
9. Force in an Elevator  

Each experiment:
- Collects the required physical quantities from the user,  
- Calculates results for all planets in the Solar System,  
- Displays the results per planet on the console.

---

## Planetary Gravitational Accelerations

The gravitational accelerations of the planets are stored in the array as follows:

| Index | Planet  | Gravity (m/s²) |
|-------|---------|----------------|
| 0     | Mercury | 3.70           |
| 1     | Venus   | 8.87           |
| 2     | Earth   | 9.81           |
| 3     | Mars    | 3.71           |
| 4     | Jupiter | 24.79          |
| 5     | Saturn  | 10.44          |
| 6     | Uranus  | 8.69           |
| 7     | Neptune | 11.15          |
| 8     | Pluto   | 0.62           |

---

## Program Workflow

1. The program prompts the user for the scientist's name.  
2. The experiment menu is displayed.  
3. The user selects an experiment.  
4. The program collects the relevant physical quantities for the chosen experiment.  
5. Results are calculated for all planets and displayed.  
6. The user can select a new experiment.  
7. Entering `-1` in the menu terminates the program.

---

## Programming Concepts Used

- Functions  
- Arrays  
- Pointers  
- Ternary operator  
- Loops (`do-while`)  
- Conditional statements (`if-else`)  
- User input validation (`scanf` return value check)

---

## Project Objective

The purpose of this project is to solve physical problems algorithmically using C programming and develop an interactive console application.
