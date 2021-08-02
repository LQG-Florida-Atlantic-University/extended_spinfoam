# Parity solutions in SFM

## Action and critical EQ
This is used to fix the notation, the notation and analysis is the same as the one in Arxiv:2104.06902.

We start with the following extended spin foam face action (Conrady-Hnybida extension)


![math](https://render.githubusercontent.com/render/math?math=%7BF%7D_%7Bf%7D%5BX%5D%3D%5Csum_%7Bv%2C%20e%20%5Csubset%20%5Cpartial%20f%7D%20%7BF%7D_%7Bvef%7D%5BX%2C%5Ckappa_%7Bvef%7D%5D)


with


![math](https://render.githubusercontent.com/render/math?math=%7BF%7D_%7Bvef%7D%5BX%2C%20%5Ckappa_%7Bvef%7D%5D%20%3D%20%5Ckappa_%7Bvef%7D%20%20%5CBig%5B%20%281%2B%20%5Ckappa_%7Bvef%7D%20%5Cdet%28%5Ceta_e%29%20%29%5Cln%20%20%5Cleft%28m_%7Bef%7D%0A%20%7B%20%7Bn%7D%5E%7B%5Cdagger%7D%7D%7B%7D_%7Bef%7D%20%5Ceta_e%20%20%7BZ%7D_%7Bvef%7D%20%5Cright%29%0A%5C%5C%20%2B%20%28%5Ckappa_%7Bvef%7D%20%5Cdet%28%5Ceta_e%29%20-1%29%20%20%5Cln%20%5Cleft%28m_%7Bef%7D%0A%20%7BZ%7D%5E%7B%5Cdagger%7D_%7Bvef%7D%20%5Ceta_e%20%7B%20%7Bn%7D%7D%7B%7D_%7Bef%7D%20%5Cright%29%20-%20%28-i%20%5Cgamma%20%2B%20%5Ckappa_%7Bvef%7D%20%5Cdet%28%5Ceta_e%29%20%29%0A%5Cln%20%7B%5Cleft%28%20m_%7Bef%7D%20%7BZ%7D%5E%7B%5Cdagger%7D_%7Bvef%7D%20%5Ceta_%7Be%7D%20%20%7BZ%7D_%7Bvef%7D%20%5Cright%29%7D%20%5CBig%5D)


where  ![math](https://render.githubusercontent.com/render/math?math=%5Ckappa_%7Bvef%7D%20%3D%20%5Cpm%201)  changes sign when changes  ![math](https://render.githubusercontent.com/render/math?math=v)  or  ![math](https://render.githubusercontent.com/render/math?math=e) . This formula of  ![math](https://render.githubusercontent.com/render/math?math=%7BF%7D_%7Bvef%7D)  unifies 2 cases: when  ![math](https://render.githubusercontent.com/render/math?math=e)  is spacelike,  ![math](https://render.githubusercontent.com/render/math?math=%5Ceta_e%20%3D%20%5Cmathbb%7BI%7D_2%2C%20%5Cdet%28%5Ceta_e%29%3E0) ,  ![math](https://render.githubusercontent.com/render/math?math=%7Bn%7D)  is the SU(2) or SU(1,1) spinor; when  ![math](https://render.githubusercontent.com/render/math?math=e)  is timelike( SU(1,1)),  ![math](https://render.githubusercontent.com/render/math?math=%5Ceta_e%20%3D%20%5Csigma_3%2C%20%5Cdet%28%5Ceta_e%29%3C0) .  ![math](https://render.githubusercontent.com/render/math?math=m_%7Bef%7D%20%3D%20%5Cpm)  is used distinguish the  ![math](https://render.githubusercontent.com/render/math?math=D%5E%7B%5Cpm%7D)  of SU(1,1) irreps. 

Suppose  ![math](https://render.githubusercontent.com/render/math?math=Z%20%3D%20%5Czeta%20n%20%2B%20%5Calpha%20J%20n) , where  ![math](https://render.githubusercontent.com/render/math?math=%5Clangle%20n%2C%20J%20n%20%5Crangle%20%3D0%2C%5Clangle%20n%2C%20n%20%5Crangle%20%3D%20%5Cdet%28%5Ceta%29%20%5Clangle%20J%20n%2C%20J%20n%20%5Crangle%20%3D%20%5Cpm%201%20%3Dm) . The  ![math](https://render.githubusercontent.com/render/math?math=%5Cpm%201%3Dm)  here repsents the  ![math](https://render.githubusercontent.com/render/math?math=D%5E%7B%5Cpm%7D)  irreps of SU(1,1), The face action now reads


![math](https://render.githubusercontent.com/render/math?math=%7BF%7D_%7Bvef%7D%5BX%2C%20%5Ckappa_%7Bvef%7D%5D%20%3D%20%5Ckappa_%7Bvef%7D%20%20%5CBig%5B%20%5Cln%20%5Cfrac%7B%5Czeta_%7Bvef%7D%7D%7B%5Coverline%7B%5Czeta_%7Bvef%7D%7D%7D%2B%202%20%5Ckappa_%7Bvef%7D%20%5Cdet%28%5Ceta_e%29%20%5Cln%20%20%7C%5Czeta_%7Bvef%7D%7C%20%0A%20%5C%5C%20-%20%28-i%20%5Cgamma%20%2B%20%5Ckappa_%7Bvef%7D%20%5Cdet%28%5Ceta_e%29%20%29%0A%5Cln%20%28%7C%5Czeta_%7Bvef%7D%7C%5E2%20%5Cpm%20%7C%5Calpha_%7Bvef%7D%7C%29%20%5CBig%5D)


The real condition  ![math](https://render.githubusercontent.com/render/math?math=%5CRe%28F%29%20%3D%200)  requires  ![math](https://render.githubusercontent.com/render/math?math=%5Calpha_%7Bvef%7D%3D0) . 

Thus


![math](https://render.githubusercontent.com/render/math?math=Z_%7Bvef%7D%20%3D%20g_%7Bve%7D%5E%7B-1%7D%20z_%7Bvf%7D%20%3D%20%5Czeta_%7Bvef%7D%20n_%7Bef%7D%2C%20%5C%3B%5C%3B%20Z_%7Bve%27f%7D%20%3D%20g_%7Bve%27%7D%5E%7B-1%7D%20z_%7Bvf%7D%20%3D%20%5Czeta_%7Bve%27f%7D%20n_%7Be%27f%7D)


which gives


![math](https://render.githubusercontent.com/render/math?math=g_%7Bve%7D%20%7C%20n_%7Bef%7D%20%5Crangle%20%3D%20%5Cfrac%7B%5Czeta_%7Bve%27f%7D%7D%7B%5Czeta_%7Bvef%7D%7D%20g_%7Bve%27%7D%20%7C%20n_%7Be%27f%7D%20%5Crangle)


The variation respect to  ![math](https://render.githubusercontent.com/render/math?math=z%2C%20%5Cbar%7Bz%7D)  gives the parallel transport equation, which reads (and its complex conjugate)


![math](https://render.githubusercontent.com/render/math?math=m_%7Bef%7D%20%5Clangle%20n_%7Bef%7D%20%7C%20%5Ceta_%7Be%7D%20g_%7Bve%7D%5E%7B-1%7D%3D%20%5Cfrac%7B%5Czeta_%7Bvef%7D%7D%7B%5Czeta_%7Bve%27f%7D%7D%20%20m_%7Be%27f%7D%20%5Clangle%20n_%7Be%27f%7D%20%7C%20%5Ceta_%7Be%27%7D%20g_%7Bve%27%7D%5E%7B-1%7D%20%5Ctag%7B1%7D)


The closure is 


![math](https://render.githubusercontent.com/render/math?math=%5Csum_%7Bf%7D%20%5Ckappa_f%20j_f%20m_%7Bef%7D%20%5Clangle%20n_%7Bef%7D%2C%20%5Csigma_i%20n_%7Bef%7D%20%5Crangle%20%3D0)



## Parity transformation

The parallel transport equation of the spin foam model take the following general form:


![math](https://render.githubusercontent.com/render/math?math=g_%7Bve%7D%20%7C%20n_%7Bef%7D%20%5Crangle%20%3D%20%5Cfrac%7B%5Czeta_%7Bve%27f%7D%7D%7B%5Czeta_%7Bvef%7D%7D%20g_%7Bve%27%7D%20%7C%20n_%7Be%27f%7D%20%5Crangle%20%20%5C%5C%0A%20m_%7Bef%7D%20%5Clangle%20n_%7Bef%7D%20%7C%20%5Ceta_%7Be%7D%20g_%7Bve%7D%5E%7B-1%7D%3D%20%5Cfrac%7B%5Czeta_%7Bvef%7D%7D%7B%5Czeta_%7Bve%27f%7D%7D%20m_%7Be%27f%7D%20%5Clangle%20n_%7Be%27f%7D%20%7C%20%5Ceta_%7Be%27%7D%20g_%7Bve%27%7D%5E%7B-1%7D%20%5Ctag%7B1%7D)



The above equations can be rewritten as the bivector equations


![math](https://render.githubusercontent.com/render/math?math=g_%7Bve%7D%20B_%7Bef%7D%20g_%7Bve%7D%5E%7B-1%7D%20%3D%20g_%7Bve%27%7D%20B_%7Be%27f%7D%20g_%7Bve%27%7D%5E%7B-1%7D%20%5Ctag%7B2%7D)


with 


![math](https://render.githubusercontent.com/render/math?math=-i%20B_%7Bef%7D%20%3D%20m_%7Bef%7D%20%7C%20n_%7Bef%7D%20%5Crangle%20%5Clangle%20n_%7Bef%7D%20%7C%20%5Ceta_%7Be%7D%20-%20%5Cfrac%7B1%7D%7B2%7D%5Cmathbb%7BI%7D_2%20%5C%2C%20%5Cqquad%20B%20%5Cin%20%5Cmathfrak%7Bsu%7D%282%29%20%5C%3B%20%5Ctext%7Bor%7D%5C%3B%20%5Cmathfrak%7Bsu%7D%281%2C1%29)


Here the generators of  ![math](https://render.githubusercontent.com/render/math?math=%5Cmathfrak%7Bsu%7D%282%29)  are given by  ![math](https://render.githubusercontent.com/render/math?math=%5Cfrac%7Bi%7D%7B2%7D%20%5Csigma_i)  and the generators of  ![math](https://render.githubusercontent.com/render/math?math=%5Cmathfrak%7Bsu%7D%281%2C1%29)  are given by  ![math](https://render.githubusercontent.com/render/math?math=%5Cfrac%7B1%7D%7B2%7D%20%5C%7B%5Csigma_1%2C%5Csigma_2%2Ci%20%5Csigma_3%20%5C%7D) . Clearly for  ![math](https://render.githubusercontent.com/render/math?math=B_%7Bef%7D%20%5Cin%20%5Cmathfrak%7Bsu%7D%282%29) , we have  ![math](https://render.githubusercontent.com/render/math?math=B_%7Bef%7D%5E%7B%5Cdagger%7D%20%3D%20-%20B_%7Bef%7D)  while for  ![math](https://render.githubusercontent.com/render/math?math=B_%7Bef%7D%20%5Cin%20%5Cmathfrak%7Bsu%7D%281%2C1%29) , we have  ![math](https://render.githubusercontent.com/render/math?math=B_%7Bef%7D%5E%7B%5Cdagger%7D%20%3D%20-%20%5Csigma_3%20B_%7Bef%7D%20%5Csigma_3) , namely,  ![math](https://render.githubusercontent.com/render/math?math=B_%7Bef%7D%5E%7B%5Cdagger%7D%20%3D%20-%20%5Ceta_%7Be%7D%20B_%7Bef%7D%20%5Ceta_%7Be%7D) . As a result, the solutions to the bivector equations  ![math](https://render.githubusercontent.com/render/math?math=%282%29)  also satisfy


![math](https://render.githubusercontent.com/render/math?math=g_%7Bve%7D%5E%7B-1%20%5Cdagger%7D%20%5Ceta_%7Be%7D%20B_%7Bef%7D%20%5Ceta_%7Be%7D%20g_%7Bve%7D%5E%7B%5Cdagger%7D%20%3D%20g_%7Bve%7D%5E%7B-1%20%5Cdagger%7D%20%5Ceta_%7Be%27%7D%20B_%7Be%27f%7D%20%5Ceta_%7Be%27%7D%20g_%7Bve%27%7D%5E%7B%5Cdagger%7D)


namely,  ![math](https://render.githubusercontent.com/render/math?math=g_%7Bve%7D%5E%7B-1%20%5Cdagger%7D%20R_%7Be%7D%20%5Cin%20%5Ctext%7BSL%7D%282%2C%20%5Cmathbb%7BC%7D%29) ,  ![math](https://render.githubusercontent.com/render/math?math=R_%7Be%7D%20%3D%20i%5E%7Bs_%7Be%7D%7D%20%5Ceta_%7Be%7D)  is also a solution, here we use  ![math](https://render.githubusercontent.com/render/math?math=s_e%20%3D%200)  for su2 and  ![math](https://render.githubusercontent.com/render/math?math=s_e%3D1)  for su11. In terms of spinors, such transformation leads to


![math](https://render.githubusercontent.com/render/math?math=m_%7Bef%7D%20%5Clangle%20n_%7Bef%7D%20%7C%20%28%28-i%29%5E%7Bs_%7Be%7D%7D%20%5Ceta_%7Be%7D%5E2%29%20g_%7Bve%7D%5E%7B%5Cdagger%7D%20%3D%20%20%5Cfrac%7B%5Czeta_%7Bvef%7D%7D%7B%5Czeta_%7Bve%27f%7D%7D%20m_%7Be%27f%7D%20%5Clangle%20%7Bn_%7Be%27f%7D%7D%20%7C%20%28%28-i%29%5E%7Bs_%7Be%27%7D%7D%20%5Ceta_%7Be%27%7D%5E2%29%20g_%7Bve%27%7D%5E%7B%5Cdagger%7D%20%5C%5C%0A%20g_%7Bve%7D%5E%7B-1%20%5Cdagger%7D%20i%5E%7Bs_%7Be%7D%7D%20%5Ceta_%7Be%7D%20%7C%20n_%7Bef%7D%20%5Crangle%20%3D%20%5Cfrac%7B%5Czeta_%7Bve%27f%7D%7D%7B%5Czeta_%7Bvef%7D%7D%20%20%20g_%7Bve%27%7D%5E%7B-1%20%5Cdagger%7D%20i%5E%7Bs_%7Be%27%7D%7D%20%5Ceta_%7Be%27%7D%20%7C%20n_%7Be%27f%7D%20%5Crangle%20%5C%5C)


which can be rewritten as


![math](https://render.githubusercontent.com/render/math?math=g_%7Bve%7D%20%7C%20n_%7Bef%7D%20%5Crangle%20%3Dm_%7Bef%7Dm_%7Be%27f%7D%20%5Cfrac%7Bi%5E%7Bs_%7Be%27%7D%7D%20%5Coverline%7B%5Czeta_%7Bvef%7D%7D%7D%7Bi%5E%7Bs_%7Be%7D%7D%20%5Coverline%7B%5Czeta_%7Bve%27f%7D%7D%7D%20g_%7Bve%27%7D%20%7C%20n_%7Be%27f%7D%20%5Crangle%20%5C%5C%0Am_%7Bef%7D%20%5Clangle%20n_%7Bef%7D%20%7C%20%5Ceta_%7Be%7D%20g_%7Bve%7D%5E%7B-1%7D%3D%20m_%7Bef%7Dm_%7Be%27f%7D%20%5Cfrac%7Bi%5E%7Bs_%7Be%7D%7D%20%5Coverline%7B%5Czeta_%7Bve%27f%7D%7D%7D%7Bi%5E%7Bs_%7Be%27%7D%7D%20%5Coverline%7B%5Czeta_%7Bvef%7D%7D%7D%20%20%20m_%7Be%27f%7D%20%5Clangle%20n_%7Be%27f%7D%20%7C%20%5Ceta_%7Be%27%7D%20g_%7Bve%27%7D%5E%7B-1%7D%20%5C%5C)


thus also satisfies the spinor parallel transport equations with 


![math](https://render.githubusercontent.com/render/math?math=%5Cln%20%5Ctheta_%7Beve%27%7D%20%5Cto%20-%5Coverline%7B%5Cln%20%5Ctheta_%7Beve%27%7D%7D%20%2B%20i%20%28s_%7Be%27%7D%20-%20s_%7Be%7D%29%20%5Cfrac%7B%5Cpi%7D%7B2%7D%20%2B%20i%20%282-m_%7Bef%7D-m_%7Be%27f%7D%29%20%5Cfrac%7B%5Cpi%7D%7B2%7D%20%5Cmod%202%20i%20%5Cpi)


where 


![math](https://render.githubusercontent.com/render/math?math=%5Ctheta_%7Beve%27%7D%20%3A%20%3D%5Cleft%28%20%5Cfrac%7B%5Czeta_%7Bvef%7D%7D%7B%5Czeta_%7Bve%27f%7D%7D%20%5Cright%29)



Now moving to the spinor variables  ![math](https://render.githubusercontent.com/render/math?math=z) , which is related to  ![math](https://render.githubusercontent.com/render/math?math=%5Czeta)  and  ![math](https://render.githubusercontent.com/render/math?math=g)  by


![math](https://render.githubusercontent.com/render/math?math=g%5E%7B-1%7D_%7Bve%7D%20z_%7Bvf%7D%20%3D%20%5Czeta_%7Bvef%7D%20n_%7Bef%7D%20%5C%2C%2C%20%5Cqquad%20g%5E%7B-1%7D_%7Bve%27%7D%20z_%7Bvf%7D%20%3D%20%5Czeta_%7Bve%27f%7D%20n_%7Be%27f%7D)


From the fact  ![math](https://render.githubusercontent.com/render/math?math=z%20%5Cin%20%5Cmathbb%7BCP%7D_1) , we can freely choose the normalization factor for the spinor  ![math](https://render.githubusercontent.com/render/math?math=z) , for example, with the parametrization  ![math](https://render.githubusercontent.com/render/math?math=%5Cmathbf%7Bz%7D%20%3D%5Cleft%28%20%5Cbegin%7Barray%7D%7Bl%7D%201%20%5C%5C%20z%20%5Cend%7Barray%7D%20%5Cright%29) 
Then spinor after the transformation becomes


![math](https://render.githubusercontent.com/render/math?math=z_%7Bvf%7D%20%3D%20%5Cfrac%7Bg%5E%7B-1%20%5Cdagger%7D%20R_%7Be%7D%20n_%7Bef%7D%7D%7B%5Clangle%20n_%2B%20%7C%20g%5E%7B-1%20%5Cdagger%7D%20R_%7Be%7D%20n_%7Bef%7D%20%5Crangle%7D)


with  ![math](https://render.githubusercontent.com/render/math?math=n_%7B%2B%7D%20%3D%20%281%2C0%29%5E%7BT%7D) .

From the reconstruction theorem, we know that


![math](https://render.githubusercontent.com/render/math?math=%5Cln%20%5Ctheta_%7Beve%27%7D%20%20%3D%20%5Cfrac%7B%5CTheta_%7Beve%27%7D%2B%20i%20n%20%5Cpi%20%7D%7B2%7D%20%2B%20bdy%20%5C%2Cphase%20%2C%20%5Cqquad%20%20n%20%5Cin%20%5Cmathbb%7BN%7D)



The critical action


![math](https://render.githubusercontent.com/render/math?math=S_c%20%3D%202%20i%20%5Cgamma%20%5Cln%20%5Cleft%7C%20%5Ctheta_%7Beve%27%7D%20%5Cright%7C%20%2B%20%28s_e%20%2B%201%20%29%20%5Cln%20%5Czeta_%7Bvef%7D%20%2B%20%28s_e%20-%201%20%29%20%5Cln%20%5Coverline%7B%5Czeta_%7Bvef%7D%20%7D%20-%202%20s_e%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bvef%7D%20%5Cright%7C%20%5C%5C%20-%20%28%28-s_%7Be%27%7D%20%2B%201%20%29%20%5Cln%20%5Czeta_%7Bve%27f%7D%20%2B%20%28-s_%7Be%27%7D%20-%201%20%29%20%5Cln%20%5Coverline%7B%5Czeta_%7Bve%27f%7D%20%7D%20%2B%202%20s_%7Be%27%7D%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bve%27f%7D%20%5Cright%7C%29)




Different case of  ![math](https://render.githubusercontent.com/render/math?math=%28s_e%2C%20s_%7Be%27%7D%29)  for  ![math](https://render.githubusercontent.com/render/math?math=S_c%20-%202%20i%20%5Cgamma%20%5Cln%20%5Cleft%7C%20%5Ctheta_%7Beve%27%7D%20%5Cright%7C) :


![math](https://render.githubusercontent.com/render/math?math=%281%2C1%29%3A%20%5C%3B2%20%5Cln%20%5Czeta_%7Bvef%7D%20-%202%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bvef%7D%20%5Cright%7C%20-%20%28%20-2%20%5Cln%20%5Coverline%7B%5Czeta_%7Bve%27f%7D%20%7D%20%2B%202%20%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bve%27f%7D%20%5Cright%7C%29%20%3D%202%20i%20%5Carg%28%5Ctheta_%7Beve%27%7D%29%5C%5C%0A%281%2C-1%29%3A%20%5C%3B2%20%5Cln%20%5Czeta_%7Bvef%7D%20-%202%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bvef%7D%20%5Cright%7C%20-%20%282%20%5Cln%20%5Czeta_%7Bve%27f%7D%20%20-%202%20%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bve%27f%7D%20%5Cright%7C%29%20%3D%202%20i%20%5Carg%28%5Ctheta_%7Beve%27%7D%29%5C%5C%0A%28-1%2C1%29%3A%20%5C%3B%20-2%20%5Cln%20%5Coverline%7B%5Czeta_%7Bvef%7D%20%7D%20%2B%202%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bvef%7D%20%5Cright%7C%20-%20%28%20-2%20%5Cln%20%5Coverline%7B%5Czeta_%7Bve%27f%7D%20%7D%20%2B%202%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bve%27f%7D%20%5Cright%7C%29%3D%202%20i%20%5Carg%28%5Ctheta_%7Beve%27%7D%29%20%5C%5C%0A%28-1%2C-1%29%3A%20%5C%3B%20-2%20%5Cln%20%5Coverline%7B%5Czeta_%7Bvef%7D%20%7D%20%2B%202%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bvef%7D%20%5Cright%7C%20%20-%20%282%20%5Cln%20%5Czeta_%7Bve%27f%7D%20%20-%202%20%20%5Cln%20%5Cleft%7C%20%5Czeta_%7Bve%27f%7D%20%5Cright%7C%29%20%3D%202%20i%20%5Carg%28%5Ctheta_%7Beve%27%7D%29)


As a result,


![math](https://render.githubusercontent.com/render/math?math=S_c%20%3D%202%20i%20%5Cgamma%20%5Cln%20%5Cleft%7C%20%5Ctheta_%7Beve%27%7D%20%5Cright%7C%20%2B%202%20i%20%5Carg%28%5Ctheta_%7Beve%27%7D%29)


thus parity transformation contributes a minus sign to the critical action modulo  ![math](https://render.githubusercontent.com/render/math?math=i%20%5Cpi%20j) .

--------

## Geometric meaning
Using the Weyl representation
 ![math](https://render.githubusercontent.com/render/math?math=g%5E%7B-1%5Cdagger%7D)  act on  ![math](https://render.githubusercontent.com/render/math?math=%281%2C0%2C0%2C0%29)  is the same as 
 ![math](https://render.githubusercontent.com/render/math?math=I_0%20g)  where  ![math](https://render.githubusercontent.com/render/math?math=I_0)  is a reflection along time direction. 
This can be seen as the following, using 


![math](https://render.githubusercontent.com/render/math?math=%5Cbar%7BX%7D%20%3D%20t%20%5Cmathbb%7BI%7D_2%20%2B%20%5Cvec%7Bx%7D%20%5Csigma_3%2C%20%5Cqquad%20%7BX%7D%20%3D%20t%20%5Cmathbb%7BI%7D_2%20-%20%5Cvec%7Bx%7D%20%5Csigma_3%2C%20%5Cqquad%20%5Cbar%7BX%7D%20%3DI%20I_0%20X)


and the transformations under SL(2,C),


![math](https://render.githubusercontent.com/render/math?math=%5Cbar%7BX%7D%20%5Cto%20g%20%5Cbar%7BX%7D%20g%5E%7B%5Cdagger%7D%2C%20%5Cqquad%20X%20%5Cto%20g%5E%7B-1%20%5Cdagger%7D%20%5Cbar%7BX%7D%20g%5E%7B-1%7D)


Here  ![math](https://render.githubusercontent.com/render/math?math=I)  is the spacetime inversion  ![math](https://render.githubusercontent.com/render/math?math=I%20v%20%3D-v)  and  ![math](https://render.githubusercontent.com/render/math?math=I_0)  is the reflection along time direction

For general vectors, the transformation gives


![math](https://render.githubusercontent.com/render/math?math=%5Cbar%7BX%7D%3Dg%20%28%20t%20%5Cmathbb%7BI%7D_2%20%2B%20%5Cvec%7Bx%7D%20%5Csigma_3%29%20g%5E%7B%5Cdagger%7D%20%5Cto%20g%5E%7B-1%20%5Cdagger%7D%20%28%20t%20%5Cmathbb%7BI%7D_2%20%2B%20%5Cvec%7Bx%7D%20%5Csigma_3%29%20g%5E%7B-1%7D%20%3D%20g%5E%7B-1%20%5Cdagger%7D%20X%28t%2C-%5Cvec%7Bx%7D%29%20g%5E%7B-1%7D%20%3DI%20I_0%20%28g%20%5Cbar%7BX%7D%28t%2C-%5Cvec%7Bx%7D%29%20g%5E%7B%5Cdagger%7D%29%20%3D%20I_0%20g%20I_0%20%5Cbar%7BX%7D)




Similarly,  ![math](https://render.githubusercontent.com/render/math?math=g%20%5Cto%20g%5E%7B-1%5Cdagger%7D%20i%20%5Csigma_3)  act on general vectors gives


![math](https://render.githubusercontent.com/render/math?math=%5Cbar%7BX%7D%20%3D%20%20g%20%20%28%20t%20%5Cmathbb%7BI%7D_2%20%2B%20%5Cvec%7Bx%7D%20%5Csigma_3%29%20g%5E%7B%5Cdagger%7D%20%5Cto%20g%5E%7B-1%5Cdagger%7D%20i%20%5Csigma_3%20%20%28%20t%20%5Cmathbb%7BI%7D_2%20%2B%20%5Cvec%7Bx%7D%20%5Csigma_3%29%20%28g%5E%7B-1%5Cdagger%7D%20i%20%5Csigma_3%29%5E%7B%5Cdagger%7D%5C%5C%0A%20%3D%20%20g%5E%7B-1%5Cdagger%7D%20%28%20t%20%5Cmathbb%7BI%7D_2%20-%20%7Bx%7D_1%20%5Csigma_1%20-%20x_2%20%5Csigma_2%20%2B%20x_3%20%5Csigma_3%29%20%20%28g%5E%7B-1%5Cdagger%7D%29%5E%7B%5Cdagger%7D%20%3D%20g%5E%7B-1%5Cdagger%7DX%28t%2Cx_1%2Cx_2%2C-x_3%29%20g%5E%7B-1%7D%5C%5C%0A%3D%20I%20I_0%20%28g%20%5Cbar%7BX%7D%28t%2Cx_1%2Cx_2%2C-x_3%29%20g%5E%7B%5Cdagger%7D%29%20%3D%20I_0%20g%20I_3%20%5Cbar%7BX%7D)


This gives out exactly the result given in Wojciech. Marcin and Hanno's paper ArXiv:1705.02862
which is 


![math](https://render.githubusercontent.com/render/math?math=G_i%20%5Cto%20I_%7Be_%5Calpha%7D%20G_i%20I_%7Bu_i%7D)


with  ![math](https://render.githubusercontent.com/render/math?math=e_%7B%5Calpha%7D)  chosen to be  ![math](https://render.githubusercontent.com/render/math?math=e_0)  and  ![math](https://render.githubusercontent.com/render/math?math=u_i%3De_0)  for su2,  ![math](https://render.githubusercontent.com/render/math?math=u_i%20%3D%20e_3)  for su11 up to spacetime inversion  ![math](https://render.githubusercontent.com/render/math?math=I%20v%20%3D-v) .