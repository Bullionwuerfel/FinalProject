
# Final Project: Public transport density function

Pseudocode:

Import a map of berlin

import an overlay of all the public transport stops in berlin from bvg api

choose a matrix of points in a neighborhood

for each point, calculate the walking distance to the nearest station. 

for each point in the matrix, calculate a color value based on that distance

display the resulting color matrix as a heatmap overlaid on the map of berlin

Additional feature:

enhance the color map by factoring in population density, informing about the potential for improving an areas accessibility to public transport.
