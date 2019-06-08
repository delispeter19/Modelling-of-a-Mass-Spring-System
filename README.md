# Modelling of a Mass Spring System

In this repository, you will find the <b>Code</b> necessary to <b>Graph</b> and <b>Animate</b> a Mass Spring System of 5 masses. 

This project was part of a comprehensive assessment at Vanier College under our professor <a href="http://euclid.vaniercollege.qc.ca/~iti/"><i>Ivan Ivanov</i></a>.

<a href="http://euclid.vaniercollege.qc.ca/~iti/proj/John_Peter_MS.pdf"><b><i>Click Here</i></b></a> to see the associated paper.

Check out our new 3D version!!!



<hr>

<div align="center">
	<img align="middle" height="250px" src="Assets\3DSpring1.gif" />
	<img align="middle" height="150px" src="Assets\D1.png" />
	<img align="middle" height="200px" src="Assets\UndampedFreeAni.gif" />
</div>

## Installation
In your Command Prompt (Cmd) type the following:
```
git clone https://github.com/delispeter19/springsdiffeq.git
```
Another option is just to clone/download the zip file from above.

## Basic Usage
At the start of each jupyter notebook, you will find a parameter screen for masses, spring constants. The masses and spring constants will determine the nature of the parameter matrix <i>P</i> defined later in the code.

```
#PARAMETERS:

#Masses:
m1=5 ; m2=1 ; m3=2 ; m4=4 ; m5=6

#Spring constants:
c1=1 ; c2=5 ; c3=3 ; c4=4 ; c5=3

```
There are also 3 possible initial conditions to modify and test. Each set of initial conditions will share the mass and spring constant parameters above. 

```
#INITIAL CONDITIONS:

#Initial Conditions 1:
u11=0. ; u21=0. ; u31=0. ; u41=0. ; u51=1.
du11=0. ; du21=0. ; du31=0. ; du41=0. ; du51=0.

ic1m=[u11,u21,u31,u41,u51,du11,du21,du31,du41,du51]

#Initial Conditions 2:
u12=0. ; u22=0. ; u32=0. ; u42=0. ; u52=0.
du12=0. ; du22=1. ; du32=0. ; du42=0. ; du52=0.

ic2m=[u12,u22,u32,u42,u52,du12,du22,du32,du42,du52]

#Initial Conditions 3:
u13=0. ; u23=0. ; u33=0. ; u43=0. ; u53=1.
du13=0. ; du23=1. ; du33=0. ; du43=0. ; du53=0.
      
ic3m=[u13,u23,u33,u43,u53,du13,du23,du33,du43,du53]
```
The above screen is essentially how you can change the animations and graphs.

