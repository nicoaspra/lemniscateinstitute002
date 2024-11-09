---
title: "Concavity and the Second Derivative Test"
prevcontenturl: ../DC-5.4-maxima-and-minima
nextcontenturl: ../DC-6.1-introduction-to-applications-of-derivatives
---



Understanding how a function behaves is crucial, especially around critical points. This is where the concepts of concavity and the second derivative come into play.

The second derivative  $y^{\prime\prime}$  represents the rate of change of the first derivative  $y'$ , which itself is the rate of change of the original function $y$. In other words,  $y^{\prime\prime}$  tells us how the slope  $y'$  is changing as $x$ increases. This insight into the changing slope allows us to determine the concavity of the curve.

{% include images.html 
	url= "DC/DC-5.5.1.jpg" 
	size= "280px"
%}

The curve is **concave upward** when the second derivative is **positive**. This means that the first derivative  $y'$  is increasing as $x$ increases. Graphically, this corresponds to the curve bending upwards like a cup. In this scenario, any tangent line drawn to the curve will lie below the curve itself. At a critical point where  $y' = 0$  and  $y^{\prime\prime} > 0$, the function attains a local minimum because the curve is at its lowest point relative to its neighboring points.


{% include images.html 
	url= "DC/DC-5.5.2.jpg" 
	size= "250px"
%}

On the other hand, the curve is **concave downward** when the second derivative is **negative**. This indicates that the first derivative  $y'$  is decreasing as $x$ increases. The curve bends downwards like an upside-down cup or a dome. In this case, any tangent line drawn to the curve will lie above the curve. At a critical point where  $y' = 0$ and  $y^{\prime\prime} < 0$, the function reaches a local maximum, representing the highest point relative to its neighboring points.

{% include images.html 
	url= "DC/DC-5.5.3.jpg" 
	size= "250px"
%}




---
$\example{1}$
Locate the critical points and determine the maxima and minima of the curve $y=x^3-3x^2-7$.
{% capture include_content %}
To locate the critical points, first differentiate the function:

$$
\begin{align*}
	\ddx\br{y} &= \ddx\br{x^3-3x^2-7} \\
	\dydx &= 3x^2-6x
\end{align*}
$$

For the critical points, set $\dydx=0$.

$$
\begin{align*}
	0 &= 3x^2-6x \\
	0 &= 3x(x-2) \\
	0 &= x(x-2) \\
	\implies 0 &= x \qquad;\quad 0 = x-2 \\
	x &=0 \qquad;\quad  x=2
\end{align*}
$$

Next, find the corresponding  $y$-component with these $x$ values.

For $x=0$,

$$
\begin{align*}
	y &= (0)^3-3(0)^2-7 \\
	y &= -7
\end{align*}
$$

Then check whether it's a maximum or minimum through the Second Derivative Test for point $(0,-7)$

$$
\begin{align*}
	\ddx\br{\dydx} &= \ddx\br{3x^2-6x} \\
	\frac{d^2y}{dx^2} &= 6x-6 \\
	&= 6(0)-6 \\
	y^{\prime\prime} &= -6
\end{align*}
$$

Since $y^{\prime\prime}= -6$ and $y^{\prime\prime}<0$, point $(0,-7)$ is a **maximum**.

For $x=2$,

$$
\begin{align*}
	y &= (2)^3-3(2)^2-7 \\
	y &= -11
\end{align*}
$$

Apply the Second Derivative Test for point $(2,-11)$

$$
\begin{align*}
	\frac{d^2y}{dx^2} &= 6x-6 \\
	&= 6(2)-6 \\
	y^{\prime\prime} &= 6
\end{align*}
$$

Since, $y^{\prime\prime}=6$ and $y^{\prime\prime}>0$, point $(2,-11)$ is a **minimum**.

{% endcapture %}
{% include solution.html details = include_content %}



---
$\example{2}$
Locate the critical points and determine the maxima and minima of the curve, $y=x^2(x+4)^2$

{% capture include_content %}
To locate the critical points, first differentiate the function:

$$
\begin{align*}
	\ddx\br{y} &= \ddx\br{x^2(x+4)^2} \\
	\dydx &= x^2\cdot\ddx\brk{(x+4)^2} + (x+4)^2 \cdot\ddx\br{x^2} \\
	&= x^2(2)(x+4)(1)+(x+4)^2(2x) \\
	&= 2x^3+8x^2+2x(x^2+8x+16) \\
	&= 2x^3+8x^2+2x^3+16x^2+32x \\
	&= 4x^3+24x^2+32x
\end{align*}
$$

For the critical points, set $\dydx=0$.

