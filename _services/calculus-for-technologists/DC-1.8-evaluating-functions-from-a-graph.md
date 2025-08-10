---
title: "Evaluating Functions From a Graph"
prevcontenturl: ../DC-1.7-vertical-line-test
nextcontenturl: ../DC-1.9-odd-and-even-functions
---


In analyzing functions represented in a graphical form, we can apply our previous understanding of functions, as we have emphasized the importance of distinguishing between dependent and independent variables. To recall, in [Function Notation](../DC-1.2-function-notation), the independent variable is located inside the parenthesis, while the dependent variable is on the other side of the equation. Translating this to a [graphical form](../DC-1.6-graph-of-functions), the independent variable corresponds to the horizontal position, and the dependent variable determines the vertical position. With this in mind, interpreting functions from a graph becomes more intuitive. To solidify this understanding, let's consider some examples.

---
$\example{1}$
From the given graph, find:
**a.** $ f(2) $,
**b.** $ f(5) $,
**c.** $ f(-6) $,
**d.** $ f(-4) $

		
{% include images.html 
    url= "DC/DC-1.8.1.png" 
    size= "500px"
%}


{% capture include_content %}
To evaluate functions from a graph, remember that $y=f(x)$, so $f(2)$ means that the $x$-coordinate is 2, and if we substitute it to the function we would get its $y$-coordinate. See the figure below.

{% include images.html 
    url= "DC/DC-1.8.2.png" 
    size= "500px"
%}


Hence, \\
**a.** $ f(2) =8$ \\
**b.** $ f(5) =1$ \\
**c.** $ f(-6) =-2$ \\
**d.** $ f(-4) =3$

{% endcapture %}
{% include solution.html details = include_content %}









---
$\example{2}$
From the given graph, find:
**a.** $ f(3)+g(4) $,
**b.** $ (f-g)(5) $,
**c.** $ 5[g(9)] + 2[f(-4)] $,
**d.** $ 7[(g\cdot f)(-6)] $

{% include images.html 
    url= "DC/DC-1.8.3.png" 
    size= "500px"
%}


{% capture include_content %}
In this problem, the solution is similar to the previous example. However, we will only be applying an additional competency that we have learned in the [Combination of Functions](..\DC-1.3-combining-functions).

$\For{a}$ \\
$$
\begin{align*}
	f(3)+g(4) &= 1+(-3) \\
	&= 1-3 \\
	&= -2	\tagans
\end{align*}
$$

$\For{b}$ \\
$$
\begin{align*}
	(f-g)(5) &= f(5)-g(5) \\
	&= 1-(-5) \\
	&= 1+5 \\
	&= 6		\tagans
\end{align*}
$$


$\For{c}$ \\
$$
\begin{align*}
	5[g(9)] + 2[f(-4)] &= 5[-2]+2[3] \\
	&= -10+6 \\
	&= -4		\tagans
\end{align*}
$$


$\For{b}$ \\
$$
\begin{align*}
	7[(g\cdot f)(-6)] &= 7[g(-6) \cdot f(-6)] \\
	&= 7[(-7)\cdot (-2)] \\
	&= 7(14) \\
	&= 98		\tagans
\end{align*}
$$

{% endcapture %}
{% include solution.html details = include_content %}