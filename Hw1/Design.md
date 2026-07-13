# Homework 1: Design Document

  * author: *Kylah Camel*
  * date: January 2025

## introduction

In this homework, I will do the thing and solve important computer science
problems and probably win a
[Turing Award](https://en.wikipedia.org/wiki/Turing_Award) for doing so.

TODO: In this document, I will write a brief description and plan for the five functions that I will be implementing as well as how I believe the caat.c program should work. 

## function 1: area_of_disk 

The purpose of this function is to take the radius of a disk and return its area using the formula, A= Pi*r^2. The function will take one parameter, which is a positive radius number, and will return the area as a double. Will also use M_PI in order to get an accurate value for PI.

## function 2: area_of_ring

The purpose of this function is to take the outer radius of the disk and the inner radius of the hole to get the area of the ring. The function will take two number parameters, the outer and inner radius, and will return the difference of the two, which would be the area of the ring.

## function 3: bigger_minus_smaller

The purpose of this function is to  subtract the larger number from the smaller one. It will take two number parameters and will see which one is greater by comparing the two in order to perform the subtraction operation.

## function 4: value_in_range

This function will take three number parameters, a lower bound, upper bound, and a specific number. The purpose of this function is to return true if the specific value is in the range of the lower bound and the upper bound and false if it is not in the range. The parameters can also be negative however, the upper bound must be greater than the lower.

## function 5: sum_of_greater_squares

The purpose of this function is to return the sum of the two greatest squares given three number parameters. These parameters are able to be negative numbers, positive, or 0.

## the caat program

The purpose of this program is to take a character from stdin one at a time and output each character to stdout  with vowel characters being outputted twice. To do this, I will use getchar() to get each character and putchar() to output each character making sure that the program ends once it finds an EOF character.