$$
\begin{align*}
	0 &= 4x^3+24x^2+32x \\
	0 &= 4x(x^2+6x+8) \\
	0 &= 4x(x+2)(x+4) \\
	\implies 0 &= 4x \qquad;\quad 0 = x+2 \qquad;\quad 0 = x+4 \\
	x &=0 \,\,\,\qquad;\quad  x=-2 \qquad\quad;\quad  x=-4
\end{align*}
$$

Determine the corresponding  $y$-component with these $x$ values.


For $x=0$,

$$
\begin{align*}
	y &= (0)^2\brk{(0)+4}^2 \\
	&= 0
\end{align*}
$$

Apply the Second Derivative Test for point $(0,0)$

$$
\begin{align*}
	\ddx\br{\dydx} &= \ddx\br{4x^3+24x^2+32x} \\
	\frac{d^2y}{dx^2} &= 12x^2+48x+32 \\
	y^{\prime\prime} &= 12(0)^2+48(0)+32 \\
	&= 32
\end{align*}
$$

Since $y^{\prime\prime}= 32$ and $y^{\prime\prime}>0$, point $(0,0)$ is a **minimum**.

For $x=-2$,

$$
\begin{align*}
	y &= (-2)^2\brk{(-2)+4}^2 \\
	&= 16
\end{align*}
$$

Apply the Second Derivative Test for point $(-2,16)$

$$
\begin{align*}
	y^{\prime\prime} &= 12(-2)^2+48(-2)+32 \\
	&= -16
\end{align*}
$$

Since $y^{\prime\prime}= -16$ and $y^{\prime\prime}<0$, point $(-2,16)$ is a **maximum**.

For $x=-4$,

$$
\begin{align*}
	y &= (-4)^2\brk{(-4)+4}^2 \\
	&= 0
\end{align*}
$$

Apply the Second Derivative Test for point $(-2,16)$

$$
\begin{align*}
	y^{\prime\prime} &= 12(-4)^2+48(-4)+32 \\
	&= 32
\end{align*}
$$

Since $y^{\prime\prime}= 32$ and $y^{\prime\prime}>0$, point $(-4,0)$ is a **maximum**.

{% endcapture %}
{% include solution.html details = include_content %}



---
$\example{3}$
Locate the critical points and determine the maxima and minima of the curve, $a^3y = x^2(2a^2-x^2)$

{% capture include_content %}
In differentiating the function, we can treat $a$ as a constant. And since $y$ is not explicitly expressed as a function of  $x$, we apply implicit differentiation.

$$
\begin{align*}
	\ddx\br{a^3y} = \ddx\brk{x^2(2a^2-x^2)} \\
	a^3 \dydx &= x^2\cdot\ddx\brk{2a^2-x^2} + (2a^2-x^2)\cdot\ddx\br{x^2} \\
	a^3 \dydx &= x^2(0-2x)+(2a^2-x^2)(2x) \\
	\dydx &= \frac{-2x^3+4a^2x-2x^3}{a^3} \\
	&= \frac{1}{a^3}(4a^2x-4x^3)
\end{align*}
$$

For the critical points, set $\dydx=0$.

$$
\begin{align*}
	0 &= \frac{1}{a^3}(4a^2x-4x^3) \\
	0 &= \frac{4}{a^3}(x)(a^2-x^2) \\
	0 &= x(a^2-x^2) \\
	0 &= x(a+x)(a-x) \\
	\implies 0 &= x \qquad;\quad 0 = a+x \qquad;\quad 0 = a-x \\
	x &=0 \,\qquad;\quad  x=-a \qquad\quad;\quad  x=a
\end{align*}
$$

Determine the corresponding  $y$-component with these $x$ values.

For $x=0$,

$$
\begin{align*}
	a^3y &= x^2(2a^2-x^2) \\
	y &= \frac{x^2(2a^2-x^2)}{a^3} \\
	&= \frac{(0)^2[2a^2-(0)^2]}{a^3} \\
	&= 0
\end{align*}
$$

Apply the Second Derivative Test for point $(0,0)$

$$
\begin{align*}
	\ddx\br{\dydx} &= \ddx\brk{\frac{1}{a^3}(4a^2x-4x^3)} \\
	\frac{d^2y}{dx^2} &= \frac{1}{a^3}(4a^2-12x^2) \\
	y^{\prime\prime} &= \frac{1}{a^3}[4a^2-12(0)^2] \\
	&= \frac{4a^2}{a^3} \\
	&= \frac{4}{a}
\end{align*}
$$

Given that $a$ is positive, $y^{\prime\prime}>0$, hence, point $(0,0)$ is a **minimum**.

