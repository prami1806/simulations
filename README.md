# simulations
Collection of fractals and simulations implemented in python, using matplotlib and turtle graphics.

## Boids model
Boids is an artificial life algorithm, developed by Craig Reynolds in 1986, which simulates the flocking behaviour of birds
As with most artificial life simulations, Boids is an example of emergent behavior; that is, the complexity of Boids arises from the interaction of individual agents (the boids, in this case) adhering to a set of simple rules. The rules applied in the simplest Boids world are as follows:
<ul>
	<li><b>separation</b>: steer to avoid crowding local flockmates</li>
	<li><b>alignment</b>: steer towards the average heading of local flockmates</li>
	<li><b>cohesion</b>: steer to move towards the average position (center of mass) of local flockmates</li>
</ul>	

## Conway's Game of Life automation
The Game of Life, also known simply as Life, is a cellular automaton devised by the British mathematician John Horton Conway in 1970.
The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead, (or populated and unpopulated, respectively). Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
<ul>
	<li>Any live cell with fewer than two live neighbours dies, as if by underpopulation.</li>
	<li>Any live cell with two or three live neighbours lives on to the next generation.</li>
	<li>Any live cell with more than three live neighbours dies, as if by overpopulation.</li>
	<li>Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.</li>
</ul>

## Barnsley Fern
The Barnsley fern is a fractal named after the British mathematician Michael Barnsley
The first point drawn is at the origin (x0 = 0, y0 = 0) and then the new points are iteratively computed by randomly applying one of the following four coordinate transformations:

ƒ1

xn + 1 = 0
yn + 1 = 0.16 yn.<br>
This coordinate transformation is chosen 1% of the time and just maps any point to a point in the first line segment at the base of the stem. This part of the figure is the first to be completed during the course of iterations.


ƒ2

xn + 1 = 0.85 xn + 0.04 yn
yn + 1 = −0.04 xn + 0.85 yn + 1.6.<br>
This coordinate transformation is chosen 85% of the time and maps any point inside the leaflet represented by the red triangle to a point inside the opposite, smaller leaflet represented by the blue triangle in the figure.

ƒ3

xn + 1 = 0.2 xn − 0.26 yn
yn + 1 = 0.23 xn + 0.22 yn + 1.6.<br>
This coordinate transformation is chosen 7% of the time and maps any point inside the leaflet (or pinna) represented by the blue triangle to a point inside the alternating corresponding triangle across the stem (it flips it).

ƒ4

xn + 1 = −0.15 xn + 0.28 yn
yn + 1 = 0.26 xn + 0.24 yn + 0.44.<br>
This coordinate transformation is chosen 7% of the time and maps any point inside the leaflet (or pinna) represented by the blue triangle to a point inside the alternating corresponding triangle across the stem (without flipping it).

## Langton's ant
Langton's ant is a two-dimensional universal Turing machine with a very simple set of rules but complex emergent behavior. It was invented by Chris Langton in 1986 and runs on a square lattice of black and white cells.
Squares on a plane are colored variously either black or white. We arbitrarily identify one square as the "ant". The ant can travel in any of the four cardinal directions at each step it takes. The "ant" moves according to the rules below:

<ul>
	<li>At a white square, turn 90° clockwise, flip the color of the square, move forward one unit</li>
	<li>At a black square, turn 90° counter-clockwise, flip the color of the square, move forward one unit</li>
</ul>
