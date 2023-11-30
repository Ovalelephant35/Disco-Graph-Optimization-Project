# An Application of Graph Optimization

## Problem Statement

The research problem focuses on optimizing the University Course Assignment System, where faculty members are categorized into three groups: "x1," "x2," and "x3," each with different course load capacities. The challenge involves developing an assignment scheme that maximizes the number of courses assigned to faculty while considering their preferences and category-based constraints. Faculty members can take multiple courses in a semester, and a course can be assigned to multiple professors, with each assignment contributing to their course load. The unique aspect of this problem lies in the flexibility of course assignments, deviating from traditional Assignment problems, and the need to align with individual preferences within category constraints.

Potential modifications to enhance the solution might include adjusting the maximum number of courses permissible for each professor category or expanding the number of categories beyond the existing three to create a more generalized solution. These modifications could provide a nuanced approach to course assignments, allowing for adaptability within the system while ensuring that courses are assigned based on faculty preferences. Developing a comprehensive and flexible assignment scheme that accommodates these considerations is crucial for optimizing the overall efficiency of the University Course Assignment System.

## Problem Constraints

1. **Faculty Categories:** The faculty members are divided into three categories: "x1," "x2," and "x3," each with distinct course loads. "x1" handles 0.5 courses, "x2" manages 1 course, and "x3" takes on 1.5 courses per semester.

2. **Course Load Flexibility:** Faculty members can handle multiple courses in a semester, and a single course can be assigned to multiple professors. This flexibility allows for diverse assignment possibilities, with each course contributing to the load of the assigned faculty members.

3. **Preference Lists:** Each faculty member maintains a preference list of at least 12 courses, ordered by personal preference. Course assignments should align with these preferences, ensuring a more personalized and satisfactory allocation.

4. **Full Assignment Requirement:** Faculty members must be fully assigned or not assigned at all to courses. This constraint ensures that each faculty member's course load is either complete or remains untouched, avoiding partial assignments.

5. **Total Faculty Constraint:** The total number of faculty members across all categories ("x1," "x2," "x3") must be less than 30, adding an overarching constraint to manage the overall faculty composition within the University Course Assignment System.


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

