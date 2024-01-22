## Double rigid-body pendulum

$$
\begin{align*}
\frac{d\theta_1}{dt} &= \omega_2 \\
\frac{d\theta_1}{dt} &= \omega_2 \\
\begin{bmatrix}
I_1 + m_1a_1^2 + m_2l_1^2 & m_2l_1a_2 \cos(\theta_1 - \theta_2) \\
m_2l_1a_2 \cos(\theta_1 - \theta_2) & I_2 + m_2a_2^2
\end{bmatrix}
\begin{bmatrix}
\frac{d\omega_1}{dt} \\
\frac{d\omega_2}{dt}
\end{bmatrix}
&=
\begin{bmatrix}
m_2l_1a_2 \omega_2 (\omega_1 - \omega_2) \sin(\theta_1 - \theta_2) - m_2l_1a_2 \omega_1 \omega_2 \sin(\theta_1 - \theta_2) - g\sin\theta_1 (m_1a_1 + m_2l_1) \\
m_2l_1a_2 \omega_1 (\omega_1 - \omega_2) \sin(\theta_1 - \theta_2) + m_2l_1a_2 \omega_1 \omega_2 \sin(\theta_1 - \theta_2) - g\sin\theta_2 m_2a_2
\end{bmatrix}
\end{align*}
$$

Here,
- $ \theta_1 $ represents the angle of pendulum 1 (unit: $rad$).
- $ \theta_2 $ represents the angle of pendulum 2 (unit: $rad$).
- $ \omega_1 $ represents the angular velocity of pendulum 1 (unit: $rad/s$).
- $ \omega_2 $ represents the angular velocity of pendulum 2 (unit: $rad/s$).
- $ m_1 $ represents the mass of rigid body 1 (unit: $kg$).
- $ m_2 $ represents the mass of rigid body 2 (unit: $kg$).
- $ a_1 $ represents the length of pendulum 1 (unit: $m$).
- $ a_2 $ represents the length of pendulum 2 (unit: $m$).
- $ l_1 $ represents the length of pendulum 1 (unit: $m$).
- $ l_2 $ represents the length of pendulum 2 (unit: $m$).
- $ g $ represents the acceleration due to gravity (unit: $m/s^2$).
- $ I_1 $ represents the moment of inertia of pendulum 1 about the center of mass and the $z$ axis (unit: $kgm^2$).
- $ I_2 $ represents the moment of inertia of pendulum 2 about the center of mass and the $z$ axis (unit: $kgm^2$).
