# plasma_outflow
Plasma outflows / sheaths physics and numerics

# plasma outflow / acoustic black hole analogy

If there is no source term in the acoustic perturbation equation ($\bar{n}=0$) then that equation is (note it looks a bit like Chebyshev's equation)

$$
(2 \sqrt{1-x^2} \psi' )' -(\Omega x \psi)' - \Omega x \psi' - \Omega^2 (1+\sqrt{1-x^2}) \psi =0.
$$

This is related to the zero-rest-mass Klein-Gordon equation with the metric

$$
ds^2 = -2 \sqrt{1-x^2} dt^2 - 2 x dt dx +(1+\sqrt{1-x^2}) dx^2
$$

noting that one nice algebraic property is that the determinant is just $g=-(1+\sqrt{1-x^2})^2$.

A more Schwarzschild-like coordinate chart can be derived by removing the off-diagonal metric components - change the time coordinate such that $dt = dh - \alpha(x) dx$ where $\alpha \equiv \frac{x}{2 \sqrt{1-x^2}}$, giving the line element

$$
ds^2 = -2 \sqrt{1-x^2} dh^2 + \frac{(1+\sqrt{1-x^2})^2}{2 \sqrt{1-x^2}} dx^2.
$$

Note that if the source terms are reinstated then the equation is very very similar to the KG equation obtained from the metric above ... algebraic mistakes?

For the record, that KG equation is

$$
\left ( \frac{2 \sqrt{1-x^2} \psi'}{1+\sqrt{1-x^2}} \right )' - \Omega \left ( \frac{x \psi}{1+\sqrt{1-x^2}} \right )' - \frac{\Omega x \psi'}{1+\sqrt{1-x^2}} - \Omega^2 \psi =0.
$$

and the acoustic perturbation equation with the source terms in is

$$
\left ( 2 \sqrt{1-x^2} \psi' -2 \Omega x \psi - \frac{1-\sqrt{1-x^2}}{x} \psi \right )' - \left ( 1+\sqrt{1-x^2} \right ) \Omega^2 \psi = 0.
$$

Please could the two equations above just be the same thing ... :)
