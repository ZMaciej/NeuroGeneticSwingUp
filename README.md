# NeuroEvolutionSwingUp
* The neural network regulator is tuned by genetic algorithm that causes the double inverted pendulum to swing up.
* Dynamics of DIP are solved by Runge–Kutta 4 (RK4) solver. 
* The pendulum is stabilized by the feedback loop when it reaches the upper position.
* Neural network have only one hidden layer.
* When the pendulum hits an edge, its power is cut off and no more points are scored.

Point are scored as described below:

<img src=/img/angle_points.jpg alt="IMAGE ALT TEXT HERE" width="500" border="10" />
