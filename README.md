# Assignment 3 – University Course Management System

## Description
This project implements a simple university course and grading management system using JavaScript.  
The goal is to demonstrate core JavaScript concepts such as asynchronous callbacks, ES6 classes, object property descriptors, and array manipulation.

## Concepts Used
- ES6 Classes
- Asynchronous callbacks using `setTimeout`
- Immutable object properties with `Object.defineProperty`
- Array methods (`map`, `reduce`, `filter`)
- Higher-order functions

## Project Structure
- `models.js` – Defines the `Student` class and data structure
- `database.js` – Simulates an asynchronous database call
- `analytics.js` – Contains analytical helper functions
- `main.js` – Entry point that orchestrates the application

## Functionality
- Fetches student data asynchronously
- Converts raw data into class instances
- Prevents modification of immutable student IDs
- Calculates class averages for specific courses
- Finds the top-performing student
- Filters students based on custom criteria

## How to Run
Make sure you have **Node.js** installed.

```bash
node main.js
