# CS50’s Introduction to AI with Python

## Lecture 0: Search Problem

### Project 0: Degrees

Program that determines how many “degrees of separation” apart two actors are. 

Using the Breadth-First Search algorithm, we look for the shortest path between any two actors by choosing a sequence of movies that connects them. For example, the shortest path between Emma Watson and Jennifer Lawrence is 3: 

```
$ python degrees.py large
Loading data...
Data loaded.
Name: Emma Watson
Name: Jennifer Lawrence
3 degrees of separation.
1: Emma Watson and Brendan Gleeson starred in Harry Potter and the Order of the Phoenix
2: Brendan Gleeson and Michael Fassbender starred in Trespass Against Us
3: Michael Fassbender and Jennifer Lawrence starred in X-Men: First Class
```