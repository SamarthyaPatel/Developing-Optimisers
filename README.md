# Developing-Optimisers

### Coursework for Optimisation Module.

Implementation of <strong>Random Search (RS)</strong> and <strong>Simulated Annealing (SA)</strong> to develop optimisers that can use the functions defined and return an approximation of the optimum.

<strong>Problem description: Welded Beam Design</strong>

![optimiser](https://user-images.githubusercontent.com/86912122/219978607-c022b585-78da-4ad9-8334-672de49d4990.png)

In a welded beam design system, we often aim to minimise the cost of manufacturing the beam, that has a fixed length sticking out of the welded surface. This depends on the four design variables: x = (x1,x2,x3,x4)⊤, where x1 is the height h and x2 is the length l of the welded part, and x3 is the thickness t and x4 is the breadth b of the beam.
The objective function can be expressed as:
minx∈X f(x) = 1.10471x21x2 + 0.04811x3x4 (14.0 + x2).

<ol>
<li> Implementation of all the functions f(x) and gi(x); ∀i ∈ [1,4] independently, where each function takes at least a Numpy array x. Each function has an independent counter that represents how many times a respective function has been called (or in other words evaluated). </li>
<li> Implementation of Random Search (RS) method discussed in the lectures that can use the functions defined and return an approximation of the optimum. </li>
<li> Implementation of Simulated Annealing (SA) method that can use the functions defined and return an approximation of the optimum solution x∗. </li>
<li> For 21 repetitions of each of the algorithms implemented in 2 and 3, compared the performances of these optimisers. The number of evaluations for each individual function f(x) or gi(x) that you are allowed at each instance of an optimisation run is 10000 at most. </li>
</ol>
