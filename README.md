## SDSS Computing Studies Python Assignment
### More GUI Input and Output (Total Marks 8)

Objectives:
* To create events triggered by buttons
* To get input from entry widgets and update Labels, Buttons and Entry widgets



### 2 Tasks

##### Task 1
Heron's method is a way of calculating the area of a triangle if all 
3 sides are known but you don't know the height of the triangle.
https://en.wikipedia.org/wiki/Heron%27s_formula#Formulation

The formula is A = sqrt(s(s-a)(s-b)s-c))
where a, b, c are the sides of the triangle, and s is given by:
s = (a+b+c)/2

Create a program that calculates the area of a triangle using the
entryboxes (in task1.png).  If they have enough information to use the
typical triangle area formula (A = b*h/2) then use that, otherwise
calculate the area using Heron's formula.  If that is insufficient,
tell the user that the area cannot be calculated from the information 
given.
(6 points) 

##### Task 2
Having a computer solve problems the way that we might is a challenging
task. Last assignment, you had a computer factor a trinomial using the
quadratic formula.

Today, try and solve the same problem, but using the method that we have
been taught.

There are 3 types of trinomials:
* Difference of Squares
* Trinomials starting with x^2
* Trinomials starting with ax^2

Write a program that uses a human approach to factoring.
Example:
To factor x^2 + bx + c, we first try to find all the pairs of
factors that multiply to make c, and then choose the pair that
adds to make b
To factor ax^2 + bx + c, we first try to find all the pairs of
factors that multiply to make ac, and then find the pair that adds
to make b.  The trinomial is then decomposed to 4 terms and 
is factored by grouping.

This assignment is broken into 3 parts:
* Identify and factor a difference of squares (easy)
* Identify and factor an x^2 trinomial (moderate)
* Identify and factor an ax^2 trinomial (challenging)
