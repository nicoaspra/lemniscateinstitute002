---
title: "Function Notation"
prevcontenturl: ../DC-1.1-introduction-to-functions
nextcontenturl: ../DC-1.3-combining-functions
---


Function notation is just another way of writing a function that is represented in equation form. Instead of writing the dependent variable $y$, this notation uses $f(x)$, and is denoted as $y = f(x)$, which is read as "$y$ is a function of $x$."
{% include tcolorbox.html 
    details= "
        y=f(x)
        "
%} 
For instance, $y = 3x^2 - 5$  can be written as  $f(x) = 3x^2 - 5$. To evaluate the function at a specific value, for example when $x = 2$, we replace all instances of $x$ with 2:

$$
\begin{align*}
	f(x) &= 3x^2-5 \\
	f(\tcA{2}) &= 3(\tcA{2})^2-5 \\
	      &= 3(4)-5 \\
	f(\tcA{2}) &= \tcB{7} \tagans
\end{align*}
$$

A significant advantage of utilizing this notation is that we can quickly identify the $\tcA{input}$ and the $\tcB{output}$ of the function by just looking at the final equation. The input is the value inside the parenthesis, and the output is the value on the other side of the equation.



{% include youtube.html 
    id="fxL8wD_4HCw" 
%}


---
$\example{1}$ \\
Let $ f(x)=3x^2+2x+5 $, find \
a. $f(0)$,
b. $f(-5)$,
c. $f(-4x)$,
d. $f(y)$,
e. $f(x-y)$


{% include solution.html details = "
$\For{a}$ \\
Replace $x$ with $0$

$$
	\begin{align*}
		f(x) &= 3x^2+2x+5 \\
		f(0) &= 3(0)^2+2(0)+5  \\
		      &= 0+0+5 \\
		      &= 5	\tagans
	\end{align*}
$$

$\For{b}$ \\
Replace $x$ with $-5$
$$
	\begin{align*}
		f(x) &= 3x^2+2x+5 \\
		f(-5) &= 3(-5)^2+2(-5)+5 \\
		      &= 3(25)+(-10)+5 \\
		      &= 75-10+5 \\
		      &= 70	\tagans
	\end{align*}
$$

$\For{c}$ \\
Replace $x$ with $4x$
$$
	\begin{align*}
		f(x) &= 3x^2+2x+5 \\
		f(4x) &= 3(4x)^2+2(4x)+5 \\
		      &= 48x^2+8x+5	\tagans
	\end{align*}
$$

$\For{d}$ \\
Replace $x$ with $y$
$$
	\begin{align*}
		f(x) &= 3x^2+2x+5 \\
		f(y) &= 3(y)^2+2(y)+5 \\
		      &= 3y^2+2y+5	\tagans
	\end{align*}
$$

$\For{e}$ \\
Replace $x$ with $x-y$
$$
	\begin{align*}
		f(x) &= 3x^2+2x+5 \\
		f(x-y) &= 3(x-y)^2+2(x-y)+5 \\
		      &= 3(x^2-2xy+y^2)+2x-2y+5 \\
		      &= 3x^2-6xy+3y^2+2x-2y+5		\tagans
	\end{align*}
$$

"
%}



---	



However, other letters or symbols can also be used before the variable to name the same function. Notations like $f(x)$, $g(x)$, $F(x)$, $\phi(x)$, etc. are just different representations of "function of $x$,'' since all of these notations have the same independent variable $x$. For instance $y = 3x^2 + 2x − 7$ can be written as any of the following:

{% include colorbox.html 
    details= "
        \begin{align*}
            f(x) &= 3x^2+2x-7	&	v(x) &= 3x^2+2x-7 	\\
            g(x) &= 3x^2+2x-7	&	R(x) &= 3x^2+2x-7 	\\
            h(x) &= 3x^2+2x-7 	&	\theta(x) &= 3x^2+2x-7 \\
        \end{align*}
        "
%} 

Nonetheless, it is not confined to the variable $x$;  it can be applied to any dependent variable.

Using distinct symbols is advantageous when dealing with two or more distinct functions that share common dependent and independent variables since it can act as the function's name.

---
$\example{2}$
Let $g(x)=x^2-3$ and $h(x)=7-2x$, find 
a. $g(3)$,
b. $g(-2x)$,
c. $h(-5)$,
d. $h(3x-y)$



{% include solution.html details = "
$\For{a}$ \\
Since $g(3)$ is required, we can quickly identify what function is the question relating to, 
$$
\begin{align*}
	g(x) &= x^2-3 \\
	g(3) &= (3)^2-3 \\
	&= 6		\tagans
\end{align*}
$$

$\For{b}$ \\
Replace $x$ with $-2x$
$$
\begin{align*}
	g(x) &= x^2-3 \\
	g(-2x) &= (-2x)^2-3 \\
	&= 4x^2-3		\tagans
\end{align*}
$$

$\For{c}$ \\
Replace $x$ with $-5$
$$
\begin{align*}
	h(x) &= 7-2x \\
	h(-5) &= 7-2(-5) \\
	&= 17		\tagans
\end{align*}
$$

$\For{d}$ \\
Replace $x$ with $3x-y$
$$
\begin{align*}
	h(x) &= 7-2x \\
	h(3x-y) &= 7-2(3x-y) \\
	&= 7-6x+2y	\tagans
\end{align*}
$$

"
%}


---
$\example{3}$ \\
Let $h(y)=7-4y-3y^2$, find $h(-4)$

{% include solution.html details = "
Replace $y$ with $-4$
$$
\begin{align*}
	h(y) &= 7-4y-3y^2 \\
	&= 7-4(-4)-3(-4)^2 \\
	&= 7+16-3(16) \\
	&= -25	\tagans
\end{align*}
$$

"
%}


---
$\example{4}$
If $v(t)=3t+7$ and $v(t)=19$, find $t$

{% include solution.html details = "
In this example, the output of the function is given, and the input $t$ is required,

$$
\begin{align*}
	v(t) &= 3t+7
\end{align*}
$$

Since $v(t)=19$, we can substitute $v(t)$ with 19,

$$
\begin{align*}
	19 &= 3t+7 \\
	12 &= 3t \\
	t &= 4	\tagans
\end{align*}
$$

"
%}
