# Extended Spinfoam

We provide functions which can be used to generate the boundary data as well as corresponding critical configurations of the extended spin foam model (EPRL with Conrady-Hnybida extension, ArXiv:1002.1959) which can contain both timelike and spacelike faces.

Here we use it to demonstrate that the parity transformation generates new classes of gauge inequivalent solutions of the extended spinfoam models. 
Such transformation is given as
$$
g \to g^{-1 \dagger}, \;\; for \ \text{SU(2)} \ , \qquad
g \to g^{-1 \dagger} i \sigma_3, \;\; for \ \text{SU(1,1)} \ .
$$
The derivation is shown in the note parity.md.

We also verify that above critical configurations are still critical solutions when we derive the equation of motion iteratively from the action (Appendix B5. in ArXiv: 1810.09042).
$$
0 = \delta_{x_1} S(x_1,x_2, \dots, x_n) \\
0 = \delta_{x_2} S(x_1^0,x_2, \dots, x_n)\\
\vdots \\
0=\delta_{x_n} S(x_1^0, x_2^0, \dots, x_n) 
$$

 One can prove that such equation of motion gives the iterative version of equation of motion from the variation of the action $E^i := \delta_{x_i} S$:
$$
	0 = \delta_{x_1} S(x_1,x_2, \dots, x_n) =E_1(x_1,x_2, \dots, x_n) , \\
	0 = \delta_{x_2} S(x_1^0, x_2, \dots, x_n) =(\delta_{x_2} S)|_{x_1=x_1^0} +\delta_{x_2} x_1^0 \ (\delta_{x_1} S)|_{x_1=x_1^0}  =(\delta_{x_2} S)|_{x_1=x_1^0} =E_2(x_1^0,x_2, \dots, x_n), \\
    0 = \delta_{x_3} S(x_1^0|_{x_2=x_2^0}, x_2^0, \dots, x_n) =(\delta_{x_3} S)|_{x_1=x_1^0,x_2=x_2^0} +\delta_{x_3} (x_1^0|_{x_2=x_2^0}) \ (\delta_{x_1} S)|_{x_1=x_1^0,x_2=x_2^0} +\delta_{x_2} (x_2^0) \ (\delta_{x_2} S)|_{x_1=x_1^0,x_2=x_2^0}  =(\delta_{x_2} S)|_{x_1=x_1^0} =E_3(x_1^0|_{x_2=x_2^0},x_2^0, \dots, x_n)  =0
    \\ \vdots \\
	0=\delta_{x_n} S(x_1^0|_{\forall_{1<i <n},\ x_i=x_i^0}, x_2^0|_{\forall_{2<i <n},\ x_i=x_i^0}, \dots, x_n) =(\delta_{x_n} S)|_{\forall i <n,\ x_i=x_i^0} = E_n(x_1^0,x_2^0, \dots, x_n)=0 
$$
with $x_i^0(x_{i+1}, \dots, x_n)$ is the solution of the corresponding equation of motion $E_n(x_1^0, \dots, x_{i-1}^0, x_i, x_{i+1},\dots, x_n)$ respect to $x_i$. 
The EoM from single vertex forms a zero-dimensional polynomial system. Thus above decomposition should relate to the triangular decomposition of the polynomial system into regular chains. 

### TODO:

- Simplicial complex with many simplicies.
- Rational univariate representation/iteratively version of the EoM