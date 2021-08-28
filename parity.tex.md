# Parity solutions in SFM

## Action and critical Equation
This is used to fix the notation (The notation and analysis is similar to my paper Arxiv:2104.06902).

We start with the following extended spin foam face action (Conrady-Hnybida extension)
$$
   {F}_{f}[X]=\sum_{v, e \subset \partial f} {F}_{vef}[X,\kappa_{vef}] 
$$
with
$$
 {F}_{vef}[X, \kappa_{vef}] = \kappa_{vef}  \Big[ (1+ \kappa_{vef} \det(\eta_e) )\ln  \left(m_{ef}
 { {n}^{\dagger}}{}_{ef} \eta_e  {Z}_{vef} \right)
\\ + (\kappa_{vef} \det(\eta_e) -1)  \ln \left(m_{ef}
 {Z}^{\dagger}_{vef} \eta_e { {n}}{}_{ef} \right) - (-i \gamma + \kappa_{vef} \det(\eta_e) )
\ln {\left( m_{ef} {Z}^{\dagger}_{vef} \eta_{e}  {Z}_{vef} \right)} \Big] 
$$
where $\kappa_{vef} = \pm 1$ changes sign when changes $v$ or $e$. This formula of ${F}_{vef}$ unifies 2 cases: when $e$ is spacelike, $\eta_e = \mathbb{I}_2, \det(\eta_e)>0$, ${n}$ is the SU(2) or SU(1,1) spinor; when $e$ is timelike( SU(1,1)), $\eta_e = \sigma_3, \det(\eta_e)<0$. $m_{ef} = \pm$ is used distinguish the $D^{\pm}$ of SU(1,1) irreps. 

Suppose $Z = \zeta n + \alpha J n$, where $\langle n, J n \rangle =0,\langle n, n \rangle = \det(\eta) \langle J n, J n \rangle = \pm 1 =m$. The $\pm 1=m$ here repsents the $D^{\pm}$ irreps of SU(1,1), The face action now reads
$$
 {F}_{vef}[X, \kappa_{vef}] = \kappa_{vef}  \Big[ \ln \frac{\zeta_{vef}}{\overline{\zeta_{vef}}}+ 2 \kappa_{vef} \det(\eta_e) \ln  |\zeta_{vef}| 
 \\ - (-i \gamma + \kappa_{vef} \det(\eta_e) )
\ln (|\zeta_{vef}|^2 \pm |\alpha_{vef}|) \Big] 
$$
The real condition $\Re(F) = 0$ requires $\alpha_{vef}=0$. 

