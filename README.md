# FEM-implementation-in-CPP
An object oriented approach for solving elliptic PDEs using Finite Element Method.


Example initial mesh

<img src="FEM-implementation-in-CPP/pics/sol_init.png" height="200" width="200" >


Example refined mesh

<img src="FEM-implementation-in-CPP/pics/sol_ref.png" height="200" width="200" >


# Finite-Difference-Methods

(1) The "Explicit Euler Method" program, solves the trivial parabolic problem, with the following initial conditions:

u(0,x)=2x,   0<=x<=1/2

u(0,x)=2-2x,   1/2<x<=1


![](Finite-Difference-Methods/images/pic11.jpg)
![](Finite-Difference-Methods/images/pic12.jpg)
![](Finite-Difference-Methods/images/pic13.jpg)
![](Finite-Difference-Methods/images/pic14.jpg)


(2) The "Upwind Method (2)" and the "Lax Wendroff Method (2)" programs, solve the following initial/boundary problem:

du/dt+2*du/dx=0

u(0,x)=10^4*(0.1-x)^2*(0.2-x)^2,   0.1<x<0.2

u(0,x)=0,   otherwise

u(t,0)=0,   0<=t<=1

Upwind Method


![](Finite-Difference-Methods/images/pic21.png)
![](Finite-Difference-Methods/images/pic22.png)
![](Finite-Difference-Methods/images/pic23.png)
![](Finite-Difference-Methods/images/pic24.png)


Lax Wendroff Method


![](Finite-Difference-Methods/images/pic31.png)
![](Finite-Difference-Methods/images/pic32.png)
![](Finite-Difference-Methods/images/pic33.png)
![](Finite-Difference-Methods/images/pic34.png)


(3) The "Implicit Euler Method (3)" and the "Crank Nicolson Method (3)" programs, solve the following initial/boundary problem:

du/dt=(1+x^2)*d^2u/dx^2+u

u(0,x)=sin(pi*x),   -1<=x<=1

u(t,-1)=u(t,1)=0,   0<=t<=1


(4) The "Upwind Method (4)" and the "Lax Wendroff Method (4)" programs, solve the following initial/boundary problem:

du/dt+u*du/dx=0,   0<t<=1, x in R

u(0,x)=exp(-10*(4*x-1)^2),   x in R


# Finite-Element-Methods

![](Finite-Element-Methods/images/Mesh.png)


Elliptic Problem


![](Finite-Element-Methods/images/Mesh1.png)
![](Finite-Element-Methods/images/Solution1.png)
![](Finite-Element-Methods/images/Mesh2.png)
![](Finite-Element-Methods/images/Solution2.png)
![](Finite-Element-Methods/images/Mesh3.png)
![](Finite-Element-Methods/images/Solution3.png)
![](Finite-Element-Methods/images/Mesh4.png)
![](Finite-Element-Methods/images/Solution4.png)
![](Finite-Element-Methods/images/Mesh5.png)
![](Finite-Element-Methods/images/Solution5.png)
![](Finite-Element-Methods/images/Mesh6.png)
![](Finite-Element-Methods/images/Solution6.png)

Parabolic Problem


![](Finite-Element-Methods/images/Mesh11.png)
![](Finite-Element-Methods/images/Solution11.png)
![](Finite-Element-Methods/images/Mesh12.png)
![](Finite-Element-Methods/images/Solution12.png)
