# Extended Spinfoam

We provide functions which can be used to generate the boundary data as well as corresponding critical configurations of the extended spin foam model (EPRL with Conrady-Hnybida extension, ArXiv:1002.1959) which can contain both timelike and spacelike faces.

Here we use it to demonstrate that the parity transformation generates new classes of gauge inequivalent solutions of the extended spinfoam models (general_spinfoam_github.nb, the Transformations section). 
Such transformation is given as
<!-- $$
g \to g^{-1 \dagger}, \;\; for \ \text{SU(2)} \ , \qquad
g \to g^{-1 \dagger} i \sigma_3, \;\; for \ \text{SU(1,1)} \ .
$$ --> 

<div align="center"><img style="background: white;" src="https://render.githubusercontent.com/render/math?math=g%20%5Cto%20g%5E%7B-1%20%5Cdagger%7D%2C%20%5C%3B%5C%3B%20for%20%5C%20%5Ctext%7BSU(2)%7D%20%5C%20%2C%20%5Cqquad%0D%0Ag%20%5Cto%20g%5E%7B-1%20%5Cdagger%7D%20i%20%5Csigma_3%2C%20%5C%3B%5C%3B%20for%20%5C%20%5Ctext%7BSU(1%2C1)%7D%20%5C%20.%0D"></div>

The derivation is shown in the note parity.md.

In the code (general_spinfoam_github.nb, the action section), we also verify that above critical configurations are still critical solutions when we derive the equation of motion iteratively from the action (Appendix B5. in ArXiv: 1810.09042).
<!-- $$
\begin{aligned}
0 = \delta_{x_1} S(x_1,x_2, \dots, x_n) \\
0 = \delta_{x_2} S(x_1^0,x_2, \dots, x_n)\\
\vdots \\
0=\delta_{x_n} S(x_1^0, x_2^0, \dots, x_n) 
\end{aligned}
$$ --> 

<div align="center"><img style="background: white;" src="https://render.githubusercontent.com/render/math?math=%5Cbegin%7Baligned%7D%0D%0A0%20%3D%20%5Cdelta_%7Bx_1%7D%20S(x_1%2Cx_2%2C%20%5Cdots%2C%20x_n)%20%5C%5C%0D%0A0%20%3D%20%5Cdelta_%7Bx_2%7D%20S(x_1%5E0%2Cx_2%2C%20%5Cdots%2C%20x_n)%5C%5C%0D%0A%5Cvdots%20%5C%5C%0D%0A0%3D%5Cdelta_%7Bx_n%7D%20S(x_1%5E0%2C%20x_2%5E0%2C%20%5Cdots%2C%20x_n)%20%0D%0A%5Cend%7Baligned%7D%0D"></div>

 One can prove that such equation of motion gives the iterative version of equation of motion from the variation of the action <!-- $E^i := \delta_{x_i} S$ --> <img style="transform: translateY(0.1em); background: white;" src="https://render.githubusercontent.com/render/math?math=E%5Ei%20%3A%3D%20%5Cdelta_%7Bx_i%7D%20S">:
<!-- $$
\begin{aligned}
	0 &= \delta_{x_1} S(x_1,x_2, \dots, x_n) =E_1(x_1,x_2, \dots, x_n) , \\
	0 &= \delta_{x_2} S(x_1^0, x_2, \dots, x_n) =(\delta_{x_2} S)|_{x_1=x_1^0} +\delta_{x_2} x_1^0 \ (\delta_{x_1} S)|_{x_1=x_1^0}  =(\delta_{x_2} S)|_{x_1=x_1^0} =E_2(x_1^0,x_2, \dots, x_n), \\
    0 &= \delta_{x_3} S(x_1^0|_{x_2=x_2^0}, x_2^0, \dots, x_n) =(\delta_{x_3} S)|_{x_1=x_1^0,x_2=x_2^0} +\delta_{x_3} (x_1^0|_{x_2=x_2^0}) \ (\delta_{x_1} S)|_{x_1=x_1^0,x_2=x_2^0} +\delta_{x_2} (x_2^0) \ (\delta_{x_2} S)|_{x_1=x_1^0,x_2=x_2^0}  =(\delta_{x_2} S)|_{x_1=x_1^0} =E_3(x_1^0|_{x_2=x_2^0},x_2^0, \dots, x_n)  =0
    \\ \vdots \\
	0 &=\delta_{x_n} S(x_1^0|_{\forall_{1<i <n},\ x_i=x_i^0}, x_2^0|_{\forall_{2<i <n},\ x_i=x_i^0}, \dots, x_n) =(\delta_{x_n} S)|_{\forall i <n,\ x_i=x_i^0} = E_n(x_1^0,x_2^0, \dots, x_n)=0 
\end{aligned}
$$ --> 

