---
title: "NA Seminars 2022 (Autumn)"
excerpt: ""
collection: seminars
---

## Jump to Date: 
[Sept. 1](#week-35), [Sept. 8](#week-36), [Sept. 15](#week-37), [Sept. 22](#week-38), [Sept. 29](#week-39), [Oct. 6](#week-40), [Oct. 13](#week-41), [Oct. 20](#week-42), [Oct. 27](#week-43), [Nov. 3](#week-44), [Nov. 10](#week-45), [Nov. 17](#week-46), [Nov. 24](#week-47), [Dec. 1](#week-48), [Dec. 8](#week-49), [Dec. 15](#week-50)

## Week 35

Title: Towards Robust and Interpretable Scientific Machine Learning: Theory, Algorithms, and Applications

Time: 2022-09-01, 14.00-15.00

Speaker: Yeonjong Shin (KAIST)

Location: Zoom https://kth-se.zoom.us/j/63299293349

Abstract: Machine learning (ML) has achieved unprecedented empirical success in diverse applications. It now has been applied to solve scientific problems, which has become an emerging field, Scientific Machine Learning (SciML). Many ML techniques, however, are very complex and sophisticated, commonly requiring many trial-and-error and tricks. These result in a lack of robustness and interpretability, which are critical factors for scientific applications. This talk centers around mathematical approaches for SciML, promoting robustness and interpretability. The first part is about how to embed physics into neural networks (NNs). I will present a general framework for designing NNs that obey the first and second laws of thermodynamics. The framework not only provides flexible ways of leveraging available physics information but also results in expressive NN architectures. The second part is about the training of NNs, one of the biggest challenges in ML. I will present an efficient training method for NNs - Active Neuron Least Squares (ANLS). ANLS is developed from the insight gained from the analysis of gradient descent training.

## Week 36

TBA

## Week 37

Title: Hybrid Projection Methods for Solution Decomposition in Large-scale Bayesian Inverse Problems

Time: 2022-09-15, 14.00-15.00

Speaker: Jiahua Jiang (Birmingham)

Location: KTH, 3721, Lindstedsvägen 25
 
Abstract: We develop hybrid projection methods for computing solutions to large-scale inverse problems, where the solution represents a sum of different stochastic components. Such scenarios arise in many imaging applications (e.g., anomaly detection in atmospheric emissions tomography) where the reconstructed solution can be represented as a combination of two or more components and each component contains different smoothness or stochastic properties. In a deterministic inversion or inverse modeling framework, these assumptions correspond to different regularization terms for each solution in the sum. Although various prior assumptions can be included in our framework, we focus on the scenario where the solution is a sum of a sparse solution and a smooth solution. For computing solution estimates, we develop hybrid projection methods for solution decomposition that are based on a combined flexible and generalized Golub-Kahan processes. This approach integrates techniques from the generalized Golub-Kahan bidiagonalization and the flexible Krylov methods. The benefits of the proposed methods are that the decomposition of the solution can be done iteratively, and the regularization terms and regularization parameters are adaptively chosen at each iteration. Numerical results from photoacoustic tomography and atmospheric inverse modeling demonstrate the potential for these methods to be used for anomaly detection.

## Week 38

TBA

## Week 39

Title: Reduced order models for inverse scattering problems

Time: 2022-09-29, 14.00-15.00

Speaker: Jörn Zimmerling (Uppsala)

Location: KTH, 3721, Lindstedsvägen 25

Abstract: In inverse scattering one tries to determine the coefficients of a PDE from measurements of the field that is driven by the PDE. Broadly, methods in inverse scattering fall into two categories: (1) Qualitative methods that try to reconstruct the support of scatterers and (2) Quantitative methods that try to reconstruct the PDE coefficients. Here we will focus on wave equations and reconstructing the wave speed from remote measurements.

Quantitative methods often formulate the problem as a PDE constrained optimization. That is, the PDE is used to map coefficients to simulated data and the mismatch between this data with the measurements is minimized in some norm to retrieve the unknown coefficients.
 
In this seminar we propose two alternative approaches involving reduced order modeling. A reduced-order model is a small algebraic system that can be directly obtained from the measured data and captures key properties of the underlying wave dynamics. In the first approach, the inverse scattering problem is reformulated in terms of a minimization of the reduced-order model mismatch rather than data mismatch. In a second approach we use the reduced order model to estimate the wave inside the unknown medium to aid inversion.

The measured data in inverse scattering experiments depends non-linearly on the PDE coefficient, which leads PDE constraint optimization to converge to local minima without a sufficiently good initial guess. We show that the reformulation using reduced-order models leads to a better-behaved objective function that is able to reconstruct the unknown PDE coefficients even for a poor initial guess.

## Week 40

Title: Analyzing Neural Network-Based Schemes for High-Dimensional Elliptic PDEs

Time: 2022-10-06, 14.00-15.00

Speaker: Marius Zeinhofer (Simla)

Location: KTH, 3721, Lindstedsvägen 25

Abstract: Motivated by recent empirical success, we examine how neural network-based ansatz classes can mitigate the curse of dimensionality for high-dimensional, elliptic partial differential equations with variational structure. The high-dimensionality of the PDEs can either be induced through a high-dimensional physical domain or a high-dimensional parameter space. The latter include parametric right-hand sides, parametric domains, and material constants. Our main result shows that any scheme that computes neural network based $W^{1,p}$-approximations, leverages the extraordinary approximation capabilities of neural networks and, thus, is able to mitigate the curse of dimensionality if the ground truth solution is smooth or possesses Barron regularity. Popular examples of $W^{1,p}$-convergent schemes include, e.g., the Deep Ritz Method and physics-informed neural networks. We present numerical experiments supporting our theoretical findings.

## Week 41

Title: DoD-stabilization for solving hyperbolic conservation laws on cut cell meshes

Time: 2022-10-13, 14.00-15.00

Speaker: Sandra May (Uppsala)

Location: KTH, 3721, Lindstedsvägen 25

Abstract: Cut cells methods have been developed in recent years for computing flow around bodies with complicated geometries.  For mesh generation, the flow body is cut out of a regular Cartesian grid resulting in so called cut cells. Cut cells can have irregular shape and may be very small. For the solution of time-dependent hyperbolic conservation laws, this causes the small cell problem: explicit time stepping schemes are not stable on the arbitrarily small cut cells.

In this talk we present the Domain of Dependence (DoD) stabilization for overcoming this issue for DG schemes. The stabilization is based on adding suitable penalty terms to the spatial discretization. The terms are designed to restore proper domains of dependence. In time, one can use a standard explicit time stepping scheme. The resulting scheme possesses several desirable theoretical properties, such as being monotone for scalar conservation laws for the first-order scheme.

In this talk we will discuss the idea behind the DoD stabilization and give an overview of the development so far. This includes among others the solution of the linear advection equation in 1d and 2d and of the compressible Euler equations in 1d, all using higher order polynomial degrees. The talk is complemented by numerical results.

This is joint work with (in alphabetic order) Gunnar Birke, Christian Engwer, Andreas Nuessing (all Univ. Muenster, Germany) and Florian Streitbuerger (TU Dortmund, Germany). 

## Week 42

Cancelled due to PhD student study plan evaluation.


## Week 43

Oct 26-27, SwedComp, No Seminar

## Week 44

Title: Fast Summation Methods Based on Barycentric Lagrange Interpolation

Time: 2022-11-03, 14.00-15.00

Speaker: Robert Krasny

Location: KTH, 3721, Lindstedsvägen 25

Abstract: Many problems in scientific computing involve long-range particle interactions, for example the Coulomb interaction of charged particles. To address the cost of computing these interactions in large-scale computations, we present two fast summation methods based on barycentric Lagrange interpolation, a treecode (BLTC) and a fast multipole method where the interaction lists are formed by dual tree traversal (BLDTT). The methods are kernel-independent, and the form of the approximation enables an efficient GPU implementation. The performance of the BLTC and BLDTT is demonstrated, and an application to the electrostatics of solvated biomolecules is presented.

## Week 45

Time: 2022-11-10, 14.00-15.00

Speaker: Anna Broms and Emanuel Ström (KTH)

Location: KTH, 3721, Lindstedsvägen 25

Abstract: PhD study plan evaluations.

## Week 46

Title: Fluid Modeling in Three Dimensions: Topological Classification, Boolean Algebra, Geometric Representation, and Their Applications to Interface Tracking and Mean Curvature Flows.

Time: 2022-11-17, 14.00-15.00

Speaker: Qinghai Zhang (Zhejiang University)

Location: Zoom [https://kth-se.zoom.us/j/63299293349](https://kth-se.zoom.us/j/63299293349)

Abstract: Solid modeling has been an established field while fluid modeling is still an undefined concept. However, there is a need of fluid modeling in numerically solving PDEs on complex moving domains: sometimes we have to have a solid ground for the topology and geometry of complex domains so that subsequent analysis can be performed. We answer this need by proposing for three-dimensional continua a modeling space, a complete topological classification, a Boolean algebra, and a geometric representation of their boundary. We united these techniques in a framework for numerically solving geometric PDEs such as the mean curvature flows with fourth- and higher-order convergence.

## Week 47

Title: Uniform convergence rates for Lipschitz learning on graphs

Time: 2022-11-24, 14.00-15.00

Speaker: Leon Bungert (Hausdorff Center for Mathematics)

Location: KTH, 3721, Lindstedsvägen 25
 
Abstract: The last few years have seen a deluge of discrete-to-continuum convergence results for various problems in graph-based learning and numerical analysis. This theory makes connections between discrete numerical models on one hand and continuum partial differential equations or variational problems on the other hand. Current works use either a Gamma-convergence framework or PDE techniques, which give uniform convergence rates, albeit with more restrictive conditions on the graph bandwidth that often rule out the sparse graphs used in practice. In this talk I will show how to obtain uniform convergence rates for solutions of the graph infinity Laplacian equation which depend only on the convergence rates of the graph distance function. The proof utilizes the comparison-with-cones characterization and involves a homogenized non-local operator with a much larger bandwidth. This allows us to prove convergence rates for all graph bandwidths strictly above the connectivity threshold. Furthermore, using percolation theory we can even obtain improved convergence rates for graph bandwidths on the connectivity threshold.
 
This is joint work with Jeff Calder and Tim Roith.

## Week 48

Title: TBA

Time: 2022-12-01, 14.00-15.00

Speaker: Pip Matharu (KTH)

Location: KTH, 3721, Lindstedsvägen 25

Abstract: TBA

## Week 49

Title: TBA

Time: 2022-12-08, 14.00-15.00

Speaker: Joar Bagge (KTH)

Location: KTH, 3721, Lindstedsvägen 25

Abstract: TBA

## Week 50

TBA
