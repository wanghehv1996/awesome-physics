# Awesome Physics

### Materials
- Rigid body
  - Rigid body
  - Joint
  - Fracture
- Soft body
  - Cloth
  - Deformable
- Fluid
  - Liquid
  - Smoke
- Others
  - Granular
  - Snow
  - Hair

### Methods
- Smoothed Particle Hydrodynamics (SPH)
- Position based Dynamics (PBD)
- Material Point Method (MPM)
- Finite Element Method (FEM)
- ...

### Numerical Solvers
- Conjugate Gradient (CG) / Preconditioned Conjugate Gradient (CG)
- Multi-grid (MG)
- ...

### Book/Course note/Survey

Note: The book resources can be found on [Dalab Seafile](http://dalab.se.sjtu.edu.cn:81/d/e3d109e7721e422eb13d/)

- Simulation Basics
  - [2001 Physically Based Modeling: Principles and Practice](http://www.cs.cmu.edu/~baraff/sigcourse/)
  - [2018 An Introduction to Physics-Based Animation](http://www.cs.ucr.edu/~shinar/papers/2018_introduction_to_pba.pdf)
    - [Video from SIGGRAPH 2019](https://www.youtube.com/watch?v=b_WJ-HwalwU)
  - [Ten minute physics](https://matthias-research.github.io/pages/tenMinutePhysics/index.html)

Materials
- Fluid
  - Fluid Simulation for Computer Graphics (2nd Edition)
    - All you need to know about the Eulerian fluid simulation.
  - Fluid Engine Development
    - How to write a fluid simulation with C++
- Rigid body
  - [2001 Physically Based Modeling: Principles and Practice](http://www.cs.cmu.edu/~baraff/sigcourse/)
    - Basics of the rigid body simulation
  - [2005 Stable, Robust, and Versatile Multibody Dynamics Animation](http://image.diku.dk/kenny/download/erleben.05.thesis.pdf)
    - When there is multiple rigid body and complex joints between them
- Cloth
  - Cloth Simulation for Computer Graphics
- Collision
  - [2021 Contact and Friction Simulation for Computer Graphics](https://siggraphcontact.github.io/)
- Deformable
  - [2012 FEM Simulation of 3D Deformable Solids: A practitioner's guide to theory, discretization and model reduction](https://viterbi-web.usc.edu/~jbarbic/femdefo/)
  - [2020 Dynamic Deformables: Implementation and Production Practicalities](http://www.tkim.graphics/DYNAMIC_DEFORMABLES/)

Methods
- MPM
  - [2019 On Hybrid Lagrangian-Eulerian Simulation Methods: Practical Notes and High-Performance Aspects](https://yuanming.taichi.graphics/publication/2019-mpm-tutorial/)
  - [2016 The Material Point Method For Simulating Continuum Materials](https://www.math.ucla.edu/~cffjiang/research/mpmcourse/mpmcourse.pdf)
- SPH
  - [A Survey on SPH Methods in Computer Graphics](https://animation.rwth-aachen.de/publication/0577/)
  - [2019 Smoothed Particle Hydrodynamics Techniques for the Physics Based Simulation of Fluids and Solids](https://interactivecomputergraphics.github.io/SPH-Tutorial/)
- PBD
  - [A Survey on Position Based Dynamics](http://mmacklin.com/2017-EG-CourseNotes.pdf)
    - Basics of PBD and all materials simulated with PBD
Numerical Solvers
- CG
  - [An Introduction to the Conjugate Gradient Method Without the Agonizing Pain](https://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf)


### Codes
- High performance computing
  - [Taichi](https://github.com/taichi-dev/taichi)
- Rigid body:
  - [Bullet](https://github.com/bulletphysics/bullet3)
- Fluid
  - [SPlisHSPlasH](https://github.com/InteractiveComputerGraphics/SPlisHSPlasH)
  - [PhysIKA](https://github.com/PhysikaTeam/PhysIKA)
  - [PhiFlow](https://github.com/tum-pbs/PhiFlow)
- Position based dynamics
  - [PositionBasedDynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics)
  - [Nvidia Flex](https://developer.nvidia.com/flex)


### For Dummies/ELI5
- Fluid simulation
  - Fluid Simulation for Computer Graphics (2nd Edition)
    - Basics of fluid simulation, Sec 1,2,3,5
  - [An Introduction to the Conjugate Gradient Method Without the Agonizing Pain](https://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf)
    - Conjugate Gradient is a common linear solver used in fluid simulation.
  - TODO: a code repo
- Position based dynamics
  - [A Survey on Position Based Dynamics](http://mmacklin.com/2017-EG-CourseNotes.pdf)
    - Basics of PBD, Sec 1,2,3,4-4.22,5(The constraints you need)
  - [PositionBasedDynamics](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics)
  - [Nvidia Flex](https://developer.nvidia.com/flex)
- Screen space rendering
  - [Screen Space Fluid Rendering with Curvature Flow](https://www.cs.rug.nl/~roe/publications/fluidcurvature.pdf)
  - [Narrow-Band Screen-Space Fluid Rendering](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14510)
- Rigid body
  - [2001 Physically Based Modeling: Principles and Practice](http://www.cs.cmu.edu/~baraff/sigcourse/)
  - [Stable, Robust, and Versatile Multibody Dynamics Animation](http://image.diku.dk/kenny/download/erleben.05.thesis.pdf)
    - Basics of Rigid body simulation, Sec 2, 4
  - [Bullet](https://github.com/bulletphysics/bullet3)

### Reference
- http://www.physicsbasedanimation.com/
