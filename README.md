# CS50’s Introduction to AI with Python

This project was completed as part of the course assignments.  
The following description is adapted from the original project specification.  

## Project 0: Degrees (Lecture 0 – Search)  

Program that determines how many “degrees of separation” apart two actors are.  

Using the Breadth-First Search algorithm, the program finds the shortest path between any two actors by identifying a sequence of movies that connects them.  

For example, the shortest path between Emma Watson and Jennifer Lawrence is 3:  

```
Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class
```

**Notes**
- The description above is adapted from the official project specification.
- Implemented using the course’s starter code, with modifications made to fulfill the project requirements.
- Completed as part of the CS50’s Introduction to AI with Python (2024 edition) coursework.


### How to Run

1. Run the program using the command `python degrees.py`.
2. Enter the names of the source and target actors.
3. The program will output the shortest path (sequence of movies and actors) connecting them.