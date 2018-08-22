---
layout: post
title: "Simple Pendulum"
date: 2018-08-18 15:28:59 -0400
categories: draft
author: "Bart Simpson"
meta: "Springfield"
---

Let us consider the simple pendulum placed in a uniform gravitational field.

The coordinates of the mass are 

$$
\begin{equation}
   \left\{ 
   \begin{array}{r c l}
   x & \hspace{-1ex} =& \hspace{-1ex} \ell\sin\phi \\
   y & \hspace{-1ex} =& \hspace{-1ex} -\ell\cos\phi 
   \end{array} \right. 
\end{equation} 
$$

such that the kinetic and potential energy are

$$
\begin{equation}
   T = \frac{1}{2}m[(\ell\dot{\phi}\cos\phi)^2 + (\ell\dot{\phi}\sin\phi)^2] = \frac{1}{2} m \ell^2 \dot{\phi}^2
\end{equation}
$$

and 

$$
\begin{equation}
   U = -mg\ell\cos\phi , 
\end{equation} 
$$

respectively. Hence the Lagrangian of the system is 

$$
\begin{equation}
   L = \frac{1}{2} m \ell^2 \dot{\phi}^2 + mg\ell\cos\phi .
\end{equation} 
$$
	

The relevant derivatives of the Euler-Lagrange equation are

$$
\begin{align}
   \frac{\partial L}{\partial \dot{\phi}} &= m\ell^2 \dot{\phi} \\
   \frac{d}{dt} \frac{\partial L}{\partial \dot{\phi}} &= m \ell^2 \ddot{\phi} \\
   \frac{\partial L}{\partial \phi} &= -mg\ell\sin\phi 
\end{align}
$$

such that equation of motion is 

$$
\begin{equation}
   \ell\ddot{\phi} + g \sin\phi = 0 .
\end{equation} 
$$
