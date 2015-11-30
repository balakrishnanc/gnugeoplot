# About

Simple gnuplot script to plot latitude-longitude coordinates on a World map. The attached World map (`world-50m.txt`) is at 1:50m resolution. The script should run fine on OSX as long as gnuplot 4.6.x or higher is installed. On other platforms, the font specified in the script 'Gill Sans' might not be available and hence, adjust the plotting script accordingly. If no text (axis title, legend, or key is required), remove font specifications and let gnuplot choose the default font for the platform.

# Acknowledgements

The script is based on a blog post by Brighten Godfrey [[1]] on how to generate attractive scientific plots using gnuplot.

[1]: http://youinfinitesnake.blogspot.de/2011/02/attractive-scientific-plots-with.html