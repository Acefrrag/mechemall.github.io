---
    layout: documentation

    project: furuta
    title: Mathematical Modeling
    type: sect
---

The model of the system is from Quansar. To model the system they used a lagrangian approach. To do that it is necessary to describe the configuration of the sytem with the lagrangian coordinates $$[q_{1}, q_{2}, ...... q{n}]$$ with $$ n = d.o.f $$.

{% include_relative images/model.html %}

They decided to describe the system with the angles $$[\theta(t) , \alpha(t)]$$, with the angles positive for CCW rotations of the pendulum,. The angle alpha is measured from the positive $$z$$ semi-axis.



 then they wrote down the lagrangian equation:

$$ \frac{\delta L}{\delta t \delta q_{i}} - \frac{\delta L}{\delta q_{i}} = Q_{i}$$

Where L = T - V is the lagrangian function, with T kinetic energy and V is the potential energy of the whole system whilst $$Q_{i}$$ are the generalized non-conservative forces acting on the entire system with respect to the coordinate $$q_{i}$$.

For the rotary arm:

* it's massless, with inertia $$ J_{r} $$;
* length $$ L_{r} $$;

For the pendulum:

* inertia $$ J_{p} $$;
* it has a lumped mass $$m_{p}$$ positioned at $$ \frac{L_{p}}{2} $$;
* length $$ L_{p} $$;

We have 2 differential equations of motion:

$$ \frac{\delta L}{\delta t \delta \theta} - \frac{\delta L}{\delta \theta} = Q_{1}$$

$$ \frac{\delta L}{\delta t \delta \alpha} - \frac{\delta L}{\delta \alpha} = Q_{2}$$

with $$ Q_{1} = \tau - B_{r} \dot{\theta} $$ and $$Q_{2} = -B_{p}\dot{\alpha}$$, where $$B_{r}$$ and $$B_{p}$$ are the coefficent of viscous friction, and $$\tau$$ is the torque applied by the attached motor.


As a result the lagrange equation of motion are obtained:




<br> <!--Blank Row-->
<br>
<br>
<br>



<footer>
	something
</footer>
