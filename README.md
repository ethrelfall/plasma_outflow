# plasma_outflow
Plasma outflows / sheaths physics and numerics

# plasma outflow / acoustic black hole analogy

If there is no source term in the acoustic perturbation equation ($\bar{n}=0$) then that equation is

$$
(2 \sqrt{1-x^2} \psi' )' -(\Omega x \psi)' - \Omega x \psi' - \Omega^2 (1+\sqrt{1-x^2}) \psi =0.
$$

This is related to the zero-rest-mass Klein-Gordon equation with the metric

$$
ds^2 = -2 \sqrt{1-x^2} - 2 x dt dx +(1+\sqrt{1-x^2}) dx^2
$$

noting that one nice algebraic property is that the determinant is just $g=-(1+\sqrt{1-x^2})$.

A more Schwarzschild-like coordinate chart can be derived by removing the off-diagonal metrix components - change the time coordinate such that $dt = dh - \alpha(x) dx$ where $\alpha \equiv \frac{x}{2 \sqrt{1-x^2}}$, giving the line element

$$
ds^2 = -2 \sqrt{1-x^2} dh^2 + \frac{(1+\sqrt{1-x^2})^2}{2 \sqrt{1-x^2}} dx^2.
$$
