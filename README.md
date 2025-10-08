# Tic Tac Toe Kata

A Test Driven Development exercise to implement the classic Tic Tac Toe game.

## Table of Contents

- [Overview](#overview)
- [Game Rules](#game-rules)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Suggested Test Progression](#suggested-test-progression)
- [Evaluation Criteria](#evaluation-criteria)
- [Test Driven Development](#test-driven-development)

## Overview

This kata is designed to demonstrate proficiency in Test Driven Development (TDD) and programming fundamentals. You will build a working Tic Tac Toe game by writing tests first, then implementing the minimal code needed to make those tests pass.

## Game Rules

Tic Tac Toe is played on a 3x3 grid by two players (X and O).

1. Players take turns placing their mark in an empty cell
2. The first player to get three of their marks in a row wins
3. Rows can be horizontal, vertical, or diagonal
4. If all nine cells are filled without a winner, the game is a draw
5. X always goes first

## Requirements

Implement a fully functional Tic Tac Toe game that follows the rules above. The implementation details and architecture are left to your discretion.

## Getting Started

1. Choose your preferred programming language
2. Set up your testing framework
3. Start with the simplest test case (e.g., create an empty board)
4. Follow the Red-Green-Refactor cycle for each feature
5. Commit frequently with meaningful messages


## Test Driven Development

TDD follows a simple cycle known as Red-Green-Refactor:

1. **Red**: Write a failing test that describes the desired behavior
2. **Green**: Write the minimum code necessary to make the test pass
3. **Refactor**: Clean up the code while keeping tests green

Benefits of TDD include:
- Confidence that your code works as intended
- Built-in regression testing
- Better code design through incremental development
- Living documentation through test cases