<div align="center"><img style="background: white;" src="https://render.githubusercontent.com/render/math?math=%5Cbegin%7Baligned%7D%0D%0A%090%20%26%3D%20%5Cdelta_%7Bx_1%7D%20S(x_1%2Cx_2%2C%20%5Cdots%2C%20x_n)%20%3DE_1(x_1%2Cx_2%2C%20%5Cdots%2C%20x_n)%20%2C%20%5C%5C%0D%0A%090%20%26%3D%20%5Cdelta_%7Bx_2%7D%20S(x_1%5E0%2C%20x_2%2C%20%5Cdots%2C%20x_n)%20%3D(%5Cdelta_%7Bx_2%7D%20S)%7C_%7Bx_1%3Dx_1%5E0%7D%20%2B%5Cdelta_%7Bx_2%7D%20x_1%5E0%20%5C%20(%5Cdelta_%7Bx_1%7D%20S)%7C_%7Bx_1%3Dx_1%5E0%7D%20%20%3D(%5Cdelta_%7Bx_2%7D%20S)%7C_%7Bx_1%3Dx_1%5E0%7D%20%3DE_2(x_1%5E0%2Cx_2%2C%20%5Cdots%2C%20x_n)%2C%20%5C%5C%0D%0A%20%20%20%200%20%26%3D%20%5Cdelta_%7Bx_3%7D%20S(x_1%5E0%7C_%7Bx_2%3Dx_2%5E0%7D%2C%20x_2%5E0%2C%20%5Cdots%2C%20x_n)%20%3D(%5Cdelta_%7Bx_3%7D%20S)%7C_%7Bx_1%3Dx_1%5E0%2Cx_2%3Dx_2%5E0%7D%20%2B%5Cdelta_%7Bx_3%7D%20(x_1%5E0%7C_%7Bx_2%3Dx_2%5E0%7D)%20%5C%20(%5Cdelta_%7Bx_1%7D%20S)%7C_%7Bx_1%3Dx_1%5E0%2Cx_2%3Dx_2%5E0%7D%20%2B%5Cdelta_%7Bx_2%7D%20(x_2%5E0)%20%5C%20(%5Cdelta_%7Bx_2%7D%20S)%7C_%7Bx_1%3Dx_1%5E0%2Cx_2%3Dx_2%5E0%7D%20%20%3D(%5Cdelta_%7Bx_2%7D%20S)%7C_%7Bx_1%3Dx_1%5E0%7D%20%3DE_3(x_1%5E0%7C_%7Bx_2%3Dx_2%5E0%7D%2Cx_2%5E0%2C%20%5Cdots%2C%20x_n)%20%20%3D0%0D%0A%20%20%20%20%5C%5C%20%5Cvdots%20%5C%5C%0D%0A%090%20%26%3D%5Cdelta_%7Bx_n%7D%20S(x_1%5E0%7C_%7B%5Cforall_%7B1%3Ci%20%3Cn%7D%2C%5C%20x_i%3Dx_i%5E0%7D%2C%20x_2%5E0%7C_%7B%5Cforall_%7B2%3Ci%20%3Cn%7D%2C%5C%20x_i%3Dx_i%5E0%7D%2C%20%5Cdots%2C%20x_n)%20%3D(%5Cdelta_%7Bx_n%7D%20S)%7C_%7B%5Cforall%20i%20%3Cn%2C%5C%20x_i%3Dx_i%5E0%7D%20%3D%20E_n(x_1%5E0%2Cx_2%5E0%2C%20%5Cdots%2C%20x_n)%3D0%20%0D%0A%5Cend%7Baligned%7D%0D"></div>

with <!-- $x_i^0(x_{i+1}, \dots, x_n)$ --> <img style="transform: translateY(0.1em); background: white;" src="https://render.githubusercontent.com/render/math?math=x_i%5E0(x_%7Bi%2B1%7D%2C%20%5Cdots%2C%20x_n)"> is the solution of the corresponding equation of motion <!-- $E_n(x_1^0, \dots, x_{i-1}^0, x_i, x_{i+1},\dots, x_n)$ --> <img style="transform: translateY(0.1em); background: white;" src="https://render.githubusercontent.com/render/math?math=E_n(x_1%5E0%2C%20%5Cdots%2C%20x_%7Bi-1%7D%5E0%2C%20x_i%2C%20x_%7Bi%2B1%7D%2C%5Cdots%2C%20x_n)"> respect to <!-- $x_i$ --> <img style="transform: translateY(0.1em); background: white;" src="https://render.githubusercontent.com/render/math?math=x_i">. As a result, the solution of <!-- $E^i := \delta_{x_i} S$ --> <img style="transform: translateY(0.1em); background: white;" src="https://render.githubusercontent.com/render/math?math=E%5Ei%20%3A%3D%20%5Cdelta_%7Bx_i%7D%20S"> is also the solution of above equations.


The EoM from single vertex forms a zero-dimensional polynomial system. Thus above decomposition should relate to the triangular decomposition of the polynomial system into regular chains. 

### TODO:

- Simplicial complex with many simplicies.
- Rational univariate representation/iteratively version of the EoM
