---
title: "Documentation in Practice"
teaching: 5
exercises: 10
questions:
- "What does developer documentation look like in practice?"
- "What does user documentation look like in practice?"
objectives:
- "Become familiar with real-life examples of documentation."
- "Practice writing different kinds of documentation."
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

## Developer Documentation

### Common Types

### Style Guides

> ## PRACTICE: Euler's Method API Documentation
>
> Have you heard of Euler's Method? It's a way to calculate a numerical
> approximation for the value of a function, based on a starting value `x_0`,
> a particular step size `h`, and the derivative of the function.
>
> Write some API documentation for the following code snippet:
>
> ```
> class EulersMethod(self):
>    def deriv(self, x, y):
>        return y**2 + y*x + x**3
>    def approx(self, y, x, h):
>        y_j = y + h*self.deriv(x, y)
>        x_j = x + h
>        return y_j, x_j
> ```
>
> **BONUS**: How would you improve this code to make it more clear?
>
{:.challenge}

## User Documentation



> ## PRACTICE: Install Python
>
> Assume that you have a new team member who does not have Python on their
> machine and wants to install it. They send you an email to ask how they
> should do it.
>
> * Do you have all the information you need to answer this question? Why or why not?
> * Given only the email, write instructions detailing how to install Python from python.org.
>
{:.challenge}

> ## REMINDER: Culture, Context, Experience
> Keep in mind culture, context, and experience when writing your instructions.
>
{:.callout}

{% include links.md %}

