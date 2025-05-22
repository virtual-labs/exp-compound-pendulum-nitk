A double pendulum system as shown in Fig 1, consists of two-point masses $m_1$ and $m_2$ suspended by strings of length $l_1$ and $l_2$ as shown below. Let the system vibrates in vertical plane with small amplitudes, under which conditions the masses may be considered to have only horizontal motion. Let $θ_1$ and $θ_2$ be the angles the strings at any instant make with vertical and let $x_1$ and $x_2$ be the horizontal displacements of the two masses, such that the following relationships holds good for small amplitudes.

<center>

<!-- ![](images/1.png) -->

$\sin \theta_1 = \theta_1 = \frac{x_1}{l_1}$   
$\sin \theta_1 = \theta_2 = \frac{x_2-x_1}{l_2}$


</center>

For finding natural frequency and mode shapes:
Considering no motion in vertical direction, the vertical components of forces on each of two masses must balance. Therefore,

<center>

<!-- ![](images/2.png) -->

$T_2 = m_2g $  
$T_1 = m_1g + T_2 = (m_1 - m_2)g$

![](images/3.png)

Fig 1. Repesentation of variables in the double pendulum

<!-- ![](images/5.png) -->

<img src="images/5.png" width=200 height=300 />

Fig 2. Free body diagram of the double pendulum
</center>

Writing down the equation of motion of two masses for motion in horizontal direction from Fig 2, we have
<center>

<!-- ![](images/4.png) -->

$m_1\ddot{x}_1 = T_2 \sin\theta_2 - T_1 \sin\theta_1$  
$m_2\ddot{x}_2 = -T_2 \sin\theta_2$

</center>

If we take $T_1$ and $T_2$ values in the above equation, we get

<center>

<!-- ![](images/6.png) -->

$m_1\ddot{x}_1 + \left[ \frac{m_1+m_2}{l_1} + \frac{m_2}{l_2} \right] gx_1 = \frac{m_2}{l_2} gx_2 $  
$m_2\ddot{x}_2 + \frac{m_2}{l_2} gx_2 = \frac{m_2}{l_2} gx_1$

</center>

Assuming the general solution of equation of motion to be:

<center>

<!-- ![](images/7.png) -->

$x_1 = X_1 \sin(\omega t)$  
$x_2 = X_2 \sin(\omega t)$

</center>

Substituting the above solutions with the equation of motion, we get

<center>

<!-- ![](images/8.png) -->

$\left\{ -m_1\omega^2 + \left[ \frac{m_1+m_2}{l_1} + \frac{m_2}{l_2} \right]g \right\} X_1 = \frac{m_2}{l_2} g X_2$  
$\left\{ -m_2\omega^2 + \left[ \frac{m_2}{l_2} \right]g \right\} X_2 = \frac{m_2}{l_2} g X_1$

</center>

This equation will give,
<center>

<!-- ![](images/9.png) -->

$\frac{X_1}{X_2} = \frac{\frac{m_2}{l_2}g}{-m_1\omega^2+\left[\frac{m_1+m_2}{l_1}+\frac{m_2}{l_2}\right]g}$  
$\frac{X_1}{X_2} = \frac{-m_2\omega^2+\left[\frac{m_2}{l_2}\right]g}{\frac{m_2}{l_2}gX_1}$

</center>

Equating the two expressions in the above two equations and cross multiplying.

If $E = (m_2 g)/l_2$ and $F = (m_1+m_2)g/l_1$ , then the frequency equation is

<center>

<!-- ![](images/10.png) -->

$\omega^4 - [\frac{(m_1+m_2)E + m_2F}{m_1m_2}]\omega^2 + \frac{FE}{m_1m_2} = 0$

</center>

The above equation is quadratic in $\omega^2$ and gives two values of $\omega^2$, and therefore two positive values of 
$\omega$ corresponding to two natural frequencies $\omega_{n1}$ and $\omega_{n2}$ of the system. The above equation is called the frequency equation since the roots of this equation gives the natural frequencies of the system.
Considering,
<center> 

<!-- ![](images/23.png) -->

$m_1 = m_2 = m$  
$l_1 = l_2 = l$

</center>
The above equations become,

<center>

<!-- ![](images/11.png) -->

$\frac{X_1}{X_2} = \frac{g/l}{\frac{3g}{l} - \omega^2}$

$\frac{X_1}{X_2} = \frac{\frac{g}{l} - \omega^2}{\frac{g}{l}}$



</center>

which gives,

<center>

<!-- ![](images/12.png) -->

$\frac{g/l}{\frac{3g}{l} - \omega^2}=\frac{\frac{g}{l} - \omega^2}{\frac{g}{l}}$

</center>
or
<center>

<!-- ![](images/13.png) -->