For $x=-a$,

$$
\begin{align*}
	&= \frac{(-a)^2[2a^2-(-a)^2]}{a^3} \\
	&= \frac{(a^2)(2a^2-a^2)}{a^2} \\
	&= \frac{(a^2)(a^2)}{a^3} \\
	&= a
\end{align*}
$$

Apply the Second Derivative Test for point $(-a,a)$

$$
\begin{align*}
	y^{\prime\prime} &= \frac{1}{a^3}[4a^2-12(-a)^2] \\
	&= \frac{4a^2-12a^2}{a^3} \\
	&= -\frac{8}{a}
\end{align*}
$$

Given that $a$ is positive, $y^{\prime\prime}<0$, hence, point $(-a,a)$ is a **maximum**.

For $x=a$,

$$
\begin{align*}
	&= \frac{(a)^2[2a^2-(a)^2]}{a^3} \\
	&= \frac{(a^2)(2a^2-a^2)}{a^2} \\
	&= \frac{(a^2)(a^2)}{a^3} \\
	&= a
\end{align*}
$$

Apply the Second Derivative Test for point $(0,0)$

$$
\begin{align*}
	y^{\prime\prime} &= \frac{1}{a^3}[4a^2-12(a)^2] \\
	&= \frac{4a^2-12a^2}{a^3} \\
	&= -\frac{8}{a}
\end{align*}
$$

Given that $a$ is positive, $y^{\prime\prime}<0$, hence, point $(a,a)$ is a **maximum**.

{% endcapture %}
{% include solution.html details = include_content %}



---
$\example{4}$
The curve $y=ax^3+bx^2+cx+d$ has critical points at $(-2,-2)$ and $(0,-6)$. Determine the equation of the curve.

{% capture include_content %}
This problem is not as straightforward as our previous examples, but we can use the concepts we know to solve it. Since the critical points lie on the curve, the function passes through the points  $(-2,-2)$  and  $(0,-6)$. Additionally, at these critical points, the derivative of the function is zero. Using this information, we can create multiple equations to determine the unknown coefficients $a$, $b$, $c$, and $d$.

At point $(-2,-2)$

$$
\begin{align*}
	y &= ax^3+bx^2+cx+d \\
	-2 &= a(-2)^3+b(-2)^2+c(-2)+d \\
	-2 &= -8a+4b-2c+d	\tag{eq.1}
\end{align*}
$$

At point $(0,-6)$

$$
\begin{align*}
	-6 &= a(0)^3+b(0)^2+c(0)+d \\
	-6 &= d	\tag{eq.2}
\end{align*}
$$

We now have two equations, but we have a total of four unknown values. Thus, it is not yet enough to complete the solution.

Another thing that we know, however, is that at the critical points, the derivatives are equal to zero. Hence, we can first differentiate the function:

$$
\begin{align*}
	\ddx\br{y} &= \ddx\br{ax^3+bx^2+cx+d} \\
	\dydx &= 3ax^2+2bx+c
\end{align*}
$$

For the critical point $(-2,2)$, set $\dydx=0$.

$$
\begin{align*}
	0 &= 3a(-2)^2+2b(-2)+c \\
	0 &= 12a-4b+c	\tag{eq.3}
\end{align*}
$$

For the critical point $(0,-6)$, set $\dydx=0$.

$$
\begin{align*}
	0 &= 3a(0)^2+2b(0)+c \\
	0 &= c	\tag{eq.4}
\end{align*}
$$

Now, we have a total of 4 equations, and is now sufficient to solve for the 4 unknown values.


First, we can substitute eq.2 and eq.4 to eq.1,

$$
\begin{align*}
	-2 &= -8a+4b-2(0)+(-6) \\
	4 &= -8a+4b	\tag{eq.5}
\end{align*}
$$

Substitute eq.4 to eq.3,

$$
\begin{align*}
	0 &= 12a-4b+(0) \\
	4b &= 12a \\
	b &= 3a		\tag{eq.6}
\end{align*}
$$

Substitute eq.6 to eq.5

$$
\begin{align*}
	4 &= -8a+4(3a) \\
	4 &= -8a+12a \\
	a &= 1		\tag{eq.7}
\end{align*}
$$

Substitute eq.7 to eq.6

$$
\begin{align*}
	b &= 3(1) \\
	b &= 3
\end{align*}
$$

Thus, we have: $a=1, b=3, c=0, d=-6$

Substituting these values into the original equation gives us the equation of the curve: $y=x^3+3x^2-6$

{% endcapture %}
{% include solution.html details = include_content %}


