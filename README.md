# Honest-Random-Number-Generator-Qiskit
A truly random number generator created using Qiskit. This was my first project using the Qiskit quantum computation library.

## Description
A somewhat big issue is the idea of randomness in computation. What does it actually mean to be random? In normal computers sudo-random number generators are used which rely on things like the time and date. But these things are not actually TRULY random. That is, given the initial conditions (ie: date/time) and the generation algorithm we could reproduce the 'random' number. This is a reversible process which means we can work our way back. Now I am going create a quantum number generator which relys on the irreversibility of quantum measurement and superposition to get me an honest random number.
(Note that I have to simulate this classically which makes this project semi redundant but this can easily be changed with access to a quantum computer)