Thus
$$
Z_{vef} = g_{ve}^{-1} z_{vf} = \zeta_{vef} n_{ef}, \;\; Z_{ve'f} = g_{ve'}^{-1} z_{vf} = \zeta_{ve'f} n_{e'f}
$$
which gives
$$
g_{ve} | n_{ef} \rangle = \frac{\zeta_{ve'f}}{\zeta_{vef}} g_{ve'} | n_{e'f} \rangle
$$
The variation respect to $z, \bar{z}$ gives the parallel transport equation, which reads (and its complex conjugate)
$$
 m_{ef} \langle n_{ef} | \eta_{e} g_{ve}^{-1}= \frac{\zeta_{vef}}{\zeta_{ve'f}}  m_{e'f} \langle n_{e'f} | \eta_{e'} g_{ve'}^{-1} 
$$
The closure condition is given by
$$
\sum_{f} \kappa_f j_f m_{ef} \langle n_{ef}, \sigma_i n_{ef} \rangle =0
$$
with $\langle \cdot, \cdot \rangle$ SU(2) or SU(1,1) invariant inner product.

## Parity transformation

The parallel transport equations of the spin foam model take the following general form:
$$
g_{ve} | n_{ef} \rangle = \frac{\zeta_{ve'f}}{\zeta_{vef}} g_{ve'} | n_{e'f} \rangle  \\
 m_{ef} \langle n_{ef} | \eta_{e} g_{ve}^{-1}= \frac{\zeta_{vef}}{\zeta_{ve'f}} m_{e'f} \langle n_{e'f} | \eta_{e'} g_{ve'}^{-1} \tag{1} 
$$

The above equations can be rewritten as the bivector equations
$$
g_{ve} B_{ef} g_{ve}^{-1} = g_{ve'} B_{e'f} g_{ve'}^{-1} \tag{2}
$$
with 
$$
-i B_{ef} = m_{ef} | n_{ef} \rangle \langle n_{ef} | \eta_{e} - \frac{1}{2}\mathbb{I}_2 \, \qquad B \in \mathfrak{su}(2) \; \text{or}\; \mathfrak{su}(1,1) 
$$
Here the generators of $\mathfrak{su}(2)$ are given by $\frac{i}{2} \sigma_i$ and the generators of $\mathfrak{su}(1,1)$ are given by $\frac{1}{2} \{\sigma_1,\sigma_2,i \sigma_3 \}$. Clearly for $B_{ef} \in \mathfrak{su}(2)$, we have $B_{ef}^{\dagger} = - B_{ef}$ while for $B_{ef} \in \mathfrak{su}(1,1)$, we have $B_{ef}^{\dagger} = - \sigma_3 B_{ef} \sigma_3$, namely, $B_{ef}^{\dagger} = - \eta_{e} B_{ef} \eta_{e}$. As a result, the solutions to the bivector equations $(2)$ also satisfy
$$
g_{ve}^{-1 \dagger} \eta_{e} B_{ef} \eta_{e} g_{ve}^{\dagger} = g_{ve}^{-1 \dagger} \eta_{e'} B_{e'f} \eta_{e'} g_{ve'}^{\dagger}
$$
namely, $g_{ve}^{-1 \dagger} R_{e} \in \text{SL}(2, \mathbb{C})$, $R_{e} = i^{s_{e}} \eta_{e}$ is also a solution, here we use $s_e = 0$ for su2 and $s_e=1$ for su11. In terms of spinors, such transformation leads to
$$
m_{ef} \langle n_{ef} | ((-i)^{s_{e}} \eta_{e}^2) g_{ve}^{\dagger} =  \frac{\zeta_{vef}}{\zeta_{ve'f}} m_{e'f} \langle {n_{e'f}} | ((-i)^{s_{e'}} \eta_{e'}^2) g_{ve'}^{\dagger} \\
 g_{ve}^{-1 \dagger} i^{s_{e}} \eta_{e} | n_{ef} \rangle = \frac{\zeta_{ve'f}}{\zeta_{vef}}   g_{ve'}^{-1 \dagger} i^{s_{e'}} \eta_{e'} | n_{e'f} \rangle \\
$$
which can be rewritten as
$$
g_{ve} | n_{ef} \rangle =m_{ef}m_{e'f} \frac{i^{s_{e'}} \overline{\zeta_{vef}}}{i^{s_{e}} \overline{\zeta_{ve'f}}} g_{ve'} | n_{e'f} \rangle \\
m_{ef} \langle n_{ef} | \eta_{e} g_{ve}^{-1}= m_{ef}m_{e'f} \frac{i^{s_{e}} \overline{\zeta_{ve'f}}}{i^{s_{e'}} \overline{\zeta_{vef}}}   m_{e'f} \langle n_{e'f} | \eta_{e'} g_{ve'}^{-1} \\
$$
thus also satisfy the spinor parallel transport equations with 
$$
\ln \theta_{eve'} \to -\overline{\ln \theta_{eve'}} + i (s_{e'} - s_{e}) \frac{\pi}{2} + i (2-m_{ef}-m_{e'f}) \frac{\pi}{2} \mod 2 i \pi
$$
where 
$$
\theta_{eve'} : =\left( \frac{\zeta_{vef}}{\zeta_{ve'f}} \right)
$$

Now moving to the spinor variables $z$, which is related to $\zeta$ and $g$ by
$$
 g^{-1}_{ve} z_{vf} = \zeta_{vef} n_{ef} \,, \qquad g^{-1}_{ve'} z_{vf} = \zeta_{ve'f} n_{e'f}
$$
From the fact $z \in \mathbb{CP}_1$, we can freely choose the normalization factor for the spinor $z$, for example, with the parametrization $\mathbf{z} =\left( \begin{array}{l} 1 \\ z \end{array} \right)$
Then spinor after the transformation becomes
$$
z_{vf} = \frac{g^{-1 \dagger} R_{e} n_{ef}}{\langle n_+ | g^{-1 \dagger} R_{e} n_{ef} \rangle}
$$
with $n_{+} = (1,0)^{T}$.

From the reconstruction theorem, we know that
$$
\ln \theta_{eve'}  = \frac{\Theta_{eve'}+ i n \pi }{2} + bdy \,phase , \qquad  n \in \mathbb{N}
$$

The critical action
$$
S_c = 2 i \gamma \ln \left| \theta_{eve'} \right| + (s_e + 1 ) \ln \zeta_{vef} + (s_e - 1 ) \ln \overline{\zeta_{vef} } - 2 s_e \ln \left| \zeta_{vef} \right| \\ - ((-s_{e'} + 1 ) \ln \zeta_{ve'f} + (-s_{e'} - 1 ) \ln \overline{\zeta_{ve'f} } + 2 s_{e'} \ln \left| \zeta_{ve'f} \right|) 
$$


Different case of $(s_e, s_{e'})$ for $S_c - 2 i \gamma \ln \left| \theta_{eve'} \right|$:
$$
(1,1): \;2 \ln \zeta_{vef} - 2 \ln \left| \zeta_{vef} \right| - ( -2 \ln \overline{\zeta_{ve'f} } + 2  \ln \left| \zeta_{ve'f} \right|) = 2 i \arg(\theta_{eve'})\\
(1,-1): \;2 \ln \zeta_{vef} - 2 \ln \left| \zeta_{vef} \right| - (2 \ln \zeta_{ve'f}  - 2  \ln \left| \zeta_{ve'f} \right|) = 2 i \arg(\theta_{eve'})\\
(-1,1): \; -2 \ln \overline{\zeta_{vef} } + 2 \ln \left| \zeta_{vef} \right| - ( -2 \ln \overline{\zeta_{ve'f} } + 2 \ln \left| \zeta_{ve'f} \right|)= 2 i \arg(\theta_{eve'}) \\
(-1,-1): \; -2 \ln \overline{\zeta_{vef} } + 2 \ln \left| \zeta_{vef} \right|  - (2 \ln \zeta_{ve'f}  - 2  \ln \left| \zeta_{ve'f} \right|) = 2 i \arg(\theta_{eve'})
$$
As a result,
$$
S_c = 2 i \gamma \ln \left| \theta_{eve'} \right| + 2 i \arg(\theta_{eve'})
$$
thus parity transformation contributes a minus sign to the critical action modulo $i \pi j$.

--------

## Geometric meaning
Using the Weyl representation
$g^{-1\dagger}$ act on $(1,0,0,0)$ is the same as 
$I_0 g$ where $I_0$ is a reflection along time direction. 
This can be seen as the following, using 
$$
\bar{X} = t \mathbb{I}_2 + \vec{x} \sigma_3, \qquad {X} = t \mathbb{I}_2 - \vec{x} \sigma_3, \qquad \bar{X} =I I_0 X
$$
and the transformations under SL(2,C),
$$
\bar{X} \to g \bar{X} g^{\dagger}, \qquad X \to g^{-1 \dagger} \bar{X} g^{-1}
$$
Here $I$ is the spacetime inversion $I v =-v$.

For general vectors, the transformation gives
$$
\bar{X}=g ( t \mathbb{I}_2 + \vec{x} \sigma_3) g^{\dagger} \to g^{-1 \dagger} ( t \mathbb{I}_2 + \vec{x} \sigma_3) g^{-1} 
\\= g^{-1 \dagger} X(t,-\vec{x}) g^{-1} =I I_0 (g \bar{X}(t,-\vec{x}) g^{\dagger}) = I_0 g I_0 \triangleright \bar{X}
$$


Similarly, $g \to g^{-1\dagger} i \sigma_3$ act on general vectors gives
$$
\bar{X} =  g  ( t \mathbb{I}_2 + \vec{x} \sigma_3) g^{\dagger} \to g^{-1\dagger} i \sigma_3  ( t \mathbb{I}_2 + \vec{x} \sigma_3) (g^{-1\dagger} i \sigma_3)^{\dagger}\\
 =  g^{-1\dagger} ( t \mathbb{I}_2 - {x}_1 \sigma_1 - x_2 \sigma_2 + x_3 \sigma_3)  (g^{-1\dagger})^{\dagger} = g^{-1\dagger}X(t,x_1,x_2,-x_3) g^{-1}\\
= I I_0 (g \bar{X}(t,x_1,x_2,-x_3) g^{\dagger}) = I_0 g I_3 \triangleright \bar{X}
$$
This is exactly the result given in Wojciech. Marcin and Hanno's paper ArXiv:1705.02862
which is 
$$
G_i \to I_{e_\alpha} G_i I_{u_i} 
$$
with $e_{\alpha}$ chosen to be $e_0$ and $u_i=e_0$ for su2, $u_i = e_3$ for su11 up to spacetime inversion $I v =-v$.