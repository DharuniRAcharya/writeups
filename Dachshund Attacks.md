# Dachshund Attacks

## Category
Cryptography

## Points
80

## Description
What if d is too small? Connect with nc mercury.picoctf.net 37455.

## Approach
### Hint 
What do you think about my pet? ([dachshund.jpg](https://mercury.picoctf.net/static/49aa9abb90668b3849ef5a20e4a6beb4/dachshund.jpg))

This image gives the hint of the Wiener's attack, named after cryptologist Michael J. Wiener, is a type of cryptographic attack against RSA. The attack uses the 
continued fraction method to expose the private key d when d is small. 

Also the nc mercury.picoctf.net 37455 was explored as shown below:

![Alt text](/DA.png)

The following python commands were used to solve this challenge.

![Alt text](/DA2.png)

Hence the result:

![Alt text](/DA1.png)
