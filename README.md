# EcoSim-Ecosystem-Simulator


Project Description

EcoSim is a Python-based ecosystem simulator that demonstrates how predators and prey interact in a shared environment. It simulates animals such as wolves and rabbits living in a grid-based ecosystem.

The program shows how factors such as reproduction, food availability, energy, and population affect the survival of different species.

Objectives

- Apply Object-Oriented Programming (OOP) concepts such as inheritance and polymorphism.
- Create a grid-based environment where animals can move, hunt, and forage.
- Track animal populations and record simulation statistics.

Main Features

- **Animal Movement:** Animals move around a shared grid environment.
- **Predator-Prey Interaction:** Wolves hunt rabbits while rabbits try to escape.
- **Reproduction:** Rabbits can reproduce based on their reproduction rate.
- **Energy System:** Animals lose and gain energy depending on their actions.
- **Population Tracking:** The program records the number of living wolves and rabbits during each turn.

Classes

| Class | Description |
|---|---|
| Organism | Base class containing shared animal attributes and methods. |
| Prey | Represents rabbits, which can reproduce, run away, and forage. |
| Predator | Represents wolves, which hunt prey and have starvation limits. |
| SimulationEnvironment | Manages the grid, simulation turns, and organisms. |
| DataTracker | Monitors animal populations and records statistics. |

Object-Oriented Programming Concepts

- **Inheritance:** Prey and Predator inherit shared attributes and methods from Organism.
- **Polymorphism:** Different organisms can have their own movement and behavior.
- **Encapsulation:** Animal attributes and behaviors are organized within their respective classes.

Technologies Used

- Python
- Object-Oriented Programming (OOP)
- GitHub

Target Users

- High school science students
- Biology instructors
- Data science learners

Group Members

- BALISA
- CAGUIOA
- PASTRANA

**Section:** 9-Potassium

Project Status

Currently under development.

## Class Diagram

View our [Class Diagram](class-diagram.md).
