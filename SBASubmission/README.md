Learner Data Analysis
Description
This application analyzes and processes learner submission data for a given course and assignment group. It calculates and returns the learner’s average score and individual assignment scores, taking into account submission penalties for late work.

Features
Data Validation: Ensures that assignment groups belong to the correct course, and checks for valid data formats.
Penalty Calculation: Deducts points for late submissions.
Score Calculation: Computes the percentage score for each assignment and the weighted average score based on assignment points.
Requirements
Functional Requirements
Data Processing:

The application processes assignment and submission data to calculate scores.
It handles late submissions by applying a penalty.
The results include a weighted average score and individual assignment percentages.
Error Handling:

Uses try/catch blocks to manage errors such as invalid data formats or mismatched course IDs.
Ensures no division by zero errors and handles invalid numeric values gracefully.
Coding Requirements
Variable Declaration:

Uses const for immutable variables and let where variable reassignment is necessary.
Calculations:

Performs mathematical operations to compute scores and percentages.
Control Flow:

Implements if/else statements to handle various conditions.
Incorporates try/catch for error management.
Loops:

Utilizes forEach loops to iterate over assignments and submissions.
Includes a continue keyword to skip non-relevant submissions.
Arrays and Objects:

Creates and manipulates arrays and objects to store and process data.
Retrieves and updates values in arrays and objects as needed.
Functions:

Defines functions for repeated tasks like date parsing and zero-division avoidance.