$\frac{w^4}{g^2} - \frac{4w^4}{l^g} + \frac{2}{l^2} = 0$

</center>
which is the frequency equation.

Solving for $\omega$, using quadratic equation we have the two values of the natural frequencies as,
<center>

<!-- ![](images/14.png) -->

$w_{n1} = \sqrt{\frac{g}{l}(2-\sqrt2)}$  
$w_{n2} = \sqrt{\frac{g}{l}(2+\sqrt2)}$

</center>

The amplitude ratio of the equations are:
<center>

<!-- ![](images/15.png) -->

$\frac{X_1}{X_2} = \frac{\frac{m_2}{l_2} g}{-m_1 \omega^2 + \left[ \frac{m_1 + m_2}{l_1} + \frac{m_2}{l_2} \right] g}$


<!-- ![](images/16.png) -->

$\frac{X_1}{X_2} = \frac{ -m_2 \omega^2 + \left[ \frac{m_2}{l_2} \right] g }{ \frac{m_2}{l_2} g X_1 }
$

</center>

If in either of the equations, on substituting for $\omega$ the value of $\omega_{n1}$, we have the first mode shape of the system i.e., when the system is vibrating with the first natural frequency $\omega_{n1}$, the mode shape is such that the ratio of the amplitude of two masses is equal to the solution of above equation.

Similarly, in either of the equations, substituting for $\omega$ the value of $\omega_{n2}$, we have the second mode shape of the system i.e., when the system is vibrating with the second natural frequency $\omega_{n2}$, the mode shape is such that the ratio of the amplitude of two masses is equal to the solution of above equation.

For calculating the motion of point masses:

The cartesian co-ordinates of two-point masses in a double pendulum are,

<center>

![](images/17.png)

</center>

On solving the equations of motion in polar coordinates and we are going to use the Lagrangian method ($L=T-V$ where $T$ is kinetic energy of system and $V$ is potential energy of system) to derive them. 

The kinetic energy of the system:

<center>

<!-- ![](images/18.png) -->

$
T = \frac{1}{2} m_1 v_1^2 + \frac{1}{2} m_2 v_2^2
$

$
T = \frac{1}{2} m_1 (\dot{x}_1^2 + \dot{y}_1^2) + \frac{1}{2} m_2 (\dot{x}_2^2 + \dot{y}_2^2)
$

$
T = \frac{1}{2} m_1 l_1^2 \dot{\theta}_1^2 + \frac{1}{2} m_2 \left[ l_1^2 \dot{\theta}_1^2 + l_2^2 \dot{\theta}_2^2 + 2 l_1 l_2 \dot{\theta}_1 \dot{\theta}_2 \cos(\theta_1 - \theta_2) \right]
$


</center>

The potential energy of system:
<center>

<!-- ![](images/19.png) -->

$
V = m_1 g y_1 + m_2 g y_2
$

$
V = - (m_1 + m_2) g l_1 \cos\theta_1 - m_2 g l_2 \cos\theta_2
$


</center>

The Lagrange equations for $\theta_1$ and $\theta_2$ are,
<center>

<!-- ![](images/21.png) -->

$\frac{d}{dt} \left( \frac{d L}{d \dot{\theta}_l} \right) - \frac{d L}{d \theta_l} = 0
$

</center>

On solving,
<center>

<!-- ![](images/20.png) -->

$\ddot{\theta}_1 = \frac{g(\sin\theta_2 \cos(\theta_1 - \theta_2) - \mu \sin\theta_1) - (l_2 \dot{\theta}_2^2 + l_1 \dot{\theta}_1^2 \cos(\theta_1 - \theta_2)) \sin(\theta_1 - \theta_2)}{l_1 (\mu - \cos^2(\theta_1 - \theta_2))}$

$\ddot{\theta}_2 = \frac{g \mu (\sin\theta_1 \cos(\theta_1 - \theta_2) - \sin\theta_2) - (\mu l_1 \dot{\theta}_1^2 + l_2 \dot{\theta}_2^2 \cos(\theta_1 - \theta_2)) \sin(\theta_1 - \theta_2)}{l_2 (\mu - \cos^2(\theta_1 - \theta_2))}$

</center>

Where $\mu = 1 + (m_1 + m_2)$, $ \ddot θ1 $ and $ \ddot θ2 $ are angular accelerations of point masses $m_1$ and $m_2$ and $ \dot θ1 $ and $ \dot θ2 $ are angular velocities of point masses $m_1$ and $m_2$.

<!-- To solve the equation of motion for the angles, we can use the Euler method. For using Euler method, we should define a time interval and iterate over time. As time changes, angular acceleration, angular velocity and angle is changed. So, from the values of angular acceleration, velocity and angle at that instant of time, we can calculate the position of the system precisely. 
Such that,
<center>

![](images/22.png)

</center> -->
