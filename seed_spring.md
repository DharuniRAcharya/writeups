# seed-sPRiNG

## Category
Binary Exploitation

## Points
350

## Description
The most revolutionary game is finally available: seed sPRiNG is open right now! seed_spring. Connect to it with nc jupiter.challenges.picoctf.org 8311.

## Approach
A program is given which needs to exploited to acquire the flag. 
Following the three steps:
- Reversing executable into assembly code
- Analysing the assembly code
- Scripting
This works on the concept of `Pseudo-Random Integers`.

Thus a simple C code to generate random numbers.
![Alt text](/seed_spring2.png)

  
