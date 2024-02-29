---
title: FEDDLib (Finite Element and Domain Decomposition Library)
list_title: News
layout: home
exclude: true
---

The [Finite Element and Domain Decomposition Library (FEDDLib)](https://github.com/FEDDLib/FEDDLib) is an open-source, C++-based, object-oriented finite element library that is built on top of [Trilinos](https://trilinos.github.io/) and has access to domain decomposition solvers, particularly via [FROSch](https://cds.uni-koeln.de/en/tools/software/frosch), a subpackage of Trilinos. Trilinos is a software project for the solution of complex multiphysics problems in science and engineering. It has a multitude of (mostly) interoperable packages, for example, for parallel linear algebra operations, meshing, and the solution of linear and nonlinear problems. 

FEDDLib has been successfully applied to problems of fluid dynamics, solid mechanics, fluid-structure interaction, and fluid-structure-chemistry interaction; see the references at the bottom.

The FEDDLib code base is developed jointly by the group of [Prof. Dr. Axel Klawonn](https://numerik.uni-koeln.de/) (University of Cologne) with [Lea Saßmannshausen](https://numerik.uni-koeln.de/arbeitsgruppe/l-sassmannshausen-m-sc), [Kyrill Ho](https://numerik.uni-koeln.de/arbeitsgruppe/k-ho-m-sc), [Natalie Kubicki](https://numerik.uni-koeln.de/arbeitsgruppe/n-kubicki-m-sc), and [Dr. Jascha Knepper](https://numerik.uni-koeln.de/arbeitsgruppe/dr-j-knepper), by [Dr. Alexander Heinlein](https://www.tudelft.nl/staff/a.heinlein/) (TU Delft), and by the group of [Prof. Dr. Oliver Rheinbach](https://tu-freiberg.de/fakultaet1/institute/numerische-mathematik-und-optimierung/team) (TU Bergakademie Freiberg).

**References**

- [FEDDLib GitHub Repository](https://github.com/FEDDLib/FEDDLib)
- [A computational framework for pharmaco-mechanical interactions in arterial walls using parallel monolithic domain decomposition methods (2024)](https://doi.org/10.1002/gamm.202370002)
- [First steps towards modeling the interaction of cardiovascular agents and smooth muscle activation in arterial walls (2023)](https://doi.org/10.1002/pamm.202200133)
- [Fully algebraic two-level overlapping Schwarz preconditioners for elasticity problems (2021)](https://doi.org/10.1007/978-3-030-55874-1_52)
- [Parallel Overlapping Schwarz Preconditioners for Incompressible Fluid Flow and Fluid-Structure Interaction Problems (2020)](http://nbn-resolving.de/urn:nbn:de:hbz:38-113450): FEDDLib was initially developed in the scope of Christian Hochmuth's dissertation. It has since undergone considerable further development.
- [Reduced dimension GDSW coarse spaces for monolithic Schwarz domain decomposition methods for incompressible fluid flow problems (2020)](https://doi.org/10.1002/nme.6258)
- [Monolithic Overlapping Schwarz Domain Decomposition Methods with GDSW Coarse Spaces for Incompressible Fluid Flow Problems (2019)](https://doi.org/10.1137/18M1184047)
