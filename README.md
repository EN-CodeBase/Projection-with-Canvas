# Projection-with-Canvas
This is code from a beautiful tutorial by Tsoding on YT. i learned a thingy here &amp; that is 3D -> 2D Projection!  :)


# To Project

Use th formulas:

$$
\begin{aligned}
x' &= \frac{x}{z} \\
y' &= \frac{y}{z}
\end{aligned}
$$

This is how you make a 3d point be projected on a 2d screen

Everything else on this file is the neceseary code neeeded to draw on the canvas.

If you want to change the image:
  1) add verticies to vs array
  2) add faces (groups of verticies connected in order) to the fs array
