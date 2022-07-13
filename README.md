#+TITLE:  Enhanced Self-Organizing Map Solution for the Traveling Salesman Problem
#+AUTHOR: Joao P. A. Dantas, Andre N. Costa, Marcos R. O. A. Maximo, Takashi Yoneyama

Using an enhanced Self-Organizing Map method, we provided suboptimal solutions to the Traveling Salesman Problem. Besides, we employed hyperparameter tuning to identify the most critical features in the algorithm. All improvements in the benchmark work brought consistent results and may inspire future efforts to improve this algorithm and apply it to different problems.

Please check the [[https://arxiv.org/abs/2201.07208][full paper]] if you need any additional information.

To run the code, you will need Python 3 and R and their dependencies. Please check the two jupyter notebooks that are in the =code= folder.

The images generated will be stored in the =diagrams= folder. Using a tool like
=convert=, you can easily generate an animation like the one in this file by
running:

#+BEGIN_SRC sh
convert -delay 10 -loop 0 *.png animation.gif
#+END_SRC
