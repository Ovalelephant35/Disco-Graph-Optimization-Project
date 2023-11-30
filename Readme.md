# University Course Assignment System Optimization

## Problem Statement

The University Course Assignment System Optimization is designed to efficiently assign courses to faculty members based on their preferences and category-based constraints. The problem revolves around three distinct faculty categories ("x1," "x2," and "x3") with different course loads. The goal is to develop an assignment scheme that maximizes the number of courses assigned to faculty while aligning with their preferences and category-based constraints.

### Problem Constraints

- Faculty categories: "x1," "x2," "x3"
- Course loads: "x1" (0.5 courses), "x2" (1 course), "x3" (1.5 courses)
- Faculty members can have multiple courses in a semester, and a course can be assigned to multiple faculty members.
- Each faculty member maintains a preference list of courses.
- Minimum number of preferences: 12 courses.
- Faculty members must be fully assigned or not assigned at all.

## Code Overview

The provided Python code uses the NetworkX library for graph representation and bipartite matching. The program takes user input for faculty preferences, creates a bipartite graph, performs maximum bipartite matching, and calculates the total course load assigned to each faculty member. The results are displayed in the form of matchings and a course assignment matrix.

## Usage

1. Run the `optimize_course_assignment` function in the provided Python script.
2. Enter the number of professors in each category, along with their preference lists.
3. View the generated bipartite graph and the results of the course assignment.

## Directory Structure

```plaintext
- optimize_course_assignment.py   # Main Python script
- README.md                        # Project documentation

