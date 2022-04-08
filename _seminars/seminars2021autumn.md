---
title: "Joint NA Seminars 2021 (Autumn)"
excerpt: ""
collection: seminars
---

## Jump to Date: 
[Nov 4](#week-44), [Nov 11](#week-45), [Nov 18](#week-46), [Nov 25](#week-47), [Dec 2](#week-48), [Dec 9](#week-49), [Dec 16](#week-49)

## Week 44

Title:Multiscale analysis and high-order schemes for nonlinear multilevel Maxwell–Bloch equations

Time: Thu 2021-11-04 14.00 - 15.00

Location: KTH, 3721, Lindstedsvägen 25 (and also Zoom: 632 9929 3349)

Speaker: Qing Xia (KTH)

Abstract: In this talk, we will consider nonlinear dispersive models for active media with material interfaces in 2D and 3D arbitrary geometry. The considered nonlinear multilevel systems in the formulation of rate equations are experimental generalizations of two-level atomic systems. A multiscale analysis of the Maxwell–Bloch equations based on asymptotic expansions will be presented. The resulting reduced envelope equations (or slow equations) capture amplitude dynamics of the underlying solutions accurately and efficiently. In addition, we will discuss efficient and high-order schemes for arbitrary multilevel systems with any number of polarization vectors in high dimensional complex geometry, with or without material interfaces, using overlapping grids in the Overture framework. The developed schemes allow compact stencils in time integration, large CFL numbers, and point-wise update of the numerical solutions. It is also shown that the multilevel systems have bounded growth in the energy estimate. Additionally, numerical evidences, including convergence results and simulations, are provided for planar and curved interfaces in both 2D and 3D.

## Week 45

Title: Finite Element Ice-Ocean Modelling

Time: Thu 2021-11-11 14.00 - 15.00

Location: KTH, 3721, Lindstedsvägen 25

Speaker: Josefin Ahlkrona (SU)

Abstract: Better computer models of ice sheets in contact with the warming ocean are needed in order to reduce the uncertainty in estimates of future sea level rise. In our group we focus on FEM modelling of ice sheets and the adjacent ocean, using mathematical models of high accuracy. In this talk we give and overview of our work on overcoming some of the major challenges of ice-ocean modelling, namely the stability and representation of a free surface problems, coupled FEM modelling of ocean flow in ice cavities, and solvers for the arising linear and non-linear systems.

## Week 46

An efficient unconditionally stable method for computing Dirichlet partitions in arbitrary domains

Time: Thu 2021-11-18 14.00 - 15.00

Location: Zoom, Meeting ID: 632 9929 3349

Speaker: Dong Wang (Chinese University of Hong Kong, Shenzhen)

Abstract: A Dirichlet k-partition of a domain is a collection of k pairwise disjoint open subsets such that the sum of their first Laplace–Dirichlet eigenvalues is minimal. In this paper, we propose a new relaxation of the problem by introducing auxiliary indicator functions of domains and develop a simple and efficient diffusion generated method to compute Dirichlet k-partitions for arbitrary domains. The method only alternates three steps: 1. convolution, 2. thresholding, and 3. projection. The method is simple, easy to implement, insensitive to initial guesses and can be effectively applied to arbitrary domains without any special discretization. At each iteration, the computational complexity is linear in the discretization of the computational domain. Moreover, we theoretically prove the energy decaying property of the method. Experiments are performed to show the accuracy of approximation, efficiency and unconditional stability of the algorithm. We apply the proposed algorithms on both 2- and 3-dimensional flat tori, triangle, square, pentagon, hexagon, disk, three-fold star, five-fold star, cube, ball, and tetrahedron domains to compute Dirichlet k-partitions for different k to show the effectiveness of the proposed method. Compared to previous work with reported computational time, the proposed method achieves hundreds of times acceleration.

## Week 47

Ylva Rydin: Numerical methods for non-stationary singular source terms in hyperbolic problems (CANCELLED)

## Week 48

Title: An efficient finite difference method for the elastic wave equation in layered media

Time: Thu 2021-12-02 14.00 - 15.00

Location: KTH, Seminar room 3721, Lindstedsvägen 25

Speaker: Siyang Wang (Umeå University)

Abstract: I will present our recent efforts in developing and analyzing an efficient finite difference method for wave propagation problems. We consider the elastic wave equation in a layered medium. The material properties are smooth in each layer but can be discontinuous at nonplanar material interfaces. The spatial discretization is based on high-order finite difference operators satisfying a summation-by-part property, and geometrical features are resolved by using curvilinear meshes. In addition, mesh sizes are adapted to the material properties to balance the number of grid points per wavelength. At material interfaces, we use the ghost point method and interpolation to impose physical conditions at nonconforming grid interfaces. With a predictor-corrector time integration method, the full discretization is provably energy-conserving with a favourable time-step restriction. The stability and accuracy properties are verified in numerical examples. In addition, we have performed tests on the benchmark problem LOH.1 in the geosciences by solving the 3D elastic wave equation, with results showing excellent agreement with the semi-analytical solution when using only 5 grid points per wavelength.

This is a joint work with Anders Petersson, Lawrence Livermore National Laboratory, USA, and Lu Zhang, Columbia University, USA

## Week 49

Title: Inverses and pseudoinverses of SBP-SAT finite difference operators

Time: Thu 2021-12-09 14.00 - 15.00

Location: Zoom, https://stockholmuniversity.zoom.us/j/61371770006

Speaker: Sofia Eriksson (Linnaeus University, Sweden)

Abstract: I will talk about Inverses of SBP-SAT Finite Difference Operators, and possibly about the related project about Pseudoinverses of singular SBP-SAT Finite Difference Operators (joint work with Siyang Wang, Umeå universitet).

For the inverses, the scalar, one-dimensional advection equation and heat equation are considered. These equations are discretized in space, using a finite difference method satisfying summation-by-parts (SBP) properties. To impose the boundary conditions, a penalty method called simultaneous approximation term (SAT) is used. Together, this gives rise to two semi-discrete schemes where the discretization matrices approximate the first and the second derivative operators, respectively. The discretization matrices depend on free parameters from the SAT treatment. We derive the inverses of the discretization matrices, interpreting them as discrete Green’s functions. In this direct way, we also find out precisely which choices of SAT parameters that make the discretization matrices singular. In the second derivative case, it is shown that if the penalty parameters are chosen such that the semi-discrete scheme is dual consistent, the discretization matrix can become singular even when the scheme is energy stable. The inverse formulas hold for SBP-SAT operators of arbitrary order of accuracy. For second and fourth order accurate operators, the inverses are provided explicitly.

## Week 50

Title: Extracting Extra Accuracy Through Post-Processing

Time: Thu 2021-12-16 14.00 - 15.00

Location: KTH, Seminar room 3721, Lindstedsvägen 25

Lecturer: Jennifer Ryan (Colorado School of Mines)

Abstract: Many numerical simulations produce data that contains hidden information. This hidden information can be exploited to create even more accurate representations of the data by appropriately constructing convolution post-processors. In this presentation we address one particular form of data — that produced by discontinuous Galerkin finite element methods. Specifically, a discussion how the Smoothness-Increasing Accuracy-Conserving (SIAC) post-processing filter takes advantage of the information hidden in the numerical solution. Previous work focused on adapting the convolution kernel for boundaries, unstructured grids, and non-smooth solutions. This presentation will focus on identifying where this hidden accuracy comes from, why the hidden accuracy is important, and how to construct convolution post-processors to take advantage of this information in order to reduce the computational cost of multi-dimensional post-processing.
