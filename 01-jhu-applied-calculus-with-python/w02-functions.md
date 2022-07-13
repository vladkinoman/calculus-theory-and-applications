# Functions

A **function** is a relationship between a set of inputs (x_i) and a set of outputs (y_i), where each input corresponds to exactly one output.

The input is also called the **independent variable**, and the output is called the **dependent variable**. 

The input of a function is also called the **argument**.

The set of all possible inputs for the function is called the **domain**, and the set of all possible outputs is called the **range**.

Functions are often written in **function notation**. $$y=f(x)$$ is read as "y equals f of x.' This notation means that y, the dependent variable, is a function of the independent variable x. 

## Representations of functions

Functions can be given through mathematical formulas, tables, graphs, and verbal descriptions. 

The tools of calculus are used on functions that are given as mathematical formulas. As a result, in this course we will see some **modeling functions** - mathematical formulas that fit real-world scenarios expressed through tables of data or visuals.

## Evaluating a function

To evaluate a function at a certain value, we substitute that value for every occurrence of the independent variable. 

For example, to evaluate the function $$f(x)=2x^2−x$$ at $$x=−1\\,$$ we substitute −1 for every x, to get $$f(−1)=2(−1)^2−(−1)=2(1)+1=3\\.$$

# Linear functions

A **linear function** is a function of the form $$f(x)=mx+b\\,$$ where m and b are constants. 

The graph of a linear function is a straight line with slope m and y-intercept (0,b). 

## Calculating slope

If you know the value of a linear function f at two points, x1 and x2, then you can find its **slope** (кутовий коефіцієнт) or **gradient** of a line ([wiki](https://en.wikipedia.org/wiki/Slope)).

$$\boxed{\text{slope} = m = \dfrac{f(x_2) - f(x_1)}{x_2 - x_1}}$$

In general, the slope of a line through two points (x1,y1) and (x2,y2) is given by  $$m = \dfrac{y_2 - y_1}{x_2 - x_1}\\,$$ and often summarized as slope=rise/run. 

The slope of a linear function can be thought of as the **rate of change** in the function. 

## Parallel and perpendicular

**Parallel lines**, lines that never intersect, must have the same slope.

A line that is parallel to a line of slope m has slope m as well. 

**Perpendicular lines** are lines that intersect at a right angle (90∘).

A line that is perpendicular to a line of slope m has slope −1/m.

## Forms for linear functions

There are two main forms used to write equations of lines: **slope-intercept form** and **point-slope form**. 

You can use either form for any line. Depending on the information you have about a line, one form may be quicker to write than the other.

### Slope-Intercept Form

$$\boxed{y = mx + b}$$

m is the slope of the line.

(0,b) is the y-intercept of the line.

### Point-Slope Form

$$\boxed{y - y_0 = m(x - x_0)}$$

m is the slope of the line.

(x0,y0) are the coordinates of any chosen point on the line.

## Functions and models

f: a rule that assigns ∀ x ∈ A → f(x) ∈ B.

ex. sqrt(2)

- Domain: x>=0 (sqrt(2)), [0, ∞]
- Range: y>=0 [0, ∞]

(f(a+h) - f(a)) / h - difference quotient, h ≠ 0

VLT - vertical line test: crosses twice - fails, so it's not a graph of a function.

**Piecewise defined functions**

You use the piece according to what condition is met on the inputs

Ex.
$$
f(x) = \begin{equation}
\begin{cases}
x^2 + 1,\ x \ge 0\\
x,\ x \lt 0
\end{cases}
\end{equation}
$$

- reading right to left.
- first - parabola pushed up 1
- bottom piece: the line goes down to negative infinity forever
- Domain: all Reals
- Range: (-∞, 0) ∪ [1, ∞)

**Symmetry**

Ex. {x x>= 0, -x x<0}

- symmetric about the y axis there
- **the absolute value of a number**
- D: all Reals
- R: [0, ∞)

**Definition**. f(x) is **even** if f(x)=f(-x) <=> y-axis symmetry

> the input of the pos or neg value produces the same output.

Ex. even powers, abs, cos(x).

**Definition**. f(x) is **odd** if f(x) = -f(x) <=> origin symmetry (spinning at 180 degrees)

> negates the entire function

Ex. odd powers (y=x cubed = the  disco function), sin(x)

**Definition**. f is increasing on interval [a, b] if f(x1) > f(x2) whenever x1 > x2 <=> "going up".

**Ex.**

slope = this the change of y over (/) the change of x.

pt-slope formula: y-y1 = m (x-x1)

y =|x| - V or a cusp.

y = x^3 (x cubed) - disco function, it goes low to high.

y = sin x (сайн of x) - sine goes right through the origin, it has a height of 1 & -1 (so it oscillates). Oscillates goes on and on forever and ever D: R, R: [-1, 1]

**Function composition**

You given 2 funcs. You can add them & subtract them, divide as long as the bottom is not zero.

Func. compos. is something that you cannot do with numbers.

**Def**. f * g ("f composed with g" = I take one function and I plug it into another).

(f * g)(x) = f(g(x))

When you're evaluating these things, you read them right to left.

This operation is not commutative! f(g(x)) ≠ g(f(x)). Commutative means order doesn't matter.

$$\sqrt(\sqrt(x)) = x^{1/4}$$

so this becomes x to the one forth.
