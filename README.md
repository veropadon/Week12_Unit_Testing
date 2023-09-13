# Week12_Unit_Testing

TestDemo Project
This repository contains unit tests for testing basic arithmetic operations and random number squaring using JUnit 5 and Mockito.

Features
Positive Number Addition: This feature ensures that two positive numbers are added correctly.
Random Number Squaring: Given a random number, it calculates its square.
Tech Stack
JUnit 5
Mockito
AssertJ
Setup
Ensure you have JUnit 5, Mockito, and AssertJ set up in your development environment.
Test Cases
Positive Number Addition
The test assertThatTwoPositiveNumbersAreAddedCorrectly checks if two positive numbers are added correctly. It utilizes parameterized tests to verify the addition of multiple sets of numbers, including edge cases where exceptions are expected.

Random Number Squaring
The test assertThatNumberSquaredIsCorrect makes use of Mockito to mock out the randomness, ensuring deterministic behavior for testing purposes. The test checks if the square of a given random number is computed correctly.

Known Issues
Ensure that class naming conventions are followed, i.e., class names should begin with an uppercase letter (like TestDemo).
