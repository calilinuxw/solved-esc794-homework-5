Download Link: https://assignmentchef.com/product/solved-esc794-homework-5
<br>
<strong>1 </strong>Work out every step of the proof of Lemmas 5.2 and 5.4 in the textbook by Gru¨ne and Pannek, finding a justification for each step taken. Be prepared to discuss your reasoning during class on 11/20.

<strong>2</strong>

Make a small modification to the discrete-time MPC code provided by the instructor

(MPCdlqrNoTerminal.m) to include a terminal equilibrium constraint. Simulate the constraintfree and the equilibrium terminal constraint cases under the same cost function, horizon and initial conditions. In each case, show time plots of the predicted trajectories and the closedloop trajectories. Comment on the results.

<strong>3</strong>

Make a small modification to the continuous-time MPC code provided by the instructor

(CTdoubleIntMPCNoTerm.m) to include a terminal equilibrium constraint. Simulate the constraint-free case with <em>T </em>= 0<em>.</em>5 and <em>δ </em>= 0<em>.</em>05 (<em>N </em>= 10), with <em>Q </em>= <em>I </em>and <em>R </em>= 1, using the provided initial condition. Then simulate the terminal equilibrium case under the same conditions. Comment on the results.

<strong>4</strong>

For the continuous-time double-integrator plant with input constraints U = [−1 1], use the linear method described in class to find an ellipsoidal terminal region and a terminal cost. Use <em>Q </em>= <em>I </em>and <em>R </em>= 1 and <em>δ </em>= 0<em>.</em>1. Then implement MPC with terminal set constraints and terminal cost. Tune the horizon for a compromise between initial feasibility and optimization speed (i.e., you may allow some infeasibility for the first few OPC runs, using fmincon’s maximum iteration limit to keep going). Use <em>T </em>= 1<em>.</em>5 initially.

It is recommended to use an initial guess based on a simulation of the plant with some arbitrary control input (such as a constant). Provide a phase plot of the predicted and actual closed-loop trajectories and show the terminal set. Experiment with <em>α </em>smaller than the maximum allowed for <em>U<sub>max</sub></em>.

<strong>5</strong>

Use ACADO to simulate an MPC controller according to Problem 5.8 in Gru¨ne and Pannek (<em>N </em>= 2). Use the supplied discrete-time example and make small modifications. Verify that the closed-loop system is asymptotically stable.