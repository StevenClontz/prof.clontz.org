---
layout: page
title: "MA 237 Writing Tips"
description: "2020 Spring - Linear Algebra"
---

Linear algebra is less about finding the "final answer", and more about
explaining why the answer is accurate. Here are a few tips that will help
you improve your full solutions so that they clearly communicate what
you're trying to say:

- *Avoid using pronouns unless it's clear what they refer to.* "It" could
be a matrix, or an equation, or a vector... if in doubt, just use the word.
- *Don't write \\(=\\) unless two things are actually equal.*
- *Almost never write \\(\rightarrow\\) in an explanation.* Sometimes the arrow
should be an equal sign. Other times the arrow should be a sentence explaining
what that "next step" is doing. It's okay to use an arrow if you're actually
just using it to point out something.
- *When using a matrix, explain how and why you constructed it.* Often,
you need a matrix because it represents a system of equations - describe
that system.
- *Use "consistent" and "inconsistent" correctly.* A matrix or vector cannot
be consistent or inconsistent. But a system of equations or a vector equation
can be consistent (has a non-empty solution set) or inconsistent
(has an empty solution set due to a contradicition, usually \\(0=1\\)).
It's sometimes okay to say "the system of equations represented by this augmented matrix
is (in)consistent" to avoid writing out the system, but notice that the matrix
must be augmented for this to make sense.
- *Don't just point out the feature of an RREF matrix.* Many problems require
pointing out a feature of an RREF matrix, but you need to explain why that
feature is relevant to the exercise.
- *Answer the question asked.* After your explanation, be sure to conclude
with the (often) "yes" or "no" answer.
- *Don't write a sentence in place of an established mathematical symbol.*
For example, "we now use technology to compute the RREF of the matrix A to
result in the matrix B" could be much more quickly communicated by just writing
$$\operatorname{RREF}(A)=B$$ or $$A\sim B$$.

The [sample solutions PDF](../pdf/ma237-sample-solutions.pdf) will help you
find the right words, but it's important you know what those words mean:
it's very easy for me to tell when a student has memorized a sentence without
understanding it most of the time, because the sentence they wrote usually isn't
exactly what I said (and no longer makes any sense because of the error).
Students who know what they're trying to say won't write exactly what I put
in the sample solution, but they'll write something else with the same
meaning.

These tips are specific to our linear algebra course, but for general advice
on how to clearly communicate mathematics,
[Prof. Francis Su](/classes/2019/08/ma320/pdf/good-math-writing.pdf)
has written a great overview. To see what "professional" mathematical writing
looks like, here's an example of a
[research paper](https://github.com/StevenClontz/research/blob/master/articles/dual-selection-games/article.pdf)
I've written. Or just look in your favorite textbook.

## Tips on explaining spanning/independence

We've covered lots of ways to tell if a set of vectors is spanning
or independent, but here the basic definitions I'd appeal to in order
to *explain* why a set of vectors is spanning or linearly indepednent (since they
directly involve vector equations you can solve with an augmented matrix).

- A set \\(\\{\vec v_1,\dots,\vec v_n\\}\\) of vectors spans a space \\(V\\)
provided that for each \\(\vec v\in V\\), there is at least one solution to the vector
equation \\(x_1\vec v_1+\dots+x_n\vec v_n = \vec v\\).
- A set \\(\\{\vec v_1,\dots,\vec v_n\\}\\) of Euclidean vectors is linearly independent
provided that the only solution to the vector
equation \\(x_1\vec v_1+\dots+x_n\vec v_n = \vec 0\\) is
\\(x_1=\dots=x_n=0\\).

If you need to show something about spanning or independence to solve a larger
problem, then feel free to just say something about pivots, rows, and/or columns.
