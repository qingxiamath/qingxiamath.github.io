---
title: "NA Seminars 2023 (Spring)"
excerpt: ""
collection: seminars
---

## Jump to Date: 
[Feb 9](#week-6), [Feb 16](#week-7), [Feb 23](#week-8), [Mar 2](#week-9), [Mar 9](#week-10), [Mar 16](#week-11), [Mar 23](#week-12), [Mar 30](#week-13), [Apr 6](#week-14), [Apr 13](#week-15), [Apr 20](#week-16), [Apr 27](#week-17), [May 4](#week-18), [May 11](#week-19), [May 18](#week-20), [May 25](#week-21), [Jun 1](#week-22), [Jun 8](#week-23), [Jun 15](#week-24-talk-1), [Jun 16](#week-24-talk-2)

## Week 6

Title: A simple and accurate numerical method for singular and near-singular integration

Time: 2023-02-09, 14.00-15.00

Speaker: Bowei Wu (UMass Lowell)

Location: Zoom [https://kth-se.zoom.us/j/63299293349](https://kth-se.zoom.us/j/63299293349)

Abstract: Boundary Value Problems (BVPs) are ubiquitous in engineering and scientific applications. One of the most robust and accurate methods for solving BVPs is the Boundary Integral Equation Method, which has the great advantage of dimensionality reduction: all of the unknowns reside on the boundary surface instead of in the volume. A key challenge when solving integral equations is that special quadrature methods are required to discretize the underlying singular and near-singular integral operators. Accurate discretization of these operators is especially important in, for example, problems that involve close structure-structure or fluid-structure interactions. In this talk, we present some recent advancements on singular and near-singular numerical integration based on one of the simplest quadrature methods -- the Trapezoidal rule.

## Week 7

Title: The projection method for high-order finite difference with summation-by-parts properties

Time: 2023-02-16, 14.00-15.00

Speaker: Gustav Eriksson (Uppsala)

Location: KTH, 3418, Lindstedsvägen 25

Abstract: High-order finite difference methods with summation-by-parts (SBP) properties for time-dependent wave propagation problems are considered. In recent times, the most common method for imposing boundary and interface conditions with SBP finite differences has been the simultaneous-approximation-term (SBP-SAT) method. The SAT method imposes the conditions weakly by adding a penalty term to the system. However, for some problems, the stability proofs with SBP-SAT are difficult and the spectral radii of the schemes can grow large. Here, we consider an alternative method that imposes the conditions strongly using orthogonal projections (SBP-P). For most problems, the stability proof with SBP-P is significantly simpler than with SBP-SAT. It follows directly if the PDE is well-posed. In this talk, I will introduce SBP finite differences and show how the projection method can be used to prove stability for a wide array of PDEs. Numerical results and comparisons between SBP-P and SBP-SAT will be presented for the incompressible Navier-Stokes equations with wall boundary conditions, the piecewise homogeneous dynamic Kirchoff-Love plate equation, and the second-order wave equation with non-conforming interfaces.

## Week 8

Title: Systematic search for singularities in 3D Euler flows

Time: 2023-02-23, 14.00-15.00

Speaker: Xinyu Zhao (McMaster U)

Location: Zoom [https://kth-se.zoom.us/j/63299293349](https://kth-se.zoom.us/j/63299293349)

Abstract: The local well-posedness of smooth solutions of 3D incompressible Euler equations has been established when the initial data is in the Sobolev space $H^s$ for $s > 5/2$.  However, it is still an open question whether these solutions develop finite-time singularities. Today, we will present a numerical study of this question where we systematically search for initial data that may lead to potential singularity through PDE-constrained optimization. The optimization problem is solved numerically using a state-of-the-art Riemannian conjugate gradient method where the Sobolev gradients are obtained through an adjoint method. The behavior of the obtained extreme flow, which features two colliding distorted vortex rings, suggests a finite-time singularity formation. This is based on a joint work with Bartosz Protas.

## Week 9

SIAM CSE, no seminar

## Week 10

Title: An intrinsic finite element method for PDEs on surfaces

Time: 2023-03-09, 14.00-15.00

Speaker:  Elena Bachini (Technische Universität Dresden, Institute of Scientific Computing)

Location: KTH, 3418, Lindstedsvägen 25

Abstract: Surface PDEs have attracted the interest of many researcher over the last twenty years, due to their applications in various fields from fluid flow to biomedical engineering and electromagnetism. Many proposed numerical approaches rely on an embedding of the surface in a higher dimensional space. We present here an alternative finite element approach based on a geometrically intrinsic formulation, that we call Intrinsic Surface Finite Element Method (ISFEM). By careful definition of the geometry and the differential operators, we are able to arrive at an approximation that is fully intrinsic to the surface. We consider first a scalar advection-diffusion-reaction equation defined on a surface. In this case, the numerical analysis of the scheme is also available, and we show numerical experiments that support theoretical results. Then, we extend the differential operators for the case of vector-valued PDEs. In this case the presented formulation allows the direct discretization of objects naturally defined in the tangent space, without the need of any additional projection. Finally, we extend ISFEM to consider moving surfaces via an intrinsic re-definition of the PDE that takes into account a time-dependent metric tensor. To evaluate our approach, we consider several steady and transient problems involving both diffusion and advection-dominated regimes and compare its performance to established finite element techniques.

## Week 11

Title: Divergence-preserving Cut Finite Element Methods

Time: 2023-03-16, 14.00-15.00

Speaker: Erik Nilsson (KTH)

Location: KTH, 3418, Lindstedsvägen 25

Abstract: Many PDEs modelling physical phenomena include a divergence condition coming from a physical conservation law. In a Finite Element Method (FEM) it is possible to satisfy this condition up to machine precision, but not for any choice of finite element space. This talk will address the divergence condition in the context of a variant of the FEM called Cut Finite Element Methods (CutFEM), which can be applied with computational benefit to problems in which the geometry undergoes deformations during the course of the simulation. In particular we will see a new way to satisfy the divergence condition up to machine precision, using CutFEM.

## Week 12

No seminar. 

## Week 13

Title: Iterative methods and structure preservation

Time: 2023-03-30, 14.00-15.00

Speaker: Viktor Linders (Lund)

Location: KTH, 3424, Lindstedsvägen 25

Abstract: Consistency, conservation, stability and accuracy are essential ingredients in the design of successful discretizations of partial differential equations. Considerable effort has been put into ensuring these properties for spatial and temporal discretizations. In the context of implicit schemes, iterative methods are used to approximate solutions to the systems of (nonlinear) equations that arise in each time step. However, iterative methods have not been designed with these concepts in mind.

In this talk we will discuss questions surrounding the preservation of structures by iterative methods and the potential impact that this could have on the quality of numerical solutions. We will see that not all iterative methods are conservative, and among those that are, many are inconsistent. In addition, iterative methods violate entropy estimates that the discretization satisfies, and can convert a dissipative scheme into an anti-dissipative one. This has a profound impact on the errors in numerical simulations. We will examine several solutions to these issues, and see that enforcing the preservation of the underlying structure can result in better numerical solutions, even when considerably larger tolerances are used.

## Week 14

Holiday, no seminar

## Week 15

No seminar

## Week 16

Title: Improving Accuracy with a Convolution Filter: Introduction, Applications, and Recent Developments

Time: 2023-04-20, 14.00-15.00

Speaker: Xiaozhou Li

Location: Zoom [https://kth-se.zoom.us/j/63299293349](https://kth-se.zoom.us/j/63299293349)

Abstract: The Galerkin method is well-known for its ability to achieve superconvergence. Specifically, the standard error of the DG method boasts a higher order of 2k+1 in the negative norm, or in a dual Sobolev space. However, in order to further enhance the accuracy of a Galerkin solution, previous studies have explored various reconstruction techniques including filtering/post-processing, etc.

By implementing a specially designed convolution filter, it is possible to replicate superconvergence in the solution space, particularly in the L2 norm. This not only improves accuracy, but also enhances the smoothness of the original solution between elements.

In this talk, we will focus on introducing the filtering technique, discussing why it is useful and demonstrating common usage. We will also explore recent developments and challenges, including its use in conjunction with the ALE-DG method, efficiency concerns, and other difficulties.

## Week 17

No seminar

## Week 18

Title: Turbulent flow and heart valve disease

Time: 2023-05-04, 14.00-15.00

Speaker: Johan Hoffman (KTH)

Location: KTH, 3424, Lindstedsvägen 25

Abstract: We present our work on computational modeling and analysis of turbulent flow in the context of heart valve disease. Abnormal blood flow in the heart is associated with an increased risk for thrombosis, and may be the result of heart valve disease or a clinical intervention to treat heart valve disease. To simulate the blood flow, we use patient-specific data from medical imaging to personalize a finite element model of the left ventricle of the heart. 

## Week 19

No seminar

## Week 20

Holiday, no seminar

## Week 21

**CANCELED**

Title: TBA

~~Time: 2023-05-25, 14.00-15.00~~

Speaker: Sven-Erik Ekström (Uppsala)

## Week 22

No seminar

## Week 23

Title: A Hybrid Integral Equation Method for the Navier-Stokes Equations

Time: 2023-06-08, 14.00-15.00

Speaker: Ludvig af Klinteberg (MDU)

Location: KTH, 3418, Lindstedsvägen 25

Abstract: Integral equation methods provide an efficient way of solving elliptic PDEs to high accuracy, particularly in complex geometries. They are however limited to homogeneous problems, and have in the context of fluid dynamics mainly been used for solving the Stokes equations. Recent years have seen development in the use of integral equation methods also for inhomogeneous problems. In these hybrid methods, the solution is represented as a sum of a layer potential and a volume potential. 

I will in this talk introduce a high-order, hybrid integral equation method for the incompressible Navier-Stokes equations in 2D. This method is the first of its kind, and it comes with a couple of attractive features, such as near-optimal scaling, simple geometry handling, and automatic satisfaction of the incompressibility constraint.

## Week 24 Talk 1
Title: Observer based data assimilation for barotropic Euler equations on networks

Time: 2023-06-15, 14.00-15.00

Speaker: Jan Giesselmann (TU Darmstadt)

Location: KTH, 3721, Lindstedsvägen 25

Abstract: In this talk, we discuss state estimation for systems described by barotropic Euler equations on networks. These are a frequently used as models for gas flows in pipeline networks. We are interested in predicting the system state based on a combination of models and measurements that have been taken over a long period of time.

We will consider two scenarios in which the system state can only be measured partially: In the first scenario, measurements can be made only at nodes of the network. In the second scenario, measurements can be made everywhere but just one field, e.g. velocity, can be measured. In both scenarios, we construct so called observers, i.e. models that combine a PDE model that encodes our understanding of the underlying physics with measurement data that are included as boundary data or source terms.

Our goal is to show that the solution of the observer system converges towards the state of the original system exponentially for long times. We achieve this under certain assumptions on the size and regularity of the solution to the original system and restrictions on the network topology. On a technical level, in the first scenario, the proof relies on Riemann invariants and the their evolution along characteristics whereas, in the second scenario, we use estimates on the evolution of an extended relative energy.

This is joint work with Martin Gugat (Erlangen) and Teresa Kunkel (Darmstadt).

## Week 24 Talk 2

Title:

Time: 2023-06-16

Speaker: Adrianna Gillman (University of Colorado)

Location: KTH, 3721, Lindstedsvägen 25

Abstract:


