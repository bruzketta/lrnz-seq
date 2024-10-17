# lrnz.seq

### 12-track sequencer based on the Lorenz system, built with Max and gen~

The Lorenz system is a system of differential equations that, under certain parameter values and initial conditions, yields chaotic solutions (known as the Lorenz attractor).

In this patch, starting from a three state variable Lorenz system, the variables are plotted on the three planes xy, xz, yz.

With the help of a `nodes` object and some processing, four different circles can be drawn on every plane and if the plotted values "enter" one of the circles, a single sample click is sent out a separate channel for every circle. The values of the variables are wrapped around a range that keeps them visible for the user.

It's possible to insert x, y, z values and to set a, b, c parameters of the equations. Also rate ad reset controls are provided.

![lrnz seq](https://github.com/user-attachments/assets/fb16080f-f2a6-4889-abf0-1dfc1f46e199)
